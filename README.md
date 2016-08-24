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