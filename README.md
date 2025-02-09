# Web Application Penetration Testing

## Project Overview
The objective of this project is to conduct a penetration testing on a simulated web application to identify and exploit vulnerabilities.

## Objectives
1. Identify and exploit vulnerabilities within the web application.
2. Assess the potential impact of discovered vulnerabilities.

## Tools and Technologies
- **Burp Suite**: Used for web application security testing and vulnerability scanning.
- **OWASP ZAP**: Employed for automated security testing and identifying common vulnerabilities.
- **SQLmap**: Utilized for detecting and exploiting SQL injection flaws.
- **Nmap**: Used for network scanning and reconnaissance.

## Methodology
### 1. Reconnaissance
- Conducted initial reconnaissance using **Nmap** to identify open ports and services running on the web server.
- Gathered information about the web application, including technologies used, server details, and potential entry points.

### 2. Vulnerability Scanning
- Utilized **Burp Suite** and **OWASP ZAP** to perform automated vulnerability scans on the web application.
- Identified common vulnerabilities such as SQL injection, cross-site scripting (XSS), cross-site request forgery (CSRF), and security misconfigurations.

### 3. Manual Testing
- Conducted manual testing to verify the findings from automated scans and to identify additional vulnerabilities.
- Exploited SQL injection vulnerabilities using **SQLmap** to demonstrate the potential impact.
- Tested for XSS vulnerabilities by injecting malicious scripts and verifying the execution on the client-side.

### 4. Exploitation
- Exploited identified vulnerabilities to assess their impact on the web application.
- Demonstrated the ability to gain unauthorized access, extract sensitive data, and perform actions on behalf of authenticated users.

### 5. Key Findings
- **SQL Injection**: Identified several SQL injection vulnerabilities that could allow attackers to access and manipulate the database.
- **Cross-Site Scripting (XSS)**: Discovered XSS vulnerabilities that could enable attackers to execute malicious scripts in users' browsers.
- **Cross-Site Request Forgery (CSRF)**: Found CSRF vulnerabilities that could allow attackers to perform unauthorized actions on behalf of authenticated users.
- **Security Misconfigurations**: Detected various security misconfigurations, such as outdated software versions and exposed sensitive files.

## Conclusion
The web application penetration testing project successfully identified multiple security weaknesses within the Web applications.

# Walkthrough | Screenshots

_DVWA - Brute Force Using Burp Suite_

*Ref 1: Brute Force*

<img src="images/image1.png"> <img src="images/image2.png"> 
<img src="images/image3.png"> <img src="images/image4.png">
<img src="images/image5.png"> <img src="images/image6.png">


_DVWA - Brute Force Using OWASP ZAP_

*Ref 2: Brute Force*

<img src="images/image7.png"> <img src="images/image8.png"> 
<img src="images/image9.png"> <img src="images/image10.png"> 
<img src="images/image11.png"> <img src="images/image12.png">
<img src="images/image13.png"> <img src="images/image14.png"> 
<img src="images/image15.png">


_DVWA - Local File Inclusion Vulnerability_

*Ref 3: Local File Inclusion*

<img src="images/image16.png"> <img src="images/image17.png"> 
<img src="images/image18.png"> <img src="images/image19.png"> 
<img src="images/image20.png"> <img src="images/image21.png">


_Web Application Scanning Using OWASP ZAP_

*Ref 4: Web application scanning*

<img src="images/image22.png"> <img src="images/image23.png"> 
<img src="images/image24.png"> <img src="images/image25.png"> 
<img src="images/image26.png"> <img src="images/image27.png">
<img src="images/image28.png"> <img src="images/image29.png">
<img src="images/image30.png">


_Session Hijacking - WebGoat 8_

*Ref 5: Session Hijacking*

<img src="images/image31.png"> <img src="images/image32.png"> <img src="images/imag33.png"> <img src="images/image34.png"> <img src="images/image35.png"> <img src="images/image36.png">
<img src="images/image37.png"> <img src="images/image38.png"> <img src="images/image39.png"> <img src="images/image40.png"> <img src="images/image41.png"> <img src="images/image42.png">
<img src="images/image43.png"> <img src="images/image44.png"> <img src="images/image45.png"> <img src="images/image46.png"> <img src="images/image47.png"> <img src="images/image48.png">
<img src="images/image49.png"> <img src="images/image50.png"> <img src="images/image51.png"> <img src="images/image52.png"> <img src="images/image53.png">


_SQL Injection_

*Ref 6: Sql Injection - WebGoat*

<img src="images/image54.png"> <img src="images/image55.png"> <img src="images/image56.png">


_Pentesting OWASP Juice Shop_

*Ref 7: Owasp Juice Shop Pentesting*

<img src="images/image57.png"> <img src="images/image58.png"> <img src="images/imag59.png"> <img src="images/image60.png"> <img src="images/image61.png"> <img src="images/image62.png">
<img src="images/image63.png"> <img src="images/image64.png"> <img src="images/image65.png"> <img src="images/image66.png"> <img src="images/image67.png"> <img src="images/image68.png">
<img src="images/image69.png"> <img src="images/image70.png"> <img src="images/image71.png"> <img src="images/image72.png"> <img src="images/image73.png"> <img src="images/image74.png">
<img src="images/image75.png"> <img src="images/image76.png"> <img src="images/image77.png"> <img src="images/image78.png"> <img src="images/image79.png"> <img src="images/image80.png">









