# Defensive OSINT

The goal is simple: understand what an attacker can learn before they act and
whether that information creates a useful attack path.

Start with the problem, not the search engine.

## What has value?

Before looking at exposure, understand what matters.

That may include:

- privileged access;
- sensitive information;
- money;
- production systems;
- decision-making authority;
- personal safety;
- availability of an important service.

Then ask:

> What would an attacker gain by affecting this value?

This keeps the investigation focused on useful risk rather than collecting
information for its own sake.

## What is the attacker trying to achieve?

Think about the threat, the attacker's objective and the potential impact.

**Threat**  
What are we protecting against?

For example: targeted social engineering, credential theft, fraud or
unauthorized access.

**Objective**  
What is the attacker trying to achieve?

For example: impersonate someone, obtain privileged access, trigger a fraudulent
payment or reach a production environment.

**Impact**  
What could happen if they succeed?

For example: financial loss, account takeover, exposure of confidential
information, a data breach or disruption of operations.

Then ask:

> What exposed information could make that easier?

Public information matters when it helps create an attack path towards something
that has value.

## What is exposed?

Use public or explicitly authorized sources.

Useful information often reveals one or more of these:

- an **identity**;
- an **access** or capability;
- an **authority** or decision-making role;
- a **relationship** that can be abused;
- a **place** or precise **time**.

Sources may include public profiles, company websites, press releases,
conference programs, job advertisements, public documents, code repositories
and technical databases.

Record facts, not interpretations.

Public AI services can help find connections, but an AI answer is not evidence.
Trace useful information back to its original source.

For professional networks, search engines, contact-data services and AI-assisted
correlation, see
[Professional identity exposure](professional-identity-exposure.md).

## What can be connected?

A single fact may mean very little.

The interesting part is what becomes possible when several facts are connected.

Think in short chains:

```text
value
  ↓
attacker objective
  ↓
public information
  ↓
useful context
  ↓
attack path
  ↓
impact
```

For example:

```text
privileged access
    ↓
obtain or impersonate that access
    ↓
conference agenda
    ↓
named IAM administrator + travel timing
    ↓
credible urgent support impersonation
```

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

## Did it work?

A treatment is useful only if it changes the attack path.

Compare the situation before and after the change.

For example:

```text
BEFORE

Public role
+ conference agenda
+ real-time travel information
+ reused identity
        ↓
easy correlation
        ↓
credible impersonation path


TREATMENT

Remove unnecessary real-time information
+ separate identities where useful
+ strengthen verification


AFTER

Can the same attack path still be built as easily?
```

The proof does not need to be complicated.

It only needs to answer:

> Did the treatment meaningfully reduce the attacker's useful context or ability
> to exploit it?

If not, reconsider the treatment.

## What is not OSINT?

Stolen data, compromised accounts, access-controlled sources and deception-based
collection are not open-source intelligence.

Physical surveillance is not OSINT either, even when it is used to confirm an
online hypothesis.

The boundary matters: this project helps people understand and reduce exposure;
it does not teach someone how to target them.
