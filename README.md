# Week 7: Homework 2: Blockchain: Prove of Work

# Item

Three Dices

# Encoding

Dice 1 + Dice 2 + Dice 3

# Objective

Throwing three dices whose summation is less than a specified number (= target = difficult target).

# All possibilities

3 (three dices are all 1) ~ 18 (three dices are all 6)

# Related to mining

- The player (i.e., miner) conducts a Proof-of-Work by throwing both dices with combined values that is less than the target.
- One can estimate the amount of work it takes to succeed from the difficulty imposed by the target

# Total possible outcomes

216 = 6 * 6 * 6

- Each die has 6 outcomes

| Target | number of possible ways |
| --- | --- |
| 3 | 1 |
| 4 | 3 |
| 5 | 6 |
| 6 | 10 |
| 7 | 15 |
| 8 | 21 |
| 9 | 25 |
| 10 | 27 |
| 11 | 27 |
| 12 | 25 |
| 13 | 21 |
| 14 | 15 |
| 15 | 10 |
| 16 | 6 |
| 17 | 3 |
| 18 | 1 |

# Easy Target

## Target is 12

- The player must throw 11 = 12 - 1 or less to win
- The number of possible ways to win is 1+3+6+10+15+21+25+27+27 = 135

## The probability of win is 135/216

# Difficult Target

## Target is 5

- The play must throw 4 = 5 - 1 or less to win
- The number of possible ways to win is 1+3 = 4

## The probability of win is 4/216