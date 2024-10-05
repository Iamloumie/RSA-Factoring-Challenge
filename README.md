# RSA Factoring Challenge

This repository contains two main files for the RSA Factoring Challenge:

1. `factors`
2. `rsa`

## Overview

The RSA Factoring Challenge is a project aimed at factoring large numbers, particularly those used in RSA encryption.
This challenge helps in understanding the security of RSA cryptosystems and the difficulty of factoring large numbers.

## Files

### 1. factors

The `factors` file is a script that attempts to find the factors of a given number.
It uses various factorization algorithms to break down composite numbers into their prime factors.

Usage (example, may vary based on implementation):

```
./factors <file>
```

Where `<file>` is a file containing the number to factor.

### 2. rsa

The `rsa` file is focused specifically on factoring numbers used in RSA encryption.
It may be optimized for bi-prime numbers (numbers that are the product of exactly two primes), which are the foundation of RSA keys.

Usage (example, may vary based on implementation):

```
./rsa <file>
```

Where `<file>` is a file containing the RSA number to factor.

## Purpose

The main goals of this challenge are:

1. To factor large numbers efficiently
2. To understand the security implications for RSA encryption
3. To implement and compare different factorization algorithms

## Requirements

- Detailed requirements would depend on the specific implementation of the scripts.
- Likely requires a Unix-like operating system (Linux, macOS, etc.)
- May require specific programming languages or libraries (e.g., Python, C, GMP library)

## How to Use

1. Clone this repository to your local machine.
2. Ensure you have the necessary permissions to execute the files:
   ```
   chmod +x factors rsa
   ```
3. Prepare a file with the number you want to factor.
4. Run the appropriate script with the input file.

## Note

The effectiveness and speed of factoring will depend on the size of the numbers and the algorithms implemented.
Large RSA numbers (2048 bits or more) used in practical cryptography are designed to be computationally infeasible to factor with current technology.
