## Incident Information
A supicious email was reported by a user after receiving a password expiration notification. the email claimed a password change could be a potential threat. The sender used microsoft brand
## Executive Summary 
Initial analysis identified indicatiors consistent with a phishisng attempt, including a suspicious domain and expiration lure 
## Initial Alert 
The investigation was initiated after a user reported a password expiration email. 
The sender domain "microsooft-security.com" contained a misspelling of the Microsost brand name, indicating a possible phishng attempt
## Evidence Collected 
Evidence                   | Description 
---------------------------|------------------------------
Sender Domain              | microsooft-security.com
Subject                    | Password Expiration Notice
Impersonation Indicator    | Microsoft brand misspeling

## Impact Assesment
The user opened the email; however, no evidence was found indicating that any links were clicked or attachments were downloaded. also no evidence of credential submission or account compromise was identified during the investigation 

Risk level: low, The phishing email was delivered and viewed by the user, but there were no malicious interaction or data exposure
 
## Recomendations
Block the sender domain "microsooft-security.com" to prevent future phishing attemps, and add it in the suspicious list.
provide phishing awareness trianing to users, emphasizing how to identify impersonation attemps and suspicious domain 
## Final verdict
The alert was a True positive
The investigation confirmed that the email ws a phishing attempt. The sender domain impersonated Microsoft branding through a misspelled name and used a password lure
Although the email was opened by the recipient, no evidence was found indicating link clicks, attachment downloads, credential submission or account compromise
