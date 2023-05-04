import random

 
plaintext_alphabet = "abcdefghijklmnopqrstuvwxyz"
ciphertext_alphabet = "CIPHERABDFGJKLNOQSTUVWXYZ"


cipher_dict = dict(zip(plaintext_alphabet, ciphertext_alphabet))


message = input("enter the message: ")


encrypted_message = ""


for ch in message:
        if ch.isalpha():
            
            if ch.islower():
                 encrypted_ch = cipher_dict[ch]
            else:
                 encrypted_ch = cipher_dict[ch.lower()].upper()
    
        else:
            encrypted_ch = ch
    
    
        encrypted_message += encrypted_ch


print("Encrypted message:", encrypted_message)
print("Cipher key:", cipher_dict)
