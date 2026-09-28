# DSA 295: Introduction to Social Network Analysis

Sean Ryan · Fall 2026

## Quick links

- **[Open the clickable report](https://strokeofluck.github.io/DSA295-FA26/DSA295_003_FA26_A2_sryan3.html)** — read the rendered Assignment 2 report in your browser.
- **[Explore Louvain communities](https://strokeofluck.github.io/DSA295-FA26/community-detection.html)** — separate exploratory page with modularity-based communities, shaded hulls, and a betweenness overlay.
- **[GitHub repository](https://github.com/StrokeOfLuck/DSA295-FA26)** — browse the source files and version history.
- **[Download page](https://strokeofluck.github.io/DSA295-FA26/)** — download the submission HTML, R Markdown, and network data.

## Assignment 2: Connectivity and Centrality

- [R Markdown source](DSA295_003_FA26_A2_sryan3.Rmd)
- [HTML submission file](DSA295_003_FA26_A2_sryan3.html)
- [Network data](drugnet.rda)

The report uses `ggraph` and links explanations to the [introSNA textbook](https://stevemcd1.github.io/introSNA/).

**Review draft:** ethnicity is labeled with the original codes 1–4 until the course code key is verified. The primary analysis uses a simple undirected projection of the largest weak component; a directed sensitivity check is included. Confirm the intended direction convention before submission.

## Exploratory: Louvain community detection

- [Rendered community page](https://strokeofluck.github.io/DSA295-FA26/community-detection.html)
- [R Markdown source](community-detection.Rmd)

This page is intentionally separate from the Assignment 2 submission. It applies Louvain community detection to the same undirected main component, reports modularity and community sizes, draws translucent hulls around detected communities, compares community structure with betweenness centrality, and counts relationships within versus between communities.

## Run locally

Keep the `.Rmd` files and `drugnet.rda` in the same folder. Open an `.Rmd` in RStudio and select **Knit**. Install packages once if needed:

```r
install.packages(c("igraph", "ggraph", "ggforce", "knitr", "rmarkdown"))
```

Upload `DSA295_003_FA26_A2_sryan3.html` to Moodle when the report is ready. The hosted report is the same HTML file, not a replacement submission format.

## Data source

`drugnet.rda` is an unmodified copy from the instructor's [intronets repository](https://github.com/stevemcd1/intronets/blob/master/inst/extdata/drugnet.rda), downloaded September 24, 2026. See the [dataset documentation](https://github.com/stevemcd1/intronets#drug-user-social-networks) for attribution and context.
