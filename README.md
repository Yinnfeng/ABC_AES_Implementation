# ABC_AES_Implementation
My First AES implementation trial

  AES is a symmetric cryptographic algorithm that uses a single key
in encryption and decryption.
For further understanding of the algorithm go to: https://en.m.wikipedia.org/wiki/Advanced_Encryption_Standard
 In the codes provided in the AES_CIPHER.java above using the guide of "https://youtu.be/J1RmZZEkN0k"
I was able to create a single client interphase, where:
-I encoded the String = "neertileshima"
-Able to Generate a secret of KEY_SIZE = 128 bits, through a KeyGenerator.getInstance using the AES algorithm to encrypt the text . 
-which I further initiated an encryption cipher mode. Which return the encoded message ( ciphertext)
-Using a similar method a decryption mode was initiated using the same algorithm.
 The decryption mode initiated a decryption using the initial key generated.
- A decrypted plaintext was finally returned and printed out along with the encoded text.

