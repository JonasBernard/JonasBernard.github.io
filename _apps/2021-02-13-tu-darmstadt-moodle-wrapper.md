---
layout: article
title: TU-Darmstadt Moodle Wrapper
permalink: /tu-darmstadt-moodle-wrapper/
external_url: https://f-droid.org/de/packages/de.jonasbernard.tudarmstadtmoodlewrapper/

cover: /assets/img/tu-darmstadt-moodle-wrapper/ic_launcher.png
header:
  theme: dark
  background: transparent
article_header:
  type: cover
  theme: light
  image:
    gradient: 'linear-gradient(135deg, #26c6da66, #d81b6066)'
    src: /assets/img/tu-darmstadt-moodle-wrapper/banner.png

comment: true
key: apps-moodle-wrapper
---

Die App "TU-Darmstadt Moodle Wrapper" ist eine Android App, mit der sich Moodle-Links der TU Darmstadt direkt in der Moodle App öffnen lassen.


<!--more-->

Man muss dazu nichts weiter tun, als die App bei F-Droid herunterzuladen und zu installieren.

### Wie funktioniert die App?

Apps können bei Android eintragen, dass sie in der Lage sind, bestimmte Webseiten aufzurufen.
Welche Webseiten in der App geöffnet werden können, wird dann zum Beispiel anhand der URL bestimmt.
Wird dann in einer App ein Link angelickt, überprüft Android, welche Apps diesen Link öffnen können, und entscheidet
selbstständig, welche App geöffnet wird. Wenn mehrere Apps gefunden werden, die Android öffnen könnte,
wird der Nutzer gefragt, was passieren soll.

Die Entwickler von Moodle kennen die URLs der Moodle Installationen (z.B. moodle.tu-darmstadt.de) nicht, und können diese
daher auch nicht in die Apps einprogrammieren.

Die TU-Darmstadt Moodle Wrapper App deklariert bei Android, dass sie in der Lage ist, moodle.tu-darmstadt.de (und einige weitere URLs)
zu öffnen. Wenn ein Moodle-Link dann angeklickt wird, macht die App nichts weiter, als einfach Moodle zu öffnen.
Dabei wird dann noch die aufgerufene Seite (z.B der Foreneintrag oder die Startseite) an die Moodle-App übermittelt.

Genauere Informationen findest du bei [GitHub](https://github.com/JonasBernard/TU-Darmstadt-Moodle-Wrapper) und hier:
<p>
<a class="button button--primary button--rounded" href="{{ page.external_url }}" target="_blank">
  <i class="fas fa-download"></i>
  Hier geht's zum Download!
</a>
</p>
