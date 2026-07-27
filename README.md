# CI-DIGITAL — Systolic Array Simulators

Interactive, dependency-free visualizations of matrix multiplication on systolic processing-element arrays.

## Versions

- **v1 — detailed 3×3 simulator:** repository root (`index.html`). It exposes each processing element, operand, product, accumulator, and result value.
- **v2 — 20×20 wavefront simulator:** `v2/index.html`. It emphasizes the meaning of *systolic* through clock-driven tile-color propagation, with hover and click inspection.

After GitHub Pages is enabled, the expected addresses are:

```text
https://pu3flm.github.io/CI-DIGITAL/
https://pu3flm.github.io/CI-DIGITAL/v2/
```

## Run locally

Serve the repository root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
http://localhost:8000/v2/
```

## Structure

```text
CI-DIGITAL/
├── .github/
│   └── workflows/
│       └── pages.yml
├── v2/
│   └── index.html
├── index.html
└── README.md
```

No framework, package manager, build system, or external runtime dependency is required.
