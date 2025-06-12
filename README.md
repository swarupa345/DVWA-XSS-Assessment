# DVWA-XSS-Assessment
A practical Reflected XSS test on DVWA (Low, Medium, High)
# DVWA Reflected XSS Vulnerability Assessment

## 🧪 Test Summary
Conducted Reflected XSS testing on DVWA for all security levels (Low, Medium, High).

## 🔍 Key Findings
- Low: No input sanitization – payload `<script>alert(document.cookie)</script>` worked
- Medium: Filter bypass using `<img src=x onerror=alert(1)>`
- High: CSRF token bypass required with image-based XSS payload

## 🛠️ Tools Used
- DVWA
- Google Chrome
- Burp Suite

## 📄 Report
See the attached PDF for detailed steps, source code review, payloads used, and mitigation strategies.

## 🛡️ Recommendations
- Proper input/output sanitization
- CSP Headers
- HttpOnly cookies

## 📸 Screenshots
