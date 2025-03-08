# Phishing Attack Simulation with Gophish  

## Overview  
This project involved deploying and configuring Gophish, an open-source phishing simulation platform, to conduct a controlled phishing attack simulation. The goal was to create realistic phishing scenarios, track user interactions, and analyze the effectiveness of security awareness training.  

---

## Deployment of Gophish  

### 1. One-Click Deployment on Railway  
- Deployed Gophish using Railway's one-click template.  
  ![Deploy Gophish on Railway](https://alphasec.io/content/images/size/w1000/2025/02/Gophish-Railway-template.png)  
- Retrieved login credentials from the deployment logs.  
  ![Deployment Logs](https://cdn.discordapp.com/attachments/837282801392943155/1347727415140552714/image.png?ex=67cce077&is=67cb8ef7&hm=e46b43ee788d1197f142bd238842bd663335247b7d40b9ef2030790af1c8e293&)  
- Accessed the Gophish admin portal and updated the default credentials for security purposes.  

### 2. Setting Up the Gophish Environment  
- Configured the Gophish admin dashboard for the phishing simulation.  
  ![Sign-In Page](https://alphasec.io/content/images/size/w1000/2023/01/Gophish-login.png)  
  ![Reset Password](https://cdn.discordapp.com/attachments/837282801392943155/1347728091216220270/image.png?ex=67cce118&is=67cb8f98&hm=a719f3091bce2297038aed418f269aeca711cbf746f2812914a16ead1c8f3e2f&)  
  ![Admin Dashboard](https://alphasec.io/content/images/size/w1000/2023/01/Gophish-dashboard.png)  

---

## Configuring the Phishing Simulation  

### User & Group Management  
![Empty Groups](https://cdn.discordapp.com/attachments/837282801392943155/1347728866952740884/image.png?ex=67cce1d1&is=67cb9051&hm=342de85d3cc5bd6a5d39b924615080dfeed88c534a2ce8433c4aac0f77a20570&)  
- Created a CSV file in Excel containing:  
  - First Name  
  - Last Name  
  - Email  
  - Position  
- Uploaded the CSV to Gophish for bulk user import.  
  ![Uploaded Users](https://cdn.discordapp.com/attachments/837282801392943155/1347728896300421160/image.png?ex=67cce1d8&is=67cb9058&hm=c80467b4f7791737666e7d3b9674b9d818874e9badef24a131bc454cd87e3e0a&))  

### Email Templates  
- Designed custom phishing email templates using Gophish’s HTML editor.  
  ![Email Template](https://cdn.discordapp.com/attachments/837282801392943155/1347728934363725876/image.png?ex=67cce1e1&is=67cb9061&hm=72786cd02da55bfeb096823d0f7dc058d111993d22ed4dd9495b65a800f81f0f&)  
- Enabled tracking images and configured attachments.  

### SMTP Sending Profiles  
- Configured MailHog on Railway:  
  ![MailHog Deployment](https://cdn.discordapp.com/attachments/837282801392943155/1347729170800578590/image.png?ex=67cce219&is=67cb9099&hm=5f92dc6c10223004275cb055d8e2302b0dd5fb00ef3b070be768b14c035dae00&)  
  ![Networking Settings](https://cdn.discordapp.com/attachments/837282801392943155/1347729231924301844/image.png?ex=67cce228&is=67cb90a8&hm=d0e88b75901626d6c00788a86f9d382896df1a735bdc0213e5b49ee1007e6580&)  
  ![TCP Proxy](https://cdn.discordapp.com/attachments/837282801392943155/1347729256763101254/image.png?ex=67cce22e&is=67cb90ae&hm=d0a22445d2ff7e7488307eaf232ca45b566dd72416195ff546bbd61a60164902&)  
- Updated Gophish’s SMTP server settings.  
  ![SMTP Configuration](https://cdn.discordapp.com/attachments/837282801392943155/1347729328846274711/image.png?ex=67cce23f&is=67cb90bf&hm=c151fc92aa817eccae66c9001e0fb11331c7e36332964e6193ca69cee72bf939&)  
- Tested email delivery via MailHog:  
  ![Test Email](https://cdn.discordapp.com/attachments/837282801392943155/1347729366548877332/image.png?ex=67cce248&is=67cb90c8&hm=67127ec461d1d55cc6176d68948ff262d8d9ee32864faa4ff60a737e9cde5a9d&)  
  ![MailHog Dashboard](https://cdn.discordapp.com/attachments/837282801392943155/1347729389076611112/image.png?ex=67cce24d&is=67cb90cd&hm=02892cc8a3d7ca2416db893a66c20f118a73041617c837cac24e2d01fbb71418&)  

### Landing Pages  
- Created a credential-capture landing page.  
  ![Landing Page](https://cdn.discordapp.com/attachments/837282801392943155/1347729434031030365/image.png?ex=67cce258&is=67cb90d8&hm=fcee541b5333eec82803a92bc124d1713a10b7ddb03b772f716fe690fdf11bec&)  

### Campaign Creation & Execution  
- Launched and monitored the phishing campaign:  
  ![Campaign Setup](https://cdn.discordapp.com/attachments/837282801392943155/1347729513072820386/image.png?ex=67cce26b&is=67cb90eb&hm=b7667d9b764b3a9f5b038bc8fe4f06eac4339e81e7e4882e4c91d4338a777f77&)  
  ![Real-Time Dashboard](https://cdn.discordapp.com/attachments/837282801392943155/1347729535726256219/image.png?ex=67cce270&is=67cb90f0&hm=6d438897ae1111bbdf0607895bd0c3467f90b87151ed729fcad0a3b1b909afd7&)  
- Verified email delivery in MailHog:  
  ![MailHog Verification](https://cdn.discordapp.com/attachments/837282801392943155/1347729562850562058/image.png?ex=67cce277&is=67cb90f7&hm=b04ba2f1d5fc4293d02469c7687a13db2ec0f04fac104dacd189a3b56a6a06d9&)  

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
