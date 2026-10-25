# Solar Angle: why the angle of sunlight matters

An interactive 3D demo that shows how tilting the sun away from "straight on" spreads the same light over a bigger area of a solar panel, so each cell receives less.

**Live demo:** https://adam210503.github.io/solar-angle/

## What it shows

- **The cos θ rule.** Light per cell = cos θ. At 0° the panel gets 100%, at 60° it gets 50%, and at 80° it gets about 17%.
- **The lit patch.** The beam keeps the same width, but its patch on the panel stretches by 1/cos θ as the sun tilts.
- **A motor and propeller** wired to the panel, spinning faster or slower with the light received.
- **Cloud cover**, modelled as a 70% reduction in light.
- **Drag to rotate** the 3D view.

## How to use it

1. Tap a preset angle (0°, 30°, 45°, 60°, 80°) or drag the slider.
2. Watch the lit patch, the percentage readout and the propeller speed change.
3. Toggle cloud cover to see the combined effect.

## Run it locally

It is a single self-contained file with no build step or dependencies. Open `index.html` in a browser. It also works offline.

## Notes

- This is a simplified model for teaching. Real panels lose slightly more at steep angles because more light reflects off the glass.
- Built with plain HTML, CSS and JavaScript, with the 3D scene drawn on an HTML canvas.

## Context

Made for a Science Centre booth presentation on solar energy as part of NUS SP1541 (Communications for Science).

## Author

Adam, NUS Data Science and Analytics
