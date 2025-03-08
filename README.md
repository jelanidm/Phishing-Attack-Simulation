# Phishing Attack Simulation with Gophish  

## Overview  
This project involved deploying and configuring Gophish, an open-source phishing simulation platform, to conduct a controlled phishing attack simulation. The goal was to create realistic phishing scenarios, track user interactions, and analyze the effectiveness of security awareness training.  

---

## Deployment of Gophish  

### 1. One-Click Deployment on Railway  
- Deployed Gophish using Railway's one-click template.  
  ![Deploy Gophish on Railway](assets/deploy-gophish.png)  
- Retrieved login credentials from the deployment logs.  
  ![Deployment Logs](assets/deployment-logs.png)  
- Accessed the Gophish admin portal and updated the default credentials for security purposes.  

### 2. Setting Up the Gophish Environment  
- Configured the Gophish admin dashboard for the phishing simulation.  
  ![Sign-In Page](assets/sign-in.png)  
  ![Reset Password](assets/reset-password.png)  
  ![Admin Dashboard](assets/admin-dashboard.png)  

---

## Configuring the Phishing Simulation  

### User & Group Management  
![Empty Groups](assets/empty-groups.png)  
- Created a CSV file in Excel containing:  
  - First Name  
  - Last Name  
  - Email  
  - Position  
- Uploaded the CSV to Gophish for bulk user import.  
  ![Uploaded Users](assets/uploaded-users.png)  

### Email Templates  
- Designed custom phishing email templates using Gophish’s HTML editor.  
  ![Email Template](assets/email-template.png)  
- Enabled tracking images and configured attachments.  

### SMTP Sending Profiles  
- Configured MailHog on Railway:  
  ![MailHog Deployment](assets/mailhog-deploy.png)  
  ![Networking Settings](assets/networking-settings.png)  
  ![TCP Proxy](assets/tcp-proxy.png)  
- Updated Gophish’s SMTP server settings.  
  ![SMTP Configuration](assets/smtp-config.png)  
- Tested email delivery via MailHog:  
  ![Test Email](assets/test-email.png)  
  ![MailHog Dashboard](assets/mailhog-dashboard.png)  

### Landing Pages  
- Created a credential-capture landing page.  
  ![Landing Page](assets/landing-page.png)  

### Campaign Creation & Execution  
- Launched and monitored the phishing campaign:  
  ![Campaign Setup](assets/campaign-setup.png)  
  ![Real-Time Dashboard](assets/realtime-dashboard.png)  
- Verified email delivery in MailHog:  
  ![MailHog Verification](assets/mailhog-verification.png)  

---

## Results & Analysis  
- Successfully simulated a phishing attack and collected engagement data.  
- Tracked email delivery, opens, clicks, and credential submissions.  
- Demonstrated the effectiveness of security awareness training through user response analysis.  

---

## Project Impact  
This project showcased my ability to:  
- Deploy and configure cybersecurity tools (Gophish, MailHog).  
- Manage phishing campaigns from setup to execution.  
- Analyze user behavior to improve organizational security awareness.  
