# README File


### Terminal-Befehl zum Erzeugen des PDFs

```bash
# Ohne Pfad (im gleichen Ordner)
jupyter nbconvert DQD_Project_Manser_Rotter.ipynb --to pdf

# Mit Pfad
# Für unser Dokument zu Verwenden
jupyter nbconvert DQD_Project_Manser_Rotter.ipynb \
  --to pdf \
  --output DQD_Project_Manser_Rotter.pdf \
  --output-dir Exports

# Ohne Input (Code)
jupyter nbconvert DQD_Project_Manser_Rotter.ipynb \
  --to pdf \
  --output DQD_Project_Manser_Rotter_ohne_Input.pdf \
  --output-dir Exports \
  --no-input

# mit Titel, Authoren und Datum
jupyter nbconvert --to pdf --LatexPreprocessor.title="Image Inpainting mit CNNs am Beispiel CIFAR-10" --LatexPreprocessor.author_names="Daniel Manser und Daniel Rotter" --LatexPreprocessor.date="27.07.2025" DQD_Project_Manser_Rotter.ipynb --output-dir Exports/

# mit title, Authoren und Datum, ohne Input
jupyter nbconvert --to pdf --LatexPreprocessor.title="Image Inpainting mit CNNs am Beispiel CIFAR-10" --LatexPreprocessor.author_names="Daniel Manser und Daniel Rotter" --LatexPreprocessor.date="27.07.2025" DQD_Project_Manser_Rotter.ipynb --output-dir Exports/ --output DQD_Project_Manser_Rotter_ohne_Input.pdf

# mit Quellen (funktioniert nicht zuverlässig)
jupyter nbconvert --to pdf \
 --LatexPreprocessor.title="Image Inpainting mit CNNs am Beispiel CIFAR-10" \
 --LatexPreprocessor.author_names="Daniel Manser und Daniel Rotter" \
 --LatexPreprocessor.date="27.07.2025" \
 --pandoc-args="--citeproc --bibliography=zotero_references.bib --csl=ieee.csl" \
 DQD_Project_Manser_Rotter.ipynb \
 --output-dir Exports/
```
