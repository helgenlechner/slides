# Ziele
  * Firma vorstellen, da wir Mitarbeiter suchen.
  * Nützliches mitteilen: 
    * Entwicklungen/Erkenntnisse der letzten Jahre (Vogelperspektive, keine Details)
    * Informatik-Studium vs Realität
  * Ich will lernen. Ich bin neugierig. Wie macht ihr ....?
  * Aus dem Nähkästchen plaudern
    * Spaßiges.
    * Wandel in den letzten 15 Jahren.
  * Es wird ein subjektiver Vortrag.
  * Meine persönliche Perspektive - andere Mitarbeiter sehen das ggf ganz anders.

# me: Thomas Güttler
  * Baujahr 1976 - Heute 43 Jahre
  * Schule in Bayreuth
  * Informatikstudium 1996-2001 HTW Dresden.
  * Seit 2003 bei tbz-pariv. 15 Jahre.

# Firma: tbz-pariv
  * Mittelständiges Unternehmen
  * Gegründet 1993, 30 Mitarbeiter. 25 Jähriges wurde im Max-Louis in der Schönherrfabrik gefeiert.
  * Wir machen kaum Akquise. Zufriedenen Kunden (Energieversorger) machen Werbung für uns.
  * Software-Produkte: 
    * modarch:
      * seit: 2003
      * Summe: 38 Mio Belege gespeichert
      * 12 Produktivsysteme
    * caps:
      * 100 Mio Druckbelege pro Jahr
      * In ABAP/SAP Routinen schreiben um Daten auszugeben.
      * Eigene Layoutsprache. Wandeln zu Postscript/PDF.
      * Druck bei uns, beim Kunden oder Versand per Mail.
    * modwork:
      * Mein Steckenpferd
      * seit 2007
      * Summe: Pro Jahr 1.8 Mio Belege
      * 10 Produktivsysteme

# ReqDevOpSup
ReqDevOpSup, mehr als DevOp. Spannend trotz Alltag bei TBZ-PARV.

  * Requirement-Engineering
  * Development
  * Operation
  * Support
 
Eine Übersicht über unseren "Full-Stack" Arbeitsbereich.

Tools: Python, Django, PostgreSQL, Linux

## Requirement-Engineering
  * Requirement-Engineering beginnt bei uns nach der Auftragserteilung (Spaß)
    * Kunde will was, Chef und Kunde haben sich preislich irgendwie geeinigt. Los geht's.
    * Als Software-Entwickler steht man dann oft da: Hmm was soll da eigentlich gemacht werden.
    * Kann ich mal den Auftrag sehen?
    * EEE ... Da steht nur Brei. (klingt abwertend. Sehr abstrakt, sehr allgemein, kann alles und nichts sein)
    * Mich hat das früher rasend gemacht. Da hatte ich Puls: Das kann doch nicht sein. Diese fünf Zeilen sind nur Luft
    * nicht ansatzweise eine Spezifikation!
    * Studium - die reine Lehre - vs Realität
  * Was will der Kunde eigentlich?
  * Telefonate - Forschungsauftrag.
  * WebKo anstatt Dienstreisen. Gemeinsame Sicht auf ein Dokument oder eine Anwendung ist Gold wert.
    * :-) Anfangs Videokonferenz. Da konnte man sich mal zuwinken "Huhuh". Dann "oh, dass letzte Mal hatte Herr Schmidt aus Augsburg aber auch noch deutlich mehr Haare auf dem Kopf..."
  * Keine UML-Tools. Die abstrakte Symbolsprache ist so genial wie Esperanto. Prinzipiell toll, praktisch nutzlos.
  * Kardinalitäten klären!
  * Sequenzdiagramm als einfache Aufzählungsliste: 
    * Schritt1, Schritt2, Schritt3, ... 
    * Das geht per Wiki, Word, Mail ... kein VISO, kein Rational-Rose.
  * Falls viel geredet wird: Stift/Tastatur nehmen und Varianten notieren: V1, V2, V2
  * Glossar: Klare Begriffswelt. Inkl. Kardinalitäten.
  * Screenshots skizzieren mit Zettel und Stift.
  * Schlank und einfach.
  * Aktuell: 
    * Inzwischen denke ich auch: (früher Puls) grobe Spec reicht. Bisher gut damit gefahren (kaum Streitigkeiten zwischen uns und Kunden).
    * Nachteil: Kunde entwickelt während dem Projekt immer neue Ideen und mehr Wünsche.
    * Es fällt schwer den Schlussstrich zu ziehen. Man will als Dienstleister ja nett sein.
    * Jeder hat mehr oder weniger das Helfersyndrom - der Mensch ist ein soziales Wesen.
    * Hier meine Frage an euch: Mir fällt es schwer, anderen Kollegen auch: 
      * Das machen wir - das ist ein späterer neuer Auftrag.
      * Wie reagieren - ohne zu unfreundlich/hart zu sein.
  * Persönliche Einschätzung:
    * Die vagen und unklaren Aufträge haben aktuell mehr Vor- als Nachteile.
    * Insbesondere wenn es dann doch nichts wird mit dem Auftrag, dann wurde nicht viel Zeit der Spezifikation verschwendet.
  * Requirements-Engineering ein weites Feld und für mich gibt es hier noch viel zu lernen.

