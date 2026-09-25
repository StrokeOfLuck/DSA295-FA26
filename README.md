# DSA 295: Introduction to Social Network Analysis

Sean Ryan · Fall 2026

## Assignment 2: Connectivity and Centrality

[Open the HTML report](https://StrokeOfLuck.github.io/DSA295-FA26/DSA295_003_FA26_A2_sryan3.html)

- [R Markdown source](DSA295_003_FA26_A2_sryan3.Rmd)
- [HTML submission file](DSA295_003_FA26_A2_sryan3.html)
- [Network data](drugnet.rda)

The report uses `ggraph` and links explanations to the [introSNA textbook](https://stevemcd1.github.io/introSNA/).

**Review draft:** ethnicity is labeled with the original codes 1–4 until the course code key is verified. The primary analysis uses a simple undirected projection of the largest weak component; a directed sensitivity check is included. Confirm the intended direction convention before submission.

## Run locally

Keep the `.Rmd` and `drugnet.rda` in the same folder. Open the `.Rmd` in RStudio and select **Knit**. Install packages once if needed:

```r
install.packages(c("igraph", "ggraph", "knitr", "rmarkdown"))
```

Upload `DSA295_003_FA26_A2_sryan3.html` to Moodle when the report is ready. The hosted report is the same HTML file, not a replacement submission format.

## Data source

`drugnet.rda` is an unmodified copy from the instructor's [intronets repository](https://github.com/stevemcd1/intronets/blob/master/inst/extdata/drugnet.rda), downloaded September 24, 2026. See the [dataset documentation](https://github.com/stevemcd1/intronets#drug-user-social-networks) for attribution and context.
