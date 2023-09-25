
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
![public clss](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/f273e38d-47d8-4256-8599-13370321b442)

2. Rechtsklick bei Projektmappe(rechte Seite) -> Hinzufügen -> Neues Projekt 
![2](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/25063670-aff5-4832-950f-0c090f8c037d)

3. "MSTest-Testprojekt" auswählen
![3](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/465a1a51-4107-4203-8de6-4f68582e7c9f)

4. Name = [Projektname] + [Tests]
![4](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/75fcd11c-53d4-455e-a012-dcd4822b9cc0)

5. Rechtsklick auf das Testprojekt -> Hinzufügen -> Projektverweis
![5](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/87d92cf3-4a7f-4eae-ba52-6820ec16204e)

6. Das Projekt, das man testen möchte, auswählen und dann auf "ok" drücken
![6](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/26d9b6af-24a8-4b97-93f7-1e92f4284663)

7. Rechts die .cs Datei umbenennen nach [Klassenname] + [Tests].cs
![7](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/09c69d9f-f140-4c94-8f3c-c2d105206f87)


8. KlassenTests.cs öffnen und dann in der ersetn Zeile "using [Projektname];"
![8](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/f99d8073-c877-48ab-a083-0d4896f3622e)



## Tests implementieren
1. Vor jeder Methodendeklaration [TestMethod] schreiben
![11](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/b0688201-e836-43c0-8780-11e6844f9088)

2. Methoden haben keine Übergabeparameter und keinen Rückgabewert
![22](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/23ebd80c-d150-4f1c-a40f-36cbd9a6f818)

3. Name = [zu testende Methode]_[Das Verhalten]
![33](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/0e1c1bff-ca5e-4f6c-a507-d4b962b1ed2a)

4. ARRANGE-ACT-ASSERT Struktur verwenden
![44](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/8d7ed08b-ec5a-4201-b6f0-bf10095dfe02)


## Tests ausführen
1. Menü -> Tests -> Alle Tests ausführen
![111](https://github.com/GSO-SW/git-zusammenfassung-winsen-rene/assets/145109199/350561e1-d32e-4c79-8f59-f5dfd9f76090)
