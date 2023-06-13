# Todos

### 2023-06-12

- Calculate the league table.
- Write a function to calculate the league table from a data file.
- Apply the function to three seasons.

### 2023-06-10

- Read in the 2022-2023 EPL data from http://www.football-data.co.uk
  into a data frame.
- How many games were played?
- Remove all columns except `HomeTeam`, `AwayTeam`, `FTR`, `HTR`,
  `FTHG`, `FTAG`.  You can add any other columns you find interesting.
- Calculate the total number of goals scored by Manchester City.
- Calculate the total number of goals scored by each team as a table.
- Calculate the goal difference for all teams.

### 2023-06-06

These exercise are related to a random walk.  Imagine you toss a coin;
if it is heads you move one step forward, otherwise one step backward.
If you plot your position over time, you will get a random walk.  We
will simulate that here.

- Write a function `f` that takes a number between 0 and 1; if the
  number is more than 0.5, it returns +1 and -1 otherwise.
- Use the function `rand` to generate 100 random numbers between 0
  and 1. Using broadcasting, transform the 100 random numbers to +/-1.
  These are your random steps forward (+1) or backward (-1).
- Calculate your position after each step by taking a cumulative sum
  of all previous steps.  Plot this array.  This is a random walk over
  time.
- Write a function to generate a random walk with `n` steps.
- Write a function to generate `m` random walks with `n` steps each.

### 2023-06-04

- Take the first 20 Fibonacci numbers and put them in an Integer array
  (use assignment to an array)
- Square all the first 20 Fibonacci numbers (use map or the broadcast
  operator).
- The limit of the ratio of consecutive Fibonacci numbers is the
  Golden Ratio. Use a `while` loop to calculate the Golden Ratio to 5
  decimal places.
- Plot the ratio of consecutive Fibonacci numbers for the first 100
  Fibonacci numbers.  (Make an array with the ratios, then plot
  using the `Plots` package.)

### 2023-06-01

- Write a function to calculate the first n numbers in the Fibonacci
  sequence.  The integer n should be an argument of the function.
- Write a function to calculate e by summing the first n terms of the
  sequence 1 + 1/1! + 1/2! + 1/3! + .... This should use a for loop.
- Write a function to calculate e by summing the above sequence until
  the tersm being added is smaller than a pre-specified number (say
  10^(-8)). This should use a while loop.


### 2023-05-31

- Update journal daily on Github
- Keep reading the Julia tutorial
- Write function to calculate sum of squares of an array
