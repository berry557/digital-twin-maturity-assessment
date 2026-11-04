# Digital Twin Maturity Assessment for Net Zero Carbon Buildings

An interactive research tool developed for assessing an organisation's maturity in implementing digital twin technology for net zero carbon buildings.

The assessment covers:

- 3 main dimensions and 9 sub-dimensions
- current and target maturity scoring
- weighted maturity results and gap analysis
- implementation strategy recommendations
- an expert evaluation survey

## Live website

After GitHub Pages deployment, the website is available at:

<https://jackzhao61725-dotcom.github.io/digital-twin-maturity-assessment/>

## Project structure

```text
.
├── index.html
├── assets/
│   ├── assessment-guide-20260811.m4v
│   └── assessment-guide-poster.jpeg
└── .github/workflows/deploy-pages.yml
```

## Local preview

Run a local static server from the project directory:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Data delivery

Assessment responses are submitted through the FormSubmit relay configured in `index.html`. The first submission to a new delivery address may require one-time email activation.

## Research attribution

Developed by Yifei Sheng, PhD Candidate, Department of Civil Engineering and Management, University of Manchester.

