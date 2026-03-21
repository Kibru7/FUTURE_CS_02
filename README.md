Project Title
Phishing Detection and Awareness Report
 
Purpose
This project documents real phishing investigations and produces an awareness report that helps employees recognize phishing, verify suspicious messages safely, and report incidents. It focuses on defensive security analysis and education.

Tools Used

Public phishing email examples and screenshots
Used to collect phishing scenarios and document visible indicators such as urgency language, sender claims, attachments, and calls to action.

Email header analyzer tools
Google message header analyzer
https://toolbox.googleapps.com/apps/messageheader/

MXToolbox email header analyzer
https://mxtoolbox.com/EmailHeaders.aspx

These tools are used to interpret raw email headers and extract security relevant results such as SPF DKIM DMARC and sender alignment.

Browser tools for safe link and domain inspection
Used for non clicking inspection such as copying link text, checking for lookalike domains, verifying whether a link is off domain, and documenting suspicious URLs safely. Links are not opened during analysis.

Analysis Approach

Step 1 Collect phishing email samples
Gather phishing email or calendar invite examples and record the visible details such as subject, sender, date, and message content.

Step 2 Analyze email headers
When raw headers are available, extract header fields and verify SPF DKIM DMARC results, domain alignment between From and Return Path, and Reply To mismatches. If only screenshots are available, document the limitation.

Step 3 Inspect sender domain and links
Check whether the sender domain matches the claimed organization and document any mismatches. Inspect link text and domains for redirection, lookalike domains, and non official login pages without clicking.

Step 4 Identify phishing indicators
Record indicators such as urgency, fear based language, reward bait, sensitive data requests, credential requests, unusual attachments, and off platform contact methods.

Step 5 Classify email risk
Classify each investigated message as Safe, Suspicious, or Phishing based on evidence.

Step 6 Document findings clearly
Write short plain language explanations of how each attack works, why it is risky, and what the user should do.

Step 7 Create prevention and awareness guidelines
Add employee prevention tips, clear do and dont guidance, and a reporting process for suspected phishing.

Repository Contents
Phishing_Detection_Awareness_Report
The main written report containing analyzed phishing cases, indicators, risk classification, and prevention guidelines.

 

Disclaimer
All content is for defensive security awareness and educational use only.
