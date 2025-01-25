---
marp: true
---
<!-- _class: top -->

# Building Secure Containers: A Practical Guide to Harbor and Vulnerability Scanning
###### by Prasanth Baskar (bupd)
---

## About Me
###### (Just Another Developer)

- Hates Bloated GUIs.
- Creator of [git-donkey](https://github.com/bupd/git-donkey) & [TimeOtter](https://github.com/bupd/timeotter)
- OSS Software Engineer - 8gears AG
- Core Contributor of Harbor Container Registry (CNCF)
---

## What We’ll See in This Talk
###### BTW don't run JS/TS on server
- What is Container Security
- Why does it matter?
- Vim: the only editor that matters
- Build Secure Container
- Best Practices

---
## What We’ll See in This Talk
###### BTW don't run JS/TS on server
- What is Container Security
- Why does it matter?
- Build Secure Container
- Best Practices
- Harbor & SBOMs - DEMO
- Do you actually need it?
- Announcements

---

## What is Container Security
###### (Nobody cares)
- Containers are the foundation of modern apps. (Hi from GPT)
- Examples [attacks](https://www.trendmicro.com/vinfo/in/security/news/virtualization-and-cloud/enhancing-software-supply-chain-security-navigating-slsa-standards-and-the-mitre-att-and-ck-framework)
---

## Why Security
###### (I don't want hackers in my house)

---

## Building Secure Container
###### (Ah crap, here we go again)
- Let's Look at Principles

---
## Principle 1: Reduce the attack surface

- Choose minimal base images

---
## DEMO
- why you should use scratch as base image

### Scratch > Distroless > Alpine > Normal Base Image

---
## Principle 2: Be Specific about what you include
- TLDR; Be Explicit and define every dependencies
- Only include libraries you really need.
- Use Open Source or well maintained libraries/dependencies

---
## Principle 3: Know what you are doing & Why
- Don't follow trends blindly
- Emphasize deliberate, conscious decisions based on your specific project requirements

---
## Now to Harbor & SBOM
- SBOM: Software Bill of Materials (aka cookbook for deps)

---
## Vulnerabilities
###### Who cares My app is working fine already
- No points (just too lazy to type)

---
## Announcements
- TimeOtter [v0.0.1](https://github.com/bupd/timeotter) is Released
- DHAAS - Docker Hub as a Storage [(next experiment)](https://github.com/bupd/dhaas)

---
<!-- _class: title -->
## Thanks for Attending!
###### You Made It Through... Somehow

![Thank You Computer Man](https://th.bing.com/th/id/R.7157092fa451872c1618424d35f72919?rik=DHTnIge1GdiUEw&riu=http%3a%2f%2fs2.quickmeme.com%2fimg%2f23%2f230661ee8821d99787bd752eaf41a33578e178491a6d703c9a914e132e8ac4ab.jpg&ehk=rVsz2CD%2fFQzOL11G4AX0mYkVtopJb3TRBZxHFkbZaQ8%3d&risl=&pid=ImgRaw&r=0)
