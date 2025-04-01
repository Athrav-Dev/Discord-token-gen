# Discord-token-gen

🚀 **EVS Gen Tool** 🚀

[+] Created By Athrav-Dev (AK)

## Overview

The **EVS Gen Tool** is a Python-based tool designed for automating Discord account creation with temporary emails and bypassing Discord's CAPTCHA using Selenium and `undetected_chromedriver`. The tool interacts with Discord's registration system and allows automated account creation for Discord with some rate-limiting checks.

## Features

- Automated Discord account creation.
- Temporary email generation for account verification.
- CAPTCHA handling using manual intervention.
- Fetches and saves Discord tokens.
- Provides logs for account creation status and errors.
- Saves generated tokens and account information to `tokens.txt` and `evs.txt` automatically.

## Requirements

Before running the tool, make sure you have the following dependencies installed:

- `undetected-chromedriver`
- `selenium`
- `colorama`
- `fake_useragent`
- `pystyle`
- `requests`
- `tls_client`

Install these dependencies using `pip`:

```bash
pip install undetected-chromedriver selenium colorama fake_useragent pystyle requests tls_client
