"""# Customised Pill Dispenser — Deliverable Package

This package contains:
- `index.html` — Multi-section website (Home, About, Design, Prototype, Contact).
- `styles.css` — Simple site styles.
- `wiring.svg` — Schematic-style wiring diagram (illustrative).
- `bom.csv` — Bill of materials (CSV).
- `arduino/CustomPillDispenser.ino` — Example Arduino sketch (adjust pins and schedule).
- `placeholder.jpg` — placeholder image (replace with the generated product photo).
- `README.md` — this file.

## How to use
1. Unzip the package and open `index.html` in a browser.
2. Replace `placeholder.jpg` with your generated prototype image for best visuals.
3. Edit `bom.csv` to update component costs. Use the Arduino sketch in `arduino/` folder with the appropriate libraries:
   - RTClib
   - Servo
   - LiquidCrystal

## Image generation prompt
Use the following prompt in your preferred image generator:

Photorealistic product shot of a compact bedside pill dispenser prototype: a circular rotating tray with six transparent compartments, white matte 3D-printed housing, small servo motor visible under the tray, a 16x2 LCD display on the front showing time and "Next dose: 08:00", three small LED indicators (green/yellow/red) beside the display, slim buzzer grille, soft studio lighting, shallow depth of field, neutral background, high resolution, realistic plastic and metal textures — styled for a biomedical device website. Include subtle shadows, minimal branding, and a front three-quarter angle that shows the compartment lid and LCD clearly.
--aspect 3:2 --quality 2 --stylize 50

"""
