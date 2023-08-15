# 1.1. Motivation
- Was ist ein Programm?
  Ein Computerprogramm ist eine Folge von Anweisungen um Aufgaben mithilfe eines Computers zu lösen. Programme sind die Schnittstelle zwischen Mensch und Computer. Sie bilden das Medium mit dem Menschen mit Computern kommunizieren und diesen Aufgaben geben können.
- Was ist programmieren?
  Programmieren ist die Tätigkeit Programm zu schreiben.
- Warum sind Programme so bedeutend? Wo kommen Programme alles zum Einsatz? 
  Unsere digitalisierte Welt baut fundamental auf Millionen von Programmen auf, die massiv unseren Alltag gestalten. Das gesamte Informationszeitalter mit der größten Erfindung des 20. Jahrhunderts, dem Internet, beruht auf Programmen. Programme lassen uns kommunizieren, Informationen austauschen, forschen und so vieles mehr.
- Warum ist es sinnvoll programmieren zu lernen?
  Programme sind so unglaublich wichtig für unsere Welt, da sie in Kombination mit Computer einfach ein unglaublich mächtiges Werkzeug sind. Durch Programme sind Computer imstande Aufgaben von Menschen zu übernehmen und das absolut Fehlerfrei und in unglaublich großen Maßstäben, die weit über die Fähigkeiten der Menschheit hinaus reichen. 
- Was machen Programme so alles?
  Programme werden vor allem dazu genutzt Daten und Informationen auszutauschen. Also zu kommunizieren. Sonst werden Programme genutzt um grob gesagt zu rechnen und berechnen sowie Computer zu verwalten und ähnliches. Praktisch alles was ihr euch digital so vorstellen könnt. Niemand kriecht in einem Computer um da die Festplatte manuell einzustellen.

# 1.2. Grundlagen anhand von Python
### Wie funktioniert ein Programm?
Der Computer versteht grundlegend nur ganz fundamentale Anweisungen in Form von Binärcodes. Alle diese möglichen Binärcodes bilden die Maschinensprache. Zum Beispiel entspricht die Binärzahl 000011000111010001011111110000000010 der Anweisung die Zahl 2 in eine bestimmte Speicherstelle zu laden (in x86 Prozessoren). 
Syntax: Welche Zeichenketten sind (valide) Programme in der Programmiersprache.
Semantik: Welche Bedeutung haben diese bzw. einzelne Zeichenketten.
Also was für Wörter, Sätze, Texte gehören zu unserer Sprache und was bedeuten diese.

### Was sind Programmiersprachen?
Programmiersprachen sind also Sprachen mit ihrer eigenen Syntax und Semantik. Da aber Computer eben grundsätzlich nur Maschinensprache verstehen, müssen alle Programme (egal in welcher Sprache) vor dem Ausführen zunächst in Maschinensprache übersetzt werden. Fundamental unterscheiden sich Programmiersprachen vor allem darin, auf welcher Abstraktionsebene, also wie "weit" sie von der Maschinensprache entfernt sind. Wir sprechen von low-level und high-level. Low-level Programmiersprachen haben benutzen Wörter, die nah an der Maschinensprache sind und ein Ausdruck in dessen Bedeutung vielleicht einigen Hunderten Anweisungen entspricht. High-level Programmiersprachen sind deutlich leichter für uns Menschen zu verstehen und zu benutzen, da sie Ausdrücke für ganz Abstrakte Anweisungen beinhalten, die in Maschinensprache übersetzt, tausenden Wörter entsprechen.
Zum Glück sind Programmiersprachen nicht so kompliziert wie gesprochene Sprachen und sind sich häufig sehr ähnlich. 

