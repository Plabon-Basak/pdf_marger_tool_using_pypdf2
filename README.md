# PDF Merger Tool

A tiny command-line utility that **merges multiple PDF files into one**, in the
exact order you specify. Built with Python and PyPDF2.

![Python](https://img.shields.io/badge/Python-3.x-3776AB)
![PyPDF2](https://img.shields.io/badge/PyPDF2-pdf--tools-red)
![CLI](https://img.shields.io/badge/CLI-Terminal-black)

## Features

- Merge any number of PDFs in a single run
- Control the output order directly from the prompt
- Validates that every file exists before merging
- Simple, guided command-line interaction

## Getting Started

### Requirements

Install PyPDF2:

```bash
pip install PyPDF2
```

### Usage

```bash
python PDF_Marger_tool/app.py
```

You will be prompted for:

1. **PDF file names** in the desired order (comma-separated)
2. The **output file name** (e.g. `merged.pdf`)

Example run:

```
Welcome to the PDF Merger Tool!
Enter PDF file names in the desired order (comma-separated): demo1.pdf,
demo2.pdf, demo3.pdf
Enter the output file name (e.g., merged.pdf): marged.pdf
Merged PDF saved as marged.pdf
```

## Demo files

The `PDF_Marger_tool` folder includes `demo1.pdf`, `demo2.pdf`, `demo3.pdf`,
and a pre-generated `marged.pdf` output, so you can try the tool immediately.

## Project structure

```
pdf_marger_tool_using_pypdf2/
â””â”€â”€ PDF_Marger_tool/
    â”œâ”€â”€ app.py        # CLI merger
    â”œâ”€â”€ demo1.pdf     # Sample PDF
    â”œâ”€â”€ demo2.pdf     # Sample PDF
    â”œâ”€â”€ demo3.pdf     # Sample PDF
    â””â”€â”€ marged.pdf    # Sample merged output
```

## License

This project is open-source and available under the [MIT License](LICENSE).