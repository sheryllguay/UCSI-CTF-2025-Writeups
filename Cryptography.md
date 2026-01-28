# Crytography
## Challenge 1: Baby Crypto
![Baby Crypto Challenge](images/baby_crypto.png) <br>
Baby Crypto is a beginner-level cryptography challenge where a text file is provided containing an encoded string. The goal is to identify the encoding method used and decode it to retrieve the flag.<br>
After opening the downloaded text file (Baby_crypto.txt), an encoded string was found:
VUNTSTI1e0IzYXNfNjRfaTVfSzFuZ30= <br>
The presence of **= padding** and the **character pattern** suggested that the string was encoded using **Base64**.<br> 
The Base64 string was decoded using **CyberChef**, producing:<br>
`UCSI25{B3as_64_i5_K1ng}`

---

## Challenge 2: Simple Crypto
![Simple Crypto Challenge](images/simple_crypto.png) <br>
Similar to Baby Crypto, Simple Crypto is a beginner cryptography challenge that builds on basic encoding knowledge. A text file is provided containing an encoded string, and the task is to decode it to reveal the flag.<br>
After opening the downloaded file (Simple_crypto.txt), the following string was found:<br>
5543534932357b4865785f49735f436f6f6c7d <br>
The string consists only of **hexadecimal characters (0–9, a–f)**, indicating that it is **Hex encoding**.
The hex string was decoded using **CyberChef**, resulting in:<br> 
`UCSI25{Hex_Is_Cool}`

---


