# 🧾 Developer Certificate of Origin (DCO)

Version 1.1 — CommonsEngine Edition  
Adapted from the original [Linux Foundation DCO](https://developercertificate.org/).

---

## 📜 Purpose

The **Developer Certificate of Origin (DCO)** is a lightweight mechanism to certify that each contribution to **CommonsEngine** is made with the necessary rights and permissions.

By signing your commits, you declare that you wrote or have the right to submit the code under the open-source license governing this project (AGPL-3.0).

This replaces the need for a separate Contributor License Agreement (CLA) and keeps contribution simple, transparent, and decentralized.

---

## 💬 The Declaration

By contributing to a CommonsEngine project, you agree to the following terms:

> **Developer Certificate of Origin 1.1**
>
> By making a contribution to this project, I certify that:
>
> 1. The contribution was created in whole or in part by me and I have the right to submit it under the open source license indicated in the file; or
> 2. The contribution is based upon previous work that, to the best of my knowledge, is covered under an appropriate open source license and I have the right under that license to submit that work with modifications, whether created in whole or in part by me, under the same open source license (unless I am permitted to submit under a different license), as indicated in the file; or
> 3. The contribution was provided directly to me by some other person who certified (1), (2), or (3) and I have not modified it.
> 4. I understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information I submit with it, including my sign-off) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.

---

## ✍️ How to Sign Your Commits

Every commit must include a `Signed-off-by` line, automatically added by using the `-s` flag in your `git commit` command:

```bash
git commit -s -m "Fix issue with authentication middleware"
```

This appends a line like the following to your commit message:

```
Signed-off-by: Your Name <your.email@example.com>
```

You can verify your signature with:

```bash
git log --show-signature
```

---

## 🧠 Tips

- The name and email in your signature must match your Git configuration.  
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```
- All contributors (including maintainers) must sign their commits.  
- Squashing or rebasing commits should retain the sign-off line.  
- Commits without a sign-off will be rejected by automated CI checks.

---

## ⚖️ Legal Note

The DCO is a personal declaration, not a legal contract.  
It ensures that the open commons remains free of proprietary restrictions and that contributors retain credit for their work.

By using this DCO, **CommonsEngine** affirms that all contributions are made in good faith and with respect for the rights of others.

---

> **CommonsEngine**  
> Building the infrastructure for digital self-determination.  
> *Powering the Digital Commons.*
