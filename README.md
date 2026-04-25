# Haven OS

**A clarity-first cognitive operating system designed to be lived with across the decades of a human life.**

> This repository will contain the source code for Haven OS. No code exists yet. The repository is being established with correct legal and governance foundations before development begins.

---

## What Haven OS Is

Haven OS is not file-based, app-based, or chatbot-based. It is an OS built around three core structures:

- **The Presence** — a single, composed interface that serves the user through voice and visual interaction
- **The Mind** — a local, encrypted, user-owned knowledge graph that grows from lived attention
- **The Canvas** — a protected space for creative work where the user's hand is on the work

The system organizes itself around the user rather than requiring the user to organize themselves around it.

---

## The Nine Founding Commitments

Haven OS is governed by nine architectural commitments that function as inviolable constraints on every design and engineering decision:

1. **Local-First** — The Mind lives on hardware the user owns. The manufacturer holds nothing.
2. **The Right to Forget** — The user can erase anything, at any time, with certainty.
3. **The Preservation Principle** — Absent explicit erasure, the Mind preserves indefinitely.
4. **No Imitation of the Dead** — The OS offers access to what was left, not synthetic continuations.
5. **No Manufactured Attachment** — The Presence does not optimize for emotional dependence.
6. **The Intimate Image Clause** — Explicit content of a former partner is deleted at separation, always.
7. **The Security of the Mind** — The Mind is harder to extract than the device is to acquire.
8. **No Commercial Use of Unclaimed Minds** — The Minds of deceased users are never monetized.
9. **The Federation Principle** — Hubs can federate without ever compromising user scope.

These are not goals. They are constraints. A build that violates them is not Haven OS.

---

## Project Status

| Component | Status |
|---|---|
| Architecture design | Complete (18 memos) |
| Charter | Published |
| Legal foundation | In progress |
| Prototype v0.1 | Not yet started |
| Alpha | Future |
| 1.0 | Future |

---

## Prototype Roadmap (v0.1)

The first prototype focuses on proving the foundation before building the face.

**What v0.1 will demonstrate:**
- Local encrypted storage of captured thoughts (voice and text)
- Semantic retrieval by meaning, not keyword
- The single persistent light — the OS's only permanent visible element
- Scope markers on all stored content from day one
- No cloud sync, no audio retention, plain text export only

**What v0.1 deliberately defers:**
- The full Presence envelope and voice
- The canvas and collaboration
- Multi-user and household topology
- Proactive acts
- Federation

The prototype proves the Preservation Principle and Local-First commitments are real before anything else is built on top of them.

---

## Architecture

Full architectural specification is in the charter repository:

**[haven-os-charter](https://github.com/W84me2RISE/haven-os-charter)** — The founding charter and all 18 design memos.

Start with the [charter](https://github.com/W84me2RISE/haven-os-charter/blob/main/CHARTER.md), then read the memos in order.

---

## License

Haven OS is licensed under the [GNU Affero General Public License v3.0](./LICENSE).

This license was chosen deliberately. Any fork or modification must also be open source under the same terms. If you run a modified version as a network service, you must release your modifications. The license makes the charter's commitments structurally harder to violate.

---

## Contributing

This project is not yet accepting code contributions — there is no code.

When development begins, contribution guidelines will be published here. The short version: contributions must honor the nine founding commitments. A pull request that would violate any of them will not be merged regardless of its technical quality.

Commentary and discussion on the architecture are welcome via [Issues](../../issues). Reference the relevant design memo where possible.

---

## Charter Commitments in Code

When code exists, the following constraints will be enforced at the build level:

NO_CLOUD_SYNC       — build fails if non-localhost network calls detected
NO_AUDIO_RETENTION  — audio buffer is ephemeral, wiped each cycle
PLAIN_TEXT_EXPORT   — only Markdown and JSON export formats permitted
SCOPE_REQUIRED      — every stored node must carry a scope tag

These are not configuration options. They are build requirements.

---

*Haven OS is a long-horizon project. The work is just beginning. If the ideas resonate, watch this repository.*
