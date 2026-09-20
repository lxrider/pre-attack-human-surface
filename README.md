# PRE-ATT&CK Human Surface

> What can an attacker learn before touching a system or sending the first message?

Security does not start at the firewall.

Before an attack, information about people, roles, relationships, technologies, locations and timing may already be publicly available.

Individually, those details may seem harmless.

Connected together, they can make an attack much easier.

## The idea

Start with the problem, not the framework.

Ask:

- What is the attacker trying to achieve?
- What information could help them?
- What can be connected?
- What is worth changing?

That is enough.

The goal is not to make people invisible.

It is to understand which exposed information creates useful attack paths and reduce what actually matters.

## Keep security human and understandable

Security should not become a collection of controls or procedures nobody understands.

This project deliberately avoids turning defensive OSINT into another complicated methodology.

The useful output is not a bigger collection of information.

It is a better decision.

Remove something.

Restrict it.

Separate it.

Delay it.

Verify something differently.

Or decide that the exposure is acceptable and leave it alone.

## Documentation

### [Defensive OSINT](docs/defensive-osint.md)

A simple way to connect threat, attacker objective, public exposure, attack paths and impact.

### [Professional identity exposure](docs/professional-identity-exposure.md)

How professional networks, search engines, contact-data services and AI can combine information about people and organizations.

### [Suspected surveillance: a safe response](docs/suspected-surveillance.md)

A short defensive note on recognizing concerning patterns and responding safely without teaching surveillance or counter-surveillance techniques.

### [MITRE ATT&CK mapping](docs/mitre-mapping.md)

Selected ATT&CK Reconnaissance and Resource Development techniques related to the project.

## Why PRE-ATT&CK?

MITRE retired the PRE-ATT&CK domain in 2020 and moved its scope into the Reconnaissance and Resource Development tactics.

This project uses “PRE-ATT&CK” descriptively for the preparation that happens before initial access.

It does not try to reproduce ATT&CK.

ATT&CK is a reference here, not the method.

## Scope

This is a defensive project.

It focuses on publicly available or explicitly authorized information and on practical ways to reduce unnecessary exposure.

It does not provide procedures for intrusive collection, surveillance, concealment, evasion or targeting people.

## One principle

> Do not collect information because you can. Understand why it matters.

Start with the problem.

Keep what helps solve it.

Remove the rest.
