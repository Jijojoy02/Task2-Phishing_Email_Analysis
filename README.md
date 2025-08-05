# 🎣 Phishing Email Analysis 


---

## 📝 Task Objective

To analyze a sample phishing email and identify indicators of compromise such as spoofed sender address, mismatched links, and social engineering techniques.

---

## 🧰 Tools Used

- Online Phishing Email Samples (e.g., from phishtank.com or malware-traffic-analysis.net)
- Email Header Analyzer (e.g., mxtoolbox.com, Google Admin Toolbox)
- Web Browser (for hover-link checks)
- Text Editor (for annotation and note-taking)

---

## 🔬 Steps Performed

1. **Obtained Phishing Sample**  
   - Downloaded a publicly available phishing email sample in `.eml` or text format.

2. **Checked Sender's Email Address**
   - Sender appeared to be: `security@paypa1.com` *(spoofed – notice the "1" instead of "l")*

3. **Analyzed Email Headers**
   - Used online email header analyzer (e.g., MXToolbox)
   - Found discrepancies:
     - SPF: FAIL
     - DKIM: NONE
     - IP Reputation: Blacklisted

4. **Inspected Links & Attachments**
   - Hovered over links:
     - Displayed text: `https://paypal.com/verify`
     - Actual link: `http://paypa1-account-security.io/verify.php`
   - No legitimate domain present; hosted on lookalike domain.

5. **Identified Urgent or Threatening Language**
   - Example:
     > "Your account has been limited. Log in within 24 hours or it will be suspended."

6. **Noted Mismatched URLs**
   - Link displayed as official but redirected to phishing site.
   - Mismatches found in all hyperlinks.

7. **Checked for Grammar & Spelling Errors**
   - Phrases like "We notice unusual log-in acticity." and "Please verify to protect youself."
   - Multiple typos and poor grammar indicate low-quality social engineering attempt.

8. **Summarized Phishing Traits**
   - ✅ Spoofed sender
   - ✅ Urgency and fear tactics
   - ✅ Mismatched and malicious URLs
   - ✅ Grammar/spelling errors
   - ✅ Header authentication failures

---

## 📂 Files Included

| File Name               | Description                                |
|------------------------|--------------------------------------------|
| `phishing_email_sample.txt` | Raw phishing email content              |
| `header_analysis.txt`        | Output from header analyzer tool        |
| `phishing_analysis.md`      | Full analysis and findings              |
| `README.md`                 | Task overview and methodology           |

---

## 🔐 Ethical Note

All phishing samples used are from educational archives intended for security training. No live phishing content was interacted with or executed.

