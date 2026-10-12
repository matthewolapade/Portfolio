# Matthew Olapade — Data, Research & Advanced Analytics Portfolio

A static HTML/CSS/JavaScript portfolio designed for GitHub Pages. The site has no build step or package dependencies.

## Repository structure

```text
.
├── index.html
├── styles.css
├── script.js
├── .nojekyll
├── README.md
├── assets/
│   ├── matthew-olapade-portrait.jpg
│   ├── cbn/
│   ├── uk-sme/
│   ├── maryland/
│   ├── market-opportunity-map.svg
│   ├── ai-or-evidence-pipeline.svg
│   ├── hydropower-analysis-pipeline.svg
│   └── other project visuals
└── projects/
    ├── cbn-communication.html
    ├── uk-sme-financing.html
    ├── beeston-hydropower.html
    ├── ai-or-portfolio.html
    ├── taaa-meta-analysis.html
    ├── maryland-crime.html
    ├── market-opportunity.html
    ├── uk-restaurant-fpa.html
    └── public-impact / research-communication pages
```

## Publish on GitHub Pages

1. Sign in to GitHub and create a new **public repository** named `matthew-olapade-portfolio` (or another name you prefer).
2. Extract this ZIP on your computer or phone. Upload the **contents inside** the `matthew-olapade-portfolio` folder to the repository root. Do not upload only the ZIP file and do not nest the site inside an extra folder. `index.html` must sit at the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for the Pages deployment to finish. GitHub will show the published URL in **Settings → Pages**. A project repository usually uses `https://YOUR-USERNAME.github.io/matthew-olapade-portfolio/`.
7. Open the URL on both desktop and mobile. Test the email link, WhatsApp link, project links and all image loads.

### Alternative: GitHub web upload

From the repository page, use **Add file → Upload files**, drag in all site files and folders from the extracted folder, and commit to `main`. If the browser upload has trouble with the large poster images, use GitHub Desktop or Git.

## Contact

- Email: matthewolapade56@gmail.com
- WhatsApp: +234 803 457 4086 (`https://wa.me/2348034574086`)

## Project and evidence policy

- Do not commit confidential client data, personal information, restricted raw datasets or proprietary source files.
- The site includes selected visual outputs rather than full source datasets.
- Market-opportunity themes are hypotheses requiring buyer validation, not established product-market fit.
- The Sokoto maternal-mortality project is a proposed intervention, not an impact evaluation.
- The AI/OR page labels figures from the working manuscript as pending source-level verification.
- Maryland maps are descriptive; they do not establish causality. Confirm the source and units of the crime measure before external publication.
- Hydropower analysis describes observed patterns and associations; it does not assert that hydropower caused every observed environmental change.

## Local preview

Open `index.html` in a browser. For a local web server, run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.
