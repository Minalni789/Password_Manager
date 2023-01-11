# Password_Manager
This is a program that allows the user to store and retrieve passwords.
The program uses the Fernet module from the cryptography library, which 
is a symmetric encryption method that uses a key to encrypt and decrypt data.
The program uses a key file key.key to encrypt and decrypt the password, the key is generated using Fernet.generate_key() function.
This is a basic implementation that I learned while practicing my python skills, it's not a way safe enough to store passwords.
