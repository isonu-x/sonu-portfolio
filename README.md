# Sonu Namdev Portfolio - Local Version

This is a standalone local version of the portfolio at `project.isonu-x.chatgpt.site`.
It uses plain HTML, CSS, and JavaScript, so there is no build step and no API key is required.

## Run in VS Code

1. Extract the ZIP.
2. Open the `sonu_portfolio_local` folder in VS Code.
3. Install the **Live Server** extension (if you already have it, skip this step).
4. Right-click `index.html` -> **Open with Live Server**.

## Run with Python

From the project folder:

```bash
python -m http.server 5500
```

Then open:

`http://localhost:5500`

## Project structure

- `index.html` - page structure
- `css/style.css` - complete styling and responsive layout
- `js/app.js` - navigation, Logic Lab, demos, chat guide, cart, sorting visualizer
- `assets/sonu-profile.png` - portfolio portrait
- `assets/sonu-banner.png` - banner asset
- `assets/sonu-resume.pdf` - local downloadable resume

## Notes

- The chat guide is fully local and uses keyword-based replies. It does not call OpenAI or any external API.
- Flowboard, Studio Store, Sortscape and all 10 Logic Lab examples run locally.
- Responsive layouts are included for mobile widths down to 350px.
