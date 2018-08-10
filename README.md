# Willkommen zum Guide der FOI 12


## Inhaltsverzeichnis

- [Informationen](#informationen)
- [Standarts und Codingstyle](#standarts-und-codingstyle)
- [Programme die wir benutzen](#programme-die-wir-benutzen)
---

## Informationen

### Was ist das eigentlich hier ?
---

Das ist eigentlich alles ganz einfach. Hier werden unsere Klassenprojekte hochgeladen, sodass jeder auf diese zugreifen und mitarbeiten kann.



### Und wie funktioniert das ?
---

Wir benutzen die Software <em><b>Git</b></em> und die Plattform <em><b>GitHub</b></em>. Das sind zwei verschiedene Sachen mehr dazu gleich.

### Was genau ist Git ? 
---
<em>Git</em> ist ein <em><b>VCS</b></em> (Version Control System). Ein wat ?! Das ist sehr einfach zu erklären, stell dir vor du schreibst gerade an einem Dokument und du speicherst es regelmäßig ab, aber jetzt fällt dir auf, dass du auf eine alte Version des Dokuments zurückgreifen möchtest, weil du beim Bearbeiten ein alten Text gelöscht hast. Und genau das kann <em>Git</em>. Du versionierst sozusagen deine Datei und kannst auf alte Versionen zurückgreifen. Eine gute Einführung bekommst du [hier](https://git-scm.com/book/de/v1/Los-geht%E2%80%99s-Git-Grundlagen).

### Und was ist GitHub ?
---

GitHub ist einfach nur eine Plattform die das Versionieren von Git-Projekten einfach darstellt. Natürlich hat diese tolle Plattform weitaus mehr zu bieten dazu klick einfach [hier](https://guides.github.com/activities/hello-world/). Dort findest du ein kleines Tutorial, was dich in GitHub und Git einführt.

### Weitere Ressourcen 
---

[Git Buch](https://git-scm.com/book/en/v2)

Wenn du dich noch weiter informieren möchtest, kann ich dir das Git Buch empfehlen, du kannst es dir online kostenlos durchlesen oder auch runterladen. Das Ganze ist zwar in Englisch, es gibt aber auch eine deutsche Version, die leider aber noch nicht vollständig übersetzt wurde.
</br>

---
[Interaktives Tutorial](https://github.com/jlord/git-it-electron/releases/download/4.3.0/Git-it-Win-ia32.zip) 

Beim interaktiven Tutorial ladet Ihr ein kleines Programm runter, was euch alles über Git beibringt, was Ihr wissen müsst. Der folgende Link leitet zur Downloadseite weiter, klickt einfach auf Datei speichern. Ihr erhaltet ein ZIP-Archiv, welches entpackt wird. Danach wird die <b>.exe</b> ausführen, das war's.

---

## Standards und Codingstyle

### Git
---

Natürlich müssen wir bestimmte Regeln definieren, die aussagen wie geschrieben wird.
Wenn wir Änderungen commiten, gibt die Commit Message bitte in Englisch an. 

Beispiel: 
> git commit -m "Added some File"


### Codingstyle
---

Definiert aussagekräftige Variablen und Funktionsnamen.

Beispiel Falsch:
```c
    int x = 5;
    char y[30] = {"Das ist ein String"};
```


Beispiel Richtig:
```c
    int meinWert = 5;
    char meinSatz[30] = {"Das ist ein String"};
```

---

## Programme die wir benutzen

### Der Editor
Natürlich brauchen wir einen Editor, um unsere Quelltexte zu schreiben. Ich benutze dafür [Visual Studio Code](https://code.visualstudio.com). Einen sehr flexiblen und schnellen Code Editor. Ihr könnt ihn euch [hier](https://code.visualstudio.com/download) runterladen. Natürlich könnt Ihr auch andere Editoren benutzen. Alternativen sind [Atom](https://atom.io), [Sublime Text](https://www.sublimetext.com/) und [Notepad++](https://notepad-plus-plus.org/).

### Grafisches Git Interface
Ihr könnt gerne ein Grafisches Git Interface benutzen. Hier würde ich [GitKraken](https://www.gitkraken.com/) empfehlen, da wir darüber auch das Projektmanagement steuern. Alternativen sind [GitHub Desktop](https://desktop.github.com/) oder [Sourcetree](https://www.sourcetreeapp.com/).

### Projektmanagement
Für das Projektmanagement benutzen wir wie erwähnt [GitKraken](https://www.gitkraken.com/). Es bietet das Modul <em>Glo</em> was das Projektmanagement angenehm einfach macht.