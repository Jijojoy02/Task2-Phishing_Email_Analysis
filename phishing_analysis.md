# Phishing Email Analysis

## 1. Spoofed Email Address
- **Sender:** `security@paypa1.com`
- Appears legitimate but uses a number "1" instead of the letter "l" in "paypal".

## 2. Header Analysis
- SPF: FAIL
- DKIM: NONE
- DMARC: FAIL
- Originating IP: 185.203.119.10 (blacklisted)
- Likely sent from an untrusted server.

## 3. Suspicious Links
- Displayed: `https://paypal.com/verify`
- Actual: `http://paypa1-account-security.io/verify.php`
- Link leads to a fake login page.

## 4. Threatening Language
- "Failure to verify... will result in permanent suspension."
- Tries to create urgency and fear to prompt action.

## 5. Grammar & Spelling Issues
- "actitity", "protect youself"
- Typical signs of phishing attempts.

## 6. Summary of Traits
- ✅ Spoofed address
- ✅ Malicious URLs
- ✅ Urgency tactics
- ✅ Authentication failure in headers
- ✅ Poor language quality

## Conclusion
This is a confirmed phishing email designed to steal user credentials through fear and deception.
