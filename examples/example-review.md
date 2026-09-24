# Example: a privileged administrator at a conference

This example is fictional.

## What has value?

Lina Martin has privileged responsibilities related to identity and access.

The value at stake is not her public profile itself.

It is the privileged access, authority and production systems that her role may
allow her to influence.

## What is the attacker trying to achieve?

**Threat**  
Targeted social engineering or impersonation.

**Objective**  
Obtain privileged access or convince support to bypass normal verification.

**Impact**  
Account takeover or unauthorized access to production systems.

## What is exposed?

Public information shows that Lina Martin is an identity and access administrator.

A conference page reveals when she is speaking and what she is speaking about.

Her professional profile confirms her role and employer.

A public code profile uses the same username and links her identity to
identity-related tooling.

A social post reveals that she is travelling to the event.

None of these facts is particularly sensitive on its own.

Together, they provide useful context.

## What can be connected?

The most useful chain is:

```text
privileged access
    ↓
attacker wants to impersonate a trusted administrator
    ↓
conference page
    ↓
named IAM administrator
    ↓
travel timing
    ↓
credible urgent support impersonation
```

The reused username also makes professional and technical identities easier to
connect.

The travel post may reveal when she is away, but that remains an inference
rather than a confirmed fact.

## What should change?

Remove unnecessary real-time travel information.

Separate public identities where doing so provides useful friction.

Most importantly, privileged account recovery should never rely on someone's
role, urgency or knowledge of internal context as proof of identity.

The useful outcome is not a score.

It is fewer useful connections and a verification step that people understand.

## Did it work?

Review the same public exposure after treatment.

Ask:

- Is real-time travel information still available?
- Can the professional and technical identities still be connected as easily?
- Would knowledge of Lina's role and context still help bypass account recovery?
- Does the verification process remain effective even if the attacker knows
  publicly available details?

The objective is not to remove every public fact.

It is to verify that the most useful attack path has become harder.

```text
BEFORE

Public role
+ conference
+ travel timing
+ identity correlation
        ↓
credible impersonation context


AFTER

Less unnecessary context
+ stronger identity verification
        ↓
reduced value of the public information to the attacker
```
