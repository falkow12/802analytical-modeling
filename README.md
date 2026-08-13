# Analytical Components in Modeling

Many research projects include analytical components: equations, mathematical relationships, and symbolic models that describe how a system behaves.

In this repository, we explore how analytical components fit within a larger modeling workflow. Rather than focusing on deriving equations by hand, we will use software to investigate model behavior, generate synthetic data, estimate parameters, and evaluate assumptions.

The goal is not to become an expert mathematician. The goal is to learn how computational tools can help us understand, apply, and evaluate analytical models in our own research.

This repository is a guided introduction to that workflow.

## Learning Goals

By the end of this assignment, you should be able to:

- Use software tools to explore an analytical component of a model.
- Investigate model behavior through symbolic and numerical analysis.
- Generate and inspect synthetic data from a known model.
- Estimate model parameters from observations.
- Evaluate uncertainty and model assumptions.
- Reflect on how analytical components support modeling work in your own research.

## Assignment Structure

This assignment is organized into several parts that build on one another:

- Part 1: Explore an analytical model symbolically and numerically.
- Part 2: Generate phantom data and investigate the effects of noise.
- Part 3: Estimate model parameters from observations.
- Part 4: Explore model comparison and model discovery tools.

Each part introduces ideas and software tools that are commonly used in scientific computing and research software development.

## Software Environment

Before working through the notebooks, we need to create a software environment.

In scientific computing, software environments help ensure that everyone is using compatible versions of the same tools and libraries. This improves:

- Portability
- Reproducibility
- Robustness

without requiring everyone to configure their computers in exactly the same way.

This repository includes an `environment.yml` file that describes the software needed for the assignment.

We will use Conda to create an environment in a local `./envs` directory.

### Quick Start

Create the environment:

```bash
conda env create --prefix ./envs --file environment.yml
```

If the environment already exists, update it:

```bash
conda env update --prefix ./envs --file environment.yml --prune
```

Activate the environment:

```bash
conda activate ./envs
```

Start-up Jupyter Lab using the environment:

```bash
jupyter lab
```

Open the assignment notebooks and work through them in order.

### A Brief Note on Environments

Software environments are one of the most important tools for creating reproducible scientific software.

Over the semester, we will discuss environments in more detail and explore the tradeoffs between:

- Robust environments that are easy to update and maintain.
- Reproducible environments that precisely preserve specific software versions.

These goals sometimes conflict.

For this assignment, we will keep things simple and use a lightweight environment with a minimal number of dependencies. The goal is to make it easy to get started while introducing the basic workflow.

If you are new to Conda, the following resources may be helpful:

- https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html
- https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

## Assignment Expectations

To complete this assignment:

- Clone the repository.
- Create and activate the Conda environment.
- Work through the notebooks in order.
- Complete the exercises and reflection activities.
- Discuss how the tools and ideas relate to your own research.

The goal is not simply to obtain the correct answer. The goal is to explore how analytical components contribute to larger modeling workflows and how software can help us work with those models effectively.

## Why This Repository Is Pared Down

This repository started from the course Research Software Project Template but has been intentionally simplified for use as an instructional activity.

The goal is to keep the focus on analytical modeling while introducing a few important research software concepts, including:

- software environments
- reproducible workflows
- computational exploration
- documentation
- scientific software engineering

As the semester progresses, later repositories will introduce additional tools and practices in a gradual and manageable way.

Taken together, these parts mirror a common research workflow: start from an analytical model, ask how it behaves, generate synthetic data, estimate its parameters, and then evaluate whether a fitted model is credible in a real-data setting.