# ThreatFeed — Security Advisory Aggregator

A curated, advisory/CVE-focused feed of actively-exploited vulnerabilities, zero-days, supply chain compromises, and ongoing attack campaigns. Curated by Abhishek Sharma.

**Live site:** https://sharma005.github.io/threat_hunting/

## Contents

- `index.html` — the feed (app-style layout, category filters, search, sort, light/dark toggle)
- `about.html` — coverage, sources, and workflow
- `feed.xml` — RSS 2.0 / Atom feed (subscribe in any reader)
- `items.json` — canonical data store for all advisory items
- `.nojekyll` — serve files as-is (skip Jekyll processing)

## Design

Warm "Quarry" palette with a coral accent, serif display headings, and monospace CVE/technique pills. Theme preference is remembered in the browser and defaults to your system setting.

## Sources

CISA KEV & advisories, Zero Day Initiative, vendor PSIRTs (Oracle, Cisco, Microsoft, Google, Arista), and threat-intel reporting (Rapid7, SecurityWeek, The Hacker News, GitGuardian, Phoenix Security, CYFIRMA, BleepingComputer). Refreshed every 6 hours; nothing is posted without review.

IOCs and technical details are for **defensive use only**. Verify against the linked primary source before acting.
