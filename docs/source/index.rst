Vorwort
===========

.. epigraph::
    "There is this wonderful book - everybody should know it. I think it's the greatest book on music. It is a source of constant learning for us. Obviously, you couldn't be closer to the source."
    -- András Schiff 

Dies ist eine digitalisierte Version des ersten Bands von Carl Philipp Emanuel Bachs "Versuch über die wahre Art das Clavier zu spielen".
Das Buch ist ein interessantes zeitgeschichtliches Dokument, das sowohl unterhaltsam als auch aufschlussreich im Bezug auf die Musik und Aufführungspraxis des 18. Jahrhunderts ist.
Es gilt als die erste umfassende Klavierschule in deutscher Sprache.

Das Buch ist in zwei Teile gegliedert. Der erste Teil behandelt

- Prinzipien des Fingersatzes ("Von der Finger-Setzung")
- Verschiedene Arten der Verzierungen ("Von den Manieren")
- Interpretation und Ausdruck ("Vom Vortrage")

Der zweite Teil behandelt

- Harmonielehre
- Stimmführung
- Diverse Anmerkungen zu musikalischen Bausteinen (Vorschläge und Fermaten) und Formen (Rezitativ, freien Fantasie)

Form und Satz des Buches sind für moderne Leser:innen eher ungewohnt und gleichen anstatt einem gut sortierten Einführungswerk eher einer Sammlung von Notizen (gegliedert in nummerierte Paragraphen). So schreibt der Autor in der Vorrede:

.. epigraph::
    "Diejenigen irren sich, welche ein weitläufiges Lehrgebäude von mir erwartet haben; ich habe mehr Dank zu verdienen geglaubt, wenn ich das ziemlich schwere Clavierstudium durch kurze Lehrsätze, so viel möglich, leicht und angenehm machte."

.. Rubric:: Motivation

Ich habe diese Fassung erstellt, um das Buch breiter zugänglich zu machen.
Im Vergleich zu den Faksimile-Ausgaben ist sie wesentlich einfacher zu navigieren und verfügt über einen rudimentären Stichwortindex, den ich händisch erstellt habe.
Diese Fassung ist auch besser lesbar, da die Frakturschrift des Originals gewöhnungsbedürftig und die Notationsbeispiele oft im Sopranschlüssel gesetzt sind.

.. Rubric:: Inhaltsverzeichnis

.. toctree::
    :maxdepth: 8

    part1/00_Titelblatt
    part1/01_Vorrede
    part1/02_Einleitung
    part1/03_Fingersetzung
    part1/04_Manieren
    part1/05_Vortrag
    genindex

.. Rubric:: Dieses Projekt ist im Aufbau

Dieses Projekt ist noch nicht abgeschlossen. Es wurde im August 2024 begonnen. Einen Einblick über den Fortschritt gibt die `Liste der letzten Änderungszeitpunkte <https://readthedocs.org/projects/cpe-bach-versuch-uber-die-wahre-art-das-clavier-zu-spielen/builds/>`_. Dort wird jedes Mal ein neuer Eintrag vorgenommen, wenn ich Änderungen an den Texten vorgenommen habe, die lose auch im `GitHub-Repository <https://github.com/carlwitt/CPE-Bach-Clavier/commits/main/>`_ dokumentiert sind.
Viele Abschnitte sind bereits transkribiert, aber noch nicht korrekturgelesen, wie durch die jeweiligen Trennüberschriften gekennzeichnet.

.. _quellenangaben-und-danksagung:

.. Rubric:: Quellen, Urheberrecht und Danksagungen

Das Buch wurde in zwei Teilen veröffentlicht, zunächst im Selbstverlag des Autors.
Spätere Ausgaben des Buches kamen in den 1780er und 1790er Jahren heraus, und weitere folgten im 19. und 20. Jahrhundert.

Es gibt einige Digitalisate dieser verschiedenen Ausgaben im Netz, einige möchte ich hier erwähnen:

