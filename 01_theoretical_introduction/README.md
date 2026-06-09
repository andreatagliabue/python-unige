# Python from Zero for Materials Science — Introductory Theoretical Lecture

This folder contains an instructor-facing Jupyter notebook for a 2-hour front-of-class introductory lecture.

## Files

- `notebooks/01_intro_theoretical_lecture.ipynb`: main lecture notebook with speaker notes and executable demo cells.
- `data/tensile_raw.csv`: synthetic tensile-test dataset used for the main demo.
- `data/hardness_by_treatment.csv`: small auxiliary dataset used for simple list/table examples.
- `requirements.txt`: minimal Python packages needed to run the notebook.

## How to use

From this folder, launch Jupyter and open the notebook:

```bash
jupyter notebook
```

or:

```bash
jupyter lab
```

The notebook assumes the current working directory is the project root. If you open it from the `notebooks/` folder, the first code cell automatically detects the correct data folder.

## Intended use

This is not a student exercise notebook. It is designed for the instructor to show live during a remote/front lecture.
