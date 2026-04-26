# Joining the Stream

A reasonably privacy-focused Windows 11 Pro setup for ordinary, low-attention internet use.

The aim is not to look invisible or unusual. The aim is to run a clean Windows system, avoid unnecessary account linking, keep downloads contained, update automatically, and browse in a way that blends in with normal desktop use.
Linux is a sore thumb in telemetries asgaisnt an ocean of Windows users..

## Goals

- Use a local Windows account (create Windows ISO with Rufus)
- Avoid signing into Windows with a Microsoft account
- Keep Windows, Microsoft Store apps, Defender, drivers and winget apps updated
- Use Microsoft Store and winget for app installation
- Use one main browser for general internet use
- Use Chrome only for Google services
- Treat Downloads as a quarantine zone
- Use Windows Sandbox for suspicious files
- Enable strong Defender and firewall defaults
- Use WireGuard for remote access instead of exposing services
- Use StevenBlack hosts as a quiet system-level malware and adware blocklist
- Use Storage Sense and light BleachBit cleanup by creating scripts
- Remove unnecessary built-in apps without breaking Windows
- Audit Firefox and Chrome settings, uBlock and DNS settings (OPNSense, pihole or cloudflare)
- Anything more is outside the scope of this guide

## Assumptions

This guide assumes:

- Fresh Windows 11 Pro installation
- PowerShell is being run as Administrator
- You are using a local Windows account
- You have internet access
- You want a stable daily-use system, not an extreme lockdown build

## Manual install choices

During Windows setup:

- Choose Windows 11 Pro
- Use a local account
- Do not sign into Windows with a Microsoft account
- Skip OneDrive setup
- Disable advertising ID
- Disable tailored experiences
- Disable optional diagnostic data
- Disable activity history
- Disable location unless needed
- Disable Find My Device unless you want that trade off
- Use a plain local username such as `dan`, `user`, or `desktop`

## Now for the powershell commands to create this setup

Powershell commands:

- Coming soon

## Decently secure home setup
- Replace router with OPNSense Industrial PC and WAP... Keep it simple, ...!
- AI can certainly assist, expand capability and automate tasks, but it's real advatange is feedback awareness. 
- Automated tools can correlate public data and identify individuals across services. This guide does not protect against that.
