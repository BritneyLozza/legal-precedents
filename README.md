# legal-precedents
A directory of markdown files that can be exported to DOCX, ODT and PDF.

# Why?
I wanted to just write without worrying about formatting. I did the formatting once and now its automated.

# Usage

1. Edit the .md file and change the sender and recipient information.
2. Run one of the example commands below when ready.

## Markdown to DOCX
pandoc -o precedent-letter-police.docx precedent-letter-police.md

## Markdown to ODT
pandoc -o precedent-letter-police.odt precedent-letter-police.md

## Markdown to PDF
pandoc -o precedent-letter-police.pdf precedent-letter-police.md

# Recommendation
I recommend that you output to ODT or DOCX first to make last minute format changes in case you want extra spaces.

I don't like how pandoc outputs to PDF, so I use ODT and export to PDF using LibreOffice.
