# Ghidra-Ctf
Started working on some past CTFs recently. This is a simple CTF that I found really interesting.

CTF Description: Try reversing this file? Can ya?
I forgot the password to this file. Please find it for me?

I downloaded the file and placed it in my kali linux VM.
Opened the file in Ghidra(Reverse Engineering Tool)
<img width="1920" alt="Ghidra code browser" src="https://user-images.githubusercontent.com/129632324/229681549-9a3c97b4-a852-4aa7-929a-e2171d3e1351.png">

After scrolling for a few minutes I knew there was a better way to find the flag within the code browser.<img width="637" alt="search code" src="https://user-images.githubusercontent.com/129632324/229681909-e46f8793-ccf4-4e23-a93f-05434f1db202.png">

I used the keyword "CTF" to find the flag. I searched and the code browser output displayed the location, label, namespace, and preview of the keyword "CTF"
Looking under the "preview" tab I see the flag starting with "picoCTF".<img width="1920" alt="flag" src="https://user-images.githubusercontent.com/129632324/229682764-61ff7c7b-8899-4c60-9dd5-958489b64ffb.png">
