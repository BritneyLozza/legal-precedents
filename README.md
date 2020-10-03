# legal-precedents
A directory of markdown files that can be converted into PDF or DOCX by Pandoc

# Why?
I wanted to just write without worrying about formatting. I did the formatting once and now its automated.

# Usage

## Markdown to DOCX
pandoc -o file.docx file.md

## Markdown to ODT
pandoc -o file.odt file.md

## Markdown to PDF
pandoc -o file.pdf file.md

# Caveat
I find the pandoc conversion to PDF isn't as good as simply using ODT or DOCX and exporting to PDF.
