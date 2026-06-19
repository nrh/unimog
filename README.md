# Unimog SBU / U1300L Projects

[![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

Some parts and projects designed for my U1300L - I hope you find them useful. Non-commercial use only.

Some printable parts are also available on [MakerWorld](https://makerworld.com/en/@nrh3k).

## Highlights

### Modular headlight system

<img src="headlight%20system/headlights-installed.jpeg" alt="Installed modular headlight system on the Unimog" width="560">

<img src="headlight%20system/headlight%20close%20up.JPG" alt="Close-up of the installed modular headlight system" width="560">

![Modular headlight system CAD model](<headlight system/headlight model.png>)

A modular headlight replacement system for the stock SBU / U1300L headlight setup. The goal is to make the lighting package easier to service and adapt while still fitting the original vehicle envelope.

This was built around JW Speaker 8631 and 8910 EVO 2 lamps, both in 24V, but should work with any standard PAR46 round lamp and 5x7 rectangular lamp. The brackets replace the standard Hella buckets and reuse the same mounts. They do not need separate adjusters; there is enough flexibility in the existing brackets to aim them up/down and left/right.

I had the brackets cut by SendCutSend in .119 steel and powder-coated black for about $200. In .100 aluminum, they were about half that price.

The rest of the system is 3D printed and uses heat-set inserts to mount the retaining rings to the backing plate.

Relevant files:

- `headlight system/headlight dual holder.f3d`
- `headlight system/headlight dual holder v1.f3d`
- `headlight system/headlight dual holder separate retainers.f3d`
- `headlight system/headlight dual holder separate retainers v2 WIP.f3d`
- `headlight system/headlight dual holder separate retainers.step`

Status: active development. Files marked `WIP` are works in progress.

### Dashboard cleanup

![Dashboard panel CAD model](<dashboard/dashboard model.png>)

Ongoing dashboard work to clean up and beautify the cab. This includes an old-style dash panel, gauge holders, warning light plugs, switch/knob parts, and small hole plugs for making the dashboard feel more deliberate instead of patched together.

The [light switch knob](https://makerworld.com/en/models/844162-unimog-sbu-light-switch-knob) and [dash plugs](https://makerworld.com/en/models/1440823-unimog-sbu-dash-plugs) are also on MakerWorld.

Relevant files:

- `dashboard/unimog dash old style.step`
- `dashboard/unimog dash old style.stl`
- `dashboard/double auber gauge holder.f3d`
- `dashboard/headlight knob.f3d`
- `dashboard/hole plug.f3d`
- `dashboard/round hole plug 12.3mm.f3d`
- `dashboard/round hole plug 14.3mm.f3d`
- `dashboard/square warning light plug.f3d`

Status: ongoing.

### Snorkel lamp holder

<img src="snorkel%20light%20holder%20installed.jpg" alt="Installed snorkel lamp holder" width="420">

`SBU snorkel lamp holder.f3d`

I broke the original snorkel lamp holder and did not realize replacements were still available, so I modeled my own. It turned out to be much harder than expected: the part has a lot of strange transitions, odd shapes, and packaging constraints that are not obvious until you try to reproduce it.

This is also available from my [MakerWorld profile](https://makerworld.com/en/@nrh3k).

Status: design archive / replacement part.

### OM366 pulley

<img src="om366%20pulley.png" alt="OM366 pulley CAD model" width="560">

`om366 pulley.f3d`

When adding air conditioning, I needed a dual-groove water pump pulley for the OM366. Those pulleys are difficult to find, so this model captures the needed part geometry for that conversion work.

Status: design archive / AC conversion support.

## Repository Layout

| Path | Contents |
| --- | --- |
| `headlight system/` | Modular headlight holder models and STEP export |
| `dashboard/` | Dash panel, gauge holder, plugs, knobs, and exports |
| `SBU snorkel lamp holder.f3d` | Replacement snorkel lamp holder model |
| `om366 pulley.f3d` | Dual-groove OM366 water pump pulley model |

Most source files are Autodesk Fusion `.f3d` files. Where available, `.step` files are better for CAD interchange and `.stl` files are better suited to direct mesh-based fabrication workflows.

## Notes

- These are project files from a real vehicle, not a complete commercial kit.
- Check dimensions, fitment, material choice, fasteners, and road-use legality before using any part on your own truck.
- Files marked `WIP` should be treated as experimental.
- Lighting and engine-accessory parts are safety-relevant. Verify your own installation carefully.

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
