# Lern-Bericht
Von Noel Keller

## Einleitung

In diesem Auftrag ging es darum, dass ein Benutzer von der InsecureApp in der Suchfunktion irgendeinen html befehl eingeben kann und so auf den Code von Programm "zugreifen" kann. Bei dem Beispiel, was ich im Lernbericht zeige ist das nicht wirklich eine schlimme Sache, aber durch diese Lücke kann ein Benutzer, welcher sich gut mit hacking auskennt, einfach das Programm zum Absturz bringen. 

## Was habe ich gelernt?

Ich habe gelernt, dass man bei Informationen von einem Eingabefeld zum Beispiel in jedem Fall escapen soll. Das heisst, es muss verhindert werden, dass der Browser normale Ausgaben-Daten als "Tags" interpretiert. 

## Beschreibung

![vor Escaping](https://user-images.githubusercontent.com/74292626/206466917-478c3f75-4776-41fe-ab9f-7f147303eeb0.gif)

--> Video vor Behebung

![bild lernbericht](https://user-images.githubusercontent.com/74292626/206473622-6956e2c4-7bf2-42b7-9207-b53a30111fd0.png)

Wie man oben auf dem Bild sehen kann, sollte man escape="true" setzten, damit damit eben "tags" nicht als "tags" intepretiert werden, sondern als normale Buchstaben. Die meisten Technologien Escapen standartgemäss, also kann man es in den meisten Fällen weglassen. Aber man sollte sich stets darüber informieren, weil es ist und bleibt eine Sicherheitslücke!

![nach Escaping](https://user-images.githubusercontent.com/74292626/206475645-a259659a-cce9-434b-becd-3a61d89702a0.gif)

## Verifikation

1. Wie Sie im Video sehen habe ich Sicherheitslücken in der InsecureApp kennengelernt.
2. Ausserdem habe ich gelernt, wie man die Sicherheitslücke beheben kann --> zweites Video

# Reflektion zum Arbeitsprozess

Was ist gut gelaufen --> Ich habe mich im Präsenzunterrich, wie auch im Online-Unterricht gut konzentrieren können und ich bin somit sehr zufrieden mit meiner Leistung.

Was ist nicht so gut gelaufen --> Da die Aufträge nicht leicht waren und manchmal auch schwer zu verstehen (Aufgabenstellung), habe ich nicht immer sofort begriffen, was zu tun ist und bin ein bisschen in Rückstand geraten.

**VBV**: Wenn ich nächstes Modul mal nicht begriffen habe, was zu tun ist oder wenn ich die Aufgabenstellung nicht richtig verstanden habe, dann frage ich nach, damit ich nicht wie dieses Modul in Rückstand gerate.
