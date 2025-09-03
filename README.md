# Advanced Red Team Operations Toolkit

A modular, extensible toolkit for professional red teamers and cyber security analysts in MNCs. Features real-time threat feeds, automated asset discovery, exploitation, post-exploitation, and professional reporting.

## Quick Start

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the framework: `python main.py`
4. Download final output from `output/report.txt`

## Features

- Automated Reconnaissance (subdomain, asset, vuln scan)
- Real-Time Threat Feeds (Shodan, OTX, etc.)
- Exploitation Modules (payloads, phishing, RCE)
- Post-Exploitation (privilege escalation, persistence)
- Automated Reporting (output as text file)
- Modular design (plug and play modules)

## Directory Structure

- `modules/recon/` — Reconnaissance scripts
- `modules/exploit/` — Exploitation modules
- `modules/post_exploit/` — Post-exploitation modules
- `modules/reporting/` — Reporting tools
- `output/` — Generated reports and artifacts

## Add a New Module

Just drop your Python script into the appropriate folder in `modules/`. The framework will auto-detect and run it.