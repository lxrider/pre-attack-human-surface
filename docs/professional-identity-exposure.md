# Professional identity exposure

Professional visibility is useful.

It helps people find you, understand what you do and build trust.

It can also help an attacker understand who you are, who you know, what you can
access and how to approach you.

The objective is not to disappear from the Internet.

It is to understand what your professional identity reveals and reduce what
creates unnecessary risk.

> Information does not need to be secret to become sensitive when it is aggregated.

## What does your professional identity reveal?

A professional profile rarely exists in isolation.

Profiles, posts, company pages, public documents, conference appearances, code
repositories and search results can reveal:

- your role and level of authority;
- responsibilities and access;
- colleagues and trusted relationships;
- customers, suppliers and partners;
- technologies and projects;
- office locations;
- events and travel;
- contact information;
- links between professional, technical and private identities.

A single detail may be harmless.

Several details combined may create a useful attack path.

The question is not only:

> What have I published?

It is also:

> What can someone infer by combining everything public about me?

## Think in three dimensions

Exposure is not limited to what is visible today.

A useful review should consider:

```text
CURRENT EXPOSURE
What is visible now?

        +

HISTORICAL EXPOSURE
What used to be visible?

        +

CROSS-CONTEXT EXPOSURE
What connects professional, technical and personal identities?

        ↓

CORRELATION
        ↓
ATTACK PATH
```

This matters because information removed from one platform may still exist
elsewhere, while usernames, names, email addresses, companies or photographs
may connect identities across different contexts.

## Professional networks

Professional networks are not simply public or private.

On LinkedIn, for example, what someone can see may depend on whether they are a
direct connection, part of your wider network, an unauthenticated visitor or a
search engine.

Review the privacy settings that affect:

- public profile visibility;
- visibility outside the platform;
- discoverability through email address or phone number;
- contact-detail visibility;
- connection visibility;
- activity and profile updates.

Use the level of visibility that provides the professional value you need
without exposing unnecessary context.

A connection is also more than another contact.

It may reveal additional information about you and your network.

Think about the relationship graph, not only the profile.

## Personal social networks

Professional and private identities often overlap.

Facebook, Instagram, X, TikTok, Bluesky, Reddit, Strava and similar services may
reveal context that is absent from a professional profile:

- relatives and close relationships;
- hobbies and communities;
- places regularly visited;
- travel and events;
- routines and timing;
- photographs of workplaces, badges, screens or equipment;
- usernames reused on other platforms.

The issue is not that personal social media exists.

The issue is whether it provides context that materially strengthens an attack
path.

Real-time publication deserves particular attention.

Publishing after an event may provide the same social or professional value
without revealing where someone is at that exact moment.

## Company and legal records

Professional identity also appears in public business records.

Depending on the country and context, services and registries such as:

- Pappers;
- INPI / Registre national des entreprises;
- BODACC;
- Infogreffe;
- legal notices and company publications;

may connect a person to:

- current or former companies;
- executive or representative roles;
- business partners;
- historical entities;
- registered business addresses;
- corporate events.

These sources exist for legitimate transparency purposes.

The security question is not whether they should exist.

It is what additional context they provide when connected to other public
information.

For example:

```text
business registry
    +
professional profile
    +
public technical identity
    ↓
role + history + relationships + capabilities
```

## Information exists beyond the platform

Removing information from a social profile does not guarantee that it becomes
undiscoverable.

Contact-data and sales-intelligence services such as RocketReach may aggregate
professional contact information from multiple sources.

Email-discovery services such as Hunter may find published professional
addresses or infer likely addresses from an organization's email patterns and
attempt to verify them.

Information may also remain visible through:

- company websites;
- professional directories;
- conference pages;
- public documents;
- press releases;
- association websites;
- public procurement documents;
- job advertisements;
- commercial datasets.

Your contact details do not need to be explicitly published on your profile to
become discoverable.

Privacy settings reduce exposure.

They do not guarantee invisibility.

## Historical exposure

Information can remain useful long after it has been removed from the current
website.

Web archives such as the Internet Archive's Wayback Machine may preserve older
versions of:

- team pages;
- staff biographies;
- organizational charts;
- company addresses;
- email addresses;
- technology descriptions;
- partner references;
- old projects.

Search-engine caches, copied documents and third-party mirrors may preserve
similar information.

A review should therefore ask:

> What did this organization or person expose in the past that still helps
> explain the present?

Historical information can be especially useful when it connects an old
identity, company, email address or role to a current one.

## Technical identities

Technical communities and repositories can create another layer of correlation.

