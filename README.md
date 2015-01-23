# Punisher.NaCl (Ed25519 / Curve25519 in Java)

Punisher.NaCl is a Cryptographic Library for Ed25519 signature and verification in JAVA.

It is a Java Port of Chaos.NaCl, which is essentially a C# port of DJ Bernstein's NaCl.

It is significantly faster than equivalent BigInteger implementations.

Currently, Punisher.NaCl supports only:

- Ed25519 Keypair Generation, Signing and Verification.
- SHA512 Hashing
 
This is a work in progress and the API may change at any time.

# Testing and Usability

The library is tested to work well in multiple environments.

- Java 1.6 on Windows x64
- Android 4.4
- Blackberry (With some simple code changes)

# Implementation Details

This is a Direct Port from C# with significant changes in code; due to the unavailability of native unsigned integers in Java. Any, such change should undergo a through code-review / tests with good coverage. That has not been done yet.

- Some parts of the code are not yet fully side-channel timing resistant. But, for most of the code is.




