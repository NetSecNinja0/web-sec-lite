# Web-Sec-Lite

## Overview
`Web-Sec-Lite` is a lightweight tool designed for security testing. It includes both a CLI and GUI version, allowing users to crawl websites and scan for vulnerabilities such as SQL Injection, XSS (Cross-Site Scripting), and missing security headers.

### Features:
- **Crawl Websites**: Crawl websites up to a specified depth to discover URLs.
- **SQL Injection Scanner**: Test URLs for SQL Injection vulnerabilities.
- **XSS Scanner**: Test URLs for Cross-Site Scripting (XSS) vulnerabilities.
- **Insecure Headers Check**: Verify if important security headers are missing from the response.

## Files
- `vulnerability_scanner_cli.py`: The CLI version of the Web-Sec-Lite tool.
- `vulnerability_scanner_gui.py`: The GUI version of the Web-Sec-Lite tool (built with a GUI library).
- `requirements.txt`: List of dependencies required for the project.
## Installation

### Requirements
You must enter the correct URL of the website you want to crawl and perform testing on. Example: https://example.com".

```bash
https://example.com

Before installing any tools, it's good practice to update your system to ensure you have the latest package information by running the following command:

```bash
sudo apt update

Make sure you have Python 3.x installed. You can install it by running the following command:

```bash
sudo apt install python3

Required libraries to run this tool. You can install them by running the following command:

```bash
sudo apt install python3-requests python3-bs4 python3-tk
