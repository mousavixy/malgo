# MAlgo
Math-Related Algorithms

List of Algorithms:
- Primality Testing Algorithms:
  - AKS Primality Test: A deterministic algorithm that determines whether a number is prime in polynomial time.
  - Miller-Rabin Primality Test: A probabilistic algorithm used to test the primality of an integer.
  - Fermat Primality Test: A probabilistic test based on Fermat's little theorem to check if a number is prime.
  - Solovay-Strassen Primality Test: A probabilistic test that uses Euler's criterion for primality testing.
  - Lucas-Lehmer Test: A deterministic test for the primality of Mersenne numbers.

- Integer Factorization Algorithms:
  - Pollard's Rho Algorithm: A probabilistic algorithm for integer factorization, particularly effective for finding small factors.
  - Quadratic Sieve: An efficient algorithm for factoring large integers, especially those with up to 100 digits.
  - General Number Field Sieve (GNFS): The most efficient classical algorithm known for factoring large integers.
  - Lenstra Elliptic Curve Factorization: Uses elliptic curves to factorize integers, effective for finding relatively small factors.
  - Pollard's p−1 Algorithm: Efficient for integers with factors p such that p−1 has only small prime factors.

- Greatest Common Divisor (GCD) Algorithms:
  - Euclidean Algorithm: Computes the GCD of two integers through iterative division.
  - Extended Euclidean Algorithm: An extension that also finds integer coefficients for Bézout's identity.
  - Binary GCD Algorithm (Stein's Algorithm): Computes the GCD using binary operations, often more efficient for large integers.

- Modular Arithmetic Algorithms:
  - Modular Exponentiation: Efficiently computes large powers modulo a number, essential for cryptographic applications.
  - Chinese Remainder Theorem Algorithm: Solves systems of simultaneous congruences with pairwise coprime moduli.
  - Tonelli-Shanks Algorithm: Finds square roots modulo a prime number.

- Discrete Logarithm Algorithms:
  - Baby-Step Giant-Step Algorithm: A space-time tradeoff algorithm for computing discrete logarithms in a finite group.
  - Pollard's Rho Algorithm for Discrete Logarithms: A probabilistic algorithm to compute discrete logarithms in cyclic groups.
  - Index Calculus Algorithm: Efficient for computing discrete logarithms in large prime fields, particularly in cryptographic applications.

- Continued Fraction Algorithms:
  - Continued Fraction Expansion Algorithm: Represents real numbers as continued fractions, useful in approximations and solving Diophantine equations.
  - Pell's Equation Solver: Uses continued fractions to find integer solutions to the equation x² - Dy² = 1.

- Lattice Reduction Algorithms:
  - Lenstra–Lenstra–Lovász (LLL) Algorithm: Finds a nearly orthogonal basis for a lattice, with applications in number theory and cryptography.

- Elliptic Curve Algorithms:
  - Elliptic Curve Point Multiplication: Computes multiples of points on elliptic curves, fundamental in elliptic curve cryptography.
  - Schoof's Algorithm: Determines the number of points on an elliptic curve over a finite field.

- Diophantine Equation Solvers:
  - Lagrange's Four Square Theorem Algorithm: Expresses any natural number as the sum of four integer squares.
  - Chakravala Method: An ancient algorithm to find integer solutions to quadratic Diophantine equations.

- Miscellaneous Algorithms:
  - Sieve of Eratosthenes: Efficiently generates all prime numbers up to a given limit.
  - Sieve of Atkin: A modern, faster algorithm to find all prime numbers up to a specified integer.
  - Berlekamp's Algorithm: Factors polynomials over finite fields, with applications in coding theory and cryptography.
  - Shor's Algorithm: A quantum algorithm for integer factorization and discrete logarithms, exponentially faster than classical algorithms.
