# Probability

### Informal definitions

Classic, exact definition:

- useless b/c very limited: all outcomes are equally likely
  - ex. cards

Empirical definition, according to relative frequencies:

- we look at past data
  - ex. new drug will help patients? access the prop. In some test tool patients -> do they feel better & side effects?
  - ex. stock market data

The subjective prob. def.:

> Gut feeling, life experience.

- No parsed data
  - ex. first iPad for Apple.
- Access the likelihood of success, the likelihood of failure.

## Formal definitions

Random experiment is anything that has an uncertain outcome:

- ex.: weather next Monday, stock price Tuesday.

Basic outcomes (Fair Die): 1, 2, 3, 4, 5, 6. All of the basic outcomes form a collection called Sample Space: S = {1, 2, 3, 4, 5, 6}.

Events: A, B, C....

Probability is the chance or the likelihood that uncertain event will occur:
For any event A: (impossible) 0 <= P(A) <= 1 (certain).

**Definition 1**. Classical probability:

- all basic outcomes are equally likely (not satisfied in real life apps).
- prob of event A = P(A) 
  = (number of basic outcomes that satisfy A) divided by (total number of outcomes in a sample space)

**Definition 2**. Empirical prob.:

- prob of event A = P(A)
  = (number of times the event A occurs in repeated trials) /
  (total number of trials in a random experiment)
  = proportion of times an event occurs in a large number of trials

- We have data? Derive proportions.

  - Ex. Weather? Prop of rain? Prob. of sun?

  - Ex. How many days did it go down? Up?
  - Ex. medicine, pharma (drug testing)

**Definition 3**. Subjective probability:

- an opinion or belief about the chance of occurrence.
- no data, no clue
- ex. brand new product.

## Probability rules

Fundamental Probability Rules (Colmogorov's axioms):

1. The prob. of an outcome in the sample space is 1, P(S) = 1
2. For any event A, the prob. of A is btw 0 & 1, 0<= P(A) <= 1
3. For disjoint (no elements in common) events A & B:
   P (A U B) = P(A or B) = P(A) + P(B)

Ex. A Fair Die = apply Classical Prob.

Additional rules:

- The complement rule: complement A^c = S \ A, then the complement rule: P(A^c) = 1 - P(A).

- General additional rule: P(A ∪ B) = P(A or B) = P (A) + P(B) - P (A ∩ B)

  > the last intersection helps to avoid double counting.

## Statistical independence

Ex. The sum of two fair dice.

B outcomes: 2, 3, 4,..., 12

S = {2, 3, 4,..., 12}

A = {11, 12}, B = {7}

The probability to get 7 is 0,16666, the highest! 6 ways to obtain that 7.

By counting the pos. and the total number of combinations we can calc. the probs. (sum = 1)

Pop. mistake: 11 numbers, prob 1/11? NO! All probs. aren't the same.

**Different view**

S = { (1, 1), (1, 2), ..., (2,1), ..., (6,5), (6,6)}

S has 6x6 = 36 elements/combinations. And they are now all equally likely! Now we can use the classical prob. def:

P(2) = P((1,1)) = 1/36

P(4) = P({(1,3), (2,2), (3,1)}) = 3/36 = 1/12

First die rolls and shows up a 1, that doesn't affect the second die! The outcome of the 1st die doesn't affect the outcome of the 2nd die. This is the concept of **(statistical) independence**:

- Two events A&B indep. if event A occurring or not occurring does not affect the prob. event B occurring.
- It's ease to calc. the prob of the intersect of two events:
  P (A ∩ B) = P(A and B) = P(A) * P(B).

