# Enigma
#### Built a simulator for the Enigma cipher machine using Java, encrypting plain text to ciphertext and decoding it back into readable plaintext using an electromechanical rotor mechanism by implementing different permutations of the 26 alphabets. 
#### Utilized ArrayList and OOP paradigm to simulate different types of rotors in the machine. Tested the machine under various different configurations.

## Introduction

This programming assignment is intended to exercise a few useful data structures and an object-based view of a programming problem.
You may have heard of the Enigma machines that Germany used during World War II to encrypt its military communications. This project involves building a simulator for a generalized version of this machine.

The Enigmas effect a substitution cipher on the letters of a message. That is, at any given time, the machine performs a permutation—a one-to-one mapping—of the alphabet onto itself. The alphabet consists solely of the 26 letters in one case (there were various conventions for spaces and punctuation).

For example, the notation (AELTPHQXRU) (BKNW) (CMOY) (DFG) (IV) (JZ) (S) describes seven cycles:

* A maps to E, E to L, L to T, ..., R to U, and U back to A.
* B maps to K, K to N, N to W, and W back to B.
* C maps to M, M to O, O to Y, and Y back to C.
* D maps to F, F to G, and G back to D.
* I maps to V and V back to I.
* J maps to Z and Z back to J.
* S maps to itself.

The inverse permutation just reverses these cycles:
* U maps to R, R to X, ..., E to A, and A back to U.
...
* S maps to itself.

![image](https://user-images.githubusercontent.com/83314726/184457558-96f85cad-92f5-4ed9-8139-d7f6fac3d908.png)

