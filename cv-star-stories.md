# Story 1: User Password Reset and Identity Verification

# 

# A user lost access to their corporate account and called the IT Specialist requesting an immediate password reset. My responsibility was to safely reset the user's password and verify that their access was successfully restored. First, I verified the user's identity through standard internal procedures to prevent unauthorized access. Then, I accessed the Local Active Directory (AD), performed a secure password reset, forced a "change password at next logon" policy, and followed up with the user to test the login. The user safely regained access to their account with minimal downtime, ensuring business continuity. This request directly relates to Identity Verification and Social Engineering Prevention. Before resetting any password in Local AD or Azure AD, enforcing strict identity verification is critical to prevent credential theft and initial access attacks. 































# 

# Story 2: Investigating a Suspicious Phishing Email

# 

# A user from the Pricing department received a suspicious email and contacted me to verify if the message was safe or a phishing attempt. My responsibility as an IT Specialist was to safely analyze the email thoroughly to protect the organization's sensitive financial data from potential cyber threats or data leaks. I requested the user to forward the original message as an attachment to inspect the email headers. I analyzed the SPF, DKIM, and DMARC records, and used WHOIS lookup to check the domain registration date and ownership. I also verified the sender's domain using MX Toolbox to see if it was blacklisted or hosted on a cheap shared hosting service. After verifying all email authentication parameters, I determined the safety status of the message. I successfully identified the risk level, guided the user on whether to delete or trust the email, and prevented any potential compromise of business-critical data. This response demonstrates practical awareness of Email Security and Phishing Mitigation. In a cloud environment, this directly aligns with implementing anti-phishing, anti-spoofing, and domain protection policies using Microsoft Defender for Office 365 to block Business Email Compromise (BEC) attacks.

# 

# 

