# caesar-cipher

A simple Python library for encrypting and decrypting text using the Caesar Cipher.

# Features
- Encrypt text using a shift value (1–25)
- Decrypt encrypted text
- Supports both uppercase and lowercase letters
- Written in clean, reusable library-style code
  
# Usage Example

```python
from caesar_cipher import encrypt, decrypt

encrypted = encrypt("Hello World", 3)
print(encrypted)

decrypted = decrypt(encrypted, 3)
print(decrypted)

Output:
Khoor Zruog
Hello World
