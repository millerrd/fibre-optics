# fibre-optics

Interactive optical fibre simulation for AQA A-level Physics.

## GitHub Pages web app

This repository contains a static web app (`index.html`) that runs on GitHub Pages.
It models multipath dispersion in a **single 10 km step-index optical fibre** with
simultaneous red laser-pulse animation and a launch-vs-received signal plot.

### What the simulator shows

- Core refractive index
- Step index (`Δn = core index - cladding index`)
- Fixed 10 km fibre length
- Multiple ray paths in the core
- Animated red laser pulses launched together along each path
- User-entered bit pattern transmission
- Start-vs-end signal plot showing pulse broadening and overlap when bandwidth is exceeded
- Arrival-time spread from multipath dispersion
- Estimated maximum bit rate from pulse spread
- AQA-linked explanation of total internal reflection, multimode delay spread, and bandwidth

Open `index.html` directly or enable GitHub Pages for the repository root to use it online.
