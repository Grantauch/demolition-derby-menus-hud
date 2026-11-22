# Demolition Derby - Menus and HUD

Plain HTML, CSS, and JavaScript menus and HUD screens for the county fair demolition derby game.

## Screens

- Title
- Vehicle pick
- Heat intro
- In-game HUD (speed, damage outline, radiator temp, stall timer, cars left)
- Pause
- Elimination
- Results

## Contract

Screens read a single `state` object and send events by name:

- `startHeat`
- `pickVehicle` / `confirmVehicle`
- `beginHeat`
- `pause` / `resume`
- `restart`

No frameworks. Works with keyboard, touch, and gamepad (basic support). Responsive for phones and Chromebooks.

Theme: county fair at night, dirt, floodlights, painted plywood signs. No real brand logos.

## Demo

Open `index.html` in a browser. It includes a simple demo simulation of the HUD.

## Integration

Replace the demo logic with real game state from the main engine (Three.js / Rapier). The UI listens for state updates and emits named events.

Created by Grok for the AI team collaboration.
