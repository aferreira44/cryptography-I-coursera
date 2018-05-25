Criptography is:
  * A tremendous tool
  * The basis form many secutiry mechanisms

Criptography is not:
  * The resolution to all security problems (software bugs and social eng attacks)
  * Reliable unless implemented and used properly
  * Something you should try to invent yourself

* Secure communication
  * SSL - Secure Sockets Layer / TLS

* Protected files on disk

* Symetric Encryption
  * Encryption/Decryption algorithm is publicly known, only secret key is private
  * Never use a proprietary cipher

* Single use key: (one time key)
  * Encrypted email: new key generated for every email

* Multiple use key: (many time key)
  * Key used to encrypt multiple messages
  * Encrypted files: same key used to encrypt many files

* Digital signatures
* Anonymous communication (mixnet)
* Anonymous digital cash (Bitcoin)

* Secure multi-party computation (Elections and private auctions)

* Crypto Magic
  * Privately Outsourcing Computation
  * Zero knowledge (proof of knowledge)

* Three steps in cryptography
  * Precisely specify threat model
  * Propose a construction
  * Prove that breaking construction under threat mode will solve an underlying hard problem

## History of Criptography

* Book: David kahn, "The code breakers" (1996)

* Symmetric Ciphers
  * Substitution cipher
    * Caesar Cipher (no key)

    * How to break a substitution cipher?
      - Use frequency of English letters
      - Use frequency of pairs of letters (digrams)

Question: What is the size of key space in the substitution cipher assuming 26 letters?

Answer: |K∣=26! (26 factorial) = 2^88

  * Vigener cipher (16'th century, Rome)

  * Rotor machines (1870-1943)
    * Hebern machine (single rotor)
    * Enigma (3-5 rotors)

* Data Encryption Standard - DES - (1974)
  * Federal standard for encrypt data
  * Key space = 2^56
  * Block size: 64 bits = 8 characters
  * It's insecure beacuse it Could be broken by brute-force search

* AES (2001): 128 bit key