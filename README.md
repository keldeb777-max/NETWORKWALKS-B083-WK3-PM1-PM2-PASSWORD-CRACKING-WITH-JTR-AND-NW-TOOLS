# NETWORKWALKS-B083-WK3-PM1-PM2-PASSWORD-CRACKING-WITH-JTR-AND-NW-TOOLS 

Week 3 task of my learning journey as an Intern with network involved Password cracking with Johnny The Ripper and free Networkwalks tools. I have carefully curated this report to showcase the skills i have acquired. 

## Project overview
Johnny The Ripper is a popular password cracking tool used by professionals to test how strong passwords are. It used to be solely for Unix systems but in recent times, have included a GUI version for windows and mac systems. This project shows how Johnny The Ripper (Johnny GUI) and Networkwalks password cracking tools are used to recover the password of an encrypted file.

## Project objectives
The objectives of this project are as follows:

Task 1 - Crack the password of attached PDF file (My Locked PDF1.pdf) using JTR  JOHN and JTR JOHNNY tools on your Windows PC.
Task 2 - Crack the password of the attached PDF file (My Locked PDF1.pdf) using the Networkwalks Hash Calculator and Password Cracker tools on your Windows  laptop. 

## Tools Used
Johnny The Ripper - password cracking tool 

Johnny GUI - graphical user interface for Johnny The Ripper 

[OnlineHashCrack](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php ) - online hash calculator 
Encrypted pdf 

Networkwalks Hash Calculator

Networkwalks Password Cracker

## Project Module 1 - Cracking password of PDF file using JTR 
This task involves the use of Johnny The Ripper and Johnny GUI for windows and to do so I downloaded the two. 
John The Ripper is first downloaded from the from https://www.openwall.com/john/ as shown in the screenshot below. 
<img width="959" height="500" alt="JTR download" src="https://github.com/user-attachments/assets/f25f913d-ac4d-4aff-af62-222e41b682f1" /> 

Next, the GUI of the JTR. Johnny GUI is downloaded from https://openwall.info/wiki/john/johnny 
<img width="836" height="247" alt="Johnny GUI download page" src="https://github.com/user-attachments/assets/43322343-e2e6-4dd0-808b-2898d0938f9d" />

After downloading and installing, I imported the JTR (john.exe) from the file location path to fully set up the Johnny GUI. A screenshot of this activity is shown below. 
<img width="687" height="307" alt="Screenshot 2026-09-24 061334" src="https://github.com/user-attachments/assets/353fe112-e873-4bfc-98b1-33f8faedf207" />

With JTR fully set up, I proceeded to cracking the password of the password protected PDF file, by finding the hash of the file. The file is uploaded unto the hash calculator, OnlineHashCrack. 
<img width="635" height="286" alt="hash2" src="https://github.com/user-attachments/assets/fc4587dd-3a41-40db-8d6d-f778e6f95804" />    
The OnlineHashCracker returns the hash of the protected file. 

`$pdf$4*4*128*-1028*1*16*34eb542eff4e1b0b32d25ce15a9a7281*32*b77872bfc9a24fb2f845066283a8fc1b0021446990b9e4114071a4d9104984c1*32*e7572256e4b552cd57988f5134214b91920d94d7a6bf550ea94a2995c7f2ab02 ` . 

I copied and saved the hash in a txt file. The txt file is uploaded into the Johnny GUI by selecting  'Open password file' and choose the saved txt file that contains the hash and then clicked 'Start new attack'. The password is then ran against the hash file to find the exact password.  
<img width="433" height="340" alt="Password shown" src="https://github.com/user-attachments/assets/99c9c989-d3bf-4111-a7a5-7f8bba609431" /> 
The screenshot above shows the password after the process completed. To test this I opened the file and entered the password given and it was a success. 
<img width="641" height="451" alt="locked" src="https://github.com/user-attachments/assets/599deda2-df74-44eb-9e0a-2012696d46fb" />

<img width="643" height="454" alt="results" src="https://github.com/user-attachments/assets/e524f9d8-c22b-41b0-82a7-7a21e30ffd34" />

---

## Project Module 2 - Cracking the password of a secured PDF file using Networkwalks Hash Calculator and Password Cracker.
The goal of this module is to crack the password of the password-protected file using given Networkwalks Hash Calculator and Networkwalks Password Cracker. 
With the already downloaded file, I proceeded to the [Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator ) . 
The file is uploaded and the hash is returned as shown in the screenshot below. 
File hash: ` $pdf$4*4*128*-1028*1*16*34eb542eff4e1b0b32d25ce15a9a7281*32*b77872bfc9a24fb2f845066283a8fc1b0021446990b9e4114071a4d9104984c1*32*e7572256e4b552cd57988f5134214b91920d94d7a6bf550ea94a2995c7f2ab02 
`

<img width="853" height="502" alt="nw-hash-results" src="https://github.com/user-attachments/assets/16b7ac59-a576-4c48-9ff0-3e20709a5457" />
Next task is to crack the password with [Networkwalks Password Cracker](https://networkwalks.com/password-cracker ). The hash is pasted and the attack is ran by clicking the "Start Cracking" button. 
A hash is ran through dictionary attacks till the right password is found as shown in the screenshot below. 
<img width="674" height="470" alt="nw-passwd-result" src="https://github.com/user-attachments/assets/f5070967-324f-450c-9eaf-605ff6af1601" />

The password shows `1qaz2wsx` .

To verify the password, I tested it against the file. The results is as follows. 
<img width="643" height="454" alt="results" src="https://github.com/user-attachments/assets/6051f042-ad58-4500-abfb-63740b2cd6dd" /> 

## Conclusion 
This project has shown how to crack passwords to a password secure file using John The Ripper GUI and Networkwalks Password cracker. This was also made possible by finding the hash of the files using [OnlineHashCrack](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php ) and the [Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator ) . 

## Recommendation
The project discloses how easy it is for attackers to break dictionary or easy-to-guess passwords. It is important to have hard to guess passwords by shuffling words and symbols. 

# 👤 Author

**Kelvin AGYAPONG DEBRAH**
Cybersecurity Professional B083
<a href="https://www.linkedin.com/in/kelvin-agyapong-debrah-9638b1246">LinkedIn</a> 

---

## 📌 Project Information

**Program Name:** Cybersecurity Internship at Networkwalks | **Week:** 03 | **Project:** Password Cracking with John the Ripper and Networkwalks Password Cracker | **Repository:** GitHub

