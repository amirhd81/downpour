# Security policy

## Supported versions
Security fixes go into the latest release. Downpour updates itself, so please keep automatic updates on.

| Version | Supported |
|---|---|
| Latest release | ✅ |
| Older releases | ❌ (update to the latest) |

## Reporting a vulnerability
Please **don't open a public issue** for security problems.

Instead, email **amir.hd.davoudi1381@gmail.com** with:
- what you found and how to reproduce it,
- the Downpour version and macOS version,
- whether it's in the app or the browser extension.

You'll get a reply within 7 days. Once it's fixed, the release notes will credit you, unless you'd rather stay anonymous.

## What Downpour does to stay safe
- The browser extension talks only to the Downpour app on your own Mac (127.0.0.1), and the app refuses requests that come from websites.
- Site logins are stored in the macOS Keychain.
- Updates are signed and checked before they're installed.
- Downloaded files are marked as coming from the internet, so macOS checks downloaded apps before they first open.