## Dev
  * Wenn man zB Klettern oder Langstreckenlauf macht ist klar: Man braucht passendes Material
    * Seil, Karabiner oder beim Laufen ordentliche Turnschuhe.
  * Bei Softwareentwicklung genauso: stabile und zuverlässige Werkzeuge zum Datenpogo
    * Django, Python, PostgreSQL, Linux, ABAP (SAP)
  * Entwicklung meist per PyCharm.
    * 1996 bis 2014 emacs (18 Jahre lang). Dann PyCharm
  * Django mit etwas jquery+Ajax.
    * Bisher noch ganz altertümlich-antik GET -> HTML zum Browser, Nutzer klimpert Daten rein, GET/POST, Webserver schickt wieder HTML zum Browser
    * Wandel zu jquery+Ajax.
  * Bisher noch keine "große" JS-Lib (Angular, React, Vue, ...).
    * Der Kunde hält uns bussy. Ständig neue Wünsche.
  * Aktuelles Forschungsthema: KI
    * Posteingang: 
      * Erkennen der Belegart anhand des Volltextindexes (tesseract)
      * Bisher wird die Belegart im Unternehmen unserer Kunden per Hand gesetzt.
      * Die Belegart könnte bald ganz gut erraten werden.
  * CI: Agil, Prod-Deploy selten älter als zwei Wochen. (modwork/Posteingang, Archiv ist das hohe Tempo nicht nötig)
    * Schön: Test und Deploy auf Knopfdruck (Noch Jenkins, ggf mal gitlab) stolz darauf sein.
    * Viele Tests. Alle Tests laufen zu lassen (vor Deploy) 30 Minuten.
    * Kaum Fehler im Produktivsystemen mehr - das war mal anders. Früher Aktion-Feuerwehr ssh zum Prod-Server --> Stressfrei (war Arbeit)
  * Aktuell ohne Container. Der Hype ist bei uns noch nicht angekommen.
      * Ein System ist ein einem Linux-User (modwork_eins_d, modwork_eins_q, modwork_eins_p)
      * Python Virtual-Env in $HOME des Nutzers.
      * Vorteil: Schlank und N Systeme auf einem Linux lauffähig. SSH in die Virtual-Env ist möglich.
      * Nachteil: Updates sind nicht atomar. Die Virtualenv wird durch Config-Management angepasst.
  * Deployment:
    * Konfigurationsmanagement: Salt. Fehlentscheidung. Lieber Ansible
    * Ggf theoretisch besser,  Aber: StackOverflow: 1k Fragen zu Salt, 10k Fragen zu Ansible.
    * Also: Salt ... dead-end.
  * Gelernt: Refuse to guess. 
    * Kein "schlaues" raten. 
    * Das geht schief und dann bist du Schuld. Aber in echt ist der unklare Input-Brei Schuld.
    * Auf klaren Input bestehen, damit Raten nicht nötig ist. Überengagierter junge Softwareentwickler. "haha, da fällt mir noch was ein - hier noch ein *Regex* .."
  * Gelernt: Konfig in DB, nicht in Textdateien.
    * Als Entwickler liebt man seine Versionsverwaltung. Kuschelig, weich, warm und super sicher. Nichts kann verloren gehen.
    * Aber: Konfig in Dateien im git können durch den Kunden schlecht angepasst werden. Also Web-GUI für sich und Kunden erstellen.
    * Darum Konfig in die DB.
  * Gelernt: Dealing with legacy code:
    * Quelltext funktioniert täglich beim Kunden.
    * Es gibt keinen mehr der alles kennt. Zu Umfangreich, zu alt.
    * Was tun, wenn man nicht durchblickt? looks_like_dead_code('2018-07-11 tguettler: topline looks unused?')

