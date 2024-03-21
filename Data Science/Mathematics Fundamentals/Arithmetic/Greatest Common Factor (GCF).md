#arithmetic 
The Greatest Common Factor (GCF), also known as the Greatest Common Divisor (GCD), is the largest positive integer that divides each of the integers in a set without leaving a remainder. It has important applications in algebra also [[GCF of Algebraic Expressions|GCF of Algebraic Expressions]]. Here are the methods to find it, with examples:
### 1. Prime Factorization Method

- **Steps**:
  1. Factor each number into its prime factors.
  2. Identify the common prime factors across these numbers.
  3. Multiply these common factors together to get the GCF.

- **Example**:
  - Find the GCF of 48 and 180.
  - Prime factors of 48: \(2^4 \times 3\)
  - Prime factors of 180: \(2^2 \times 3^2 \times 5\)
  - Common prime factors: \(2^2 \times 3\) (choose the lowest power of common primes)
  - GCF: \(2^2 \times 3 = 4 \times 3 = 12\)

### 2. Euclidean Algorithm

- **Steps**:
  1. For two numbers, subtract the smaller from the larger.
  2. Repeat with the difference and the smaller number.
  3. Continue until the numbers are equal, which is the GCF.

- **Example**:
  - Find the GCF of 48 and 180.
  - Subtract the smaller from the larger: \(180 - 48 = 132\)
  - Continue with 132 and 48: \(132 - 48 = 84\)
  - Continue with 84 and 48: \(84 - 48 = 36\)
  - Continue with 48 and 36: \(48 - 36 = 12\)
  - Continue with 36 and 12: \(36 - 12 = 24\); \(24 - 12 = 12\); Now both are 12.
  - GCF: 12

### 3. Listing Factors Method

- **Steps**:
  1. List all factors of each number.
  2. Identify the largest factor that appears in all lists.

- **Example**:
  - Find the GCF of 48 and 180.
  - Factors of 48: 1, 2, 3, 4, 6, 8, 12, 16, 24, 48
  - Factors of 180: 1, 2, 3, 4, 5, 6, 9, 10, 12, 15, 18, 20, 30, 36, 45, 60, 90, 180
  - The largest common factor: 12

### Conclusion

Each method leads to the same result but can vary in convenience depending on the numbers involved. The GCF is instrumental in simplifying fractions, dividing things into smaller sections, and other mathematical operations where divisibility is a factor.