### Was ist Python? Warum Python?
Python ist die beliebteste/meist benutze (sehr) high-level Programmiersprache. Sie ist sehr leicht zu verstehen und lernen. Sie wird unglaublich viel für Data Science, Machine Learning genutzt und ist perfekt für den Alltagsgebrauch geeignet. Ob Roboter steuern oder kleine Rätsel lösen. Python ist überhaupt nicht geeignet für große Infrastruktur-Projekte oder sehr effiziente Programme. Python ist so abstrakt, dass den Programmierer\*innen wenig Kontrolle über die tatsächlichen Maschinencode bleibt. Stellt es euch so vor: Je weiter wir uns von der Maschinensprache entfernen mit unserer Programmiersprache, desto schwieriger wird es 1:1 jedes Wort perfekt zu übersetzten. 

### Grundlegende Konzepte in Colab
Wichtig: Programmieren lernt Mensch indem Mensch programmiert. Deshalb praktisch zum mitverfolgen in interaktiven Notebook. (Mit Colab/Jupyter zum mitverfolgen und z.B. mit Fehlern eingebaut)
- Variablen (Bezeichnung für einen Speicherplatz)
  Deklarieren/Initialisieren, Operationen
- Schleifen
  for-loop, while-loop
- Bedingungen
  if, else if, else, boolesche Operatoren 
- Funktionen

- Wie führe ich ein Programm aus?
  Menschen haben Programme geschrieben um zu überprüfen, ob unser Text (Code) valide in der Sprache ist, ihn zu übersetzten und ihn auszuführen. Darum müssen wir uns also nicht kümmern. Wir müssen nur sinnvollen Text schreiben.
- Was sind bugs? Lesen von Fehlermeldungen (Errors)
  Zum Glück müssen wir nicht gleich die Sprache perfekt sprechen können. Wir werden stehts auf Fehler hingewiesen. Wenn irgendetwas dabei schief geht, wir zum Beispiel ein Wort benutzen, dass es gar nicht in der Sprache gibt, bekommen wir eine Fehlermeldung/ein Error.
- Was sind Bibliotheken/Libraries?
  Libraries sind einfach nur Sammlungen von Code, die wir in unseren Programmen benutzten und importieren können. Statt alle Funktionen immer von selbst zu schreiben haben viele Tolle Menschen eben libraries geschrieben, dessen Funktionen wir direkt in unserem Programmcode benutzen können als hätten wir sie selbst geschrieben. Libraries machen Programme unglaublich mächtig (Eine Person schreibt und alle profitieren davon).

# 1.3. Die Welt drumherum
Das Programmieren ist zwar eigentlich nur das Schreiben des Programms alles des Programmtextes allerdings gehört in der Praxis noch deutlich mehr dazu. Schließlich wollen wir unser Programm ja gerne auch ausführen (was auch echt eine Herausforderung sein kann), verwalten, mit anderen Teilen, etc. Außerdem gibt es so viele Programme, die wir schreiben können.

