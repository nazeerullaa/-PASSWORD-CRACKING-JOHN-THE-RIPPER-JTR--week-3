# PASSWORD-CRACKING-JOHN-THE-RIPPER-JTR--week-3
(JtR) is a password security auditing and password-recovery tool. It works primarily by taking a password hash and trying possible passwords until it finds one that produces the same hash. The Jumbo version supports hundreds of hash/cipher types and many encrypted file formats.

```Password
   ↓
Hash algorithm
   ↓
Password Hash
   ↓
     John the Ripper
   ↓
Try possible passwords
   ↓
Hash each guess
   ↓
Compare with target hash
   ↓
Match?
 ┌───────┴───────┐
 YES             NO
 ↓                ↓
Password found   Try next guess

```
1)Download the 64-bit Windows binary from the official John the Ripper page:
"Official John the Ripper downloads"

2)Look specifically for:
“1.9.0-jumbo-1 64-bit Windows binaries”

3)Choose the 7z or ZIP binary, not the source-code ZIP.

4)Extract it.

Open:
```
john-1.9.0-jumbo-1-win64
└── run
    ├── john.exe
    ├── john.pot
    ├── password.lst
    └── ...
```

In Johnny, select:

...\run\john.exe

One important point: if your extracted folder has directories like src, doc, run, but run contains no john.exe, you almost certainly have the source distribution rather than the precompiled Windows binary. Openwall's installation documentation confirms that source distributions need to be compiled, while binary distributions are ready to run

https://www.openwall.com/john/
<img width="1890" height="915" alt="Screenshot 2026-09-26 173616" src="https://github.com/user-attachments/assets/7fd2b4fd-5ec1-43a0-b191-f614bb313ee8" />

1)Open the official Johnny page:
"Openwall Johnny page"

2)Scroll down to “Binary redistributables.”
You will see:
"Binaries 2.2 (CURRENT)"
Under that,

3)choose:

"Windows → johnny_2.2_win.zip"

4)Download the ZIP file.

After downloading, right-click:

"johnny_2.2_win.zip → Extract All"

5)Open the extracted Johnny folder.

6)Look for the Johnny application/executable (johnny.exe).

"Double-click johnny.exe to launch the GUI."
*Since Johnny is only the frontend, it needs John the Ripper installed separately.* You already have JtR, 
so in Johnny's settings point it to your existing John executable.













































https://openwall.info/wiki/john/johnny
<img width="1887" height="917" alt="Screenshot 2026-09-26 173727" src="https://github.com/user-attachments/assets/f1b4da6a-0c3b-4bb3-ba42-8bed2653d84d" />

<img width="1523" height="1076" alt="Screenshot 2026-09-26 173903" src="https://github.com/user-attachments/assets/48c98428-02b5-44ef-bc64-81e35ddc9650" />
1)After installing johnny(front-end) we have to open johnny software 


2)we have to select path of john(back-end)

3)go to setting->click on browesing-> select john path

<img width="1282" height="920" alt="Screenshot 2026-09-26 173949" src="https://github.com/user-attachments/assets/cca92d88-c6e6-433c-90ec-0e24606d96cc" />
<img width="1917" height="1002" alt="Screenshot 2026-09-26 173836" src="https://github.com/user-attachments/assets/f75bbe6d-741f-436c-9ea1-0e4301367a55" />

Let's download a locked pdf

<img width="1917" height="1032" alt="image" src="https://github.com/user-attachments/assets/fb01dce1-5ef6-459e-aca3-f2e45eb6ecd3" />
# Hashcrack — Definition

Hashcrack is an automated password-cracking tool that uses Hashcat to identify hash types and test password candidates against hashes.
it is used for hash creation 

click on browseing -> select on locked pdf path -> hash is created of that pdf
"copy that hash"
https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

<img width="1886" height="920" alt="image" src="https://github.com/user-attachments/assets/9116de2e-062f-43c6-8437-f78033125ad3" />

<img width="1896" height="1021" alt="Screenshot 2026-09-26 180527" src="https://github.com/user-attachments/assets/d6e093dd-bb08-4895-b8d2-6dedc27d2c48" />

<img width="1892" height="906" alt="Screenshot 2026-09-26 180718" src="https://github.com/user-attachments/assets/3b7e0689-e79f-402e-ae4f-a60cc7a2ca53" />

# Make a text file past that hash

<img width="1508" height="1010" alt="Screenshot 2026-09-26 180754" src="https://github.com/user-attachments/assets/2f9be26c-e6e5-435a-8b4e-d8abfce41b6a" 
  
# Open johnny software select the hash text file 

click start button 

<img width="1541" height="1016" alt="Screenshot 2026-09-26 180849" src="https://github.com/user-attachments/assets/fbe92ec2-e422-4038-8e6f-5fcbe092805f" />

# we can see that password

<img width="872" height="687" alt="Screenshot 2026-09-26 180938" src="https://github.com/user-attachments/assets/b4fd1859-4e9c-4e7f-ba49-73a49bf6808c" />

# let's verified password by entering password

<img width="1915" height="965" alt="Screenshot 2026-09-26 181115" src="https://github.com/user-attachments/assets/3a222dda-4c67-4399-841a-e80388d66599" />
<img width="1025" height="855" alt="Screenshot 2026-09-26 181010" src="https://github.com/user-attachments/assets/1ce83185-2e21-40f3-8637-0028b40835ab" />


# Method 2
upload locked pdf for generate hase
https://networkwalks.com/hash-calculator/
<img width="1200" height="887" alt="image" src="https://github.com/user-attachments/assets/f1e398d1-6ab1-4180-94df-16dec6f6ffac" />
<img width="1247" height="761" alt="Screenshot 2026-09-26 221626" src="https://github.com/user-attachments/assets/1ee6f366-c1a3-4ccc-ba2b-036e7f8db2d8" />
past the hash and crack it https://networkwalks.com/password-cracker/
<img width="1200" height="887" alt="Screenshot 2026-09-26 221654" src="https://github.com/user-attachments/assets/c39b45d4-832e-4929-8c1d-adfbd63eb50f" />

linkedin id :https://www.linkedin.com/in/md-nazeerullaa-51211133a/














MD Nazeerulla
