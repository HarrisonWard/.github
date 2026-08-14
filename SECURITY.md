# Security Policy

Found something wrong? Tell me. I would rather hear it from you than find it later.

## Reporting a Vulnerability

**Use GitHub's Private Vulnerability Reporting.** Go to the affected repository, click the **Security** tab, then **Report a vulnerability**. It's private, it goes straight to me, and it keeps the whole conversation in one place with a proper audit trail.

If that isn't available on a particular repo, open a normal issue **without the sensitive detail**, and just say you have a security report and I'll open a private channel from there.

Please don't post exploit detail in a public issue before there's a fix.

## What to Include

The more of this you can give me, the faster this goes:

- Which repository, and which file or template
- What the issue is and why it matters
- How to reproduce it
- Your read on impact and severity
- A suggested fix, if you have one

## What You Can Expect Back

| Stage | Target |
|---|---|
| I acknowledge your report | 3 business days |
| Initial assessment and severity call | 10 business days |
| Fix or documented mitigation | 30 days, faster for anything critical |
| Public disclosure | Coordinated with you, after a fix ships |

You get credit in the advisory and the release notes unless you'd rather not. Just say which.

## Scope

**In Scope**

- Code, scripts, and automation in any public repository here
- Dependencies carrying a known vulnerability
- Secrets, credentials, keys, or internal identifiers committed by accident
- **Errors in security guidance, control mappings, or policy language** that would leave someone materially worse off if they followed it as written

That last one is deliberate. Most of what's here is documentation, not code. A control mapping pointing somewhere wrong is a real defect. **No One Is as Dumb as All of Us**, which is exactly why more eyes on this material make it better. Tell me when it's wrong.

**Out of Scope**

- Vulnerabilities in third-party services this material merely references
- Scanner output with no demonstrated impact
- Social engineering, physical access, or anything aimed at me rather than the published material
- Disagreements about risk tolerance or how to read a framework. Those are welcome, but open a discussion, not a security report.

## Safe Harbor

Research in good faith, stay in scope, avoid privacy violations and service disruption, and give me reasonable time to fix things before going public, and I will not pursue or support any action against you.

## What This Material Is

Templates, policy language, control mappings, and reference material. **Starting points, not finished compliance programs**, and not legal or regulatory advice. Adapt anything you use to your own environment and obligations, and have qualified counsel review anything carrying legal weight.

---

*Last reviewed: August 2026*
