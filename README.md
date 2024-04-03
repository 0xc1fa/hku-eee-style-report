# HKU EEE LaTeX Style Guide

This repository provides a LaTeX template designed according to the HKU EEE guidelines,  specifically adhering to CAES9541 and ELEC4848 (FYP) standards. Follow the instructions below to manage media data, configure your development environment, and utilize the template effectively.

## Visual Studio Code Configuration

A default `settings.json` file is included to configure your Visual Studio Code environment. It's located in the `.vscode` directory. Ensure the LaTeX Workshop extension is installed in Visual Studio Code for optimal use.

## LaTeX Tips

Here are some tips to help you customize and compile your document efficiently:

### Document Formats
Switch between different document formats by altering the first import statement:

- Use `\usepackage{progressreport}` with a font size of `12pt` for a progress report.
- Use `\usepackage{finalreport}` with a font size of `11pt` for a standard report.

### Compilation Options
Choose one of the following compilation methods based on your needs:

- Execute `xe*2` if citations are not required.
- For documents needing citations or abbreviations, execute `xelatex -> makeindex -> bibtex -> xelatex*2`.

### Capitalization of "Figure" and "Table"
To automatically capitalize "Figure" and "Table" in your text, prefer using `\Cref` over `\ref` or `\cref`.
