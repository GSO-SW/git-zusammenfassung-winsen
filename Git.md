# Git

## git-Befehle

###
- `git init`		erstellt ein .git Ordner und das local Repository
- `git status` 		zeigt den Status der staging area
- `git config` 		get und setzt die Optionen für das Repository 
- `git checkout`	verschiebt den HEADER zu Commits oder Branches
- `git add` 		added Dateien in die staging area
- `git commit` 		erstellt ein Commit und wird in die Repository hinzugefügt
- `git branch` 		erstellt einen branch
- `git log` 		zeigt die Historie der ganzen Commits an

### Commits zusammenführen
- `git merge` 		führt mehrere branches zusammen 
- `git rebase` 		nimmt die Änderungen eines Branches und fügt die es zu einem anderen Branch zu
- `git cherry pick` kopiert Änderungen eines Commits zu einem anderen Commit

### Remote-Befehle
- `git push` 		gibt die neusten Commits vom local in den Remote
- `git pull` 		holt die neusten Commits vom remote und bringt die zum local. Der Stand vom local wird geupdated
- `git clone` 		klont, mithilfe eines Links, ein Repository in GitHub und fügt es zu dem local dazu.

### Git-Befehle zurücksetzen
- `git reset`		Der Commit, den man resetten will, muss vor diesem Commit ein branch sein oder den Hashwert vom vorherigen Commit. Für Local-Repositories.
- `git revert`		[git revert [Branchname (meistend main)]]. Für Remote-Repositories.

## Merge Konflikte beheben
-	Gucken was in der Beschreibung steht. Meistens muss man selber den Merge machen.
-	Danach git add  und dann git commit

## Was sollte man machen, wenn man in VIM ist?
-	ESC Taste dann „:q!“ schreiben und dann Enter Taste
