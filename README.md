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

### Programme 

The workshop takes place over two days and combines teaching with live coding.

**Day One** 

| Time | Session | Description |
|--|----|----|
| 10:00 - 12:30 | **What they forgot to teach you about computers** | File system organisation, file types, working directories and paths.|
|  | **Introduction to R, RStudio and project organisation.** | You will learn about data types such as “numerics” and “characters” and object types such as “vectors” and “dataframes” and create your first graph! These are the building blocks for the rest of your R journey. You will also learn about the layout of RStudio and a workflow using scripts and RStudio Projects to keep your work organised.|
| 12:30 - 13:30 |  | Lunch |
| 13:30 - 16:00 | **Types of variable, summarising and plotting distributions** | Revise the difference between continuous and discrete values and how we summarise and visualise them. Importing data from text files and excel files and developing your understanding of working directories and paths. |

**Day Two**         

| Time | Session | Description |
|--|----|----|
| 10:00–12:30           | **Summarising data with several variables** | Building on the previous day's work exploring single variables, you will learn how to summarise and visualise datasets containing multiple variables. You will identify response and explanatory variables, explore the principles of "tidy" data, carry out a simple data tidying exercise, and learn how to save figures for publication and reporting. |
| 12:30–13:30           | **Lunch**                                   |    |                                                                                                                                                                                                        
| 13:30–16:00           | **Data organisation in spreadsheets**       | Learn how to recognise the underlying structure of your data and arrange it in a ‘tidy’ format to make your life easier. | 
|            | **R workflows**       | Explore and modify workflows for qPCR analysis, RNA sequence analysis, flow  cytometry analysis or ImageJ files. | 

## Audience

This workshop is intended for researchers, technical staff, and postgraduate students in the life sciences who wish to develop practical data analysis skills using R and RStudio.

It is suitable for:

- PhD students, postdoctoral researchers, research assistants, and laboratory technicians working with biological data
- academic staff and industry scientists seeking more reproducible and efficient data analysis workflows
- researchers who currently rely on spreadsheets or point-and-click software and wish to transition to code-based analysis
- participants with little or no prior programming experience
- anyone who has attempted to learn R independently but found file management, working directories, data organisation, or coding workflows challenging

### Audience

This workshop is designed for researchers, technical staff, and postgraduate students in the life sciences who want to develop practical data analysis skills using R and RStudio.

The course is  suitable for:

- PhD students, postdoctoral researchers, research assistants, and laboratory technicians working with biological data.
- Academic staff and industry scientists seeking to improve the reproducibility and efficiency of their data analysis workflows.
- Researchers who currently use spreadsheets or point-and-click software and want to transition to code-based analysis.
- Participants with little or no prior programming experience who need a supportive introduction to scientific computing concepts.
- Anyone who has attempted to learn R independently but found file management, working directories, data organisation, or coding workflows challenging.

### Prerequisites

No previous programming experience is required.

There are Windows PCs at the venue and you are not required to bring your own machine. Participants from outside of York will be provided with a temporary IT account.

### What you will learn

After this workshop the successful learner will be able to:

- explain what an operating system is and the organisation of files and directories in a file system
- explain root, home and working directories along with absolute and relative file paths
- find their way around the RStudio windows, use an RStudio Project to organise work and a script to run commands
- use the R command line to create and use the basic data types in R
- distinguish between continuous and discrete variables and be able to appropriately summarise and plot them in R import data in to RStudio from a variety of file types
- explain what is meant by ‘tidy’ data and organise data in spreadsheets.
- customise and save publication quality figures
- Use and modify R workflows for qPCR analysis, RNA sequence analysis, flow cytometry analysis or ImageJ files

### Venue

The workshop will take place in the department of Biology at the University of York. 

Room B/R/012 (PC classroom) is located on the Ground Floor of Biology Block R in the Biomedical and Natural Sciences Building at the University of York's Campus West. Use the [University of York Campus Map](https://www.york.ac.uk/map/) for directions. 

## Repository contents

This repository contains the complete workshop materials, including:

- Quarto source files (`.qmd`)
- example datasets
- exercises and solutions
- supporting images and figures
- reproducible workflows used throughout the workshop

## Citation

Please cite these materials if you adapt or redistribute any portion of them.
