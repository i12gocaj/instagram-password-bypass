# Instagram Password Change Bypass (Fixed)

## 🛡️ Vulnerability Summary

In [04/2025], I discovered a vulnerability in Instagram that allowed an attacker to change the password of any account they had access to without knowing the current password.

⚠️ **This vulnerability has been responsibly disclosed and is no longer active.**  
I reported it to Meta via their [Bug Bounty Program](https://hackerone.com/meta).

## 🔍 Impact
Full account takeover for logged-in users, bypassing password verification during change.

## 🧪 Proof of Concept
Video: `demo/proof.mov`

## 📄 Responsible Disclosure

See `reportMeta&writeup/writeup-report.pdf` for the disclosure and response timeline.

Meta responded to the report with a message that, to this day, remains unclear. The wording even seemed to suggest they were not planning to fix the issue — despite its critical nature. However, the vulnerability was silently patched at a later time, indicating that they likely did address it eventually.

## 👨‍💻 Author
Javier González Casares