# README File


### Terminal-Befehl zum Erzeugen des PDFs

```bash
# Ohne Pfad (im gleichen Ordner)
jupyter nbconvert DQD_Project_Manser_Rotter.ipynb --to pdf

# Mit Pfad
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

# Ohne Input und ohne Konsolenausgabe (Training des Modells)
jupyter nbconvert DQD_Project_Manser_Rotter.ipynb \
  --to pdf \
  --output DQD_Project_Manser_Rotter_ohne_Input.pdf \
  --output-dir Exports \
  --no-input \
  --TagRemovePreprocessor.enabled=True \
  --TagRemovePreprocessor.remove_all_outputs_tags="['remove_output']"
```

