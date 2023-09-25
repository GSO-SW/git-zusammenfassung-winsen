
# git-Befehle

## Basics
- `git init`		erstellt ein .git ordner und das local Repository
- `git status` 		zeigt den Status der staging area
- `git config` 		get und setzt die Optionen für das repository 
- `git checkout`	verschiebt den HEADER zu Commits oder Branches
- `git add` 		added Dateien in die staging area
- `git commit` 		erstellt ein Commit und wird in die Repository hinzugefügt
- `git branch` 		erstelle einen branch`
- `branch` 			ein Namensschild für bestimmte Commits
- `git log` 		zeigt die Historie der ganzen Commits an

## Commits zusammenführen
- `git merge` 		führt mehrere branches zusammen 
- `git rebase` 		versetzt commits zum Ursprung des branches zurück 
- `git cherry pick` kopiert Änderungen eines Commits zu einem anderen Commit

## Remote-Befehle
- `git push` 		gibt die neusten Commits vom local in den Remote
- `git pull` 		holt die neusten Commits vom remote und bringt die zum local. Der Stand vom local wird geupdated


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
