# # Personal Budget Tracker – Gruppe 16


## Projektübersicht
Dieses Projekt ist ein **konsolenbasierter Budget-Tracker in Python**, mit dem Benutzer ihre **Einnahmen und Ausgaben erfassen, speichern und auswerten** können.  
Die Daten werden **lokal in einer CSV-Datei** gespeichert und bleiben auch nach einem Neustart des Programms erhalten.

Das Projekt wurde im Rahmen des Moduls **Grundlagen Programmierung** im Studiengang **BSc Wirtschaftsinformatik** entwickelt.

---

## Projektteam
- **Mahmut Altun** – Eingabe & Validierung  
- **Saruyan Tharmakulasingam** – Datei-Management (CSV speichern & laden)  
- **Assvinth Mathikanthan** – Auswertungen & Statistiken  

---

## Funktionen
- Erfassen von **Einnahmen und Ausgaben**  
- Speicherung der Daten in einer **CSV-Datei**  
- Laden der Transaktionen als **Dictionary-Struktur**  
- **Monatsübersicht** (Einnahmen, Ausgaben, Saldo)  
- **Auswertung nach Kategorien**  
- **Eingabevalidierung** (Datum, Typ, Betrag, Kategorie)  

---

## Projektstruktur
```
Budget_Tracker_GR6/
│
├── main.py           # Startpunkt der Anwendung
├── eingabe.py        # Benutzereingaben & Validierung
├── daten.py          # Speichern & Laden der CSV-Daten
├── auswertung.py     # Auswertungen & Statistiken
├── budget_daten.csv  # CSV-Datei mit gespeicherten Transaktionen
└── README.md         # Projektbeschreibung
```

---

## Verwendete Technologien
- **Python**  
- **CSV-Datei** zur lokalen Datenspeicherung  

---

## Programmstart
Der Einstiegspunkt des Programms ist die Datei **main.py**.

### Start über eine Entwicklungsumgebung (z. B. VS Code)
1. Die Datei `main.py` öffnen  
2. Den **Run-/Start-Button** klicken  
3. Die Menüoptionen erscheinen im Terminal  

### Start über das Terminal
Im Projektordner das Terminal öffnen und folgenden Befehl ausführen:
```bash
python main.py
```
Die Benutzerinteraktion erfolgt in beiden Fällen über das Terminal.

---

## Datenformat (CSV)
Die CSV-Datei verwendet folgendes Format:
```csv
datum;typ;kategorie;betrag;beschreibung
2025-01-01;EINNAHME;Lohn;3500.00;Gehalt
2025-01-02;AUSGABE;Essen;20.50;Pizza
```

---

### Besonderheiten / Highlights
- Robuste CSV-Verarbeitung  
- Einheitliche Datenstruktur mit Dictionaries  
- Sauber strukturierter und kommentierter Code  
- Fehlerbehandlung bei ungültigen Eingaben und beschädigten CSV-Zeilen


