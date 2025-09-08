# MPIM Quarto template

## Installing

There are two main ways of installing this format.

### Create a new Quarto project
```bash
quarto use template mpimet/quarto
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

### Add to existing Quarto project

If you already have an existing Quarto project an want to add this format to the project, please run:

```bash
quarto add mpimet/quarto
```

This can also be used to update the format to a newer version.

## Example

Here is the source code for a sample poster: [poster.qmd](poster.qmd) and a sample slide deck: [slides.qmd](slides.qmd).

You can build the samples by running:
```
quarto render <source_file>
```
