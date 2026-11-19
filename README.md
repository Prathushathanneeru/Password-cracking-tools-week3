# Password-cracking-tools-week3
The two ways to crack the password of the locked files using John the Ripper and Networkwalks Password Cracker.  
## John the Ripper(JtR)
The Password cracking tool and System administrators and cybersecurity professionals use the tool to identify weak passwords, perform penetration tests, and recover forgotten credentials through offline hash cracking.
- Download John the Ripper from official website on your windows PC: https://www.openwall.com/john/
- Download Johnny GUI from official website: https://openwall.info/wiki/john/johnny
- From Johnny open path for John the Ripper and perform the operations.
- As per the week3 module1 of Networkwalks to perform password cracking on the locked files.
- Each pdf file has different password and the passwords are obtained by the hash value of that file.
- The hash value can be obtained by the open source of Open the hash website & upload your pdf file to find its hash: https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php
- Save hash value in Text file and open that text file from Johnny, then the password of that particular file is displayed.
## PDF Passwords Cracked Using John the Ripper (JtR) and Hidden Flags Extracted
<img width="1917" height="1018" alt="image" src="https://github.com/user-attachments/assets/247dabc2-12a6-4044-bf25-965babf326d2" />

<img width="1917" height="966" alt="image" src="https://github.com/user-attachments/assets/4aae21ed-7c21-4f48-9307-75fbf558166b" />

<img width="1916" height="1022" alt="image" src="https://github.com/user-attachments/assets/d75cf786-4c79-45da-9815-3146f8c904a6" />

## Networkwalks Password Cracking Tool
- Open Networkwalks Hash Calculator in your web browser: https://networkwalks.com/hash-calculator/
- Upload the locked PDF file to the Hash Calculator. The tool will read the file and give you the hash value.
- Copy the hash value and paste in the Password Cracking dictionary created by the Networkwalks.
- Open the Networkwalks Password Cracker in your web browser: https://networkwalks.com/password-cracker/
- In that dictionary the Built-In list (100 passwords) are present.
- In the Networkwalks Password Cracker tool has a feature to upload our own list of passwords or by using tool we can generate 'N' number of password list.
- Finally, the matched password is displayed and that password is used to unlock the pdf files.
## PDF Password Cracked using Networkwalks Password Cracker Tool

<img width="1917" height="1016" alt="image" src="https://github.com/user-attachments/assets/8002dea0-15ae-4e1d-8d9a-a75d00586e4b" />

<img width="647" height="822" alt="image" src="https://github.com/user-attachments/assets/1a6eda46-3591-434d-8926-8d8f3811584a" />

## Key Learnings

- Understood how document password protection works and how password hashes are extracted for security analysis.
- Gained hands-on experience with John the Ripper and Johnny 2.2 for password auditing.
- Explored password recovery techniques and learned how they can be used to assess password strength.
- Recognised the importance of password complexity in protecting sensitive files against unauthorised access.
- Learned how password auditing helps identify weak passwords and contributes to improving overall security.