Public sources may include:

- GitHub and GitLab profiles;
- public commits;
- package registries;
- technical forums;
- Stack Overflow;
- personal websites;
- usernames reused across services.

A technical profile can reveal useful professional context such as:

- technologies used;
- areas of responsibility;
- personal or work email addresses;
- project names;
- organizational affiliations;
- patterns of username reuse.

The risk usually comes from correlation rather than the source itself.

For example:

```text
LinkedIn
current security role
        +
GitHub
same username + technical projects
        +
old conference biography
former company and email
        ↓
strong identity correlation
```

## Events, talks and long-form content

Conference pages, webinars, podcasts, videos and slide decks often provide more
context than a normal profile.

They may reveal:

- precise responsibilities;
- current projects;
- architecture choices;
- customers or partners;
- travel dates;
- future events;
- internal vocabulary.

Long-form interviews are particularly useful for understanding how someone
thinks, what they work on and what they consider important.

That information may help an attacker create a more credible approach.

## Public documents and metadata

Public PDFs, reports, tender documents, presentations and other files can expose
information beyond their visible text.

Depending on how they were produced, document metadata may reveal:

- author names;
- usernames;
- organizations;
- software used;
- creation or modification dates.

The objective is not to teach metadata extraction as an offensive technique.

It is simply to remember that a published document may reveal more context than
its visible content.

## Search engines remember differently

Changing or deleting information at the source does not necessarily remove it
immediately from search results.

When possible, remove or correct unwanted information at the original source
first.

Then check what search engines still associate with your name.

In the European Union, the right to de-referencing may allow a person, under
certain conditions, to ask a search engine to stop associating specific results
with searches for their name.

De-referencing is not deletion.

The original information may still exist on the source website.

Reducing exposure therefore means looking at both the original source and how
easily it can be found.

## Known breach exposure

For defensive self-review, it can also be useful to know whether a personal or
professional email address has appeared in a known data breach.

Services such as Have I Been Pwned can help an individual or organization check
known exposure without obtaining or using stolen breach datasets.

The useful question is not:

> What leaked data can I find?

It is:

> Has an identifier associated with this person or organization been exposed in
> a way that changes the risk?

A known exposed address, for example, may increase the credibility of phishing,
password-reuse or impersonation scenarios.

## AI changes the scale

AI makes correlation easier.

Public AI services can combine information spread across profiles, websites,
documents, news, code repositories and other public sources.

MITRE ATT&CK describes the use of public AI services for reconnaissance as
**T1682 — Query Public AI Services**.

The important change is scale.

Information that would previously require several searches and manual
correlation can now be summarized quickly into a more complete picture of a
person or organization.

That picture may contain:

- organizational relationships;
- technologies;
- professional interests;
- likely contact information;
- recent activities;
- plausible reasons for contacting someone.

AI can also make impersonation easier by turning that context into convincing
written, audio or visual content.

MITRE ATT&CK covers this under **T1683 — Generate Content**.

A message that knows your manager, customer, technology or recent conference
attendance may feel familiar.

Familiarity is not proof of identity.

Sensitive or unusual requests should still be verified through another trusted
channel.

## Correlation matters more than collection

The objective is not to accumulate as much information as possible.

The useful question is:

> What connection does this information enable?

For example:

```text
Pappers
founder / former company
        +
LinkedIn
current privileged role
        +
GitHub
reused technical identity
        +
Instagram
current event or travel
        +
Wayback Machine
historical biography or contact information
        ↓
richer identity graph
        ↓
more credible attack path
```

Any one of these sources may provide little value.

The combination can be much more useful.

## Reduce what matters

Do not try to remove everything.

Professional visibility has value.

Focus on information that materially helps create an attack path.

Consider reducing or restricting:

- unnecessary private contact information;
- precise descriptions of privileged responsibilities;
- internal technical details;
- links between professional and private identities;
- unnecessary username reuse;
- real-time travel or location information;
- photographs showing badges, screens, documents or restricted areas.

Publishing after an event instead of during it can often provide the same
professional value with less exposure.

Where information cannot reasonably be removed, strengthen the process it might
otherwise help bypass.

For example, publicly knowing someone's role should never be sufficient to
bypass identity verification.

The principle is simple:

> Keep what provides value. Reduce what only makes an attack easier.

And then verify:

> Did the change actually make the useful attack path harder?

## One final principle

Public information is not automatically a security problem.

The risk appears when information creates useful context, relationships or
timing that helps someone affect something that has value.

> Do not collect more. Connect better, decide what matters, and reduce the
> useful attack path.
