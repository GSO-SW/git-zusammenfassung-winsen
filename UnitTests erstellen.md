# UnitTests erstellen

## Vorbereitung
1. Die Klasse, die man testen möchcte, auf "public" setzen
2. Rechtsklick bei Projektmappe(rechte Seite) -> Hinzufügen -> Neues Projekt 
3. "MSTest-Testprojekt" auswählen
4. Name = [Projektname] + [Tests]
5. Rechtsklick auf das Testprojekt -> Hinzufügen -> Projektverweis
6. Das Projekt, das man testen möchte, auswählen und dann auf "ok" drücken
7. Rechts die .cs Datei umbenennen nach [Klassenname] + [Tests].cs
8. KlassenTests.cs öffnen und dann in der ersetn Zeile "using [Projektname];"

## Tests implementieren
1. Vor jeder Methodendeklaration [TestMethod] schreiben
2. Methoden haben keine Übergabeparameter und keinen Rückgabewert
3. Name = [zu testende Methode]_[Das Verhalten]
4. ARRANGE-ACT-ASSERT Struktur verwenden

## Tests ausführen
1. Menü -> Tests -> Alle Tests ausführen