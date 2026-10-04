# Generative AI in your organisation: breakout exercise

A 30-minute breakout worksheet for executive education. Groups frame a workflow, rate the work, choose how AI enters it (horizontal, vertical or agentic), answer five leadership questions that adapt to that choice, and design a first 90-day experiment.

The worksheet is a single static HTML file with no build step and no server. Answers are saved in the participant's browser (localStorage) and are not sent anywhere. Participants can print the page, save it as a PDF or download their answers as a text file.

## Files

- `genai-breakout.html`: the worksheet. Rename it to `index.html` if you want it served at the root of the site.

## Run it locally

Open `genai-breakout.html` in a browser. The fonts load from Google Fonts, so the page falls back to Georgia and a system sans-serif when offline.

## Publish with GitHub Pages

1. Settings, then Pages.
2. Under Build and deployment, choose Deploy from a branch.
3. Select the branch that holds the file and the `/ (root)` folder, then save.

The site address appears on the same page after a minute or two.

## Adapt the exercise

- Mode-specific questions (worksheet items 5 to 9): edit the `BRANCH_CONTENT` object at the top of the script. Each mode has a title, lead line, helper text and placeholder for every question.
- Universal questions (items 1 to 3, 10 and 11), the header, the three mode cards and the report-back box: edit the HTML.
- If you change the structure, change `STORAGE_KEY` so that answers saved by an earlier version do not load into the new one.
- If you add or remove a field, update the Download answers code at the bottom of the script to match.

## Credit

Adapted from a breakout exercise by Nicos Savva, London Business School. The layout and visual design follow the original.

## Licence

To be added once reuse terms have been confirmed with the original author.
