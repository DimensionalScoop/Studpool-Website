---
layout: page
title: Fernzugriff
---

## Per SSH
Der Server ist im Internet über SSH erreichbar; ihr könnt euch von einem beliebigen PC mit Internetverbindung auf dem Server einloggen.
Unter Linux und Mac im Terminal:  
`$ ssh -Y <user>@stud.physik.tu-dortmund.de`  

Unter Windows benötigt man einen SSH-Client, etwa [PuTTY](http://www.putty.org/). Mit diesen Einstellungen kann man sich dann verbinden:  
![](/assets/putty.png)  

### Screen
Hilfreich, etwa wenn man lange Berechnungen durchführen will, ist `screen`.
Wenn man eingeloggt ist kann man im Terminal  
`$ screen`  
eingeben, um einen screen zu öffnen. Dort stößt man dann z.B. die Berechnung an und drückt dann `Ctrl+A` und dann `D`. Dann kann man sich ausloggen, während die Berechnung im Hintergrund weiterläuft.  

Um später wieder auf den screen zuzugreifen, gibt man  
`$ screen -R`  
ein.

## Per x2go
Wenn man sich den [x2go Client](http://wiki.x2go.org/doku.php) herunterlädt (oder unter z.B. Ubuntu das Paket mit `$ sudo apt-get install x2goclient` installiert), hat man einen graphischen Fernzugriff. D.h. man kann auch von zu Hause aus so wie im Pool auf die Desktopoberfläche zugreifen.
