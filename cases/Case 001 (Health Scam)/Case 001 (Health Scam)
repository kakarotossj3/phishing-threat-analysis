# Phishing Email Analysis – Case 001 (Health Scam)
## 1. Executive Summary
The use of a random news leveraging health-related content with high priority, using a screenshot of a famous news channel/website to impersonate the victim to click on hyperlink.
Final assessment: Malicious email

## 2. Email Metadata
Subject: "The noise is almost completely gone"
From (Display): Dr. Oz: Do this for tinnitus
From (Address): alert.ohoea@naturespaints.com
Sender: alert.ovwkj@quivifyc.allphanexushub.com
Return-Path: alert.mmkgb@naturespaints.com
Date: 09 April 2026

## 3. Sender Analysis
### Observations
Multiple sender identities detected:
•	naturespaints.com
•	quivifyc.allphanexushub.com
Suspicious domain naming pattern

### Authentication Results
- SPF: pass (sender IP is 20.73.42.36) smtp.mailfrom=naturespaints.com
- DKIM: pass (signature was verified) header.d=quivifyc.allphanexushub.com
- DMARC: bestguesspass action=none header.from=naturespaints.com

### Assessment
Despite SPF and DKIM passing, there is a domain misalignment between sender identities, which may indicate an intentional spoofing.

## 4. Header Analysis
- Originating IP: 20.73.42.36
- Hostname: quivifyc.allphanexushub.com
- X-MS-Exchange-Organization-AuthAs: Anonymous

### Notable Indicators
The message was classified as "Anonymous" by Microsoft 365, indicating it originated from an external source and was not authenticated as an internal organizational sender. Even though this information by its self does not indicate a phishing email, it is a strong suggestion aligned with other indicators.
Original source using a random domain, which may indicate a spam infrastructure.

## 5. Content Analysis

### Social Engineering Techniques
- Urgency (high priority mark)
- Emotional appeal
- Branding imitation

### Language Patterns
- Marketing-style phrasing

## 6. URL & Domain Analysis

- **Malicious URLs:** hxxp://172-202-98-170.cloud-xip.com/4TaNni31428MQTS1397vjrftnncyb316MNYPSMRLQBWAJVH709357SJDM295402A12
- **Domain(s):** hxxp://172-202-98-170.cloud-xip.com/

### Checks Performed
- Domain age: ~4 years
- Reputation
	- Virustotal: Malicious
	- Hybrid Analysis: Malicious
	- AbuseIP: Abusive activity
	- Talos Intelligence: Untrusted

### Behavior
It is a webpage 200 status but no content provided.

## 7. Attachment or Body Content Analysis (if applicable)

Tracking pixel identified in the HTML source code.

## 8. Indicators of Compromise (IOCs)

### Domains
- quivifyc.allphanexushub.com
- cloud-xip.com

### URLs
- Multiple cloud-xip.com links

### IP Addresses
- 20.73.42.36
- 172.202.98.170

### Email Addresses
- alert.ohoea@naturespaints.com
- alert.ovwkj@quivifyc.allphanexushub.com

## 9. MITRE ATT&CK Mapping

- T1566 – Phishing  

## 10. Threat Context

### Exploitability
- No direct exploit observed

### Campaign Indicators
- No direct campaign observed so far

## 11. Mitigation & Recommendations

- Block identified domains and IP addresses
- Block suspicious sender
- Filter emails with sender/domain mismatch 
- User awareness training
- Block connections to suspicious or not categorized domains

## 13. Evidence & Analysis Artifacts

### Email attachment
![Alt Text](https://github.com/kakarotossj3/phishing-threat-analysis/blob/ed15fadb7ab3fa230f5916feee05e7cc301fd503/cases/Case%20001%20(Health%20Scam)/Evidences/email_attachment.png)

### Email Headers
 

### Malicious URL Analysis
Looking into Virustotal, the suspicious URL was identified by three vendors as Malware/Malicious and one as Spam.
 
Since its webpage has no content, it was not identified malicious code.
Looking for the IP address 172.202.98.170, different subdomains was retrieve by DNS and most of them are malicious.
 

Hybrid Analysis brings an attempt to open the webpage, but with no success. It classified the URL as Malicious with a score of 70/100.
 
 

### Attachment or Body Content Analysis
Email body content with tracking pixel mapped.
 

### Additional Evidence
Delivery information supporting authentication.
 
