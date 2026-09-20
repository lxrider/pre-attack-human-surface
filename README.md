# PRE-ATT&CK Human Surface

> Cybersecurity does not start when you open your laptop.

It starts the day you are born online: when a name, picture, account, address, relationship or habit can be associated with you.

It becomes critical when that digital identity gives you access to resources, authority or other people's trust.

This project starts from a simple question:

> What can an attacker learn and prepare before touching a system or sending the first message?

## Why I built this

This project connects two parts of my experience: cybersecurity and private investigation training.

Both begin with the same habit: observe facts, understand the context and act before a situation becomes an incident.

It is not about turning people into security experts. It is about giving them a few practical ways to understand and reduce their own exposure.

## The idea

Before an attack, someone can use public information to:

1. **Find** a person, role, account or technology.
2. **Connect** identities, relationships, places and routines.
3. **Understand** what the person can access or influence.
4. **Prepare** a digital or physical approach.

The goal is not to make people invisible. It is to remove unnecessary clues, break obvious connections and prepare a simple response.

## Start from a blank page

No score. No new framework. Four questions:

1. **What matters?**
   Which resource, decision, activity or person are we protecting?

2. **What is visible?**
   What can an unknown person actually find through open sources?

3. **What can be understood or prepared?**
   Can those facts reveal access, authority, a relationship, a place or a moment?

4. **What do we change now?**
   Remove, separate, delay, verify or prepare a response.

This is the way I like to work: start from a blank page, understand the real need, build something simple, test it, explain it and improve it.

## OSINT, used defensively

OSINT is central to the project because public information is often where preparation begins.

A defensive OSINT review means looking at your authorized public surface before an attacker does:

- search engines, public websites and social media;
- job postings, event programs and public documents;
- code repositories and open technical databases;
- pictures, metadata, locations and visible relationships.

Compromised accounts, stolen data and access-controlled sources are not OSINT. Physical surveillance may validate an online hypothesis, but it is not OSINT either.

See [Defensive OSINT](docs/defensive-osint.md).

## Use it

- [Review an exposure in 15 minutes](playbooks/15-minutes.md)
- [Prepare a public event or trip](playbooks/event-travel-72h.md)
- [Respond safely to suspected surveillance](playbooks/suspected-surveillance.md)
- [Record an exposure and decide what to change](templates/exposure-review.md)

## Keep security human and understandable

Security should not become a collection of controls nobody understands.

For me, security starts with understanding the business first: what matters, what is at stake, the systems that support it, the risks, the constraints, and above all, the people who rely on them.

If you can't explain what you're doing in simple words, or teach it to others in a way they can understand, then you're probably building the rocket from *Tintin on the Moon* :)

The person being protected is part of the solution, not the problem.

## MITRE ATT&CK

The project mainly connects to [Reconnaissance - TA0043](https://attack.mitre.org/tactics/TA0043/) and [Resource Development - TA0042](https://attack.mitre.org/tactics/TA0042/).

ATT&CK covers the cyber side. It does not fully model physical surveillance or personal protection. The [mapping](docs/mitre-mapping.md) keeps that boundary clear.

## Scope

This is a defensive project. It does not provide surveillance, concealment, evasion or intrusive collection procedures.

A strange observation is not proof of hostile surveillance. Record facts, look for corroboration, avoid profiling and do not confront. In France, call **17** or **112** in case of immediate danger.

## Contents

```text
docs/       threat model, defensive OSINT and MITRE mapping
playbooks/  three short operational guides
templates/  exposure review and factual observation log
examples/   one fictional walkthrough
```

Sources and acknowledgements are listed in [REFERENCES.md](REFERENCES.md).

## Understand. Observe. Connect. Act.
