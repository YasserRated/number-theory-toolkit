# Number Theory Toolkit (C++)

A **comprehensive and professional number theory toolkit** for **competitive programming** and **problem solving**.  
This header file includes optimized implementations of the most important number theory algorithms.

---

## 🚀 Features
- GCD & LCM
- Fast Power & Modular Exponentiation
- Prime Check & Sieve of Eratosthenes
- Euler’s Totient Function
- Extended Euclidean Algorithm
- Modular Inverse
- Chinese Remainder Theorem (CRT)
- Fibonacci (Fast Doubling)
- Miller-Rabin Primality Test
- Pollard's Rho Factorization
- Number Theoretic Transform (NTT)

---

## 🛠️ Usage
Include the header file in your project:

```cpp
#include "number_theory.hpp"
using namespace nt;

int main() {
    cout << gcd_t(48, 18) << "\n";  // Output: 6
    cout << lcm_t(12, 18) << "\n";  // Output: 36
    cout << mod_pow(2, 10, 1e9+7) << "\n";  // Output: 1024
}

```

---

## 📂 File Structure
```
number-theory-toolkit/
├── number_theory.hpp   # The main toolkit header file
├── example.cpp         # Example usage file
└── README.md           # Project documentation
```
