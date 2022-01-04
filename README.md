# Latex Template

Das Projekt dient nicht Latex nutzern einen einfachen Einstieg in Latex zu geben. 
Veränderungen von Stil und Makros sollten in der Datei mystyle.sty vorgenommen werden.
In der master.tex Datei sollten lediglich alle weiteren *.tex Dateien* inkludiert werden (wie im Beispiel \include{chapters/chapter1}).
Alle weiteren *.tex Dateien* sollten im Ordner chapters aufbewahrt werden. 
In dem Ordner für die Workflows findet sich eine *.yml* Datei, diese lässt derzeit einmal die Woche das Dokument compilen mit der Veränderung bei on: [push] wird jedes mal, wenn ihr Sachen in den master pusht ein neues PDF-Dokument gebaut.

[PDP-Dokument](https://github.com/git-fabus/latex-template/build/master.pdf)
