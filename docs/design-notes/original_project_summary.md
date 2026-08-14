# README

Source: `README.docx`

## Extracted Text

# Offline Flyback SMPS (Custom Transformer)

Bench-validated offline flyback switch-mode power supply using a **custom hand-wound RM10/I transformer** and a **Power Integrations TinySwitch (TNY285)** controller.

Designed and built from first principles, with emphasis on **correct magnetics design, drain-stress control, and measurement-verified operation** through the completed four-layer PCB package.

The deadbug prototype was used for unrestricted probing and bring-up. The completed design includes a **four-layer PCB** for the cleaned-up power-stage implementation, with the transformer and PCB treated as production-grade prototype hardware rather than a certified production supply.

Input

- 120 VAC â†’ ~170 VDC bulk

Output (bench prototype)

- Demonstrated half-amp operating point: **10 Ohm, approximately 4.94 V output and approximately 494 mA calculated load current**. An additional 5.6 Ohm characterization captured approximately 882 mA calculated load current.

- Output voltage: **~4.94 V**


Transformer (measured, assembled)

- Saturation: **16% of Bmax at 5W**, estimated 48W limit

- Lm: **2.476 mH**

- Ls: **26.64 ÂµH**

- Laux: **26.77 ÂµH**

- Turns ratio (Np/Ns): **~9.64**

- Leakage inductance: **~53 ÂµH**

- Coupling factor: **~0.989**

- Hi-pot: **~1.5 kVAC / 60 s**, documented as pre-compliance dielectric-strength evidence against the applicable insulation requirements; not certification
- Insulation testing: winding and insulation construction reviewed and tested as part of the transformer pre-compliance evidence record

Drainâ€“source stress

- Drain Vp-p: **~298â€“308 V**

- Ringing amplitude: **~98 Vp-p**

- Ringing frequency: **~339â€“392 kHz**

- Peak drain voltage: **344 V (max)**

Status

- Bench validation complete

- Board assembled & currently validating

The transformer and completed four-layer PCB establish a production-grade prototype platform for further controlled validation, design review, and potential productization. Production release, certification, and regulatory approval remain separate activities.
