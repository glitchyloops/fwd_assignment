# fwd_assignment
Q1 - Digit Gatekeeper
This program counts numbers between L and R that:

are divisible by K
do not contain digit 0
have a prime digit sum
Functions
isPrime(num) → checks if a number is prime
digitGatekeeper() → takes input (L, R, K), applies conditions, shows count
How to run

Call:

digitGatekeeper();

Then enter:

L (start)
R (end)
K (divisor)

The result is shown using alert(count).
Q2 - Roll Seed Lock
This program transforms a number N using a given seed for 3 iterations, then checks a condition.

Rules

Repeat 3 times:

If N is even → N = N / 2 + seed
If N is odd → N = N * 3 - seed

After 3 steps:

Check if N is a 3-digit number
Check if middle digit of N equals seed
Output
Shows "YES, N" if both conditions are true
Otherwise shows "NO, N"
How to run

Call:

rollSeedLock();

Then enter:

N (starting number)
seed (single digit recommended)
Q3 - Mirror Corridor
Finds the smallest X such that N + X is a palindrome and divisible by K.

Steps
Input N and K
Try X from 0 to 100000
Check if N + X is palindrome and divisible by K
Output smallest X, else -1
Run
mirrorCorridor();
Q4 - Fare Calculator
Calculates total fare using base, distance, delay, and seed.

Rules
fare = base + 7 × distance
If minutesLate > 15 → add 20
If distance > 10 → add 10% extra
If seed is odd → subtract seed
If seed is even → add seed
Final fare is rounded up to nearest multiple of 5
Output

Displays the final calculated fare.

Run
fareCalculator();
Q5 - Skipping Numbers
Adds natural numbers while skipping multiples of (seed + 2) until the sum reaches N.

Logic
divisor = seed + 2
Start from m = 1
Skip numbers divisible by divisor
Keep adding others to sum
Stop when sum ≥ N
Output

Displays:

m → last number checked
sum → final accumulated sum
Run
skippingNumbers();
Q6 - Contest Score Judge
Calculates contest score based on answers and decides PASS/FAIL.

Scoring
Correct (a) → +3 each
Partial (b) → +1 each
Wrong (c) → -2 each
If score < 0 → set to 0
If total questions > 50 → subtract 10
Result
score ≥ 60 → PASS
otherwise → FAIL
Output

Displays: score, status

Run
contestScoreJudge();