.. list-table::
   :header-rows: 1

   * - Quelle
     - Fassung
     - Sprache
     - Format
     - Lizenz
   * - `IMSLP <https://imslp.org/wiki/Versuch_über_die_wahre_Art_das_Clavier_zu_spielen,_H.868,_870_(Bach,_Carl_Philipp_Emanuel)>`_
     - Verschiedene Ausgaben als Faksimile-Scans
     - deutsch
     - PDF
     - Public Domain
   * - `archive.org <https://archive.org/details/BACHCarlPhilippeEmanuel.EssayOnTheTrueArtOfPlayingKeyboardInstruments/page/n3/mode/2up>`_
     - Übersetzung von William J. Mitchell
     - englisch
     - PDF, Text (mit Fehlern aus der Texterkennung)
     - Unklar
   * - `IMSLP <https://imslp.org/wiki/Versuch_über_die_wahre_Art_das_Clavier_zu_spielen,_H.868,_870_(Bach,_Carl_Philipp_Emanuel)>`_
     - Transkription von Jean-Pierre Coulon
     - französisch
     - PDF, LaTex
     - `Creative Commons (CC BY-SA 3.0) <https://creativecommons.org/licenses/by-sa/3.0/>`_
   * - `Deutsches Textarchiv <https://www.deutschestextarchiv.de/book/show/bach_versuch01_1759>`_
     - Sorgfältiges Digitalisat der zweiten Auflage
     - deutsch
     - HTML, Text, XML, TCF
     - Textlizenz `Creative Commons (CC BY-SA 4.0) <https://creativecommons.org/licenses/by-sa/4.0/>`_

Jean-Pierre Coulon hat eine qualitativ hochwertige transkribierte Version des Buches erstellt, in der auch die notierten Beispiele aufwändig transkribiert wurden. Diese verwende ich auch in meiner Fassung.

Das Deutschen Textarchiv bietet neben den Faksimiles auch mehrere Textfassungen, unter anderem eine mit normalisierter Orthographie.

.. Rubric:: Methodik

Ich habe eine Texterkennungssoftware auf die Erstausgabe der deutschen Faksimile-Scans angewendet.
Da die Texterkennung viele Fehler enthielt, habe ich als Grundlage für meine Fassung ein LLM (Large Language Model) verwendet, um die Fehler aus der Texterkennung auszubessern. 
Das funktioniert trotz der historischen Sprache erstaunlich gut, erfordert aber trotzdem viele händische Korrekturen. 
In diesem KI-gestützten Prozess wurde die alte Rechtschreibung behutsam modernisiert ("Antheil" wurde zu "Anteil"), allerdings nicht konsequent ("vereinet" wurde nicht zu "vereint"). 
Altmodische Satzstrukturen und Formulierungen wurden beibehalten ("Die Vollkommenheit desselben wäre leicht daraus zu erweisen"). 

An vielen Stellen habe ich auf die Fassung mit normalisierter Ortographie des Deutschen Textarchivs zurückgegriffen, da diese eine bessere Qualität als die automatisch erstellte Fassung des LLMs aufweist.

Ich habe alle Inhalte zwar Korrektur gelesen, es handelt sich hier aber keinesfalls um eine edierte Fassung.

Mir persönlich bereitet die Ausgabe in dieser Form Freude, da der ursprüngliche Charakter erhalten bleibt, der Text aber insgesamt besser lesbar wird.

Die Korrektur der Texte per Abgleich mit dem Faksimile ist ein relative aufwändiger Prozess, der noch einige Zeit in Anspruch nehmen wird.
Verbesserungen und Korrekturen können gerne über GitHub vorgeschlagen werden.


.. Rubric:: Über mich

Mein Name ist `Carl Witt <https://sites.google.com/view/carl-witt/work-and-education>`_.
Ich bin Amateurmusiker und erstelle diese Transkription als Freizeitprojekt ohne Anspruch auf Wissenschaftlichkeit oder Vollständigkeit erstellt.
