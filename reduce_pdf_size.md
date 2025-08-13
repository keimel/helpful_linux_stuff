```
gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/screen -dNOPAUSE -dQUIET -dBATCH -sOutputFile=output.pdf input.pdf
```

| dPDFSETTINGS=/Option | Description |
|---|---|
| screen | Has a lower quality and smaller size. (72 dpi) |
| ebook | Has a better quality, but has a slightly larger size (150 dpi) |
| prepress | Output is of a higher size and quality (300 dpi) |
| printer | Output is of a printer type quality (300 dpi) |
| default | Selects the output which is useful for multiple purposes. Can cause large PDFS |
