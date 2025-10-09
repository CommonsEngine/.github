# 🛡️ Security Advisory Template

> **Status:** Draft  
> **Last Updated:** YYYY-MM-DD  
> **Project:** [project-name]  
> **Advisory ID:** CE-[year]-[sequential-number]

---

## 🔍 Summary

Provide a concise, plain-language overview of the vulnerability.  
Explain what the issue is, how it affects users, and its potential impact on confidentiality, integrity, or availability.

Example:

> A vulnerability was discovered in `@commonsengine/Sovereign` versions ≤ 1.3.4 that could allow unauthorized access to private file metadata via a crafted API request.  
> This issue has been fixed in version **1.3.5**.

---

## 🧩 Affected Components

| Component / File | Versions Affected | Description |
|------------------|------------------|--------------|
| e.g. `/src/auth/middleware.js` | ≤ 1.3.4 | Improper validation of access tokens |

List all affected packages, modules, or services.

---

## ⚙️ Technical Details

Describe the vulnerability in technical terms appropriate for maintainers and developers.

- Root cause (e.g., logic flaw, missing validation, dependency issue)  
- Exploitation method (if applicable)  
- Example request/response or proof of concept (redacted if sensitive)

If relevant, include CVSS (Common Vulnerability Scoring System) rating:

```
CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:N  
Severity: HIGH (8.6)
```

---

## 🧱 Mitigation

Provide recommended actions to secure affected systems.

- Upgrade to **[fixed version]** immediately.  
- If upgrade is not possible, apply the following temporary mitigation:  
  ```bash
  npm audit fix
  ```
  or manual patch snippet.

List any configuration changes, environment updates, or dependency upgrades needed.

---

## 🧩 Fixed Versions

| Project / Package | Fixed Version | Release Date |
|-------------------|----------------|---------------|
| e.g. `Sovereign` | 1.3.5 | 2025-02-01 |

---

## 🧪 Verification

Explain how to verify that the fix is applied and functioning correctly.

Example:

```bash
npm list @commonsengine/Sovereign
# should report 1.3.5 or higher
```

Include test coverage confirmation or regression proof if available.

---

## 🙌 Credits

This issue was responsibly disclosed by:  
**[Researcher Name / Handle]** — [contact or link]  

We thank them for their contribution to the security of the digital commons.

---

## 🕊️ Disclosure Timeline

| Date | Event |
|------|--------|
| YYYY-MM-DD | Vulnerability reported |
| YYYY-MM-DD | Maintainers acknowledged receipt |
| YYYY-MM-DD | Patch developed |
| YYYY-MM-DD | Release published |
| YYYY-MM-DD | Advisory made public |

---

## 🔒 References

- [Patch or commit link](#)  
- [Release notes](#)  
- [GitHub Advisory Database entry](#)  
- [CVE ID (if assigned)]  

---

## 🧾 License

This advisory is published under the same license as the project (AGPL-3.0),  
and may be reproduced for transparency and public interest.

---

> **CommonsEngine**  
> Building the infrastructure for digital self-determination.  
> *Powering the Digital Commons.*
