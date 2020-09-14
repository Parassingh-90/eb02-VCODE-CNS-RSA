## Storyboard (Round 2)

Experiment 3: Write a Java Program to implement RSA algorithm.

### 1. Story Outline:
<div align="justify">
The experiment is based on implementation of RSA algorithm for encryption and decryption of message using asymmetric encryption.
RSA is the initial letters of the surnames of Ron Rivest, Adi Shamir, and Leonard Adleman.The experiment involves generating the public key and private key using two large prime numbers entererd by user and then using the calculated key pairs to encrypt the message and decrypt the message.
The user choses two large prime numbers for P and Q.This evaluates some value of e which plays a vital role in calculation of Public key and Private key. After that user enter the message to be encrypted,sending the message to the reciever and then again decrypting it to plaintext message.Simulator will provide the user a better understanding of the overall procedure involved in RSA algorithm implementation.</div>

### 2. Story:
<div align="justify">
RSA (Rivest–Shamir–Adleman) is one of the principal open key cryptosystems and is broadly utilized for secure information transmission. The abbreviation RSA is the underlying letters of the family names of Ron Rivest, Adi Shamir, and Leonard Adleman,who publicly announced the algorithm in 1977. This cryptosystem uses, 2 different keys i.e public key and private key.In RSA factoring the product of two large prime numbers are very difficult.
Based on this prime number sender generate a key pair value i.e public and private key. User announced the public key to publicly for encrypting the data and kept the private key secretly.To decrypt the message user use the owned private key.
In RSA algorithm -key generation, key distribution, encryption and decryption steps are used to secure the message transmission..
The Most importance principle behind RSA is that it is practical very difficult to find three very large positive integers e, d and n such that with modular exponentiation for all integers m (with 0 ≤ m < n), and that knowing e and n, or even m, it can be extremely difficult to find d. 
RSA involves a public key and a private key for proper securing the data. The public key is announced to everyone, and it is used for encrypting messages. The message/data can encrypted by anyone with the help public key of receiver and can only be decrypted by using the private key of receiver. The public key is represented by the value of n and e; and, the private key, by the value of d and n.
In Java we use Big Integers for calculating the above mentioned values and some algorithmic functions are to be created for fully implementing the algorithm.</div>

#### 2.1 Set the Visual Stage Description:
<div align="justify">
We divide our whole simulator into two parts.The top part comprises the instructions for the simulator and the bottom part is for simulator actions which is further subdivided into simulator representation part and code display part.The home screen shows 2 text boxes for entering values into P and Q.On submitting the form vanishes and is replaced by the form for inputting value of e. Then the details about P, Q, Phi, n and Public-Private key pairs are displayed.
The message to be sent for encryption is to eneterd now in the text box displayed.On submitting a message box with encrypted message and send button is displayed.On clicking send the message is sent to the reciever and displayed on recieving side with a Decrypt button.The decrypt button will decrypt the message and retrieve the plain text.
The side panel continously shows the appropriate code running for the ongoing process.</div>

#### 2.2 Set User Objectives & Goals:

1. The prime objective of this experiment is to demonstrate the process of Encryption and Decryption using RSA algorithm.<br>
2. The simulator visually shows every step so that user may better understand the logic behind the process.<br>
3. To depict the process of public key and private key generation.<br>
4. To display the different scenarios on chosing different values of P and Q.<br>
5. To answer the assesment based on the observations.<br>

#### 2.3 Set the Pathway Activities:

1. User has to provide two large Prime numbers for P and Q in the text boxes provided.<br>
2. Click on Submit and the appropriate value of e is displayed to be chosen from a list.<br>
3. Click on Submit and the details about P and Q is displayed.<br>
4. Public key and Private key is also calculated using given formulae and displayed then.<br>
5. The message to be sent should be entered now in the "Enter message" text box.<br>
6. Click on Encrypt button and message is encrypted using given formulae and displayed on sender's end.<br>
7. Click on Send button to send the message to the reciever.<br>
8. Click on Decrypt button to decrypt the recieved messsage.<br>
9. The sent message is displayed on reciever's end.<br>

##### 2.4 Set Challenges and Questions/Complexity/Variations in Questions:

Q. John wants to set up his own public and private keys. He chooses p = 13 and q = 19 with e = 23. Find d?<br>
A.11<br>
B.<b>47</b><br>
C.37<br>
D.19<br>

Q. For p = 17 and q = 11 and choose e=7. Apply RSA algorithm where message=88 and find the cipher text?<br>
A.80<br>
B.<b>11</b><br>
C.56<br>
D.23<br>


##### 2.5 Allow pitfalls:

1. The simulator is designed for particularly smaller messages and therefore student needs to be attentive while choosing the message to be sent.<br>
2. The student have a great opportunity to try different prime number combinations to implement RSA.<br>
3. The student need to enter different prime numbers for P and Q so attention is needed here or conclusion may differ thereafter.

##### 2.6 Conclusion:

1. Assessment/evaluation of the pre-test and post-test should be given immediately to the user. The moment the student clicks on the answer of his choice, the CORRECT ANSWER should be displayed below the question. This would enable the student to understand whether he is right or wrong.<br>
2. This would prompt the users as to how many answers were correctly answered.<br>
3. The given plain text is to be encrypted using RSA and then answered accordingly.<br>
4. The given Cipher text is to be decrypted using RSA and then answered accordingly.<br>

##### 2.7 Equations/formulas: 

n = P x Q where P,Q are two large Prime numbers<br>
&Phi; = P-1 x Q-1 <br>
e = i such that GCD(i,&Phi;)=1 <br>
d = (k x &Phi; + 1)/e for some integer k <br>
Cipher text = message^e modulus n <br>
Plain text = Cipher^d modulus n <br>

### 3. Flowchart 

<img src="flowchart/flowchart.png"/><br>

### 4. Mindmap:

<img src="mindmap/mindmap.png"/>

### 5. Storyboard :

<img src="storyboard/storyboard.gif"/>
