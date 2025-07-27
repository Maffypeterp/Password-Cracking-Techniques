# Password-Cracking-Techniques
Password cracking refers to the process of recovering passwords from data stored or transmitted by a computer system

### Objective

Password cracking is the process of recovering or guessing a password in order to gain unauthorized access to a computer system, account, or network. The goal was to test system strength and to exploit vulnerabilities.

### Skills Learned

-  Understand how attackers think and operate

-  Skilled in using tools like John the Ripper, Hashcat in a terminal environment.

-  Ability to identify weak vs strong password policies.

-  Learned how salting improves password storage security.

-  Ability to evaluate the effectiveness of different attack methods.

### Tools Used

*** Type: Offline password cracker

*** Platform: Kali Linux

*** File Type: Password Lists

*** Cracking Tools: Using John, Hashcat, with wordlists 


### Steps

Below are the key steps taken in the Password cracking technique:

1. Generate some sample passwords with the file named passwords.txt

This screenshot shows the file name password.txt contains sample passwords.

* Ref 1. [Password Lists](https://github.com/Maffypeterp/Password-Cracking-Techniques/blob/main/Screenshot%202025-07-22%20121214.png)

2. Use openssl to hash the password in MD5 format
 
* Ref 2.

3. The file named hashed_password.txt will contain the MD5 hashes of sample passwords and prepare hashes in a format hashes_john.txt01

This screenshot shows the file name hashed_john.txt01 contains a list of hashed passwords

* Ref 3.[Hashed password]( https://github.com/Maffypeterp/Password-Cracking-Techniques/blob/main/Screenshot%202025-07-22%20121335.png)

4. Crack the hashed passwords with John the Ripper, and John will attempt to match the hashes with the provided passwords.

* Ref 4.

5. Once John finishes view the cracked passwords.

* Ref 5.

Reporting

* Ref 6.


