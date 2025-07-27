# Zeitaufzeichnungen

| Datum  | Von   | Bis   | Dauer h | Sum Manser | Sum Rotter | Aktivität |
|--------|-------|-------|---------|------------|------------|-----------|
| 11.07. | 10:15 | 10:30 | 0.25    | 0.25       |            | Besprechung + Workspace Setup |
| 11.07. | 10:15 | 10:30 | 0.25    |            | 0.25       | Besprechung + Workspace Setup |
| 16.07. | 12:15 | 12:30 | 0.25    |            | 0.50       | Vorbereitungen |
| 17.07. | 15:15 | 16:45 | 1.5     |            | 2.00       | Recherche |
| 17.07. | 20:00 | 21:00 | 1.00    |            | 3.00       | Troubleshooting und venv aufsetzen |
| 21.07. | 11:15 | 13:15 | 2.00    | 2.25       | 3.00       | Recherche (Vorrangig Architektur) |
| 23.07. | 18:00 | 19:45 | 1.75    | 5.00       | 3.00       | Architektur beschreiben und venv Erstellen |
| 24.07. | 11:30 | 13:30 | 2.00    | 7.00       | 3.00       | Vorbereitung des praktischen Teils (Datensatz, Strukturierung) |
| 24.07. | 15:00 | 17:30 | 2.50    | 9.50       | 3.00       | Durchführung des praktischen Teils |
| 24.07. | 18:00 | 19:00 | 1.00    | 10.50      | 3.00       | Praxisteil weiterführen und überarbeiten |
| 25.07. | 14:30 | 19:30 | 5.00    | 15.50      | 3.00       | Praxisteil weiterführen, PDF-Export, README-Datei |
| 25.07. | 11:00 | 14:00 | 3.00    | 18.50      | 3.00       | Praxisteil umgestalten und anpassen (Appendix usw.) |
| 25.07. | 17:00 | 19:00 | 2.00    | 20.50      | 3.00       | Praxisteil verbessern (Kürzen, gestalten, etc.) + Appendix |
| 27.07. | 10:00 | 12:30 | 2.5     | 20.50      | 5.50       | Executive Summary schreiben |
| 27.07. | 14:30 | 20:00 | 5.5     | 20.50      | 11.0       | Exec. Sum, Überschr. updaten, nbconv config |






Notizen:  
11.7. 15 min Besprechung, Vorbereitung des Workspace, beide  
16.7. 12:15-12:30 Zeitaufzeichnungen dok anlegen, fixen von Quellen URLs

17.7. 15:15-16:45 Recherche

27.7.

- 10:00-12:30 Executive Summary schreiben
- 14:30-16:30 Executive Summary weiterschreiben und kürzen, Ubuntu VM setup für nbconvert
- 17:30-19:30 Update Überschriften, spielen mit nbconvert um namen zu displayen
- 20:00-21:30 metadaten bearbeiten, nbconvert befehl und environment fixen.

---

Daniel Manser - genaue Beschrebung der Tätigkeiten

1. Freitag 11.07.2025: 
	- 10:15 - 10:45
		- Teammeeting mit Rotter Daniel: Besprechung der Vorgehensweise
2. Montag 21.07.2025:
	- 11:15 - 13:15
		- Recherche (Vorrangig Architektur)
3. Mittwoch 23.07.2025:
	- 18:00 - 19:45
		- Verfassen der Architektur und Erstellen einer venv
4. Donnerstag 24.07.2025:
	- 11:30 - 13:30 
		- Vorbereitung des Praktischen Teils
			- Auswahl Datensatz
			- Strukturierung
	15:00 - 17:30:
		- 1. Durchführung des praktischen Teils:
			- venv mit python Version 3.10.13 erstellen
			- Datensatz laden
			- Autoencoder erzeugen
			- Modell trainieren
			- Visualisieren
	18:00 - 19:00:
		- Praxisteil weiterführen
5. Freitag 25.07.2025
	- 14:30 - 19:30
		- pdf-Export
		- README Datei
		- Verbesserung des praktischen Teils:
			- Plot: Trainings- vs. Validierungsverlust
			- Training in `history` speichern
			- EarlyStopping hinzufügen
6. Samstag 26.07.2025
	- 11:00 - 14:00
		- Praxisteil umgestalten und anpassen:
			- Grafiken verschönern
			- Code in den Appendix verschieben
			- Beschreibung der Schritte im Hauptteil
	- 17:00 - 19:00
		- Praxisteil verbessern
			- Hauptteil verkürzen
			- Visuelle Gestaltung verschönern
			- Überflüssige Teile entfernen

Dataset:

- CIFAR10 oder Human Faces https://www.kaggle.com/datasets/ashwingupta3012/human-faces

Wir sollen ja min. 1 Paper oder so zitieren, folgende Vorschläge aus den Quellen:

- Paper to cite: https://arxiv.org/pdf/1804.07723 -> aus wandb.ai Quelle
- Artikel to cite: https://pyimagesearch.com/2020/02/17/autoencoders-with-keras-tensorflow-and-deep-learning/ -> aus wandb.ai Quelle zum Thema Autoencoders
- Artikel to cite: https://www.sciencedirect.com/science/article/pii/S0925231218306745 -> aus kaggle Quelle

