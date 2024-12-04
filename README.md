# Phishing Analysis Lab 2

## Objective

Putting phishing analysis skills to the test by triaging and gathering information about an ongoing phishing campaign from Blue Team Labs Online.

### Skills Learned

- Identifying phishing techniques and tactics used in malicious emails.
- Extracting key information, such as email headers, URLs, and attachment metadata.
- Analyzing attachments for potential malicious content.
- Recognizing indicators of compromise (IOCs) within email artifacts.
- Enhancing investigative and analytical skills for email-based threats.

### Tools Used

- VirtualBox for an isolated environment, using a Windows 10 virtual machine and snapshots for analysis
- VirusTotal to scan the email attachment and URLs, identifying potential malware and phishing indicators
- whois.domaintools for reverse DNS on orginating IP Address of the email
- URL2PNG, to view the heading text on the web page (of the suspicious URL)
- Notepad for text editing and text viewing
  
## Steps
#### 1. Analyse the suspicious email
<img width="510" alt="image" src="https://github.com/user-attachments/assets/be0f1e2d-3591-488c-9884-06107c1497cc">
<img width="497" alt="image" src="https://github.com/user-attachments/assets/03f4ca20-c6a2-412f-b2fd-1c80f91fdf7e">

#### 2. Analyse the suspicious email header (a snippet is provided here)
<img width="406" alt="image" src="https://github.com/user-attachments/assets/fdf2f998-3357-4b30-9d14-c263c079d852">

#### 3. Using URL2PNG to see what is the heading text on this page
<img width="338" alt="image" src="https://github.com/user-attachments/assets/c4ad1d00-fad6-43f2-a088-a76a680ce677">

#### 4. Use VirusTotal to analyse the suspicious URLs in the email 
<img width="499" alt="image" src="https://github.com/user-attachments/assets/29d302e3-4b67-43c4-9468-03cf5a3c2d9e">
<img width="502" alt="image" src="https://github.com/user-attachments/assets/5f45d4d5-723e-4d4b-954c-3043555bac9e">
<img width="500" alt="image" src="https://github.com/user-attachments/assets/45f3d919-06af-4f90-a96b-9e0a13da3950">


## Results
<img width="360" alt="image" src="https://github.com/user-attachments/assets/fdce6f20-9ade-4739-8a98-d2828f195cd7">
<img width="350" alt="image" src="https://github.com/user-attachments/assets/b259055f-f504-47cd-87d8-caa6a37d79d8">



