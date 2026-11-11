# CREDITSENSE — Credit underwriting research lab

**Understand the ingredients of an underwriting decision.**

<sub>Interactive web application / Financial analytics / Portfolio study</sub>

---

## What this explores

Train logistic regression on synthetic borrowers, inspect feature weights, probability calibration, confusion metrics and individual decisions.

## Run the project

```bash
python -m http.server 8000
```

Open http://localhost:8000/ in your browser.

## Explore the code

| Source | Role |
|---|---|
| [`README.md`](./README.md) | Project documentation |
| [`app.js`](./app.js) | Main application logic |
| [`index.html`](./index.html) | Web entry point |
| [`style.css`](./style.css) | Visual design |
| [`test.mjs`](./test.mjs) | JavaScript tests |

## Reading the results

Uses illustrative data or model assumptions. It is not a real credit, fraud, investment, or trading decision service. For meaningful experiments, vary one input at a time and compare the result with the implementation. Keep private datasets and credentials out of the repository.

<details><summary><strong>Original technical guide and test notes</strong></summary>

# CREDITSENSE — Credit underwriting research lab

Train logistic regression on synthetic borrowers, inspect feature weights, probability calibration, confusion metrics and individual decisions.

**Run:** open index.html in a browser, or serve locally using `python -m http.server 8080` at the main portfolio root.

**Data:** synthetic seeded data. This is a research demonstration, not a trading, lending or security decision system.

**Tests:** `node --test test.mjs`. No dependencies.

</details>

---

<sub>More projects in [Sharanya Pal's engineering portfolio](https://github.com/sharanyapal?tab=repositories).</sub>
