# GID — Glasses Interface Device

**Self-describing, addressable input for the glasses era.**

GID is a proposed sister standard to HID — the standard that made keyboards,
mice, and game controllers self-describing and driver-free. HID carried input
computing for decades, but it rests on one built-in assumption: input
terminates at the host operating system and goes to the focused application on
that host. HID has no way to address a separate display surface — the glasses —
or one application among several running on them.

Smart glasses break that assumption. The host is the phone in your pocket; the
display is on your face; and several app surfaces may share it at once. Today
each vendor reinvents a private Bluetooth channel to bridge that gap — none of
them portable, discoverable, or reusable. GID standardizes the layer they all
keep rebuilding: self-describing, **addressable** input, designed for forward
compatibility.

## Status

GID is in active design. The irreversible foundations — the wire envelope,
versioning and negotiation, the extension mechanism, and the addressing
scheme — are being settled before anything is frozen.

**The first published draft of the GID specification will be uploaded to this
repository soon.** Until then this repository is a placeholder; the canonical
introduction lives on the website below.

## Learn more

- Website — https://gid.pekelabs.com
- Why GID exists — https://gid.pekelabs.com/why
- How it works — https://gid.pekelabs.com/how
- Roadmap — https://gid.pekelabs.com/roadmap

## Community

GID is meant to be shaped in the open, with explicit provenance. The standard
is better the more it is argued with.

- Discord — https://discord.gg/hAAR933XY6
- Contact — info@pekelabs.com

## Stewardship

GID is stewarded by PeKe Labs and intended as an open, community-shaped
standard. Debuted as a concept at AWE XR 2026.