## Operation
  * Betreuen der Server
  * Freitag Abend will man mit seinen Freunden am Lagerfeuer sitzen, ein Bierchen trinken und sich Geschichten erzählen.
  * Darum ist es sehr uncool wenn Freitag kurz vor Schluss der Kunde anruft: Platte voll! Jetzt handeln - Freunden absagen wegen Aktion Feuerwehr .. NEIN
  * Nein, wir wollen den Freitagabend genießen und darum vorausschauend den Op-Teil von DevOp machen. 
  * Server laufen in der Regel in VM, die im Rechenzentrum des Kunden (Energieversorger) steht.
  * Für uns super bequem - fast so gut wie Schokoladeneis mit Mandelkrokant: 
    * Keine Verantwortung für Hardware oder Backup
    * Hardware ist doof, unzuverlässig, immer zu langsam, sperrig
  * Ein Server pro Kunde reicht. Kein Cloud-Spaß nötig, keine HV-Lösung. Web-Server und DB laufen auf dem gleichen Server.
  * Eigenes Tool für die Serverüberwachung.
    * Ähnlich wie Nagios (modcron): Check-Scripts werden aufgerufen. Falls 0, dann OK. 1 ist WARNING, 2 ist ERROR
    * Dezentrales System. Das Tool modcron läuft auf dem Server autonom. 
    * Alle N Minuten werden die Ergebnisse abgeholt.
  * Betreuen der Server wird nebenbei gemacht.
  * Wir leben glücklich ohne Charts.
    * Wir haben keine Kurven/Diagramme von Serverauslastung oder ähnliches.
    * Schöne Bildchen, tolle Progrämmchen die mir Kürvchen zeichnen.
    * Bisher nicht nötig.
    * Anschauen von Charts ist nicht produktiv - Lieber neues entwickeln.
    * Serverüberwachung ist ein notwendiges Übel. Darum nur wenig Herzblut und Aufmerksamkeit ... passt.
  * Kein Zentrales Log-Management.
    * Geht bisher ohne.
    * Logs werden auf dem Hosts ausgewertet.
    * Alles, was nicht LogLevel INFO ist, geht an den Serverüberwacher.

