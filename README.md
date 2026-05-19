# Pill Buddy

Speculative design of a smart pill-organizer device family.

## Concept

A portable weekly pill organizer with on-device pill recognition. Seven open-top bays rotate around a fixed electronics hub; a hinged door with a top-down camera identifies pills and verifies what was taken. Reminders escalate from local (LED + chime + display) → phone push → opt-in caregiver notification. Works fully without a cloud account; cloud is opt-in only for caregiver sharing.

Three device variants under the Pill Buddy umbrella (working names):

- **Disc** — primary product. 6″ diameter weekly device with 7 bays, rotating donut, hub door with camera.
- **Pocket** — alternate path. Single-day pocket-sized companion; hub sits atop a pill cup with camera pointing down.
- **Strip** — retrofit / entry path. Standard 7-bay flip-top weekly tray with an addressable LED strip bonded underneath and a clip-on end-cap (OLED + MCU + button). No camera; verification is lid-open + button press.

## Documents

- **Design spec (Disc + Pocket):** [`docs/specs/2026-05-15-design.md`](docs/specs/2026-05-15-design.md)
- **Strip variant spec:** [`docs/specs/2026-05-19-strip.md`](docs/specs/2026-05-19-strip.md)
- **Brainstorm form-factor evolution (HTML mockups):** [`brainstorm/`](brainstorm/)
  - [v1](brainstorm/v1-initial.html) — initial dial + flap concept
  - [v2](brainstorm/v2.html) — rotating ring around fixed hub
  - [v3](brainstorm/v3.html) — wheel slips over hub column
  - [v4](brainstorm/v4.html) — smart cap + passive donut
  - [v5](brainstorm/v5.html) — all electronics in hub, integrated door
  - [v6](brainstorm/v6.html) — donut sandwich (locked baseline)

## Status

Brainstorm output. Spec is ready for implementation planning. No hardware, firmware, or app code yet — only documentation.
