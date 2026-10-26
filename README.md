# Student Enrollment and Grading Record System

Implements an interactive console-style student record system in Python. Records persist in a text file, and final grades are calculated from a 40% quiz and 60% exam weighting.

## Workflow

1. Load existing student records from `records.txt`.
2. Add students with validated numeric scores.
3. View or search records by student ID.
4. Update scores and recalculate final grades.
5. Compute the class average and persist changes.

## Data Requirements

- `records.txt` is created and updated by the program.

Datasets and generated artifacts are not included unless they are embedded directly in the notebook.

## Requirements

- Python standard library only

Install missing packages in your Jupyter or Google Colab environment before running the notebook.

## Running the Notebook

1. Open [`napinasproblem1.ipynb`](napinasproblem1.ipynb) in Jupyter Notebook or Google Colab.
2. Place any required data files in the path expected by the notebook.
3. Update local or Google Drive paths where needed.
4. Run the cells from top to bottom.

## Outputs

- Interactive record-management prompts
- Persistent `records.txt` file
- Weighted final grades and class average

## Repository Contents

```text
.
|-- README.md
`-- napinasproblem1.ipynb
```

## Notes

- This repository preserves the analysis as a notebook-first educational project.
- Results may vary with dataset versions, random splits, package versions, and available hardware.
- Review file paths and runtime-specific commands before executing outside Google Colab.
