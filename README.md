# GoodData hands-on

A self-contained browser presentation about the end-to-end GoodData data cycle:

\`source → transform → semantic model → CI/CD → BI personas → executive decision\`

The presentation shell is [\`index.html\`](./index.html); the editable slide outline lives in [\`content.json\`](./content.json). Change the text or HTML inside the \`slides\` array, then reload the deck.

Because the browser loads the outline as JSON, serve the folder locally instead of opening the HTML with \`file://\`:

```bash
python3 -m http.server
```

Then open the printed \`http://localhost:8000\` URL. Use arrow keys, the space bar, or the on-screen controls to navigate.

The deck is framework-free and organized around the full pipeline: ingestion/database → transformation → GoodData analytics → AI → delivery surfaces → end users. The JSON outline separates content from the presentation shell while keeping this project’s existing single-page structure.
