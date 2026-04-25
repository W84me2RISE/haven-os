# Contributing to Haven OS

## Current Status

Haven OS is not yet accepting code contributions. There is no code.

This will change. When it does, this document will be updated with
specific guidelines. Until then, the ways to contribute are:

---

## What You Can Do Now

**Read the architecture.**
The full design is in the charter repository:
https://github.com/W84me2RISE/haven-os-charter

Start with CHARTER.md, then the design memos in order.

**Open an issue.**
If you have a question, critique, or observation about the architecture,
open an issue in the charter repository. Reference the specific memo
where relevant. Serious engagement with the design is welcome.

**Watch this repository.**
When development begins, watchers will see it first.

---

## What Will Be Required When Code Contributions Open

Every contribution to Haven OS must honor the nine founding commitments
in the charter. This is not aspirational — it is a hard requirement.

A pull request that would cause Haven OS to:
- Send user Mind data to a server the user does not own
- Retain audio beyond the immediate transcription cycle
- Bypass scope enforcement
- Create a mechanism for manufactured attachment
- Introduce surveillance capability

...will not be merged. Technical quality is not a substitute for
charter compliance.

**The Developer Certificate of Origin (DCO) will be required.**
Every commit must include a sign-off certifying that you have the right
to contribute what you are contributing: 

git commit -s -m "Your commit message"

This adds a `Signed-off-by` line to your commit. It is lightweight,
legally meaningful, and required.

---

## The Standard

When in doubt about whether a contribution honors the charter, ask
yourself the test from the charter itself:

*Does this decision honor the commitments, or erode them?*

If you are not sure, open an issue and discuss before submitting code.
