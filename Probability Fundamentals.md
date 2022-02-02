Probability Fundamentals
===

## Table of Contents

[TOC]

## Introduction
**Probability** is the likelihood of something happening. For example, A is likely to occur, B is definitely happening, there is a 40% chance of C, etc.

You'll need to be able to work through paradoxes to make the best possible decisions and predictions when things are left up to random chance.
* Simpson's Paradox
https://www.britannica.com/topic/Simpsons-paradox

Probability lets us reason not only about the most likely future events but also about possible causes of past events.

Starting With Probability
---
### Using Outcomes
![](https://i.imgur.com/7bkzI4K.png)
![](https://i.imgur.com/ICm2QzS.png)
**Explanation**
Given the answer choices, it is much more likely that Katie, despite her past history, is only one of these rather than both of these. There is some probability that Katie does not help with the school's music club. In addition, the event that Katie is both a teacher and helps with the music club is a subset of the event that Katie is a teacher. (A subset is a set contained within another set.) Thus, it cannot be more likely than the event that Katie is a teacher.

While we can't predict most events with absolute certainty, we can try to estimate how likely they are to happen using probability.e.g. Usually, if I do not eat breakfast, I get a headache mid-morning. This morning I did not eat breakfast, so I will probably get a headache.This  statement somehow seems to be reasonable


![](https://i.imgur.com/QenQ4xQ.png)
![](https://i.imgur.com/1jqusRU.png)
The sum of all of the probabilities for the different colors in each bag must sum to exactly 100\%. It can't be more than that.

Before diving any further into probability, let's review some fundamental properties of probability:
* Probability is a number between 00 and 11, usually indicated with a capital P. For example, P(heads) indicates the probability of getting heads.
* Probability can be expressed as a fraction, decimal, or percent.
* The set of all possible outcomes is called the sample space. The sum of the probabilities of all outcomes in a sample space is exactly 1,1, or 100\%.100%. For example, the probability of a coin landing on heads plus the probability of a coin landing on tails must equal exactly 11 because a coin cannot land on both heads and tails.
* The most straightforward probability calculation is by outcomes. When there are some number of equally likely outcomes, the probability of a “successful” outcome can be calculated as --> no. of successful Outcomes/no. of total Outcomes

### Outcome Distributions
For some probability problems, it might be difficult to count all possible outcomes. For this reason, we represent the outcomes with lists and tables that make counting easier.
When faced with a tricky probability question, creating an outcome distribution chart can help show all of the possible outcomes.
*Look at the example below:*
![](https://i.imgur.com/Q9aHzGm.png)
![](https://i.imgur.com/LGOK2PH.png)
![](https://i.imgur.com/90FDPbP.png)

*A handy solving technique in probability is to note when there is some sort of symmetry which causes two or more probabilities to be equal.*

### Complements
Sometimes, it's easier to count what did not happen than what did.
We explore how complements help us simplify and solve probability problems. Together, an event and its complement create all possible outcomes. The probability that something doesn't happen is 11 minus the probability that it does happen.

We use complements to solve problems in probability. Because the probability that something happens and that it doesn't happen add up to one, we can compute the one that's easier to find.


### Expected Value
When making difficult decisions, we often consider best-possible and worst-possible outcomes. Is there a better way to make choices?
Now we'll see how long-run averages can help us reason through making decisions when outcomes are uncertain.
The **expected value** (EV) is an anticipated value for an investment at some point in the future. In statistics and probability analysis, the expected value is calculated by multiplying each of the possible outcomes by the likelihood each outcome will occur and then summing all of those values.
*Look at the example below:*
![](https://i.imgur.com/8AT96y8.png)
![](https://i.imgur.com/MXbR4gi.png)
![](https://i.imgur.com/oa1etnN.png)
![](https://i.imgur.com/0h1rLVg.png)
![](https://i.imgur.com/rtaxchO.png)
*We were trying to determine not only if we should expect to gain or lose money in the long run, but how much. This number is called expected value and tells us what to expect, on average, in the long run.*

While we often can't predict the consequences of our decisions, expected values let us see which choice would give us a better outcome in the long run.

### Games & Gambling
Many gambling games are based on probability and expected values. We can apply the ideas we’ve been using to analyze outcomes for lotteries, coin tosses, and other games of pure chance.

Roll the Dice
---
### The Rules of Sum and Product
* **The Rule of Product**: When calculating the probability that multiple independent events will all occur, the probabilities are multiplied.
***Example:***
What is the chance of rolling a sum of 99 followed by a sum of 1010 on a pair of standard dice?
The probability of a sum of 9 is 4/36. The probability of a sum of 3/36.The overall probability of a 9 followed by a 10 is (4/36)*(3/36)
Because two die rolls do not affect each other (they are independent), multiplication is allowed.

Two events are ***independent*** if the probability of one of them occurring does not affect the probability of the other occurring.

* **The Rule of Sum**: the probability the event as a whole will occur is a sum of the probabilities of each individual part, as long as the parts cannot occur at the same time.

A good rule of thumb (given independence) is the Rule of Product applies when an event **and** another event occur, while the Rule of Sum applies when an event **or** another event occurs.

### Common Intuitive Fallacies
The goal is to compare two events in each problem and identify the event that’s more likely.
Avoid the pitfalls of probability in situations where mistakes are common.

### Complementary Probabilities
In games with no possible draws, the probability of winning and the probability of losing add up to one. So, it's enough to find just the simpler of the two!

The **Rule of 1** states that if the Rule of Sum is applied and every individual part of an event is accounted for, the probabilities ought to add up to 1, or 100%.

The **complementary probability** of an event is the probability that something **doesn't** occur. Assuming there are only two choices (occurrence or non-occurrence) by the Rule of 1 the probability of an event not happening is 1 minus the probability of it happening. (Note: 1 also means 100\% .)

**Example**: If you know a certain strategy has a 10\% chance of winning and there are no ties, it has a 100\% - 10\% = 90% chance of losing.

Finding the complementary probability — the probability of the opposite event — is easier than computing the relevant probability directly. Thanks to the rules of probability it's enough to find one of them!

### Using Symmetry
Sometimes symmetry causes two or more probabilities to be equal, which reduces the number of overall probabilities you need to calculate.

![](https://i.imgur.com/RIV2Y4h.png)


In a number of dice games we found symmetry that made some probabilities equal. This useful shortcut allowed us to quickly solve these probability problems.

### Endgame Strategy

![](https://i.imgur.com/R75D01h.png)


In the game of Shut the Box, one needs to think ahead to find the optimal strategy. 

![](https://i.imgur.com/e1mcI2c.png)

We saw that playing Shut the Box optimally comes down to comparing the probabilities of rolling different sums on a pair of dice. 


Fairness and Expected Value
---
### Introduction to Fairness
In a fair game, all players involved have an equal chance of winning, or if it's a solo game, the player has an equal chance of winning and losing. 

![](https://i.imgur.com/08Y1DEr.png)
If we determine a game is not entirely fair, we can try and determine what our chances are of winning. This can help us decide whether we want to play or not.


### Barbotte
In the game of Barbotte, each of the two players is assigned four winning combinations of two dice.

You are playing Barbotte with a friend using a pair of standard, six-sided dice. You take turns rolling both dice. According to the rules, you or your opponent win the round by rolling one of these four combinations: (3,3), (5,5), (6,6), or (6,5).

You lose the round if you or your opponent roll these combinations: (1,1), (2,2), (4,4), or (2,1). All other pairs result in neither a win nor a loss and the game continues.
You lose the round if you or your opponent roll these combinations: (1,1), (2,2), (4,4), or (2,1). All other pairs result in neither a win nor a loss and the game continues.

The game is fair two-fold: not only do you have an equal chance to win or lose against your opponent, but there are equal chances of rolling a winning or losing combo.


### Roulette
Roulette is a game of chance with many different kinds of bets.
![](https://i.imgur.com/W0J4cZo.png)
The “RED” bet wins on numbers colored red and “BLACK” bet wins on numbers colored black. They return 1:1 odds—that is, if a player wins, they win as much as they bet, doubling their money pile of that bet.

Is betting on red a fair bet? In other words, in the long run would you expect to break even betting on red only?
![](https://i.imgur.com/uqWBjgQ.png)

![](https://i.imgur.com/Zn0RkFe.png)

![](https://i.imgur.com/PvXGMcI.png)

We found that on average, roulette players are expected to lose money. This makes roulette an unfair game — the house is expected to win in the long run.

### Piglet
In the game of piglet, the player rolls a six-sided die and can either win or lose money depending on what they roll.

![](https://i.imgur.com/VKkAiPH.png)
![](https://i.imgur.com/guQGZNn.png)
![](https://i.imgur.com/HcUhvfC.png)

The key to winning the game of piglet is deciding when to quit and when to keep rolling the die. We established optimal strategies for different variations of the game using expected values.


### Linearity of Expectation
Linearity of expectation lets us compute the expected value of the sum of several outcomes, like the sum of dice rolls.

This concept is a general result called linearity of expectation. It means that if you are adding up two unknown quantities (for example the values of two dice), the expected value of their sum equals the sum of their expected values.

Thanks to the linearity of expectation, we can compute the expectation of a sum by adding individual expectations. This concept let us find the best strategy in a more complicated variation of the game of piglet.


### Bunco 

Given a choice between different variations of the same game, one should pick the one with the highest expected value.
![](https://i.imgur.com/mBCiKnZ.png)
![](https://i.imgur.com/z11izA4.png)
![](https://i.imgur.com/h78LNa3.png)
![](https://i.imgur.com/WzUIBUa.png)
![](https://i.imgur.com/jXeboBt.png)


### Symmetry
When two or more outcomes are equally likely, you can take advantage of this to compute the expected value.

One of the most powerful arguments in probability and combinatorics is that of symmetry. If we can match up equally likely possibilities from two different cases, then we can say that these two cases have the same probability of happening.

This also works with expected value. For instance, because heads and tails are symmetric, if we flip many coins, we expect half of them to land on heads.

![](https://i.imgur.com/bNhGmme.png)

![](https://i.imgur.com/2HvVv0g.png)
![](https://i.imgur.com/28fAWbg.png)
![](https://i.imgur.com/4HyjNdN.png)

### Stein's Game
Stein's game can be played with different numbers of cards, and this choice impacts the probability of winning and the expected returns.

To play Stein's game with NN cards, a dealer takes NN cards numbered 1, 2, \ldots, N1,2,…,N and shuffles them. Then, the player flips them over one by one, and they will be paid \dollar 1$1 every time a new highest card shows up. (The first card always counts as a highest card, since you haven't seen any cards yet.)

![](https://i.imgur.com/0HWC9vA.png)
![](https://i.imgur.com/8iM6tX0.png)

![](https://i.imgur.com/PSxTGs4.png)

### Information Asymmetry
The expected value of a game can be different depending on how much a player knows, and it can even change for the same person as they get more information.

In games, different players often have different information available to them. For example, in a game of poker, each player knows their own cards, but they do not know the other players' cards.

This has a significant implication: the expected value of something can be different depending on how much you know, and it can even change for the same player as they get more information.

![](https://i.imgur.com/Hsawqtq.png)
![](https://i.imgur.com/ujPPJwB.png)


## Appendix and FAQ

:::info
**Find this document incomplete?** Leave a comment!
:::

## References
https://brilliant.org/courses/probability-fundamentals/

