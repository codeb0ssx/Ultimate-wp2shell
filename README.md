# CVE-2026-63030 (WP2Shell) – Detection & Validation Proof of Concept

> **Educational and defensive Proof of Concept (PoC)** for validating exposure to the WordPress Core vulnerabilities **CVE-2026-60137** and **CVE-2026-63030 (WP2Shell)**.

![License](https://img.shields.io/badge/Purpose-Defensive-blue)
![Research](https://img.shields.io/badge/Security-Research-green)
![Platform](https://img.shields.io/badge/Platform-WordPress-orange)
![Status](https://img.shields.io/badge/Status-Educational-important)

---

## Overview

This repository provides a **defensive validation and detection proof of concept**
for the WordPress Core vulnerabilities collectively referred to as **WP2Shell**.

According to the public security advisories, WP2Shell involves the interaction of
multiple vulnerabilities—including **CVE-2026-60137** and **CVE-2026-63030**—that
can, under specific conditions, result in **unauthenticated Remote Code Execution (RCE)**.

The purpose of this repository is to assist:

- Security researchers
- Penetration testers
- Blue teams
- Incident responders
- System administrators

in **identifying vulnerable WordPress installations**, reproducing the issue in
authorized laboratory environments, and verifying that official patches have been
successfully applied.

This project is **strictly intended for defensive security research and authorized testing**.

---

## Vulnerabilities

| CVE | Description |
|------|-------------|
| **CVE-2026-60137** | WordPress Core vulnerability involved in the WP2Shell attack chain. |
| **CVE-2026-63030** | Critical WordPress Core Remote Code Execution vulnerability (WP2Shell). |

---

## Affected Versions

Public advisories identify the following WordPress Core releases as affected:

- WordPress **6.9.0 – 6.9.4**
- WordPress **7.0.0 – 7.0.1**

Refer to the official WordPress security releases for complete patch information.

---

## Repository Goals

This project is designed to help defenders:

- Validate exposure to WP2Shell
- Detect vulnerable WordPress installations
- Verify remediation after patching
- Reproduce the vulnerability in isolated lab environments
- Support incident response and forensic investigations
- Improve understanding of the vulnerability chain

---

## Features

- Defensive vulnerability validation
- Detection of affected WordPress versions
- Research-oriented implementation
- Patch verification
- Lightweight scanner
- Educational reference implementation

---

## Academic & Defensive Research Notice

This repository is published exclusively for:

- Academic research
- Security education
- Defensive security testing
- Authorized penetration testing
- Incident response
- Patch verification
- Vulnerability validation

The software must **only** be used on systems:

- You own, **or**
- For which you have received explicit authorization.

---

## Authorization Requirement

Unauthorized testing against systems that you do not own or administer may violate
local laws, organizational policies, or international regulations.

The author **does not** encourage or support:

- Unauthorized access
- Internet-wide exploitation
- Mass scanning of third-party systems
- Malicious activity
- Abuse of vulnerable infrastructure

---

## Responsible Usage

This repository exists to demonstrate and validate publicly disclosed
vulnerability behavior within controlled environments.

It is **not** intended to serve as an offensive exploitation framework or to
facilitate unauthorized access.

Users are expected to follow responsible disclosure practices and comply with
all applicable laws and regulations.

---

## Environment

Developed and tested within a controlled research environment.

Depending on your operating system or Python version, minor adjustments may be
required.

---

## Mitigation

Administrators should:

- Upgrade WordPress to an officially patched release
- Apply all vendor security updates
- Review authentication and web server logs
- Monitor for suspicious administrative activity
- Deploy appropriate Web Application Firewall (WAF) protections
- Follow WordPress security hardening recommendations
- Continuously monitor official security advisories

---

## References

- Rapid7 — WP2Shell Research
- The Hacker News — WP2Shell Analysis
- CVE-2026-60137
- CVE-2026-63030
- WordPress Security Releases

---

# Screenshots

## Detector / Scanner

<img width="1092" height="577" alt="image" src="https://github.com/user-attachments/assets/bbd8321f-59ed-4e5f-86d1-dde74045be6e" />

<br>

<img width="845" height="652" alt="image" src="https://github.com/user-attachments/assets/bfbdbeee-5157-4d1c-92ed-de7e0146eff7" />

<br>

<img width="637" height="387" alt="image" src="https://github.com/user-attachments/assets/67de58ef-601d-4b2b-b133-710bd12ebafa" />

<br>

<img width="650" height="462" alt="image" src="https://github.com/user-attachments/assets/7822b4e9-57a1-4f7d-afe7-3c13272ae208" />

---

## Contact

**Telegram**

https://t.me/thecodeb0ss

---

## License

Released for **educational and defensive security research**.

Users are solely responsible for ensuring that all testing is conducted with
proper authorization and in accordance with applicable laws and organizational
policies.

---

## Disclaimer

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT.

IN NO EVENT SHALL THE AUTHOR OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR
OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE
OR OTHER DEALINGS IN THE SOFTWARE.

By using this repository, you acknowledge that you are solely responsible for
ensuring that your activities are authorized and comply with all applicable
laws, regulations, and organizational policies.
