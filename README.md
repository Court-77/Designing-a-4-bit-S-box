# 4-Bit S-Box Implementation

This repository contains a Python implementation of a 4-bit S-Box used in symmetric cryptography.

## What Is an S-Box?

An S-Box (substitution box) is a nonlinear transformation used in block ciphers to obscure the relationship between plaintext and ciphertext. This 4-bit S-Box maps a 4-bit input to a 4-bit output.

## Mathematical Background

The S-box function is defined as:
S(x) = 3x^2 + 5x^2 + 2x + 7 (mod 16)

For a detailed explanation of the polynomial and S-box generation, see [POLYNOMIAL.md](POLYNOMIAL.md). 
