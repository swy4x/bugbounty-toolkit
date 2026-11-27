# swy4x CyberSec Hub

A browser-first cybersecurity workspace organized by discipline and dedicated tool pages.

## Current structure

- `index.html` — Category-first CyberSec Hub explorer and browser tool workspaces.
- `bug-bounty.html` — Advanced Bug Hunting Toolkit using the original neon-purple terminal-card layout, modular copy-ready recon commands, passive web intelligence sources (crt.sh, Wayback, GAU, URLScan, Common Crawl, OTX), vulnerability-specific command references, and payload notes.
- `tools-hub.html` — Original multi-tool hub retained as a legacy reference.

## Categories

Bug Bounty & Web Security, Vulnerability Assessment, Network Security, OSINT & Intelligence, SOC & Blue Team, Malware Analysis, Digital Forensics, Security Auditing, Wireless Security, Cryptography & Passwords, Cloud & Infrastructure, API Security, Email Security, Mobile Security, Active Directory, Threat Intelligence & Incident Response, Reverse Engineering, and Learning & Cyber Labs.

## Implementation status

The homepage provides category navigation, tool search, filters, dedicated tool workspaces, and browser-side utilities. The Bug Bounty Toolkit is a command reference and generator: enter a root domain to fill `{domain}` placeholders, then copy individual commands. Commands run in the user's own terminal; the website does not execute scans. Some commands require separate CLI tools, API keys, local wordlists, or endpoint-specific edits. Passive web-recon sources are documented as separate commands instead of one fragile pipeline.

Tools marked **Service required** need a real backend/provider integration before live lookups can run. Tools marked **In development** are not implemented yet. The interface intentionally does not fabricate scan results or claim unsupported functionality.

## Safety

Use active security testing only on systems you own or are explicitly authorized to assess. Treat automated findings as leads that require verification. Do not upload sensitive files or secrets unless the tool's data handling is clearly understood.
