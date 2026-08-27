# UK regulator-to-regulator data-sharing gateways

An interactive matrix of statutory information-sharing gateways between 18 UK
regulators. Each cell answers: **can the row regulator lawfully disclose to the
column regulator — and how?**

**Live site:** https://adrasyn.github.io/reg-data-sharing/

Ratings are resolved per (edge × data type), with separate results for business /
commercial data and personal data. Click any cell for the legal basis, conditions
and limits, and links to the underlying legislation and any MoU.

## Reading the matrix

| | |
|---|---|
| **Routine** | An established gateway, used as a matter of course |
| **Permitted** | Lawful, but not a standing arrangement |
| **Via MoU** | Operationalised through a memorandum of understanding |
| **Case-by-case** | Requires a specific assessment each time |
| **Blocked** | No gateway; a statutory confidentiality bar applies |

Data protection is a *condition* on sharing personal data, not a *power* to
disclose, and cannot override a statutory confidentiality bar.

## Status

First-pass, directional map compiled 26 Aug 2026 from 18 regulator profiles.
Verified flags cover primary legislation (all bar scopes) and 80 of 95 gateway
MoUs. **Not legal advice.**

## Development

Single self-contained `index.html` — no build step, no dependencies. Open it
directly, or serve the directory with any static file server.
