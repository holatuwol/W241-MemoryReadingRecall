# About this Repository

This repository contains materials for one of the final projects for [W241: Experiments and Causal Inference](http://www.ischool.berkeley.edu/courses/datasci241) course for the online [Master of Information and Data Science (MIDS)](https://datascience.berkeley.edu) program at [UC Berkeley](http://www.berkeley.edu).

For your convenience, the report has also been compiled into GitHub-flavored markdown and can be viewed here:

[W241: Personality vs. Reading Recall Study, Final Paper](00-final-project.md)

# Compiling the Deliverable

## Create a PDF

1. Run the following command from an R console:

```
rmarkdown::render(
	'00-final-project.Rmd',
	rmarkdown::pdf_document(number_sections = TRUE))
```

## Create GitHub Flavored Markdown

1. Modify the `stargazer` calls in `05-results-summary.Rmd` and `06-future-research.Rmd` to specify `type = 'html'`
2. Remove the `\newpage` values in `00-final-project.Rmd` and `02-experimental-design.Rmd`
3. Run the following command from an R console:

```
rmarkdown::render(
	'00-final-project.Rmd',
	rmarkdown::md_document(variant = 'markdown_github'))
```