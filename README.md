# Cryptology and Hashing 

## Cryptology
- *Cryptography*: Art and science of writing secrets or hide information.
- *Cryptanalysis*: Art and science of braking the cipher text.

### Objectives of Cryptography
1. Confidentiality: The information cannot be understood by anyone for whom it was unintended.
2. Integrity: The information cannot be altered in storage or transit between sender and intended receiver without the alteration being detected
3. Nonrepudiation: The creator/sender of the information cannot deny at a later stage his or her intentions in the creation or transmission of the information 
4. Authentication: The sender and receiver can confirm each other’s identity and the origin/destination of the information.

### Types of Cryptograpgy
<img width="642" alt="Cryptography" src="https://github.com/NayanDZ/CH/assets/65315090/6e9bad18-f92b-455d-8126-83c0140b013a">

| Symmetric Key | Asymmetric Key |
| ------------- | ------------- |
| Sender & receiver share a single key that is used to encryption & decryption the message  | Different key are used to encryption & decryption the message |
| Size of cipher text is same or smaller than the original plain text  | Size of cipher text is same or larger than the original plain text |
| Encryption process is very fast  | Encryption process is slow |
| It is usedn when larger amount of data is required to transfer  | It is used to transfer small amount of data |
| Provide only Confidentiality   | It provide confidentiality, authenticity and non-repudiation |

## Hashing
Hashing is the transformation of a string of characters into a usually shorter fixed-length value or key that represents the original string.

|  | Encryption | Hashing |
| ------------- | ------------- | ------------- |
| Defination | Two-way function take plain text data and turn into ciphertext. | One-way method of hidding data using hashing alhorithum that turn plain text into unique hash digest. |
| Reversible or Irreversible | Reversible | Irreversible |
| Variable or Fixed Length Output | Variable Length | Fixed Length |
| Types | Symmetric & Asymmetric | Hashing |
| Algorithms | RC4, AES, DES, RSA, ECDSA | SHA-1, SHA-2, MD5, CRC32, WHIRLPOOL |

