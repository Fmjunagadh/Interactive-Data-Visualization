# Half Marathon Sub-2 Simulator

A responsive, interactive data visualization built with HTML, CSS and vanilla JavaScript.

## Features
- Adjust current half-marathon pace, weekly pace-improvement assumption and training duration.
- Live projected finish time and comparison with the sub-2-hour target.
- Switch between miles and kilometers.
- Dynamic pace progression chart.
- Peak long-run estimate, progress indicator, reset and export controls.
- No frameworks, build tools, API keys or external dependencies.

## Run locally
Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Create a new public GitHub repository (for example, `half-marathon-sub2-simulator`).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. Wait for GitHub Pages to publish your site. Your URL will look like:
   `https://YOUR-USERNAME.github.io/half-marathon-sub2-simulator/`

## Model assumptions
The projection applies a user-selected pace improvement per week across the selected number of weeks. This is a simple scenario model for exploring assumptions, not a scientifically validated performance predictor or a training prescription. The peak long-run figure is an illustrative estimate based on training duration.
