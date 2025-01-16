# CODTECH-AD-TASK4
BUILD A TOOL TO ENCRYPT AND DECRYPT FILES USING ADVANCED ALGORITHMS LIKE AES-256.

# PERSONAL DETAILS
Name:Anish Prajapati

Company:CODTECH IT SOLUTIONS

ID: CT08EDO

Domain:Cyber security and Ethical hacking

Duration:December 17th,2024 to january 17th,2025

Mentor:Neela Santhosh Kumar

# Overview of the project:-
THIS PROJECT IS USED TO ENCRYPT AND DECRYPT FILES USING ADVANCED ALGORITHMS LIKE AES-256.

# Key Features

•	AES-256 Encryption

•	Key Derivation

•	File Handling

•	Interactive Command-Line Interface

•	Error Handling

# How It Works
**Encryption Process:-**

Step 1 :- A random salt (16 bytes) and IV (16 bytes) are generated.

Step 2 :- The password and salt are used to derive a 256-bit AES key via PBKDF2.

Step 3 :- The plaintext file is padded using PKCS7 and encrypted block by block.

Step 4 :- The salt, IV, and ciphertext are written to the output file.

**Decryption Process:-**

Step 1:- Reads the salt and IV from the encrypted file.

Step 2:- Reconstructs the key using the password and extracted salt.

Step 3:- Decrypts the ciphertext block by block and removes the padding.

Step 4:- Writes the plaintext to the specified output file.


# Advantages

•	Security: Combines salt, IV, and PBKDF2 to resist brute-force and rainbow table attacks.

•	Portability: The encrypted file contains all the information (salt, IV) necessary for decryption.

•	Ease of Use: Command-line interface makes it simple for users to interact with.

•	Flexibility: Users can encrypt/decrypt files of any type and size.

# OUTPUT

**Encryption Process:-**

![Screenshot 2025-01-16 172216](https://github.com/user-attachments/assets/6099856b-37e6-46b0-8d24-497a8f2f36c3)

![Screenshot 2025-01-16 172249](https://github.com/user-attachments/assets/d7fc9d9a-8e03-4c50-a2b1-15cbdebf8db6)

![Screenshot 2025-01-16 172537](https://github.com/user-attachments/assets/0132ac54-93d6-455e-aced-050d87cf1894)

In the above,  we can see that on opening the file , it will be open in encypted form which lead to not allow anyone to see the data  stored in the file.


**NOTE:-** To open this and get the data present in the file, we need to  decrypt the encrypted file with same pass key or password.


**Decryption Process:-**

![Screenshot 2025-01-16 172642](https://github.com/user-attachments/assets/4e5f5333-f864-4b91-b1ab-f3e6ab30a608)

here, we can see that decrypted file is created.
![Screenshot 2025-01-16 175824](https://github.com/user-attachments/assets/d6b4b2db-21cc-43d7-9397-a55f32187ac3)

On openinng the decrypted file, we can get the data present in the file
![Screenshot 2025-01-16 172605](https://github.com/user-attachments/assets/59f2a310-6046-43cc-a265-e24a3e72d442)

**Incase of wrong password,**
![Screenshot 2025-01-16 172809](https://github.com/user-attachments/assets/7a37b0b8-18bc-4503-ad2c-4bcf3dd54130)