## Support
  * Betreuen der Nutzer
  * Wir haben keinen First-Level-Support.
  * Anrufe kommen direkt beim Entwickler an.
  * Wird abgefangen durch "Admin-vor-Ort".
  * Ziel: 
    * Konfig-GUIs entwickeln, damit der Kunde sich selber helfen kann.
    * Views programmieren, damit der Kunde seine Reports sieht
    * Dann weniger Anrufe.
  * Der Kunde wird trotzdem anrufen:
    * Punkt1: Immer freundlich bleiben.
    * Punkt2: Immer freundlich bleiben.
  * Nach dem freundlich bleiben:
    * Dem Kunden zeigen, wie die Konfig-GUI zu bedienen ist. Bsp Mail-Filter GUI. Ich bin in 2min fertig. So 10min. Aber es lohnt sich.
    * Und wenn der Kunde immer wieder wegen den gleichen Fragen anruft: freundlich bleiben. Geduld haben. 
    * Der Kunde bezahlt uns über den Wartungsvertrag. 
    * Das steht da nicht explizit drinnen - in dem Vertrag. Aber, das schließt aber dumme Fragen ein.
    * Typisches Beispiel: 
      * Mail kommen nicht in modwork an. Wir (modwork) ruft nur das pop3/IMAP Postfach ab.
      * Kunde (Leiter Kundenbetreuung) ruft an: Mail kommen nicht an. Ich prüfe: Aus meiner Sicht alles ok.
      * Mein Vorschlag: sprechen Sie doch mal mit Ihrem Mail-Admin der für das pop3 Konto zuständig ist.
      * ... Leiter Kundenbetreuung: Auch ja. Stimmt, die haben gestern ein Update gemacht ... gute Idee.
      * So einfach macht man Kunden glücklich ... ist doch schön.
      * Wenn täglich solche Unterbrechungen wären, dann müsste man handeln.
      * Aktuell ist die Anzahl der Interrupts ok.
  * Manchmal denkt man sich "der Kunde ist doof, der kann/weiß nicht mal ...". ABER: Das ist doch der Vorteil. Darum braucht er dich. Der Kunde will sich nicht mit Details herum ärgern.

# Open Source von uns
  * Open Source macht Sinn und Spaß.
  * Fragen+Antworten bei StackOverflow
  * kleine Patches zu Django oder anderen Libs.
  * github.com/tbz-pariv 
    * tbzuploader: generic http uploader
      * http "201 Created" wenn das 
    * FTP server context manager for testing ftp client code 

# Ausblick
  * Noch andere Bereiche: SAP-Schnittstellen, Layout, Druck, Kuvertierung, Scan, OCR
  * Zukunft
  * Machine-Learning: Automatisches Erkennen von Belegarten.
  * Ausbauen der Kompetenzen im SAP-Bereich (ABAP).
  * Gelernt:
    * Einzelne Aufträge bringen nicht viel. 
    * Besser: 
      * Ein Produkt mit Wartungs- und Lizenzkosten.
      * Also ein Produkt mehrfach bei mehreren Kunden einsetzen.
      * Anfangs aufpassen: Nicht zu viel für den ersten Kunden individuell programmieren - auf der anderen Seite ist der erste Kunde der wichtigste.
    * Vergleich: Man kann eine Kuh einmal schlachten, oder sehr lange melken. Zwei verschiedene Wege.
  * Früher:
    * Individuelle Softwareentwicklung. Nach dem Studium, da dachte ich mir, super, dass will ich tun. Alle Wünsch erfüllen.
    * Heute: Software, die nicht von mehreren Kunden genutzt wird, ist nur ein rosa Schleifchen. 
      * Fehleranfällig, "Dust in the wind", nicht erfolgreich.
      * Man will mehrere Menschen "glücklich machen": Individiuell vs Schema-F
  * JS vs SAP: 
    * SAP. Das ist bei unseren Kunden das zentrale Abrechnungssystem.
    * Verdammt viele Dinge wurden bei SAP grundlegend geklärt und das schon vor zwanzig Jahren.
    * ... vertiefen.
  * Chemnitzer-Linux-Tage am Python-Stand.
  * Mir macht die Arbeit bei tbz Spaß - Wer dabei sein will, bitte melden.

# Fragen
  * Auf Niveau von jquery bleiben oder "große" JS Lib nehmen?
    * Django wird degradiert zum Input/Output von Daten (Django-Rest-Framework). Zum Browser kommt JSON, Dort zaubert eine Lib ... großer Schritt
  * Mehr Code-Review und Pair-Programming?
  * Ihr auch ReqDevOpSup oder getrennte Arbeitsbereiche: 
    * Einer spricht mit Kunden, der Nächste programmiert, der nächste macht Serverüberwachung ...
  * Wie geht Akquise? Wir haben gute Produkte. Wie neue Kunden finden und gewinnen?
  * Pam noch nicht bei uns ... aber andere nette Menschen. Wie findet man einen Linux-Admin und/oder einen Web-Entwickler in Chemnitz?
  * Fragen aus dem Publikum?

# Quellen
  * https://github.com/guettli/programming-guidelines