## 1.3.1. Programme schreiben/verwalten/ausführen
### Was sind text editors bzw. IDEs?
Text editor sind einfach Programme in denen wir unseren Programmcode schreiben. Praktisch Word für Code statt für Aufsätze und co. Text editors bzw. code editors haben sehr viele Funktionen, die das Schreiben von Programmen immens vereinfachen. Sie kümmern sich um die Formatierung des Codes, bieten code completions, überprüfen, ob es keine Syntaxfehler gibt und vieles mehr. Integrated development environments kurz IDEs haben darüber hinaus noch einige features mehr, wie debugger, die beim finden von bugs helfen, benchmarking tools, um die Geschwindigkeit des Programms zu messen usw.. Der beliebteste text editor/IDE ist Visual Studio Code (VSCode). (Ist sehr zu empfehlen!)
### Was ist Linux?
Linux Betriebssysteme sind wie Windows und MacOS Betriebssysteme für Computer. Sie sind vor allem bei Programmierer\*innen beliebt, da mit Linux zu arbeiten viele Arbeitsabläufe sehr vereinfacht und mehr Kontrolle über den eigenen Computer ermöglicht. Es gibt ganz viele verschiedene "Distributionen" (Betriebssysteme), die auf dem Linux Kernel, also dem Herzen eines Betriebssystems, aufbauen. Den Linux Kernel haben wir vor allem Linus Torvalds zu verdanken. Ein sehr wichtiger Typ in unserer Welt.
### Was sind Git und GitHub?
Git ist Linus Torvalds zweites Lebenswerk. Git ist, was wir ein version control system nennen. Ein Programm, welches die Verwaltung unseres Codes und dessen verschiedenen Versionen ermöglicht. Wir programmieren zu Beginn einfach nur in höchstens ein paar Dateien, wo es leicht ist einen Überblick über Veränderungen zu haben. Der Linux Kernel bestand in 2020 zum Beispiel aber aus über 27,8 Millionen Zeilen Code. Diese wurden alle von Menschen geschrieben. Um also große Projekte zu verwalten und zum Beispiel bei Fehler leicht zu alten Versionen zurück zu springen braucht es ein version control system. Git ist dafür der absolute Standard. Code wird dabei in sogenannten Repositories verwaltet. GitHub ist ein online Dienst von Microsoft um Git Repositories über das Internet zu teilen und mit anderen Zusammenzuarbeiten. 
### Was ist ein Terminal?
Ein Terminal/die Konsole ist ein Programm in dem wir durch ein weiteres Programm, die Shell, mit dem Betriebssystem kommunizieren können und Anweisungen abgeben können. Das Wort Terminal wird häufig einfach genutzt um die Shell und die "Benutzeroberfläche" zu bezeichnen. Machen wir auch. Das Terminal ermöglicht es uns mit einfachen Text commands mit Programmen auf unserem Computer zu interagieren und das sehr gezielt und ohne die Maus und GUIs. 
Zum Beispiel benutzt Mensch fast immer ein Terminal mit einem Command um den Programmcode auf deinem Computer auszuführen. (Colab ist eine Ausnahme. Da haben wir Knöpfe.)

## 1.3.2. *Miscellaneous*
### Was sind Server?
Server sind einfach Computer, die praktisch permanent laufen und Programme ausführen.
### Was sind APIs?
Das Internet ist das ultimative Kommunikationstool. Programme übernehmen im Internet die gesamte Kommunikation. Damit Programme mit anderen Programmen kommunizieren können gibt es APIs (Application Programming Interfaces). Sie bilden die Schnittstelle um mit einander zu kommunizieren (Nach dem Schema: Wenn du das von mir willst, musst du so Fragen.) APIs haben die Welt revolutioniert. Jetzt brauchen nicht mehr Menschen mit Programmen interagieren, sondern sie können einfach untereinander interagieren. Zum Beispiel organisiert deine Wetter-App für dich die Daten der Wetterdienste von dessen Servern.
### Was sind Open-Source-Projekte?
Programmcode nennen wir open-source, wenn dieser frei eingesehen, modifiziert und geteilt werden kann. Die Welt baut so unglaublich doll auf open-source Projekten auf! (Hier kann auf jeden Fall noch deutlich mehr gesagt werden.)

### Was sind JSON und Markdown?

## 1.3.3. Lernen
Ein großer und wichtiger Teil vom programmieren ist es zu lernen. Niemand weiß alles. Alle lernen täglich Neues oder schauen Sachen nach. Im Internet die benötigen Informationen zu finden ist wohl die wichtigste Fähigkeit aller Programmierer\*innen. Viele schreckt gerade diese riesen große Menge an Infos ab. Gelernt wird Stück für Stück! Und alles kann immer und jeder Zeit nachgeschaut werden. Niemand liest von vorne bis hinten die Python Dokumentation sondern Mensch eignet sich eben das an, was gerade gebraucht wird. Learning by doing ist das Motto! Gelernt wird auch besonders davon, wie Andere das selbe Problem gelöst haben. Mensch hangelt sich einfach von Ast zu Ast.
### Wo/Wie finde ich Antworten?
Richtig Googlen lernen! ("..." in der Suche z.B.), stackoverflow, ChatGPT (Zum Beispiel für Fragen wie: "Was ist PATH?")
### Wo/Wie kann ich noch mehr lernen?
Ressourcensammlung, Youtube und co.
