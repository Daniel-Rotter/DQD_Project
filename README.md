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
```

