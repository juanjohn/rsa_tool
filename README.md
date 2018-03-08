# rsa_tool

A python script written with the intend to demonstrate a vulnerability in [rsa cryptography](https://en.wikipedia.org/wiki/RSA_(cryptosystem)).

The vulnerability exists only if the two large primes that are chosen to compute n are very close to each other (the distance between the numbers can be iterated in feasible time limits).

In such a scenario on can use [fermat factorization](https://en.wikipedia.org/wiki/Fermat%27s_factorization_method).
