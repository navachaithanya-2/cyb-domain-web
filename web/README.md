# Cybersecurity Domains

**GitHub description (301 characters):**

Cybersecurity Domains is a static HTML learning site that maps six core areas: architecture, risk assessment, operations, threat intelligence, governance, and physical security. Linked pages explain cryptography, cloud security, SOC, SIEM, pentesting, and incident response for students and newcomers.

---

A simple static website that introduces core cybersecurity domains and related topics. Open `index.html` in a browser—no build step or server required.

## Topics

The home page links to six domains:

| Domain | Page |
| --- | --- |
| Security Architecture | `secarch.html` |
| Risk Assessment | `riskassess.html` |
| Security Operations | `secop.html` |
| Threat Intelligence | `threatint.html` |
| Governance | `governance.html` |
| Physical Security | `physec.html` |

From those pages you can open nested topics such as cryptography, cloud security, access control, SOC, SIEM, incident response, vulnerability management, and pentesting.

## How to view

1. Clone this repository.
2. Open `index.html` in your browser, or serve the folder with any static file server.

Shared styles live in `style.css`.

## Structure

```
index.html      Home / domain list
style.css       Shared dark theme
*.html          Domain and topic pages
```
