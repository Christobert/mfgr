Ergänzung: Kontrollfragen (meine Antworten)

Was bedeutet „Staging“ in Git?
Staging heißt, dass ich Änderungen in die Staging Area (Index) lege. Damit wähle ich genau aus, was in den nächsten Commit soll. Erst nach git add landen die Änderungen im Commit.

Wie heißt der aktive Branch direkt nach dem Initialisieren?
Standardmäßig heißt der Branch main. Bei älteren Setups kann er noch master heißen.

Womit kann man sich alle bisherigen Commits anzeigen lassen?
Mit git log. Kurz und übersichtlich geht auch: git log --oneline --graph --decorate

Welcher Befehl zeigt den aktuellen Status des Repositories (z. B. ob Dateien gestaged oder geändert sind)?
git status

Wozu dient die Datei .gitignore?
Dort liste ich Dateien/Ordner auf, die Git ignorieren soll. Beispiel: Build-Ordner, temporäre Dateien, IDE-Settings. So landen sie nicht versehentlich im Repo.1
