# security-labs

**Hands-on security labs — find it, explain it, fix it, prove it.**

> **Status: building.** One writeup per lab. No real IPs, no client data, no live third-party targets.

This repo is my interview armour for SOC L1 / Junior Security Analyst roles. Every lab follows the same loop:

1. **Find** — reproduce the issue in a controlled lab.
2. **Explain** — what the vulnerability is, why it exists, what an attacker gains.
3. **Fix** — the remediation and how I verified it.
4. **Prove** — screenshots, commands, logs, and a short takeaway.

## Lab index

| # | Lab | Focus | Status |
|---|---|---|---|
| 00 | [Template](labs/00-template.md) | Writeup structure | ready |
| 01 | OWASP Juice Shop — recon & auth | Web, OWASP Top 10 | planned |
| 02 | DVWA — SQL injection | Input handling, defence | planned |
| 03 | CIS hardening — Linux baseline | OS hardening | planned |
| 04 | PortSwigger — one lab/week | Web exploitation | planned |
| 05 | Log analysis — grep/awk/jq | Detection fundamentals | planned |

## Rules

- Only test systems I own or intentionally vulnerable labs I run locally.
- Redact hostnames, public IPs, tokens, and personal data.
- Every "fix" must be verified, not assumed.
- If I cannot explain it to a non-technical person, I do not understand it yet.

## Stack

Linux (Ubuntu / Kali / Debian), Docker, OWASP Juice Shop, DVWA, Burp Suite Community, Wireshark, nmap, bash, Python.

## Related

- [`homelab-soc`](https://github.com/agp-369/homelab-soc) — Wazuh SIEM, one agent, one alert, one runbook.
- [`llm-security-labs`](https://github.com/agp-369/llm-security-labs) — OWASP LLM Top 10.

> "I find what breaks, fix it, measure it, and make sure it stays fixed."
