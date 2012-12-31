Wer kennt das nicht: Man braucht mal eben ein kleines Tool, ein simples Script, um eine Aufgabe zu erfüllen. Dafür die Shell hernehmen? Das ist nicht unser Ding: Wir machen so etwas schnell und einfach in Perl.

Schnell werden aus den kleinen Scripts oft genutze Hilfen, die man nach und nach ändert und erweitert. Irgendwann ist aus dem schnellen Script ein waschechtes Programm geworden und der Wunsch nach einer intiutiveren Oberfläche kommt auf.

Dieser Beitrag zeigt mit Hilfe von Curses, wie man mit Hilfe von Curses seinen gehackten Tools eine schnieke Oberfläche verleiht und so aus einem kleinen Hack schnell ein robustes und einfach zu verwendendes Programm macht.

Als Beispiel wird ein kleines Bugtracking-System alá Bugzilla/Redmine in Perl nachgebaut - mit Curses, SQLite, Mailing-Versand und Export in verschiedene Formate.