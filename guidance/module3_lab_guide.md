# Module 3 Lab Guide: First Steps in Data Cleaning

**BAN 6003: Data Management and Analytics Integration**

This module moves from profiling to cleaning. You will work with a messy dataset and make careful, documented changes that improve its usability.

The main idea is:

> Cleaning is not guessing. Cleaning is making traceable decisions.

## Lab File

Complete:

`week3_data_cleaning_lab.ipynb`


## GitHub Repository and Running Environment

Start from this public template repository:

https://github.com/tianhaiz/ban6003-week-03-04-cleaning-reproducibility-template

Create your own GitHub repository from the template with **Use this template > Create a new repository**. I recommend making your repository public so the instructor can inspect your submission. If you use a private repository, invite the instructor GitHub account `zzz1990771` or the email `zzz1990771@gmail.com` as a collaborator.

You may run the lab in either environment:

- **Main path, recommended for beginners:** GitHub Codespaces from your own repository.
- **Optional path for technically experienced students:** clone your own repository, activate the `ban6003` conda environment, install `requirements.txt`, and run JupyterLab locally.

Submit your GitHub repository link through Canvas.

## What You Will Practice

You will practice loading raw data, creating a safe working copy, correcting numeric data types, converting date fields, identifying duplicate records, removing key-based duplicates, reviewing missing values, dropping rows with missing critical fields, imputing selected numeric values, checking suspicious values, reviewing a cleaning log, and saving a cleaned output file.

## Recommended Workflow

1. Open the notebook in Codespaces, or in local Jupyter if you are using the optional local path.
2. Select the course Python kernel if prompted.
3. Run the setup and data loading cells.
4. Inspect the raw data before changing anything.
5. Work through each cleaning step in order.
6. Read the explanation before each cleaning decision.
7. Complete the Your Turn section.
8. Save the cleaned output when prompted.
9. Save your notebook, then commit and push if using GitHub.

## What to Pay Attention To

Keep track of what changed and why. A good cleaning workflow protects the raw data, applies one kind of change at a time, and checks the result after each major step. If a value is suspicious but not clearly wrong, describe the concern instead of silently changing it.

## Minimum Completion Checklist

Before submitting, make sure:

- You loaded the raw dataset.
- You created a working copy.
- You corrected numeric and date fields.
- You checked duplicates.
- You handled missing critical fields as instructed.
- You imputed the required numeric values.
- You reviewed suspicious values.
- You saved the cleaned dataset.
- You completed the written reflection.
- You submitted your completed work through Canvas.
