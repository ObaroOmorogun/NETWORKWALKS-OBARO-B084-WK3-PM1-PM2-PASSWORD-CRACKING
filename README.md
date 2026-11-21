 [README.md](https://github.com/user-attachments/files/35210730/README.md)
# Week 3 PM1 Task: Password Cracking with John The Ripper – JTR



**THIS IS FOR EDUCATIONAL PURPOSES**



The objecting of this task is to learn how password cracking works and why it is important to use strong passwords for protection.

**Task:** Crack the password of attached PDF file (My Locked PDF1.pdf, My Locked PDF2.pdf \& My Locked PDF1.pdf3) using JTR JOHN and JTR JOHNNY tools on your Windows PC.

## Solution:



### Step 1:

* Download both the John the Ripper and Johnny GUI from their official websites
* Extract the John The Ripper Zip folder
* Run/install Johnny
* Open Johnny after installation
* Click on settings \& browse (Note: Johnny relies on John the Ripper for the actual work)
* Select John.exe located inside the run folder of the extracted John the Ripper  (ensure John the Ripper is detected)



### Step2: Password cracking stage

* Download the Encrypted pdf file to crack
* Open the hash website and upload the file to find the hash PDF Hash Extractor for Authorized Testing | OHC
* Select and copy the hash value (Note: Hash value should start with “`$pdf$...`” any character before this should be removed)
* Open notepad and save the hash value as a text file (e.g hash1.txt)
* Go back to Johnny and click on “Open password file”
* Select “Open password file (PASSWD format)
* Browse to your saved notepad hash txt file, select it and click on open
* Click on “start new attack” (the password was cracked and I was able to use it to open the locked/encrypted PDF files.)



## Week 3 PM2 Task: Password Cracking with Networkwalks Tools



Password cracking is the process of recovering a password from stored data or a protected file.



* Using the Networkwalks Hash Calculator and Password Cracker tools on Windows laptop.
* Download the encrypted or locked PDF file
* Open the Networkwalks Hash Calculator in your web browser: https://networkwalks.com/hash-calculator/
* Upload the locked PDF file to the Hash Calculator. The tool will read the file and provide the hash value that starts with `$pdf$...`
* Copy the hash value and open the Networkwalks Password Cracker in the web browser and paste
* https://networkwalks.com/password-cracker/
* Start the attack
* The cracked password will be shown on the screen



## Learning points:

* Password safety;
* The use of JTR John and JTR Johnny to recover the password of a protected PDF file;
* The use of Networkwalks to recover the password of a protected PDF file.
* The need to use strong password and not to reuse password.

