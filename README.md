# swy4x CyberSec Hub

A browser-first cybersecurity workspace organized by discipline and dedicated tool pages.

## Current structure

- `index.html` — Category-first CyberSec Hub explorer and browser tool workspaces.
- `bug-bounty.html` — Preserved original Bug Bounty Toolkit page.
- `tools-hub.html` — Original multi-tool hub retained as a legacy reference.

## Categories

Bug Bounty & Web Security, Vulnerability Assessment, Network Security, OSINT & Intelligence, SOC & Blue Team, Malware Analysis, Digital Forensics, Security Auditing, Wireless Security, Cryptography & Passwords, Cloud & Infrastructure, API Security, Email Security, Mobile Security, Active Directory, Threat Intelligence & Incident Response, Reverse Engineering, and Learning & Cyber Labs.

## Implementation status

The homepage now provides category navigation, tool search, filters, dedicated tool workspaces, and initial browser-side utilities such as SHA-256 hashing, Base64, URL encoding/decoding, JWT decoding (without signature verification), password generation, IPv4 subnet calculation, IOC extraction, email-header parsing, browser information, and a finding-report template.

Tools marked **Service required** need a real backend/provider integration before live lookups can run. Tools marked **In development** are not implemented yet. The interface intentionally does not fabricate scan results or claim unsupported functionality.

## Safety

Use active security testing only on systems you own or are explicitly authorized to assess. Treat automated findings as leads that require verification. Do not upload sensitive files or secrets unless the tool's data handling is clearly understood.
