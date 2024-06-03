# Project: Phishing Attack Investigation

## Introduction
Phishing attacks are a prevalent cybersecurity threat where attackers deceive individuals into providing sensitive information by masquerading as a trustworthy entity. This project aims to equip you with the skills to identify, investigate, and respond to phishing attacks effectively.

## Pre-requisites
- Basic understanding of email systems
- Familiarity with phishing techniques
- Basic knowledge of email analysis tools

## Lab Set-up and Tools

To conduct a phishing attack investigation, you'll need a simulated environment that includes tools for email analysis. Here’s a detailed setup:

### 1. Email Server Simulation
**Description**: Set up a local email server or use an email simulation service to receive and send emails. This allows you to safely analyze phishing emails without exposing your real email account to potential risks.

**Tools**: 
- **Halon MTA**: A flexible and powerful email server software.
- **MailCatcher**: A simple SMTP server which captures emails sent to it for later inspection.
- **Mutt**: A small but powerful text-based email client for UNIX operating systems.

### 2. Phishing Email Samples
**Description**: Obtain a set of phishing email samples to analyze. These can be sourced from public repositories, cybersecurity forums, or created for educational purposes.

**Tools**:
- **PhishTank**: A collaborative clearing house for data and information about phishing on the Internet.
- **OpenPhish**: A service providing free access to a continuously updated list of active phishing URLs.

### 3. Email Analysis Tools
- **Thunderbird**: An open-source email client by Mozilla that supports multiple email accounts and has powerful email management features.
- **PhishTool**: A tool specifically designed for analyzing and investigating phishing emails.
- **Email Header Analysis Tools**: Online tools like MXToolbox or EmailHeaders.net which can parse and analyze email headers.

## Setting Up the Lab Environment

### 1. Install Thunderbird
- Download and install Thunderbird from the [official website](https://www.thunderbird.net/).
- Set up an email account using either a real or simulated email server.

### 2. Set Up Email Server Simulation
- Install MailCatcher: 
  ```sh
  gem install mailcatcher
  mailcatcher
Access MailCatcher at http://127.0.0.1:1080/ to view captured emails.

### 3. Obtain Phishing Email Samples
Download phishing samples from PhishTank or OpenPhish.
Import the samples into Thunderbird for analysis.
### 4. Install and Configure PhishTool
Register for a free account at PhishTool.
Follow the setup instructions provided by PhishTool to integrate it with Thunderbird.

## Exercises

### Exercise 1: Identifying Phishing Emails
**Objective**: Learn to recognize phishing emails based on common characteristics.

**Steps**:
1. Set up your email analysis environment using Thunderbird.
2. Load the provided phishing email samples into Thunderbird.
3. Identify and document common phishing indicators (e.g., suspicious sender address, generic greetings, urgent language, suspicious links).

**Expected Output**:
- A list of identified phishing emails with documented indicators.

### Exercise 2: Analyzing Email Headers
**Objective**: Understand how to analyze email headers to uncover information about the email's origin.

**Steps**:
1. Select a phishing email from Exercise 1.
2. Open the email header information in Thunderbird.
3. Analyze the header to identify:
   - Sender's IP address
   - Email servers the email passed through
   - Any discrepancies in the sender's information

**Expected Output**:
- A detailed report on the email header analysis with identified IP addresses and server information.

### Exercise 3: Investigating Suspicious Links
**Objective**: Learn to investigate suspicious links in phishing emails without compromising your system.

**Steps**:
1. Identify suspicious links in the phishing emails from Exercise 1.
2. Use a URL analysis tool (e.g., VirusTotal, PhishTool) to investigate the links.
3. Document the findings, including the risk level and any associated malicious activity.

**Expected Output**:
- A report detailing the analysis of each suspicious link, including screenshots and risk assessments.

### Exercise 4: Reporting and Documenting the Phishing Attempt
**Objective**: Create a comprehensive report of the phishing investigation.

**Steps**:
1. Compile findings from Exercises 1-3 into a single report.
2. Include the following sections:
   - Executive summary
   - Detailed analysis of phishing emails
   - Email header analysis
   - Suspicious link investigation
   - Recommendations for preventing future phishing attacks
3. Present the report in a clear and professional format.

**Expected Output**:
- A comprehensive phishing investigation report ready for presentation to stakeholders.

### Additional Resources
- [PhishTool](https://phishtool.com)
- [VirusTotal](https://www.virustotal.com)
- [How to View Email Headers](https://support.google.com/mail/answer/22454?hl=en)

---

By completing these exercises, you will gain practical experience in identifying, analyzing, and responding to phishing attacks, enhancing your skills in cybersecurity incident response.
