# Akesa Diag Tool

A Windows desktop toolbox for network, email and file-system diagnostics.

**[Download the latest version](https://github.com/RamboFR05TY/AkesaDiagTool-releases/releases/latest)**: run `AkesaDiagTool-Setup-<version>.exe`.

Once installed, the app updates itself: it checks for new versions in the background and offers
**Restart now** when one is ready (otherwise it installs the next time the app is closed).
**About & updates** inside the app shows the installed version and what's new.

## What's in it

- **Overview:** My Network (interfaces, public IP), Speed Test
- **Diagnostics:** Ping, Traceroute, Ping Plotter, DNS Lookup (with IP owners), HTTP / TLS Check,
  Whois, SMTP Tester, Email Security (SPF, DKIM, DMARC, MTA-STS, BIMI, blacklists)
- **Local network:** LAN Device Scan (vendors, open ports), Port Scanner, Wake-on-LAN
- **Utilities:** Subnet Calculator, Path Length Checker, Disk Usage, History of saved results

## First install: Windows SmartScreen

The installer is not code-signed yet, so Windows may show *"Windows protected your PC"*.
Click **More info → Run anyway**. Updates after that install without this prompt.

## Upgrading from "Network Diag Tool"

Earlier builds were called Network Diag Tool. For a clean install location, uninstall it from
**Settings → Apps** and then run the new installer. Saved History and Wake-on-LAN devices are kept.

---

This repository holds release builds only; the source code is private.
