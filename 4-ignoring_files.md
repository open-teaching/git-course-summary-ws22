# Ignoring Files in git

Zu ignorierende Dateien sind normalerweise Build-Artefakte und maschinell generierte Dateien, die von deiner Repository-Quelle abgeleitet werden können oder aus anderen Gründen nicht committet werden sollen. Einige gebräuchliche Beispiele:


Ignorierte Dateien werden in einer speziellen Datei namens .gitignore verfolgt, die im Root-Verzeichnis deines Repositorys eingecheckt wird. Es gibt keinen expliziten "git ignore"-Befehl: Stattdessen muss die .gitignore-Datei manuell bearbeitet und committet werden, wenn neue Dateien hinzukommen, die ignoriert werden sollen. .gitignore-Dateien enthalten Muster, die mit den Dateinamen in deinem Repository abgeglichen werden, um zu bestimmen, ob diese ignoriert werden sollen oder nicht.