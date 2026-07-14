Last updated: 14.July 2026 

# Internet Insecure Database

## 📌 Overview

**Internet Insecure Database** is a private, self‑hosted internet scanning and inventory system. Similar to Shodan or Censys, it collects and catalogs information about publicly accessible servers and services. The project is designed exclusively for internal security research, educational purposes, and network analysis.

---

## 🗄️ Database Export

This repository contains a **CSV export** of the database, providing a snapshot of the collected data. The export includes all discovered hosts, open ports, service fingerprints, geolocation data, and ASN information.

### 📂 File

| **File** | **Description** |
|----------|-----------------|
| `InternetInsecureDatabase.csv.gz` | Full database export in CSV format |

---

## 📊 CSV Schema

The CSV file contains the following columns:

| **Column** | **Type** | **Description** |
|------------|----------|-----------------|
| `host_id` | Integer | Unique host identifier |
| `ip_address` | String | IPv4 or IPv6 address |
| `hostname` | String | Reverse DNS or hostname (if available) |
| `port` | Integer | Open port number |
| `service_name` | String | Service type (e.g., http, ssh, ftp) |
| `product` | String | Detected product / software |
| `version` | String | Detected version |
| `banner` | String | Service banner or raw response |
| `country` | String | Country name (GeoIP) |
| `country_code` | String | Country code (ISO 3166-1) |
| `asn_number` | Integer | Autonomous System Number |
| `asn_organization` | String | ASN organization name |
| `first_seen` | Timestamp | Date and time of first discovery |
| `last_seen` | Timestamp | Date and time of most recent discovery |

---

## 🔍 Sample Data

The CSV export follows the schema described above. Each row represents a single open port on a discovered host, along with all associated metadata.

---

## 🛠️ Purpose

This dataset is intended for:

- Security research and analysis
- Network mapping and inventory
- Threat intelligence and reconnaissance
- Educational use in cybersecurity training

---

## ⚠️ Disclaimer

This data is collected from publicly accessible internet sources and is intended solely for research and educational purposes. The dataset does not contain any sensitive or personally identifiable information. Users are responsible for ensuring compliance with all applicable laws and regulations when using this data.

---

## 📄 License

This project and its data export are provided for **internal research and educational purposes only**. 

Redistribution or commercial use of the data is not permitted without explicit permission.

---
```text
#┌────────────────────────────────────────────────────────────────────────┐
#│                                                                        │
#│         ███████╗████████╗ ██████╗ ███████╗██████╗ ████████╗██╗         │
#│         ██╔════╝╚══██╔══╝██╔═══██╗██╔════╝██╔══██╗╚══██╔══╝██║         │
#│         ███████╗   ██║   ██║   ██║█████╗  ██████╔╝   ██║   ██║         │
#│         ╚════██║   ██║   ██║   ██║██╔══╝  ██╔══██╗   ██║   ██║         │
#│         ███████║   ██║   ╚██████╔╝███████╗██║  ██║   ██║   ██║         │
#│         ╚══════╝   ╚═╝    ╚═════╝ ╚══════╝╚═╝  ╚═╝   ╚═╝   ╚═╝         │
#│                                                                        │
#│                       "old school, still root"                         │
#│                    "stoerti - the jobless hacker"                      │
#│                                                                        │
#│    ┌──────────────────────────────────────────────────────────────┐    │
#│    │  40 years in the trenches.     │  6 months unemployed in DE. │    │
#│    │  They fired the one who knew.  │  This is my legacy.         │    │
#│    │                   -- no patches for reality --               │    │
#│    └──────────────────────────────────────────────────────────────┘    │
#│                                                                        │
#└────────────────────────────────────────────────────────────────────────┘
```
## This is Grindware

What is Grindware?

Grindware is software that exists because nobody pays me to build the things that actually matter.

I've been unemployed for six months. Not because I can't code – but because the market doesn't care about skills anymore. It cares about buzzwords, certificates, and who you know. 
So instead of waiting for a job that never comes, I build.

Grindware is the result of that.

### The Philosophy Grindware is:

Built out of necessity – not for profit, not for investors, not for a product roadmap. Built because something needed to exist and nobody else was going to build it.

Released for free – because locking code behind a paywall feels wrong when you know what it's like to have nothing.

Honest – no marketing fluff, no "enterprise-grade" nonsense. Just code that works.

Unpolished but functional – it gets the job done. If you need a pretty UI, go somewhere else.

### Why "Grindware"?
Because that's what it is. Code written during the grind. During the late nights. During the 47th job rejection. During the moments when you realize that the system doesn't care about you, so you might as well build your own.

Grindware is survival code.

### Who is Grindware for?
Developers who are tired of corporate BS

Security researchers who need tools that actually work

Anyone who believes software should be useful, not just profitable

People who are also grinding

### What Grindware is NOT
Not a company

Not a startup

Not a product

Not for sale

Grindware is just code. From one unemployed developer to the world.

### Support Grindware
If you use Grindware, that's enough. If you want to support it, you can:

⭐ Star the repository

🐛 Report bugs

🔧 Contribute code

💬 Share it with someone who might need it

### Contact
I'm always open to work. If you need a developer who actually builds things, let's talk.

Grindware – Built in the grind, released for free.

## 📬 Contact

For questions or inquiries regarding this dataset, please contact klaus@schloss-buskow.de

---

**Last Updated:** July 2026
