# CI-DIGITAL — Systolic Array Pulse Simulator

Interactive, dependency-free visualization of matrix multiplication on a 3 × 3 systolic processing-element array.

## What it demonstrates

- clock-aligned data injection;
- horizontal propagation of matrix `A` values;
- vertical propagation of matrix `B` values;
- one local multiply–accumulate operation per active processing element;
- pipeline fill, concurrent computation, and final matrix accumulation.

## Run locally

Open `index.html` directly in a modern browser, or serve the repository root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

The repository includes `.github/workflows/pages.yml`, which packages the repository root and deploys it through GitHub Pages after pushes to `main`.

Expected public address after GitHub Pages is enabled for this repository:

```text
https://pu3flm.github.io/CI-DIGITAL/
```

## Structure

```text
CI-DIGITAL/
├── .github/
│   └── workflows/
│       └── pages.yml
├── index.html
└── README.md
```

No framework, package manager, build system, or external runtime dependency is required.
