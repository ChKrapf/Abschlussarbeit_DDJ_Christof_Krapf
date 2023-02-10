# Abschlussarbeit CAS Datenjournalismus - "Wer ist der mächtigste Spielerberater im europäischen Fussball?"
 
Wer berät die je 100 Fussballer mit dem höchsten Marktwert aus den fünf grossen europäischen Ligen. 

## 0 Checkliste
Fragestellung: Spielerberater bewegen sich im Hintergrund der Fussballwelt. Welches sind die mächtigsten Player?
Relevanz: Es gibt Geschichten über mächtige Beraterinnen und Berater, beispielsweise im Zuge des Todes von Mino Raiola, sein Dossier übernahm mit Rafaela Pimenta eine der wenigen Frauen in diesem Geschäft. Eine Datenanalyse, wer die Hauptplayer sind, hat es noch nicht gegeben. 
Knackpunkt: Bei manchen Spielern ist die Beraterin oder Berater nicht öffentlich sichtbar, findet man heraus, welche Personen sich hinter den Firmenkonstrukten der Beraterfirmen verstecken?
Briefing-Person: Im Kurs mit Barnaby zwei Mal besprochen, sowohl Fragestellung als auch Methode. 

## 1 Datenquelle
Die Plattform www.transfermarkt.ch listet nahezu jeden (Profi)-Fussballer der Welt auf, dazu wird ein Marktwert geschätzt. Diese Marktwerte werden als relativ zuverlässig erachtet und auch in diversen Medien immer wieder verwendet. Jeder Spieler hat auf Transfermarkt ein Profil, darin enthalten sind diverse Informationen wie Klub, Alter, Nationalität etc. Auch der Spielerberater oder die Agentur ist besonders bei Spitzenspielern hinterlegt. 

## 2 Datenbeschaffung
Eine Liste mit den 100 wertvollsten Spielern der fünf grossen europäischen Fussballligen (Bundesliga, Premier League, La Liga, Serie A und Ligue 1) lassen sich auf Transfermarkt abrufen. Es ist jedoch nicht möglich, diese 100 Spieler auf einer Seite anzuzeigen, vielmehr werden je 25 Spieler pro Seite angezeigt. Mit einem Scraper wurde zunächst der Pfad für den Direktlink zum betreffenden Spielerprofil ausgelesen. Nach einer ersten Reinigung der Daten wurde die definitive URL für jeden Spieler generiert. So habe ich eine Liste mit 500 Links erstellt - zu den 500 wertvollsten Spielern Europas. Diese Liste habe ich gescrapt und dabei Name, Marktwert und Berater herausgelesen und daraus ein Dataframe erstellt. 

## 3 Datenanalyse
Transfermarkt hat verschiedene Hürden eingebaut, um das Scrapen der Webseite zu erleichtern. Bei einigen Spielern fand sich der Namen nicht im entsprechenden Feld des Profils. Das ist zwar unschön. Ich habe allerdings auf eine Korrektor verzichtet, da mich lediglich die Marktwerte und die Agenten interessieren. Weil es ein ziemlich kleiner Datensatz ist (mit 500 Positionen), habe ich die Datenanalyse im Excel vorgenommen. 

## 4 Publikation/weiteres Vorgehen
Geplant ist mit der Datenanalyse aufzuzeigen, welches die Hauptplayer sind, dieser Text wird mit einigen Grafiken versehen. Hauptstück wird ein Porträt über Rafaela Pimenta sein - sie ist die einzige Frau im Konzert der mächtigen Spielerberater. 

## 5 Aufwand
- Daten sichten, Methode prüfen: 2h
- Planung der Recherche: 1 h
- Programmierung Scraper: 12 Stunden
- Analyse der Daten: 2 Stunden
- Grafiken: 1 Stunde
Gesamtaufwand ohne Text schreiben: 18 Stunden
