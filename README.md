# Zenbook Cyberdeck

A cyberdeck built from the mainboard of an Asus Zenbook 14 (Q4071 / Q407IQ). This is a
re-housing project: the laptop is fully functional and is being moved out of its clamshell
into a custom 3D-printed enclosure, primarily to replace the built-in keyboard.

## Donor machine

- **Model:** Asus Zenbook 14, Q4071 (internal: Q407IQ)
- **CPU:** AMD Ryzen 5 4500U
- **GPU:** AMD Radeon Vega 8 (integrated) + NVIDIA GeForce MX350 2GB (discrete)
- **RAM:** 8GB
- **Storage:** 256GB SSD
- **Display:** 14" 1920×1080
- **Ports:** USB-C, USB 3.2 Gen 2 Type-A, USB 2.0, HDMI, microSD

The board, original screen + cable, and original power input are all known-good and stay
together as a unit. No motherboard transplant — the Zenbook board is the brain.

## Goal

Re-house the working Zenbook into a custom enclosure with input devices I actually want.
Secondary goal: a multi-week hands-on project to learn my new 3D printer.

## Initial plan

These are current decisions and may change as the build progresses.

- **Form factor:** slab / upright-deck vs. clamshell — TBD, decided at layout mock-up.
- **Keyboard:** external USB keyboard (the whole reason for the build). Original keyboard dropped.
- **Pointer:** trackball over USB. Plug-and-play unit vs. integrated sensor/ball/bearings — TBD.
- **Trackpad:** dropped entirely.
- **Power/display:** reuse original Zenbook panel, cable, and power input as-is.
- **Retro accents:** possible reuse of switches / aesthetic from a salvaged Atari 2600. The
  2600 shell itself is too large to serve as the enclosure — print a retro-styled case instead.

## Status

**In progress — teardown & measurement phase.** Gutting the Zenbook to a known-good unit and
capturing the measurements all printed parts will key off of.

## Repository layout

- `docs/` — build log, design decisions — *TBD*
- `measurements/` — caliper data, cable-routing photos — *TBD*
- `case/` — CAD source files — *TBD*
- `printed_parts/` — final STLs — *TBD*
- `images/` — progress photos — *TBD*

## References

Builds and docs informing this project:

- [framedeck](https://github.com/brickbots/framedeck) — slab-style cyberdeck from a laptop mainboard
- [garrwolfdog modular cyberdeck](https://medium.com/@garrwolfdog/building-a-cyberdeck-799a3412557a) — rail-based, iteration-friendly design

## License

TBD — likely MIT or CC BY-SA 4.0.
