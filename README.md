# Secure_File_Storage_and_Sharing

- Task: Developing a secure file storage using GoLang to store and share files with people we trust maintaining Confidentiality and Integrity throughout the system. Clients can perform init user, get user data, store file, append file, load file and share file with other users and revoke access permission for other users too. 
- Approach: This required the use of Cryptography concepts considering that the file storage server provided is untrusted. The algorithms used are:
            - Argon2key for password hashing (to prevent brute force attack)
            - RSA encryption and signature verification (for Authentication)
            - AES encryption (for Confidentiality)  
            - HMAC (for Integrity)  
- This was done as a part of course CS628A instructed by Prof. Pramod Subramanyam.