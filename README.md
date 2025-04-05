# Subdomain Scanner (Python)

This tool checks for active subdomains on a given domain using a basic wordlist and HTTP requests.

## How It Works
- Sends HTTP requests to common subdomain prefixes (e.g., blog.example.com)
- Flags subdomains that return successful responses

## Tools Used
- Python 3
- requests module

## Usage
```bash
python subdomain_scanner.py
