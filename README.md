## Links
- [Senior](https://www.asksenior.in/learn)
- [TLE Eliminators](https://www.tle-eliminators.com)

## Dynamic Programming

<details>
<summary>Problems</summary>

- [DP Sheet AtCoder](https://atcoder.jp/contests/dp/tasks)
- [DP Sheet CSES](https://cses.fi/problemset/)
- [Divisible Group Sums](https://vjudge.net/problem/lightoj-1125)
- [Knapsack 2](https://atcoder.jp/contests/dp/tasks/dp_e)
- [An Easy LCS](https://vjudge.net/problem/lightoj-1110)
- [Coin Change (II)](https://vjudge.net/problem/lightoj-1232)
- [Candies](https://atcoder.jp/contests/dp/tasks/dp_m)
- [Increasing Subsequence](https://cses.fi/problemset/task/1145)
- [Removal Game](https://cses.fi/problemset/task/1097)
- [Two Sets II](https://cses.fi/problemset/task/1093)
- [Slimes](https://atcoder.jp/contests/dp/tasks/dp_n)
- [Array Walk](https://codeforces.com/contest/1389/problem/B)
  <details>
  <summary>Note</summary>
  In my solution, why it is needed to use total_left_move as state where total_move doesn't?
 Why total_left_move changes the futureLet's look at a concrete scenario where omitting total_left_move from the state breaks your logic. Assume $z = 2$ and $k = 5$.Imagine reaching index i = 3 with prev_move = 1 (meaning you just arrived here by moving right) via two different paths:Path A: You reached index 3 having used 0 left moves so far.From this point on, you are still allowed to make up to 2 left moves. This opens up options to cycle back and forth on high-value elements nearby.Path B: You reached index 3 having already used 2 left moves so far.From this point on, you are allowed to make 0 left moves. You can only move right.If your DP table only checks dp[i][prev_move], it treats Path A and Path B as completely identical.If Path B reaches index 3 first in your recursion, it calculates the maximum score possible (which is heavily restricted because it cannot move left anymore) and stores it in dp[3][1]. Later, when Path A reaches index 3, your code sees that dp[3][1] is already calculated, skips the recursion, and blindly returns that heavily restricted score—completely wiping out its ability to use its 2 available left moves.
  </details>

</details>


## Number Theory

<details>
<summary>Problems</summary>

- [No Cost Too Great (Easy Version)](https://codeforces.com/contest/2154/problem/C1)
- [Stable Groups](https://codeforces.com/contest/1539/problem/C)
- [M-arrays](https://codeforces.com/contest/1497/problem/B)
- [Ugly Numbers](https://vjudge.net/problem/uva-136)
- [Chef and Prime Divisors](https://vjudge.net/problem/codechef-chapd)
- [Again Prime? No Time.](https://vjudge.net/problem/uva-10780)
- [Trailing Zeroes (I)](https://vjudge.net/problem/lightoj-1028)
- [Integer Divisibility](https://vjudge.net/problem/lightoj-1078)
- [Divisors 2](https://vjudge.net/problem/spoj-div2)
- [Odd Numbers of Divisors](https://vjudge.net/problem/spoj-odddiv)
- [Swords](https://codeforces.com/contest/1216/problem/D)
- [Power Sequence](https://codeforces.com/contest/1397/problem/B)
- [How Many bases?](https://vjudge.net/problem/uva-12216)
- [Elections in Saransk (easy version)](https://codeforces.com/contest/2236/problem/F1)

</details>


## Combinatorics

<details>
<summary>Problems</summary>

- [Tiles](https://codeforces.com/contest/1178/problem/C)

</details>


## Modulo and Binary Exponentiation

<details>
<summary>Problems</summary>

- [Modulo](https://vjudge.net/problem/Toph-modulo)
- [Geometric Progression](https://vjudge.net/problem/AtCoder-abc293_e)

</details>

## Graph Theory

<details>
<summary>Problems</summary>

- [Nearest Opposite Parity](https://codeforces.com/contest/1272/problem/E)
- [Trapped in the Witch's Labyrinth](https://codeforces.com/contest/2034/problem/C)
- [Drunken Maze](https://codeforces.com/contest/2041/problem/D)

</details>


## Segment Tree

<details>
<summary>Problems</summary>

- [Number of Minimums on a Segment](https://codeforces.com/edu/course/2/lesson/4/1/practice/contest/273169/problem/C)
- [Interesting Array](https://codeforces.com/contest/482/problem/B)
- [SUM and REPLACE](https://codeforces.com/contest/920/problem/F)

</details>


## Offline Queries

<details>
<summary>Problems</summary>

- [Yaroslav and Divisors](https://codeforces.com/contest/301/problem/D)

</details>


## Bitmask

<details>
<summary>Problems</summary>

- [Preparing Olympiad](https://codeforces.com/contest/550/problem/B)
- [Little Girl and Maximum XOR](https://codeforces.com/contest/276/problem/D)
- [Sum of XOR Functions](https://codeforces.com/contest/1879/problem/D)
- [Interesting Array](https://codeforces.com/contest/482/problem/B)
- [Max Sum OR (Hard Version)](https://codeforces.com/contest/2146/problem/D2)
- [The 67th XOR Problem](https://codeforces.com/contest/2218/problem/E)
- [Test Generator](https://codeforces.com/contest/2203/problem/C)

</details>


## Binary Search

<details>
<summary>Problems</summary>

- [K-th Sum](https://codeforces.com/problemset/problem/XXXX)
- [Chat Ban](https://codeforces.com/problemset/problem/YYYY)
- [Scuza](https://codeforces.com/contest/1742/problem/E)

</details>


## Two Pointers

<details>
<summary>Problems</summary>

- [Monocarp's String](https://codeforces.com/problemset/problem/2145/C)
- [Binary Deque](https://codeforces.com/contest/1692/problem/E)
- [Hidden Knowledge of the Ancients](https://codeforces.com/contest/2149/problem/E)
- [Subarrays with K Different Integers](https://leetcode.com/problems/subarrays-with-k-different-integers/description/)

</details>


## Difference Array

<details>
<summary>Problems</summary>

- [Greg and Array](https://codeforces.com/contest/295/problem/A)
- [Karen and Coffee](https://codeforces.com/contest/816/problem/B)
- [Little Girl and Maximum Sum](https://codeforces.com/contest/276/problem/C)

</details>




## Just Fix It

<details>
<summary>Problems</summary>

- [Sum of Two Values](https://codeforces.com/problemset/gymProblem/102961/G)
- [ Subarray Divisibility](https://codeforces.com/problemset/gymProblem/102961/ZC)

</details>


## Super Implementation Technique

<details>
<summary>Problems</summary>

- [Divisible Pairs](https://codeforces.com/contest/1931/problem/D)
- [Find the Different Ones!](https://codeforces.com/contest/1927/problem/D)
- [Romantic Glasses](https://codeforces.com/contest/1915/problem/E)
- [Bracket Coloring](https://codeforces.com/contest/1837/problem/D)

</details>

## Need to be Handled Smartly

<details>
<summary>Problems</summary>

- [Mathematically Hard](https://vjudge.net/problem/lightoj-1007)
- [Primal Fear](https://vjudge.net/problem/spoj-vectar8)
- [Ugly Numbers](https://vjudge.net/problem/uva-136)
</details>

## Regular Bracket Sequence

<details>
<summary>Problems</summary>

- [Cost of a Bracket Sequence](https://codeforces.com/contest/2233/problem/C)

</details>


## Random

<details>
<summary>Problems</summary>

- [Catching the Krug](https://codeforces.com/contest/2152/problem/B)
- [ Friends and the Restaurant](https://codeforces.com/contest/1729/problem/D)
- [Stone Age Problem](https://codeforces.com/contest/1679/problem/B)
- [Jumping Through Segments](https://codeforces.com/contest/1907/problem/D)
- [Production of Snowmen](https://codeforces.com/contest/2182/problem/C)
- [Racing](https://codeforces.com/contest/2110/problem/C))
- [Flower Boy](https://codeforces.com/contest/2106/problem/D)

</details>



