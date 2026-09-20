# Defensive OSINT

The goal is simple: see what an attacker can learn before they act.

Start with the problem, not the search engine.

## What matters?

Think about the threat, the attacker's objective and the potential impact.

**Threat** — What are we protecting against?

For example: targeted social engineering, credential theft, fraud or unauthorized access.

**Objective** — What is the attacker trying to achieve?

For example: impersonate someone, obtain privileged access, trigger a fraudulent payment or reach a production environment.

**Impact** — What could happen if they succeed?

For example: financial loss, account takeover, exposure of confidential information, a data breach or disruption of operations.

Then ask:

> What exposed information could make that easier?

Public information matters when it helps create an attack path.

## What is exposed?

Use public or explicitly authorized sources.

Useful information often reveals one or more of these:

- an **identity**;
- an **access** or capability;
- an **authority** or decision-making role;
- a **relationship** that can be abused;
- a **place** or precise **time**.

Sources may include public profiles, company websites, press releases, conference programs, job advertisements, public documents, code repositories and technical databases.

Record facts, not interpretations.

Public AI services can help find connections, but an AI answer is not evidence. Trace useful information back to its original source.

For professional networks, search engines, contact-data services and AI-assisted correlation, see [Professional identity exposure](professional-identity-exposure.md).

## What can be connected?

A single fact may mean very little.

The interesting part is what becomes possible when several facts are connected.

Think in short chains:

`public information → useful context → attack path → impact`

For example:

`conference agenda → named IAM administrator → employer and travel date → credible support impersonation`

Keep facts and assumptions separate.

If an important conclusion depends on an assumption, verify it.

## What should change?

Do not try to remove everything.

Change what meaningfully reduces risk.

That may mean:

- removing information that has no useful public value;
- separating personal and professional identities;
- restricting visibility;
- reducing unnecessary detail;
- delaying posts about travel, events or locations;
- verifying sensitive requests through another trusted channel.

The goal is not invisibility.

The goal is to make useful attack paths harder.

## What is not OSINT?

Stolen data, compromised accounts, access-controlled sources and deception-based collection are not open-source intelligence.

Physical surveillance is not OSINT either, even when it is used to confirm an online hypothesis.

The boundary matters: this project helps people understand and reduce exposure; it does not teach someone how to target them.
