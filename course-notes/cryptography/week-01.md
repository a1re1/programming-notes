## History
Ancient Cryptography; early signs of encryption in Egypt; Caesar Cipher
Symmetric Ciphers; until 1976
  - Block Ciphers: DES (2^56); AES(2^128)(2^192)(2^256); Caesar Cipher; Affine Cipher; 3DES(2^112); IBM's Lucifer (2^64); IDEA (International Data Encryption Standard)
  - Stream Ciphers: RC4
  - MAC: message authentication codes
  - PRNG: pseudo-random number generators
Asymmetric ciphers; in 1976 public-key proposed by Diffe, Hellman, and Merkle
  - RSA; Diffe-Hellman key exchange
Hybrid Schemes of both symmetric and asymmetric are used today

## Uses
Cryptanalysis; trying to reveal plain text from a cipher-text method
- Classical Cryptanalysis
  - Mathematical Analysis
  - Brute-Force
- Implementation Attacks (Side Channel Attacks)
- Social Engineering

-public :: asymmetric RSA, ECC
-private :: symmetric DES, AES

## Classical Ciphers
~Convention: lowercase is cipher text; UPPERCASE IS PLAIN TEXT

### Substitution Cipher
- Encrypts Letters instead of bits (like all ciphers until after WWII)
- replace each plain text letter with another letter
Attacks against substitution ciphers
  - (1) Exhaustive Key Search: Try every possible substitution
  - (2) Letter Frequency Analysis

### Caesar (Shift) Cipher
- Special case of substitution cipher where each letter is shifted by a set amount

|Prefix|bits|digits|key space|
|---|---|---|---|
|Kilo K|10|3|2^10 = 1024|
|Mega M|20|6|2^20 = 1 million|
|Giga G|30|9|2^30 = 1.1 billion|
|Tera T|40|12|2^40 = 1.1 trillion|
|Peta P|50|15|2^50 = 1.13 quadrillion|
|Exa E|60|18|2^60|
|Zetta Z|70|21|2^70|
|Yotta Y|80|24|2^80|
|---|90|27|2^90|
