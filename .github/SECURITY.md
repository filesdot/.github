# 🔐 Security Policy

## 📜 Scope
This project is a **curated list of links, themes, and configuration resources**. As such, "security vulnerabilities" typically fall into one of these categories:
- 🚩 Malicious or phishing links submitted to the list
- 🔑 Hardcoded secrets, API keys, or personal data in example configs
- 🦠 Compromised upstream repositories or themes with supply-chain risks
- 🕵️ Doxxing or privacy violations in documentation/screenshots

## 📬 Reporting a Vulnerability
If you discover a security-related concern, **please do not open a public issue**. Instead:
1. Email us at: `filingdot@gmail.com`
2. Include:
   - URL/file location of the concern
   - Description of the risk
   - Steps to reproduce/verify (if applicable)
   - Your contact info (optional, for follow-up)

We acknowledge reports within **48 hours** and aim to resolve critical issues within **7 days**.

## 🛡️ What to Expect
- ✅ **Confidentiality**: Your report will not be shared publicly without your consent
- 🔍 **Verification**: We will validate the concern and assess impact
- 🛠️ **Resolution**: We'll remove/replace affected content, notify downstream users if needed, and update the list
- 🙏 **Acknowledgment**: With your permission, we'll credit you in our changelog/security advisories

## 📖 Best Practices for Contributors
- Never submit configs containing real tokens, passwords, or personal paths
- Always verify upstream repo health before linking
- Use placeholder paths in examples: `~/.config/tool/config.toml`
- If you maintain a linked project, keep dependencies updated and enable Dependabot/Renovate

## 📚 References
- [GitHub Private Vulnerability Reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability)
- [OpenSSF Best Practices for Open Source](https://bestpractices.coreinfrastructure.org/)
- [Awesome List Contribution Guidelines](CONTRIBUTING.md)
