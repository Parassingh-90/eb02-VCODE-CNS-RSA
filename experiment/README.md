This folder has <br>
### Aim<br>
Student must be able to understand the concept of cryptography.<br>

### Theory<br>
<div align="justify">RSA (Rivest–Shamir–Adleman) is one of the principal open key cryptosystems and is broadly utilized for secure information transmission. The abbreviation RSA is the underlying letters of the family names of Ron Rivest, Adi Shamir, and Leonard Adleman,who publicly announced the algorithm in 1977. This cryptosystem uses, 2 different keys i.e public key and private key. In RSA factoring the product of two large prime numbers are very difficult. Based on this prime number sender generate a key pair value i.e public and private key. User announced the public key to publicly for encrypting the data and kept the private key secretly. To decrypt the message user use the owned private key. In RSA algorithm -key generation, key distribution, encryption and decryption steps are used to secure the message transmission. The Most importance principle behind RSA is that it is practical very difficult to find three very large positive integers e, d and n such that with modular exponentiation for all integers m (with 0 ≤ m < n), and that knowing e and n, or even m, it can be extremely difficult to find d. RSA involves a public key and a private key for proper securing the data. The public key is announced to everyone, and it is used for encrypting messages. The message/data can encrypted by anyone with the help public key of receiver and can only be decrypted by using the private key of receiver. The public key is represented by the value of n and e; and, the private key, by the value of d and n. In Java we use Big Integers for calculating the above mentioned values and some algorithmic functions are to be created for fully implementing the algorithm.<br></div>

### Procedure<br>
1. User has to provide two large Prime numbers for P and Q in the text boxes provided.<br>
2. Click on Submit and the appropriate value of e is displayed to be chosen from a list.<br>
3. Click on Submit and the details about P and Q is displayed.<br>
4. Public key and Private key is also calculated using given formulae and displayed then.<br>
5. The message to be sent should be entered now in the "Enter message" text box.<br>
6. Click on Encrypt button and message is encrypted using given formulae and displayed on sender's end.<br>
7. Click on Send button to send the message to the reciever.<br>
8. Click on Decrypt button to decrypt the recieved messsage.<br>
9. The sent message is displayed on reciever's end.<br>

### Pre Test<br>
Q 1. Which is an example of asymmetric encryption?<br>
<b>a. RSA<br></b>
b. Blowfish<br>
c. AES<br>
d. DES<br>

Q 2. What is disadvantage of symmetric encryption?<br>
a. Complex<br>
<b>b. Secured Secret Key Transmission<br></b>
c. Not much used<br>
d. Less Secure Encryption<br>

Q 3. What part of encryption remains secret?<br>
a. Public Key<br>
<b>b. Private Key<br></b>
c. Both<br>
d. None<br>

Q 4. Why we need encryption?<br>
a. Make Fast Transmission<br>
<b>b. Make Secured Transmission<br></b>
c. Not needed<br>
d. Easy Access<br>

Q 5. Which one is a prime number?<br>
a. 35<br>
<b>b. 53<br></b>
c. 39<br>
d. 51<br>


### Post Test<br>
Q 1. What is the formula for encryption of message?<br>
a. Message*n<br>
b. Message^n mod phi<br>
<b>c. Message^e mod n<br></b>
d. e^n mod phi<br><br>

Q 2. What is the formula for decryption of message?<br>
a. Message*d<br>
<b>b. Message^d mod n<br></b>
c. Message^e mod n<br>
d. d^n mod phi<br>

Q 3. What is public key?<br>
a. Combination of (d,n)<br>
<b>b. Combination of (e,n)<br></b>
c. e<br>
d. phi<br>

Q 4. What is private key?<br>
<b>a. Combination of (d,n)<br></b>
b. Combination of (e,n)<br>
c. e<br>
d. phi<br>

Q 5. Let two prime are p=3 and q=5.Public key is e=5 and Private keys d=17. Given Message is "HI" find the ciphertext<br>
a. 16<br>
<b>b. 17<br></b>
c. 18<br>
d. 19<br>

### References<br>
1. Cryptography and Network Security, Atul Khate, 2nd edition, TMH, 2006 <br>
2. Cryptography and Network security, William Stallings, 4th edition, Pearson Education, 2010
