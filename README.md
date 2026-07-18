# (WP2Shell) – Proof of Concept

> **Educational and defensive Proof of Concept (PoC)** for validating exposure to the WordPress Core vulnerabilities **CVE-2026-60137** and **CVE-2026-63030 (WP2Shell)**.

![Purpose](https://img.shields.io/badge/Purpose-Defensive%20Research-blue)
![Platform](https://img.shields.io/badge/Platform-WordPress-orange)
![Python](https://img.shields.io/badge/Python-2.7.17-yellow)
![OS](https://img.shields.io/badge/Tested%20on-Windows-blueviolet)
![License](https://img.shields.io/badge/License-Educational-success)

---

## Overview

This repository provides a **defensive detection and validation proof of concept**
for the WordPress Core vulnerabilities collectively known as **WP2Shell**.

According to publicly available security research, **WP2Shell** describes a
vulnerability chain involving **CVE-2026-60137** and **CVE-2026-63030** that,
under specific conditions, can result in **unauthenticated Remote Code Execution (RCE)**.

The objective of this project is to help:

- Security researchers
- Penetration testers
- Blue teams
- Incident responders
- System administrators

identify vulnerable WordPress installations, reproduce the issue in authorized
laboratory environments, and verify successful remediation after applying
official security updates.

This repository is intended **strictly for educational, defensive, and
authorized security research purposes**.

---

## Vulnerabilities

| CVE | Description |
|------|-------------|
| **CVE-2026-60137** | WordPress Core vulnerability involved in the WP2Shell vulnerability chain. |
| **CVE-2026-63030** | Critical WordPress Core Remote Code Execution (RCE) vulnerability, publicly referred to as WP2Shell. |

---

## Affected Versions

According to the public advisories, the following WordPress Core versions are affected:

- WordPress **6.9.0 – 6.9.4**
- WordPress **7.0.0 – 7.0.1**

Users should upgrade to the latest patched release provided by the WordPress
Security Team.

---

## Repository Goals

This project is designed to assist defenders in:

- Validating exposure to WP2Shell
- Detecting vulnerable WordPress installations
- Verifying remediation after patching
- Reproducing the issue within isolated lab environments
- Supporting incident response and forensic investigations
- Improving technical understanding of the disclosed vulnerabilities

---

## Features

- Defensive vulnerability validation
- Detection of affected WordPress versions
- Research-oriented implementation
- Patch verification
- Lightweight detector / scanner
- Educational reference implementation

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

## Academic & Defensive Research Notice

This repository has been published solely for:

- Academic research
- Security education
- Defensive security validation
- Authorized penetration testing
- Incident response
- Patch verification
- Vulnerability assessment

The software must **only** be executed against:

- Systems you own, or
- Systems for which you have received explicit authorization.

---

## Authorization Requirement

Unauthorized testing against systems that you do not own or administer may
violate local laws, organizational policies, or international regulations.

The author **does not** encourage or support:

- Unauthorized access
- Internet-wide exploitation
- Mass scanning of third-party systems
- Malicious activity
- Abuse of vulnerable infrastructure

---

## Responsible Usage

This repository demonstrates publicly disclosed vulnerability behavior for
defensive validation and educational purposes only.

It is **not intended** to function as an offensive exploitation framework or to
facilitate unauthorized access.

Users are expected to comply with all applicable laws, regulations, and
responsible disclosure practices.

---

## Tested Environment

The proof of concept was developed and validated in the following environment:

- **Operating System:** Microsoft Windows
- **Python Version:** **2.7.17**

Execution on other operating systems or Python versions may require minor
modifications.

---

## Mitigation

Administrators are strongly encouraged to:

- Upgrade WordPress to an officially patched release
- Apply all available security updates
- Review authentication and web server logs
- Monitor for suspicious administrative activity
- Deploy Web Application Firewall (WAF) protections
- Follow WordPress security hardening recommendations
- Continuously monitor official WordPress security advisories

---

## References

- Rapid7 — WP2Shell Research
- The Hacker News — WP2Shell Analysis
- CVE-2026-60137
- CVE-2026-63030
- WordPress Security Releases

---

## Contact

**Telegram**

https://t.me/thecodeb0ss

---

## License

This project is released for **educational and defensive security research**.

Users are solely responsible for ensuring that all testing is conducted with
proper authorization and in accordance with applicable laws, regulations, and
organizational policies.

---

## Disclaimer

THE SOFTWARE IS PROVIDED **"AS IS"**, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT.

IN NO EVENT SHALL THE AUTHOR OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR
OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE
OR OTHER DEALINGS IN THE SOFTWARE.

By using this repository, you acknowledge that you are solely responsible for
ensuring that your activities are authorized and comply with all applicable
laws, regulations, and organizational policies.
