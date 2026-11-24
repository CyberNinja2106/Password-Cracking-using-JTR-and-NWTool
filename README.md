# Password Cracking using JTR and NWTool

## Description
This project demonstrates password recovery on password-protected PDF files using two different methods — John the Ripper (JTR) with the Johnny GUI, and the Networkwalks Hash Calculator & Password Cracker tools (NWTool). Each module extracts the hash from a locked PDF and then cracks it to recover the original password.

## Repository Structure
```
├── JTR/
│ ├── Screenshots/
│ │ ├── Screenshot 2026-11-24 232327.png
│ │ ├── Screenshot 2026-11-24 232349.png
│ │ ├── Screenshot 2026-11-24 232418.png
│ │ ├── Screenshot 2026-11-24 233547.png
│ │ ├── Screenshot 2026-11-24 233859.png
│ │ ├── Screenshot 2026-11-24 234311.png
│ │ ├── Screenshot 2026-11-24 234408.png
│ │ ├── Screenshot 2026-11-24 235749.png
│ │ ├── Screenshot 2026-11-24 235839.png
│ │ ├── Screenshot 2026-11-25 000152.png
│ │ └── Screenshot 2026-11-25 000248.png
│ ├── pdf-1/
│ │ ├── My Locked PDF1 Hash.txt
│ │ └── My Locked PDF1.pdf
│ ├── pdf-2/
│ │ ├── My Locked PDF2 Hash.txt
│ │ └── My Locked PDF2.pdf
│ └── pdf-3/
│ ├── My Locked PDF3 Hash.txt
│ └── My Locked PDF3.pdf
│
└── NWTool/
├── My Locked PDF1/
│ ├── My Locked PDF1 (for NW Tools Lab WK3-PM2).hash.txt
│ └── My Locked PDF1 (for NW Tools Lab WK3-PM2).pdf
├── My Locked PDF2/
│ ├── My Locked PDF2.hash.txt
│ └── My Locked PDF2.pdf
├── My Locked PDF3/
│ ├── My Locked PDF3.hash.txt
│ └── My Locked PDF3.pdf
└── screenshots/
├── Screenshot 2026-11-25 001850.png
├── Screenshot 2026-11-25 001940.png
├── Screenshot 2026-11-25 002005.png
├── Screenshot 2026-11-25 002025.png
├── Screenshot 2026-11-25 002050.png
├── Screenshot 2026-11-25 002106.png
├── Screenshot 2026-11-25 002543.png
└── Screenshot 2026-11-25 002728.png
```
## Module 1: JTR
Used John the Ripper (JTR) along with its GUI version, Johnny, to recover the password of a locked PDF file. The hash was extracted from the PDF using an online PDF hash extractor, saved as a text file, then loaded into Johnny and cracked using a dictionary attack. The recovered password was then used to open the protected PDF.

### Screenshots
![Screenshot](JTR/Screenshots/Screenshot%202026-11-24%20232327.png)
![Screenshot](JTR/Screenshots/Screenshot%202026-11-24%20232349.png)
![Screenshot](JTR/Screenshots/Screenshot%202026-11-24%20232418.png)
![Screenshot](JTR/Screenshots/Screenshot%202026-11-24%20233547.png)
![Screenshot](JTR/Screenshots/Screenshot%202026-11-24%20233859.png)
![Screenshot](JTR/Screenshots/Screenshot%202026-11-24%20234311.png)
![Screenshot](JTR/Screenshots/Screenshot%202026-11-24%20234408.png)
![Screenshot](JTR/Screenshots/Screenshot%202026-11-24%20235749.png)
![Screenshot](JTR/Screenshots/Screenshot%202026-11-24%20235839.png)
![Screenshot](JTR/Screenshots/Screenshot%202026-11-25%20000152.png)
![Screenshot](JTR/Screenshots/Screenshot%202026-11-25%20000248.png)

## Module 2: NWTool
Used the Networkwalks Hash Calculator and Password Cracker (browser-based tools) as an alternative to JTR. The locked PDF was uploaded to the Hash Calculator to extract its hash, which was then pasted into the Password Cracker tool to run a dictionary attack and recover the password. The recovered password was used to open the protected PDF.

### Screenshots
![Screenshot](NWTool/screenshots/Screenshot%202026-11-25%20001850.png)
![Screenshot](NWTool/screenshots/Screenshot%202026-11-25%20001940.png)
![Screenshot](NWTool/screenshots/Screenshot%202026-11-25%20002005.png)
![Screenshot](NWTool/screenshots/Screenshot%202026-11-25%20002025.png)
![Screenshot](NWTool/screenshots/Screenshot%202026-11-25%20002050.png)
![Screenshot](NWTool/screenshots/Screenshot%202026-11-25%20002106.png)
![Screenshot](NWTool/screenshots/Screenshot%202026-11-25%20002543.png)
![Screenshot](NWTool/screenshots/Screenshot%202026-11-25%20002728.png)
