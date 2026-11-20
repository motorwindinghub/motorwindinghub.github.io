# MotorWinding Hub

Free motor winding & electrical engineering calculators — a static single-page site built for GitHub Pages.

**Live site:** https://motorwindinghub.github.io

## What it is

An original, English-language calculator hub for motor rewinding workshops and field electricians, based on IEC standards (400V / 230V, 50Hz). Pure HTML5, CSS3 and vanilla JavaScript — no frameworks, no build step, no backend.

## Calculators (all client-side)

1. **Motor Winding Turns & Copper Weight** — MTL, total wire length, weight with 5% allowance, coil resistance at 20°C/75°C, slot fill factor, material cost. Copper and aluminium.
2. **SWG / AWG / mm² Wire Gauge Converter** — enter any one value, get the rest plus resistance/km and a safe-current guide.
3. **3-Phase Motor Current & Breaker** — rated current In = P/(√3·V·η·cosφ), starting current, MCCB, AC-3 contactor, EOCR setting.
4. **Capacitor & Power Factor** — single-phase run/start capacitor estimates and 3-phase kVAr for PF correction.
5. **Voltage Drop & Cable Sizing** — drop in V and %, pass/fail against the 5% limit, suggested minimum cable size.

Also included: a 3-phase 400V 4-pole motor reference table, six practical winding guides, FAQ, About and Disclaimer.

## Deploy to GitHub Pages

1. Create a public repository named **motorwindinghub** under the GitHub user **motorwindinghub**.
2. Upload all files from this folder to the repository root (`index.html`, `README.md`, `.nojekyll`).
3. In the repository: **Settings → Pages → Build and deployment → Deploy from a branch → branch `main`, folder `/ (root)` → Save.**
4. The site goes live at **https://motorwindinghub.github.io** within a few minutes.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000/
```

## Disclaimer

All results are estimates for guidance only. Verify protection settings, cable sizes and capacitor values against the motor manufacturer's nameplate data and local wiring regulations. Consult a licensed electrician before energising any machine.
