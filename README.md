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

#### 3. Analyse the suspicious attachment in the email 
<img width="473" alt="image" src="https://github.com/user-attachments/assets/fae98f73-15a3-48b2-8f2a-26455136cded">

#### 4. Perform reverse DNS on the Originating IP address using (whois.domaintools.com)
<img width="473" alt="image" src="https://github.com/user-attachments/assets/1d7b3bf0-14d8-490c-a422-a7a8cfc31164">

#### 5. Using URL2PNG to see what is the heading text on this page
<img width="338" alt="image" src="https://github.com/user-attachments/assets/c4ad1d00-fad6-43f2-a088-a76a680ce677">

#### 6. Use VirusTotal to analyse the suspicious URL in the email attachment
<img width="473" alt="image" src="https://github.com/user-attachments/assets/2d6dba06-6275-47a4-b164-71a2ad8bf7e7">


## Results
<img width="473" alt="image" src="https://github.com/user-attachments/assets/532aee1f-c950-444e-97c2-16288318392a">

