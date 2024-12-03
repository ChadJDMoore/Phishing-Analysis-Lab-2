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
<img width="473" alt="image" src="https://github.com/user-attachments/assets/75b8a369-4de2-4b77-9dc6-17697fd719f3">

#### 2. Analyse the suspicious email header (a snippet is provided here)
<img width="473" alt="image" src="https://github.com/user-attachments/assets/ff70cd90-2efe-4110-a5c1-07cd35d182d8">

#### 3. Analyse the suspicious attachment in the email 
<img width="473" alt="image" src="https://github.com/user-attachments/assets/fae98f73-15a3-48b2-8f2a-26455136cded">

#### 4. Perform reverse DNS on the Originating IP address using (whois.domaintools.com)
<img width="473" alt="image" src="https://github.com/user-attachments/assets/1d7b3bf0-14d8-490c-a422-a7a8cfc31164">

#### 5. Using URL2PNG to see what is the heading text on this page
<img width="473" alt="image" src="https://github.com/user-attachments/assets/0c466821-6725-4fa7-a5de-67e60b515e3f">

#### 6. Use VirusTotal to analyse the suspicious URL in the email attachment
<img width="473" alt="image" src="https://github.com/user-attachments/assets/2d6dba06-6275-47a4-b164-71a2ad8bf7e7">


## Results
<img width="473" alt="image" src="https://github.com/user-attachments/assets/532aee1f-c950-444e-97c2-16288318392a">

