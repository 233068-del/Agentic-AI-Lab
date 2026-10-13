# Agentic AI Lab

A hands-on collection of AI and machine-learning lab notebooks implemented as Jupyter notebooks. This repository documents step-by-step experiments, analysis, and results across multiple lab assignments (Labs 3–6).

## Repository snapshot (current)
The repository contains the following notebooks and files:

- `README.md` — This file (project overview and instructions).
- `agentic-ai-lab-04-task-1.ipynb` — Lab 4 task 1: exercises and experiments for the fourth lab.
- `agentic-ai-lab-04-task-2.ipynb` — Lab 4 task 2: continuation of Lab 4 exercises.
- `agentic-ai-lab-04-task-3.ipynb` — Lab 4 task 3: additional exercises and examples.
- `agentic-ai-lab-04-task-4.ipynb` — Lab 4 task 4: experiments and analysis.
- `agentic-ai-lab-04-task-5.ipynb` — Lab 4 task 5: final exercises for Lab 4.
- `lab-3-task-1.ipynb` — Lab 3, task 1: dataset loading and initial baseline.
- `lab-3-task-2.ipynb` — Lab 3, task 2: preprocessing and training diagnostics.
- `lab-3-task-3-final.ipynb` — Lab 3 final: consolidated pipeline and final evaluation.
- `lab-5-activity-1-2.ipynb` — Lab 5 activities 1 & 2: exercises and demonstrations.
- `lab-05-task-1-final.ipynb` — Lab 5 task 1 final: completed task with analysis and results.
- `lab-5-task-2.ipynb` — Lab 5 task 2: further experiments and model variants.
- `lab-6-all-activites.ipynb` — Lab 6: combined activities and walkthroughs for Lab 6.
- `lab-06-all-tasks.ipynb` — Lab 6 alternative/archival notebook containing all tasks for Lab 6.

If you recently added other files that are not listed above, tell me their filenames and I will add them to this README.

## Project overview
The notebooks walk through a typical machine-learning workflow:

1. Data loading and exploratory data analysis (EDA)
2. Preprocessing and feature engineering
3. Model selection and baseline experiments
4. Training, validation, and hyperparameter tuning
5. Visualization of results and final evaluation

Each notebook contains code cells, explanatory text, and plots that document the experimental process.

## How to run
1. Clone the repo:
   git clone https://github.com/233068-del/Agentic-AI-Lab.git
2. Create and activate a Python virtual environment (recommended):
   python -m venv .venv
   source .venv/bin/activate  (on Windows use `.venv\Scripts\activate`)
3. Install dependencies (create a `requirements.txt` or install commonly used packages):
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   (Some notebooks may require TensorFlow or PyTorch.)
4. Start Jupyter and open the notebook you want:
   jupyter notebook

Notes:
- Some notebooks may expect data files in a `data/` folder or specific package versions. Check the top cells of each notebook for exact imports and dataset paths.

## Key results (high-level)
- Baseline models show learning behavior with measurable validation improvements across iterations.
- Preprocessing and hyperparameter tuning provided most of the performance gains.
- Final notebooks summarize results with plots and metric tables.

## Reproducibility and recommended repo improvements
To make this project easier to reproduce and share, consider adding:
- `requirements.txt` or `environment.yml` (exact package pins)
- `data/` folder or instructions/links to obtain datasets
- `LICENSE` and `CONTRIBUTING.md` if you plan to collaborate publicly
- `results/` or `docs/` folder with exported plots and a short written report
- A small script to run core experiments non-interactively (for CI or batch runs)

## Next steps you can ask me to do
- Add the exact list of Python packages to `requirements.txt` (I can create it from the notebooks' imports).
- Extract and summarize numeric results (best validation scores) from the final notebooks.
- Produce a simple `run_all.sh` or `Makefile` to reproduce key experiments.
- Clean up duplicate/archival notebooks (e.g., choose one `lab-6` notebook and archive the other).

## Contact
Prepared by the repository author. For questions or collaboration, open an issue or contact the repository owner on GitHub.
