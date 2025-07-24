# Master's Thesis Project

This repository contains my master's thesis work, including the main thesis document, proposal, and various explorations related to my research.

## Structure

- **`masters-thesis-proposal/`** - Initial thesis proposal document
- **`mmt-exploration/`** - First exploration of MMT (Metamath/Mathematical Theory) concepts
- **`mmt-exploration-2/`** - Second iteration of MMT research
- **`mmt-exploration-4/`** - Fourth exploration with references
- **`mmt-exploration-5/`** - Latest MMT exploration with images and alternative approaches
- **`file.tex`** - Standalone LaTeX file

## Building Documents

Each directory contains LaTeX source files that can be compiled using:

```bash
pdflatex main.tex
bibtex main  # if references are used
pdflatex main.tex
pdflatex main.tex
```

Or using latexmk for automated building:

```bash
latexmk -pdf main.tex
```

## Requirements

- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- Required packages (typically handled automatically by modern LaTeX distributions)

## Research Focus

This thesis explores MMT (Metamath/Mathematical Theory) concepts, including:
- Theoretical foundations
- Practical implementations
- Alternative approaches and methodologies

## Images and Resources

Visual resources and diagrams are stored in the `images/` subdirectories within each exploration folder.