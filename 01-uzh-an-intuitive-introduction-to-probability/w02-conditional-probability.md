# Conditional probability

Ex.:

1. what is the p that the person is younger than 20?

2. p that person's main language is French?

Person's answer: from Zurich.

Person residing in Switzerland:

1. P(0-19 years) = 20.2%
2. P(French) = 22.4%

However, person res. in Zurich:

1. P(0-19) = 19.6%
2. P(French) = 3.2% ↓

---

The p. of Event A occurring is P(A).

Information update: Event B occurred. Now we are changing the p.

What is the p of Event A occurring given that Event B occurred?

New p: **P(A|B), "the conditional probability of A given B"**.

Ex. P(A=French) = 22.4%, P(A=French|B=Zurich) = 3.2%.

A ∩ B (joint), but don't think of the S. B is the new sample space! Outcomes outside B are no longer possible. Q: **How likely is the event A within a new state space B?** It's cond. prob.

> Q: Knowing that B has occurred, makes the probability of A to occur more likely.
>
> Incorrect!

Focus on B.

**Definition**. P(A|B) = P(A ∩ B) / P(B).

> Normalizing our probs. on the sp B the event that occurred.

Ex. P(A) was higher (1/2) before the event B occurred (now it's 1/3). So: Events A and B are **dependent**.

Ex. P(A) = 1/2, but P(A|B') = 1/2. B' occurred, but it didn't change the p of A. So: Events A and B' are **independent**.

> Question 2
>
> P(A) = 0.3 and P (A|B) = 0.2 What can you tell about P(B)?
>
> Answer: I cannot calculate P(B) without also knowing P(B/A).

General multiplication rule:

- P(A ∩ B) = P(A|B) * P(B)
- P(A ∩ B) = P(B|A) * P(A)

Ex. Swiss population data:

- 17.6% of Swiss res. live in Zurich
- 19.6% of all Zurich are 0-19 y old.
- Q: prop of Swiss res. both live in Zurich and 0-19: 0.176 * 0.196 = 0.034496 ~3.45%.

Probability concept: **Empirical Probability**.

P(Zurich) = 0.176, P(0-19 years|Zurich) = 0.196

P(Z & 0-19) = P(Z ∩ 0-19) = P(Z) * P(0-19|Z) = 0.0345

It's an every day concept: a proportion of a proportion, and then we multiply.

Independence:

P(A) = P(A|B) & P(B) = P(B|A)

Multiplication rule for independent events:

P(A ∩ B) = P(A) * P(B).

Ex.

W_i = event that machine works well on day i
F_i = event that machine fails on day i
P(W_1 ∩ W_2) = P(W_1) x P(W_2 | W_1) = 0.9 x ?
If **yes** (independence), P(W_1 ∩ W_2) = P(W_1) x P(W_2) = 0.9^2 = 0.81

> Bathtub curve: middle range = indep. is okay assumption, front end/back end ≠ indep.

**Probability tables**

|        | Africa         | Americans | totals        |
| ------ | -------------- | --------- | ------------- |
| hotel  | 279'870->0.010 | 1'825'085 | 0.600         |
| other  | 50'481->0.002  | 297'955   | 0.400         |
| totals | 330'351->....  | 2'125'040 | 1.000 (green) |

difficult to look at it -> transform them into proportions, using empirical probability.

Very right column, very bottom row = marginal probabilities (b/c margins of the table).

Joint probabilities are in the middle (hotel & other).

**Set-up of a probability table**

A1, A2, ..., Am are mutually exclusive (can't happen simultaneously) and collectively exhaustive events.

B1, B2, ..., Bk are k mutually exclusive and collectively exhaustive events.

The margin is the sum of the interior.

Ex.

P(Europe|other) = P ("Europe" ∩ "other") / P(other) = 0.381/0.400 = 95.25%