# Analytical Modeling Assignment

In many research projects, models come from papers, reports, or domain experts before you have your own data. Your job as a researcher is to interrogate those models with software: understand assumptions, test behavior, and decide what is trustworthy.

This repository is a guided starting point for that workflow.

## Learning Goals

By the end of this assignment, you should be able to:

- Use software tools to explore an analytical model at a high level.
- Generate and inspect synthetic data from a known model.
- Recover model parameters from observations and evaluate uncertainty.
- Reflect on when analytical modeling is useful in your own research.

## Part-Based Structure

This assignment is intentionally split into parts so we can review progress in class:

- Part 1: Explore an existing model symbolically and numerically.
- Part 2: Generate phantom data and interpret noise effects.
- Part 3: Recover parameters from observations.
- Part 4 (optional): Try model discovery tools.


To get credit for the assignments Students should:

1. Clone the repository.
2. Initialize the environment.
3. Work through the assignment notebooks.

## Quick Start

In a terminal prompt create the enviornment using conda (follow the prompts):

```bash
conda env create --prefix ./envs --file environment.yml 
```

Then activate the enviornment:

```bash
conda activate ./envs
```

Then open jupyter (or jupyter lab) in the current directory:


```bash
jupyter lab
```

Once you have jupyter open the Assignemnt instructions notebooks starting from Part 1. 

- [Assignment Instructions Part 1](Assignment_Instructions_Part_1.ipynb)
- [Assignment Instructions Part 2](Assignment_Instructions_Part_2.ipynb)
- [Assignment Instructions Part 3](Assignment_Instructions_Part_3.ipynb)
- [Assignment Instructions Part 4](Assignment_Instructions_Part_4.ipynb)

## Why This Repository Is Pared Down

This repo started from the course Research Software Project Template, but it is intentionally reduced for this assignment. The goal is to keep the workflow simple while still meeting baseline expectations for reproducibility, testing, and readable project history. 

