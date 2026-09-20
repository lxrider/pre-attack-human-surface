# Defensive OSINT

The goal is simple: see your public exposure before an attacker does, then decide what to change.

Information becomes dangerous when it reveals one of five things:

- an **identity**;
- an **access** or capability;
- an **authority** or decision-making role;
- a **relationship** that can be abused;
- a **place** or precise **time**.

## 1. What matters?

Start with the attacker's objective and the impact it could create, not the search engine.

Ask:

- What is the attacker trying to achieve?
- What would that mean for the person or the organization?

Examples: getting a fraudulent payment approved, taking over privileged access, reaching a production environment, learning details of a confidential meeting or identifying a private home address.

Then ask what exposed information could help make that possible.

## 2. What is visible?

Use only public or explicitly authorized sources:

- search engines and public profiles;
- company websites, biographies and press releases;
- conference programs and public calendars;
- job advertisements and supplier pages;
- public code repositories and technical databases;
- images, documents and metadata intentionally available online.

Record the source, date and exact fact. A fact is not an interpretation.

Public AI services can reveal useful leads or connections, but they can also invent them. Record the original source and never treat an AI answer as evidence on its own.

## 3. What can be connected?

Build short chains:

`public source → person or role → access, relationship, place or time → possible consequence`

Example:

`conference agenda → named IAM administrator → travel date and employer → credible support pretext`

Write assumptions as assumptions. Confirm them with a second independent source before treating them as reliable.

## 4. What do we change now?

Choose the smallest useful action:

- **remove** information that has no public value;
- **separate** personal and professional identities;
- **delay** posts about travel, events or locations;
- **reduce** unnecessary detail in biographies, documents and job adverts;
- **verify** sensitive requests through a second channel;
- **prepare** a contact and response plan.

Use the [exposure review template](../templates/exposure-review.md) to keep the result short.

## What is not OSINT?

Stolen data, compromised accounts, access-controlled sources and deception-based collection are not open-source intelligence. Physical surveillance is not OSINT either, even when it is used to confirm an online hypothesis.

The boundary matters: this project helps people reduce exposure; it does not teach someone how to target them.
