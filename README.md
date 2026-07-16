# Introduction to reproducible data analysis in R

## Overview

This repository contains all materials for the two-day workshop **Introduction to reproducible data analysis in R**.

The workshop provides a hands-on introduction to reproducible data analysis using **R** and **RStudio**, covering essential scientific computing concepts including file systems, working directories, data organisation, data visualisation, and reproducible workflows. Through live coding exercises, participants will learn to import, analyse, and present data in R before applying these skills to biological datasets.

The workshop is designed for beginners with little or no prior programming experience and is particularly suitable for researchers, technical staff, and postgraduate students working with biological data.

After this workshop the successful learner will be able to:

- explain what an operating system is and how files and directories are organised within a file system
- explain root, home and working directories, and distinguish between absolute and relative file paths
- navigate the RStudio interface, organise work using RStudio Projects, and write analyses in scripts
- use the R command line to create and manipulate the basic data types in R
- distinguish between continuous and discrete variables and appropriately summarise and visualise them
- import data into R from a variety of file formats
- explain the principles of tidy data and organise spreadsheets accordingly
- customise and save publication-quality figures
- use and modify reproducible R workflows for qPCR analysis, RNA sequencing analysis, flow cytometry analysis, or ImageJ-derived datasets

Materials are organised as a Quarto (`.qmd`) website.

## Background

Modern biological research increasingly depends on reproducible data analysis. As biological datasets become larger and more complex, researchers are expected to develop workflows that make every stage of data collection, analysis, and presentation transparent and repeatable.

Coding is central to reproducibility because it explicitly records every step performed on raw data. Rather than relying on manual point-and-click operations, scripts provide a complete record that can be rerun, shared, and reviewed.

Generative AI tools such as ChatGPT and GitHub Copilot have transformed what is possible for non-programmers by making it easier than ever to generate code. However, producing code is only part of the process. Understanding what code is doing—and being able to evaluate, modify, and validate AI-generated solutions—requires a foundation in programming concepts.

Research consistently shows that AI coding assistants work best for people who already understand the code being generated. Without that foundation, it is difficult to know when the output is incorrect, incomplete, or doing something other than intended. Learning to code improves both the quality of prompts you can write and your ability to judge the answers you receive.

This workshop provides that foundation through practical, live-coded examples using R.

R is a free, open-source language designed for statistical computing and data visualisation. It is particularly well suited to scientific data analysis and has long been popular with users who do not initially consider themselves programmers, while providing a pathway towards more advanced programming skills.

## About the workshop

The workshop is delivered through live coding, allowing participants to code alongside the instructor throughout the two days.

Topics include:

- scientific computing fundamentals including file systems, paths, and working directories
- navigating RStudio and organising work using scripts and RStudio Projects
- creating, importing, summarising, and visualising data in R
- understanding R data types and variable types
- organising spreadsheet data using tidy data principles
- producing publication-quality graphics
- exploring and modifying reproducible workflows for biological data analysis, including examples from qPCR, RNA sequencing, flow cytometry, and ImageJ

## Programme

### Day 1

| Time | Session | Description |
|------|---------|-------------|
| 10:00–12:30 | What they forgot to teach you about computers | File systems, file types, working directories, paths, and project organisation. Introduction to R, RStudio, scripts, RStudio Projects, basic data types, and creating your first graph. |
| 12:30–13:30 | Lunch | |
| 13:30–16:00 | Types of variables, summarising and plotting distributions | Continuous and discrete variables, summary statistics, visualisation, importing text and Excel files, and developing confidence with working directories and file paths. |

### Day 2

| Time | Session | Description |
|------|---------|-------------|
| 10:00–12:30 | Summarising data with several variables | Working with datasets containing multiple variables, identifying response and explanatory variables, tidy data principles, simple data tidying, and saving publication-quality figures. |
| 12:30–13:30 | Lunch | |
| 13:30–16:00 | Data organisation in spreadsheets and R workflows | Recognising the underlying structure of data and arranging spreadsheets into tidy formats for analysis. Exploring and modifying workflows for qPCR analysis, RNA sequencing analysis, flow cytometry analysis, or ImageJ-derived datasets. |

## Audience

This workshop is intended for researchers, technical staff, and postgraduate students in the life sciences who wish to develop practical data analysis skills using R and RStudio.

It is suitable for:

- PhD students, postdoctoral researchers, research assistants, and laboratory technicians working with biological data
- academic staff and industry scientists seeking more reproducible and efficient data analysis workflows
- researchers who currently rely on spreadsheets or point-and-click software and wish to transition to code-based analysis
- participants with little or no prior programming experience
- anyone who has attempted to learn R independently but found file management, working directories, data organisation, or coding workflows challenging

## Prerequisites

No previous programming experience is required.

Windows PCs will be available at the venue, and participants are **not** required to bring their own computer. Participants from outside the University of York will be provided with a temporary IT account.

Participants who prefer to use their own machine should install the following before attending:

- **R** version **4.4.1** or later: <https://cloud.r-project.org/>
- **RStudio Desktop** version **2024.12.1+563** or later: <https://posit.co/download/rstudio-desktop/>
- CRAN packages:
  - `tidyverse`
  - `devtools`
- TinyTeX by running the following command from the RStudio Terminal:

```bash
quarto install tinytex
```

## Repository contents

This repository contains the complete workshop materials, including:

- Quarto source files (`.qmd`)
- example datasets
- exercises and solutions
- supporting images and figures
- reproducible workflows used throughout the workshop

## About the instructor

Emma Rand is a Professor in the Department of Biology at the University of York, where she specialises in teaching data science and reproducibility, particularly to researchers who do not initially see themselves as programmers.

She leads the UKRI-funded **Cloud-SPAN** and **Digital Research Skills Catalyst** projects, which develop and deliver FAIR training materials to support the research community in developing practical digital research skills.

## Citation

Please cite these materials if you adapt or redistribute any portion of them.
