# Rapport SAE 2.03

## pdf
`pandoc -N rapport.md --pdf-engine=pdflatex --metadata title="Rapport - SAE 2.03" --toc -o rapport.pdf --variable colorlinks=true`

## pdf
`pandoc -f markdown -t html rapport.md -o rapport.html --metadata title="Rapport - SAE 2.03" --self-contained --css=styles.css --toc --number-sections --variable=toc-title:"Sommaire"`

