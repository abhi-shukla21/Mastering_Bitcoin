# Chapter 4: Keys, Addresses

### Introduction

- Ownership of bitcoin is established through *digital keys, bitcoin addresses and digital signatures*.
- Digital keys are created and saved in user files and databases called *wallets* which are not a part of the bitcoin network.



### Public key cryptography and cryptocurrency

- Bitcoin uses elliptic curve multiplication as a basis of it's cryptography.

- k -----Elliptic-curve multiplication------>K------Hashing----->A

  private														public					BTC

  key															   key						address

##### Private keys

- A number picked at random

- Used to create signature required for txn

  ###### Generating a private key from a random number

##### Public keys

*K = k \* G* 

K = public key, k = private key, G = constant generator point

##### Elliptic Curve Cryptography Explained 

![image-20210629133224402](C:\Users\Abhishek\Mastering_Bitcoin\img\image-20210629133224402.png)

- Bitcoin uses secp256k1 which is

y<sup>2</sup> = (x<sup>3</sup> + 7) over (F<sub>p</sub>)

or 

y<sup>2</sup> mod p = (x<sup>3</sup> + 7) mod p

