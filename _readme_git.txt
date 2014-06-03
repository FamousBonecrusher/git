Git
===

Download des Clients von
http://git-scm.com/

Git arbeitet "Root"-Folder basiert (das Repository liegt als versteckter .git Folder dann in diesem Folder),
 .h. die Files in diesem und den darunterliegenden Ordnern sind automatisch der Versionskontrolle unterworfen.
(Anmerkung: es können auch explizit Files ausgenommen werden)

1.  Repository anlegen (im "Root"-Folder)
=> in Folder gehen:
git init

1a. Statusabfrage
git status

2. Staging (="Verladerampe")
Vorstufe zum Commit
sammelt alle Änderungen/alle geänderten Files, die dann gemeinsam committed werden können
git add .

3. Commit
d.h. ins Archiv bringen
git commit

4. normal weiter


* Git Gui  (besser ist der GitHub-Client s.u.)
=========
Auf Englisch umstellen:

Leider gibt es in den Einstellungen des GIT GUI nicht die Möglichkeit die gewünschte Sprache einzustellen. 
Will man aber Englisch als Sprache, dann kann man einfach das deutsche Message Bundle umbenennen. 
Die Datei liegt unter C:\Program Files (x86)\Git\share\git-gui\lib\msgs

de.msg => umbenennen zB nach SEB_de.msg

* GitHub Client
===============
Download von
www.github.com

