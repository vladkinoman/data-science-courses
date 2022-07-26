# Discrete random variables

A **random var.** assigns a single num. value to each basic outcome in the sample space.

Their names: X, Y, Z, etc.

**Disc. random var.** X can take on only a finite number of values (or at most a countably infinite number).

p(x) = P(x) = P(X=x) = Pr(x)

> P(X=x): rand. var. X takes on a specific value and then it's ordered by x.

When we sum P() we get to the concept of the Probability distribution. A probability mass function (abbreviated PMF) completely describes the probability properties of the random variable. It shows the p. that a random var. X is exactly equal to some deterministic value x.

The cumulative distribution function (abbreviated CDF) shows the p. that a random var. X takes a value less than or equal to a deterministic value x.

Notation: F(x) = P(X≤x), where -∞ < x < ∞.

> It means: F(x) = P(X=1) + P(X=2) +...+ P(X=x).

> Ex. X is the sum of the outcomes of the two dice. The state space S is {2, 3, ..., 11, 12}.
>
> P(X=2) = 1/36
>
> P(X=3) = 2/36, ..., P(X=12) = 1/36
>
> P(X=x) = 0 for all values x not in {2, 3, 4, ..., 12}
>
> - The # of pos. outcomes for X is clearly infinite, so X is a disc. rand. var.
> - All pos. outcomes for the sum of two fair dice are not equally likely (тобто ймовірність отримати 7 вище ніж отримати 2). Therefore X is not uniformly distributed.
>
> If you have a table, then you can get a graphical representation of P(X=x). Like a Column diagram, or a Staggered chart for Cumulative distribution of F(d) (for step function).

> Ex. Roulette. 0 - 36.
>
> We assume an absolute fair game. We assume that all 37 numbers are equally likely. This p. dist. is also called the **uniform probability distribution**.
>
> P(R=0) = P(R=1) = ... = P(R=36) = 1/37
>
> The Column graph gives an idea that all numbers are equally likely (all columns are similar). This is a discrete uniform distribution (every one of n values has equal p 1/n).

**Expected value**

more possible values in rand values = graph. repr. gets messy.

We like summarize info into Summary Measures.

First one is Average Mean (or Expected Value, мат. сподіванння :ukraine: ). **Mean** of a disc. rand. var. X is the probability weighted sum of all possible values.

μ = E(x) = x1 * p(x1) + x2 * p(x2) + ... + xk * p(xk)

How to understand? A: if I repeat that experiment many times, then the average will get close to μ.

>  Ex. Roulette bet on red:
>
> - red = net win of 1
> - black = net loss of 1
>
> What is the expected value? How much money will you win or lose on average?
>
> Rand. var B and its values 1 (win), -1 (lose).
>
> P(B = 1) = 18/37 = 0.4865
>
> P(B =-1) = 19/37 = 0.5135 (19 = 18 black + 1 green)
>
> E(B) = 1x18/37 + (-1)x19/37 = -1/37 = -0.027027 - this is how much chips you will lose if you will bet on this color. "House advantage" (lang. of gambling) - on avg the casino wins money.

> Ex.
>
> Offer:
>
> - Extra fee = 84$
> - Deductible = 100 $
>
> Buy the insurance?
>
> Random var = accident payment
>
> accident? damage exceeds 800 = you need to pay 800 in that case. No? 0 - no accident. A0 has two values: 800 & 0.
>
> > we neglect accident like bumper damage of say 500
>
> With extra insurance:
>
> A1 has two values: 100 & 0 (no accident).
>
> P of accident = p
>
> Expected payments:
>
> - without extra insurance:
>
> E(A0) = 800 x p + 0 x (1-p) = 800 p
>
> - with extra insurance:
>
> E(A1) + 84 = 100 x p + 0 x (1-p) + 84 = 100p + 84
>
> At which p would these payments be the same? 8 1/3 %.
>
> If p is high = buy the insurance, if p is small = you shouldn't buy the insurance.

