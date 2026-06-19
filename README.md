# Unimog SBU / U1300L CAD Projects

[![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

CAD models and fabrication files for work on my Mercedes-Benz Unimog SBU / U1300L. The truck started with an OM366A and now runs an OM366LA, so some of these parts come from the practical work of keeping old military truck hardware useful while making it fit the way I want it to.

This repo is part design archive, part build log, and part reference for other Unimog owners solving similar problems.

## Highlights

### Modular headlight system

<img src="headlight%20system/headlights-installed.jpeg" alt="Installed modular headlight system on the Unimog" width="560">

<img src="headlight%20system/headlight%20close%20up.JPG" alt="Close-up of the installed modular headlight system" width="560">

![Modular headlight system CAD model](<headlight system/headlight model.png>)

A modular headlight replacement system for the stock SBU / U1300L headlight setup. The goal is to make the lighting package easier to service and adapt while still fitting the original vehicle envelope.

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

Status: design archive / replacement part.

### U1300L light carrier

`u1300L light carrier.f3d`

Model for the U1300L light carrier. This appears to be the same model family as the SBU setup and is kept here with the other front lighting work.

Status: design archive.

### OM366 pulley

`om366 pulley.f3d`

When adding air conditioning, I needed a dual-groove water pump pulley for the OM366. Those pulleys are difficult to find, so this model captures the needed part geometry for that conversion work.

Status: design archive / AC conversion support.

## Repository Layout

| Path | Contents |
| --- | --- |
| `headlight system/` | Modular headlight holder models and STEP export |
| `dashboard/` | Dash panel, gauge holder, plugs, knobs, and exports |
| `SBU snorkel lamp holder.f3d` | Replacement snorkel lamp holder model |
| `u1300L light carrier.f3d` | U1300L light carrier model |
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
