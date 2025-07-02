Sample Description:
For this task, I used a sample phishing email from CanIPhish. The email was titled “ID Badge Update Needed – Urgent” and appeared to be sent from eHealth Support using the email address health-care@webnotifications[.]net. The email was addressed to john[.]doe@mybusiness[.]com.

The content of the email claimed that healthcare personnel were required to update their ID badge and asked the recipient to upload a new ID photo to proceed with verification. It included personalized text , professional-sounding language, and a call-to-action button labeled “Update your ID badge.”

Phishing Indicators in the Email Content:
Several characteristics made this email suspicious. First, the sender's email address does not belong to a legitimate or known healthcare organization — the domain webnotifications[.]net seems unrelated and untrustworthy. Secondly, the subject line included the word “Urgent”, which is a common trick used by attackers to pressure users into acting quickly without thinking. The message content asked the user to click a link and upload ID photo , which is a typical tactic used in phishing to collect sensitive data.

Although the email used healthcare-related branding and images to appear legitimate, it lacked official contact information, proper signatures, and any real organizational identification. This generic presentation, combined with the urgent tone and questionable domain, suggests it is a phishing attempt.

Header Analysis:
To further validate the suspicion, I analyzed the email header using the free tool on MXToolbox. The results confirmed the phishing nature of the email. The SPF authentication failed, meaning the sender was not authorized to send emails on behalf of the domain used. The DKIM alignment and authentication also failed, indicating the email was not properly signed or verified. Additionally, no DMARC record was found, which means the domain has no protective policy in place to prevent spoofing.

The sending server was identified as mail.fakehealthcare.org, which is not a recognized or trusted source. All of these results point to a high possibility of spoofing, where the attacker pretends to be someone they are not.


