**Ethical Hacking Technical Report**
Client: secureitglobal.com
Date: [05-10-24]
Prepared by: [Frederick Salazar] and [Joshua Secundo]

 **Executive Summary**:
 The technical results of the ethical hacking evaluation for secureitglobal.com are presented in this report. The evaluation's goal was to find weaknesses in the company's systems, apps, and network infrastructure. Critical and high-risk flaws were found using a variety of testing approaches, such as vulnerability scanning and penetration testing. Together with practical suggestions for correction, this study offers thorough explanations of these findings.

 **Vulnerability Summary**:

  **Network Infrastructure**:
  
  **Critical**: Unauthorized access to device management interfaces and possible network breach are made possible by default credentials found on network devices (such as switches and routers).
  **High**: There is no network segmentation, which allows for lateral network mobility and amplifies the effect of possible breaches.
  
  **Web Applications**:
  
  **Critical**: A vulnerability in the web-based management site of the organization that allows attackers to execute arbitrary commands on the server, possibly using Command Injection.
  **High**: The online payment gateway's inadequate input validation allows for SQL Injection attacks and illegal database access.
  
  **Operating Systems**:
  
  **Critical**: SSL certificates that have expired on important servers leave them vulnerable to data eavesdropping and man-in-the-middle attacks.
  **High**: User accounts with lax password restrictions, making passwords more easily guessed and raising the possibility of unwanted access.
  
  **Wireless Networks**:
  
  **Critical**: Guest users are vulnerable to data interception and eavesdropping on guest Wi-Fi networks due to inadequate authentication mechanisms (e.g., WEP, WPA) and a lack of encryption.
  **High**: Unauthorized access points that were found to be operating inside the company network were used to support man-in-the-middle attacks by masquerading as authentic Wi-Fi networks.
  
  **Social Engineering**:
  
  **High**: Employees sharing sensitive information over insecure communication channels (e.g., email, messaging apps) due to lack of awareness about data protection practices.
  **High**: Lack of employee training and awareness about social engineering tactics, resulting in successful phishing attacks and credential theft.
 
  Recommendations:
  
  **Network Infrastructure**:
  Change default credentials on all network devices and implement strong password policies.
  Implement network segmentation to isolate critical assets and restrict lateral movement within the network.
 
  **Web Applications**:
  Patch or update the web-based administration portal to fix the command injection vulnerability.
  Enhance input validation mechanisms in the online payment gateway to prevent SQL Injection attacks.
 
  **Operating Systems**:
  On crucial servers, renew SSL certificates and make sure they are updated frequently.
  Enforce more stringent password regulations and give user accounts multi-factor authentication.
  
  **Wireless Networks**:
  Upgrade guest Wi-Fi networks to require strong passphrases and use WPA2 or WPA3 encryption.
  To find and eliminate unwanted access points, do routine inspections of your wireless network.
  
  **Social Engineering**:
  To enlighten staff members about data protection procedures and the dangers of revealing sensitive information, offer thorough security awareness training.
  To identify and stop phishing emails before they get in employees' inboxes, use email filtering technologies.
  
  Signature: Frederick Salazar and Joshua Secundo
