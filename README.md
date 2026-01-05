# AIML Class with Sir Idrees (2025)

Welcome — this repository contains materials for the "AI & Machine Learning" class taught by Sir Idrees in 2025. It includes lecture notes, code notebooks, datasets (when permissible), assignments, and example projects used during class sessions.

## Table of contents

- Overview
- Getting started
- Repository structure
- Environment & requirements
- How to use the notebooks
- Assignments & grading
- Contribution guidelines
- License & contact

## Overview

This repo collects course resources to help students follow along, reproduce experiments, and submit assignments. Materials may include:

- Jupyter notebooks for lectures and practicals
- Python scripts and helper utilities
- Slides and reading materials
- Small example datasets (or links to larger datasets)

## Getting started

1. Clone the repository:

   git clone https://github.com/mobrahi/aiml-class-with-sir-idrees-2025.git
   cd aiml-class-with-sir-idrees-2025

2. Create and activate a virtual environment (recommended):

   python -m venv .venv
   source .venv/bin/activate   # macOS / Linux
   .\.venv\Scripts\activate  # Windows (PowerShell)

3. Install dependencies (if a requirements file is present):

   pip install -r requirements.txt

## Repository structure (suggested)

- notebooks/         - Jupyter notebooks for lectures and labs
- slides/            - Lecture slides and PDFs
- assignments/       - Assignment instructions and submission folders
- data/              - Small datasets or dataset pointers (do NOT commit large raw datasets)
- scripts/           - Utility scripts and helpers
- reports/           - Example solution write-ups or student reports
- README.md          - This file

Adjust structure as needed for the course.

## Environment & requirements

- Python 3.8+ (3.10 recommended)
- Common libraries: numpy, pandas, scikit-learn, matplotlib, seaborn, jupyterlab

If there is no `requirements.txt`, create one with:

   pip freeze > requirements.txt

## How to use the notebooks

- Open notebooks locally with Jupyter Lab / Notebook:

   jupyter lab

- Restart the kernel and run all cells when you first open a notebook to ensure outputs are reproducible.
- If notebooks depend on datasets, check `data/` or follow any instructions in the notebook header to download data.

## Assignments & submissions

- Assignment instructions are placed in `assignments/`.
- Follow the submission format outlined in each assignment (e.g., a zip file or GitHub Classroom link).
- Include reproducible code, a short README, and any output files required by the assignment.

## Contribution guidelines

- Students: open a new branch for assignment submissions, or follow the course's submission instructions.
- Instructors / TAs: add, update, or remove materials as needed. Keep large data off the repo and provide download links.

## License

Unless otherwise stated, course materials in this repository are provided for educational use by the class participants. If you want a permissive license, consider adding an `MIT` or `CC-BY` license file. Contact the course instructor for specific licensing questions.

## Contact

For questions about the repository or course materials, open an issue or contact the instructor/maintainer.

---

Created by @mobrahi for the 2025 AI/ML class with Sir Idrees.
