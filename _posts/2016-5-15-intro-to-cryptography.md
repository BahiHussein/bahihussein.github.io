---
layout: post
title: Introduction To Cryptography
---

## Cryptography
Cryptography is the science of providing security for information. It has been used historically as a means of providing secure communication between individuals, government agencies, and military forces. Today, cryptography is a cornerstone of the modern security technologies used to protect information and resources on both open and closed networks. [source](https://technet.microsoft.com/en-us/library/cc962030.aspx)

According to Webopedia.com, Cryptography is defined as 

>The art of protecting information by transforming it (encrypting it) into an unreadable format, called cipher text. Only those who possess a secret key can decipher (or decrypt) the message into plain text. Encrypted messages can sometimes be broken by cryptanalysis, also called codebreaking, although modern cryptography techniques are virtually unbreakable.


## Encryption

Encryption is the conversion of plain text into cipher text, which cannot be easily understood by anyone except authorized parties.

## Decryption

It is the reverse of encryption. Decryption is the conversion of cipher text to plain text.

![Image of encryption decryption](https://bahihussein.github.com/images/enc-dec.png)

## Types of Encryption

1. Symmetric Cryptography
2. Asymmetric Cryptography (Public Key)

### Symmetric Cryptography 

>Symmetric-key algorithms are algorithms for cryptography that use the same cryptographic keys for both encryption of plaintext and decryption of ciphertext. The keys may be identical or there may be a simple transformation to go between the two keys. The keys, in practice, represent a shared secret between two or more parties that can be used to maintain a private information link. This requirement that both parties have access to the secret key is one of the main drawbacks of symmetric key encryption

[source](https://en.wikipedia.org/wiki/Symmetric-key_algorithm)

![Symmetric Cryptography](https://bahihussein.github.com/images/symmetric.png)

Key(A) is a shared secret sequence of characters shared between to parties. The same key can be used for encryption and decryption 

### Asymmetric Cryptography (Public-key cryptography)

Asymmetric cryptography, is any cryptographic system that uses pairs of keys (public and private keys). The Public Key is used only for encryption and Private Key is used only for decryption.

![Asymmetric Cryptography](https://bahihussein.github.com/images/asymmetric.png)

>In a public-key encryption system, any person can encrypt a message using the public key of the receiver, but such a message can be decrypted only with the receiver's private key. For this to work it must be computationally easy for a user to generate a public and private key-pair to be used for encryption and decryption. The strength of a public-key cryptography system relies on the degree of difficulty (computational impracticality) for a properly generated private key to be determined from its corresponding public key. Security then depends only on keeping the private key private, and the public key may be published without compromising security.
[source](https://en.wikipedia.org/wiki/Public-key_cryptography)



## Study Material 

1. [Journey Into Cryptography Course By KhanAcadaemy](https://www.khanacademy.org/computing/computer-science/cryptography)
