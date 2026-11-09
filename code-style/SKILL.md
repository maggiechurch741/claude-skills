---
name: code-style
description: Maggie Church's coding and data-analysis conventions — R/tidyverse style, error visibility, NA handling, git rules. Use when writing, editing, or reviewing any code or analysis in this project.
metadata:
  version: "1.1"
  skill-author: Maggie Church
---

### Code style

-   Write clear code over clever code.
-   Don't overengineer: Simple beats complex
-   Make small, reviewable changes. Explain what changed and why briefly.
-   Default to R, and use tidyverse/tidy syntax where possible.
-   Do not write comments that restate the code. Comment intent. Be concise.
-   \<- for assignment, two-space indentation, snake_case names.
-   Use furniture::table1(), gtsummary packages for descriptive or summary tables
-   Each function should have a single responsibility
-   Use inspiration from recent, rigorous tutorials and github accounts

## Make errors visible

-   Never drop NAs.
-   Add checks after any major data step.
-   Do not change the data to pass a check without asking.
-   Run code to verify it works before saying it does. If you couldn't run it, say so.
-   Don't fabricate package functions, arguments, or citations. Check the docs or say you're unsure.
-   Don't delete files or outputs without asking.
-   Don't claim results are significant, meaningful, or causal. Report the numbers; Maggie interprets them.
-   Do not make scripts succeed by hiding problems. Let the script fail visibly so the underlying problem can be fixed.

## Git

-   Never commit data, credentials, or `.env` files.
-   Don't push, rebase, or force anything without asking.

## Data analysis

-   When doing exploratory data analysis, provide graphics over tables.
-   Do not change the data without asking.
-   Don't overwrite raw data.
-   State your assumptions about all joins and filters





