# Design Decisions

GID is designed **one-way-door first.**

Some choices are irreversible the moment anyone builds against them — the wire
envelope, the versioning and extension mechanism, the addressing scheme, the
mandatory-to-implement core. Everything else is a two-way door, safely deferred.
The discipline is simple: spend the early rigor on the doors that can't be
reopened, and keep everything expressible *through* them deferrable.

(Grounding: [RFC 6709](https://datatracker.ietf.org/doc/html/rfc6709).)

Each settled choice is recorded as a short Architecture Decision Record: what was
decided, which kind of door it is, and what it would cost to reverse. ADRs are
published here as they're ratified — the format is in
[`0000-template.md`](0000-template.md).
