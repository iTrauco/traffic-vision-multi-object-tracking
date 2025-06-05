# Development Branch

This branch contains development-centric workflows for implementing components that enable end-to-end pipeline functionality not included in the scenario06 notebooks.

## Overview

These components and workflows are the result of several months of iterations and refinement to develop the frameworks and methodologies required to implement data science infrastructure as and end-to-end pipeline.

## Source Materials

- **Case Study README**: [Data Science SAD Repo](https://github.com/iTrauco/data-science-sad/blob/scenario06/traffic-vision/multi-object-tracking/README.md)
- **Analysis Notebook**: [Traffic Vision Multi-Object Tracking - System Analysis and Design Proposal](https://github.com/iTrauco/data-science-sad/tree/scenario06/traffic-vision/multi-object-tracking/notebooks)

## Branch Strategy

- `dev` is the primary and default branch 
- Feature branches will be merged into `dev` as the full end-to-end pipeline evolves


## Purpose

This branch contains the real-world implementation of the components and systems designed in the scenario06 notebooks. The dev branch and notebooks are iteratively updated together as implementation details are refined and confirmed.

Key aspects:
- Practical implementation of notebook designs
- Working code for all system components
- Integration patterns discovered during development
- Solutions that will be documented back in the notebooks

## Environment Setup

```bash
# Activate the environment
conda activate scenario6-traffic-vision

# If environment doesn't exist, create from file
conda env create -f environment.yml
```

## Note

The implementations here represent practical application of the concepts analyzed in the [Traffic Vision Multi-Object Tracking - System Analysis and Design Proposal](https://github.com/iTrauco/data-science-sad/tree/scenario06/traffic-vision/multi-object-tracking/notebooks), evolved through real-world iteration and refinement.