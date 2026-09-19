# credit_card_embroidery

Credit-card–sized machine embroidery designs and their die-cut kit packaging,
made for **EMF 2026** (Electromagnetic Field). By [@borisnotes](https://borisnotes.com).

The designs are digitized for a **Brother PR650** 6-needle machine (`.pes`), with
Inkscape `.svg` sources alongside. Some pieces combine embroidery with electronics
(conductive thread, LEDs, a coin-cell battery PCB) — a stitched "blinky" badge.

## Layout

```
designs/            embroidery designs — machine files (.pes) + vector sources (.svg)
  credit-card/        the badge itself, credit-card footprint (~86 mm wide)
                        credit_card*.pes / .svg   — badge + variants
                        credit_card_panel*        — multi-up hooping panels
                        credit_card_02 / _thick_02 — stitch-density variants
  this-is-fine/       "this is fine" dog artwork, sizing mockups (credit vs real size)

packaging/          die-cut card/envelope templates that hold a finished kit
  package.svg          base / blank template
  mushroom/           "Blinky Mushroom" — v1 (line art) → v2 → v3
  alien/  frog/  rocket/  emf/   themed variants

logos/             emf_logo.svg, emf2026-logo-white-gradient.svg

stickers/          sticker art + QR codes (links back to this repo)
```

## Kit contents (per packaging template)

Badge canvas · needle · colour thread (red, white, black, peach) · conductive
thread · green LEDs · self-blinking LEDs (fast + slow) · battery PCB · CR2032 cell.

## Working with the files

- **Loading on the PR650:** copy `.pes` files to the **root** of a USB stick
  formatted **FAT32 / MBR** (not exFAT or NTFS — the machine won't mount those).
- **Editing:** open the `.svg` in Inkscape; re-digitize to `.pes` with your
  embroidery software (Ink/Stitch, PE-Design, etc.).
