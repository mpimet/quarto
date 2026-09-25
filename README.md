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

This repository contains two examples:
  * Poster: [poster.qmd](poster.qmd)
  * Slide deck: [slides.qmd](slides.qmd)

You can view a rendered version of the [poster](https://mpimet.github.io/quarto/poster.html) and [slides](https://mpimet.github.io/quarto/slides.html),
or build the examples locally by running the following command:
```
quarto render <source_file>
```
