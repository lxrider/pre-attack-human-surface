# MITRE ATT&CK mapping

MITRE retired the PRE-ATT&CK domain in 2020 and moved its scope into the Reconnaissance and Resource Development tactics.

This project uses “PRE-ATT&CK” descriptively for the preparation that happens before initial access.

This repository does not try to reproduce ATT&CK. It uses selected techniques to ask better defensive questions.

| What may be exposed | ATT&CK connection | Defensive question |
| --- | --- | --- |
| Names, email addresses and credentials | [T1589 — Gather Victim Identity Information](https://attack.mitre.org/techniques/T1589/) | Which identities can be linked to privileged access? |
| Roles, projects, locations and business relationships | [T1591 — Gather Victim Org Information](https://attack.mitre.org/techniques/T1591/) | What does the organization reveal about authority and trust? |
| Social media, news, public profiles and code | [T1593 — Search Open Websites/Domains](https://attack.mitre.org/techniques/T1593/) | Which public sources reveal people, habits or technology? |
| Company pages and public documents | [T1594 — Search Victim-Owned Websites](https://attack.mitre.org/techniques/T1594/) | What do our own websites disclose? |
| Internet-facing services | [T1595 — Active Scanning](https://attack.mitre.org/techniques/T1595/) | On owned or explicitly authorized infrastructure, what can direct external probing reveal? |
| DNS, certificates, registration data and other open datasets | [T1596 — Search Open Technical Databases](https://attack.mitre.org/techniques/T1596/) | Which technical links are visible without touching the target? |
| Commercial or restricted datasets | [T1597 — Search Closed Sources](https://attack.mitre.org/techniques/T1597/) | Which exposures exist beyond public search, and who is authorized to review them? |
| Information aggregated by public AI services | [T1682 — Query Public AI Services](https://attack.mitre.org/techniques/T1682/) | Can the answer be traced to an original source, or is it only an unverified lead? |
| Domains, email accounts, infrastructure and personas prepared in advance | [TA0042 — Resource Development](https://attack.mitre.org/tactics/TA0042/) | Which clues make a malicious approach credible? |

## What ATT&CK does not cover well here

ATT&CK is a cyber knowledge base. It does not fully describe:

- repeated physical observation;
- a predictable journey or transition point;
- a person being approached in a public place;
- the practical safety response when surveillance is suspected.

That gap is intentional in this project. Use ATT&CK to understand digital preparation, then use simple personal-safety practices for the physical side.

## The useful output

Do not end with a technique ID. End with an action: remove, separate, delay, verify or prepare.
