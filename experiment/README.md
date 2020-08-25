This folder has <br>
### Aim-Must be able to understand the concept of cryptography.<br>

### Theory<br>
RSA (Rivest–Shamir–Adleman) is one of the first public-key cryptosystems and is widely used for secure data transmission. The acronym RSA is the initial letters of the surnames of Ron Rivest, Adi Shamir, and Leonard Adleman, who publicly described the algorithm in 1977. In such a cryptosystem, the encryption key is public and distinct from the decryption key which is kept secret (private). In RSA, this asymmetry is based on the practical difficulty of factoring the product of two large prime numbers. A user of RSA creates and then publishes a public key based on two large prime numbers, along with an auxiliary value. The prime numbers must be kept secret. Anyone can use the public key to encrypt a message, but only someone with knowledge of the prime numbers can decode the message. The RSA algorithm involves four steps: key generation, key distribution, encryption and decryption. A basic principle behind RSA is the observation that it is practical to find three very large positive integers e, d and n such that with modular exponentiation for all integers m (with 0 ≤ m < n), and that knowing e and n, or even m, it can be extremely difficult to find d. RSA involves a public key and a private key. The public key can be known by everyone, and it is used for encrypting messages. The intention is that messages encrypted with the public key can only be decrypted in a reasonable amount of time by using the private key. The public key is represented by the integers n and e; and, the private key, by the integers d and n. In Java we use Big Integers for calculating the above mentioned values and some algorithmic functions are to be created for fully implementing the algorithm.<br>

### Procedure<br>
1.User has to provide two large Prime numbers for P and Q in the text boxes provided.<br>
2.Click on Submit and the appropriate value of e is displayed to be chosen from a list.<br>
3.Click on Submit and the details about P and Q is displayed.<br>
4.Public key and Private key is also calculated using given formulae and displayed then.<br>
5.The message to be sent should be entered now in the "Enter message" text box.<br>
6.Click on Encrypt button and message is encrypted using given formulae and displayed on sender's end.<br>
7.Click on Send button to send the message to the reciever.<br>
8.Click on Decrypt button to decrypt the recieved messsage.<br>
9.The sent message is displayed on reciever's end.<br>

### Pre Test
### Post Test
### References<br>
https://www.geeksforgeeks.org/rsa-algorithm-cryptography/<br>
https://www.tutorialspoint.com/cryptography_with_python/cryptography_with_python_understanding_rsa_algorithm.htm<br>

