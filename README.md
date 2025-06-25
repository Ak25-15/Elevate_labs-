# 📧 Phishing Email Analysis Report

## 🔍 Sample Email Content (from `email_sample.txt`)
**From:** Apple Support `<security@apple-support.com>`  
**Subject:** Urgent: Your Apple ID has been locked

> Dear Customer,  
> We noticed suspicious activity in your Apple account. Your account has been temporarily locked.  
> To restore your account, please verify your information by clicking the link below:  
> http://apple.support-login-verification.com  
> If you do not verify in 24 hours, your account will be permanently disabled.  
>  
> Best Regards,  
> Apple Support Team

---

## 🚩 Phishing Indicators Identified

1. **Fake Sender Email**: The sender’s domain `@apple-support.com` is not Apple’s official domain.
2. **Suspicious Link**: URL `http://apple.support-login-verification.com` is a lookalike and not secure (http).
3. **Urgency Language**: Phrases like *“verify in 24 hours”* are meant to scare the user.
4. **Generic Greeting**: “Dear Customer” is a red flag — legitimate services use your name.
5. **Spelling/Grammar**: Tone and wording are suspicious.
6. **Social Engineering**: Tries to trick you into revealing login credentials.

---

## 🧪 Tools Used

- MXToolbox Header Analyzer
- Visual inspection (hovering links, sender details)
- Text editor (for analysis)

---

## 💡 Concepts Applied

- Phishing Email Analysis
- Email Spoofing
- Header Inspection
- Social Engineering Tactics

## ✅ Conclusion

This email shows multiple red flags such as a spoofed email address, suspicious URL, and threatening language. It is a clear example of a phishing attempt designed to steal user credentials through social engineering.
