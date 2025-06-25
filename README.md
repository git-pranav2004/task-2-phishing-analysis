Task 2 – Phishing Email Analysis

Description

Phishing emails are deceptive messages sent by attackers to trick users into giving up confidential information such as passwords, credit card numbers, or login credentials. These emails often appear to come from trusted sources like banks, tech companies, or online services (e.g., PayPal, Amazon).

The goal of this task was to:
Identify phishing traits in a suspicious email.
Analyze its email header using online tools.
Understand the tactics used by attackers to deceive users.

Document the findings in a structured and security-aware format.

Files Included

What is a phishing email.pdf 🔹 Explains the concept of phishing emails, how they work, and why they’re dangerous.

phishing_sample.pdf  🔹 Contains:

A realistic phishing email sample (spoofed as PayPal).
Complete step-by-step header analysis.
Final observations and phishing indicators.

Summary of Findings

Spoofed sender domain: The email used paypalsecure.com, not the legitimate paypal.com.
Suspicious links: Redirected to a fake verification site (paypal-verification-center.com).

Header analysis:

SPF, DKIM, and DMARC failed – confirming spoofing.
Originating IP was not authorized to send mail for the sender's domain.
Reply-To redirected responses to another fake domain.
Social engineering tactics: Included urgency, fear of account suspension, and fake login activity from Russia.

Conclusion

This task enhanced awareness of how phishing emails operate and how to inspect them beyond just the email body. Analyzing headers, inspecting URLs, and understanding social engineering are essential skills for cybersecurity. The exercise also demonstrated the importance of email authentication mechanisms like SPF, DKIM, and DMARC.
