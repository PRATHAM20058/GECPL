# GECPL - AI & ML Experiments

Standardized Git & GitHub Workflow for AI/ML Project Submissions.

## Repository Structure

```
GECPL/
├── README.md
├── .gitignore
├── AI/
│   ├── EXPERIMENT-1.PY
│   ├── EXPERIMENT-2.PY
│   ├── ...
│   └── EXPERIMENT-13.PY
└── ML/
    ├── EXPERIMENT-1.PY
    ├── EXPERIMENT-2.PY
    ├── ...
    └── EXPERIMENT-12.PY
```

## Workflow

```
newfeature/experiment-X ──PR──> dev ──PR──> main
```

Each experiment is developed on its own feature branch and merged into `dev` via Pull Request.
Once all experiments are complete, `dev` is merged into `main` via a final Pull Request.
