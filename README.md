# Escape-Room: Basquiats Atelier

Digitaler Escape-Room zu Leben und Werk von Jean-Michel Basquiat für den Kunstunterricht in Jahrgang 6 (Partnerarbeit, ca. 45 Minuten).

## Inhalt

Sieben Räume: Kindheit in Brooklyn, SAMO©, Zeitstrahl, Bildsymbole, Galerie, Bilddetektive, Ruhm und Vermächtnis. Jeder gelöste Raum liefert einen Buchstaben, mit dem Lösungswort öffnet sich die Ateliertür. Es gibt einen Timer, Tipps (werden gezählt) und eine Abschlussseite. Der Spielstand wird im Browser gespeichert; „Spiel neu starten“ unten auf der Seite setzt ihn zurück.

## Passwort

Der Spielinhalt ist verschlüsselt (AES-256, Schlüssel aus dem Passwort per PBKDF2). Ohne das richtige Passwort zeigt die Seite nur die Eingabemaske. Das Passwort gibt die Lehrkraft im Unterricht bekannt. Nach der Eingabe bleibt der Zugang bis zum Schließen des Browser-Tabs bestehen.

## Nutzung

1. `escape-room.html` herunterladen.
2. Daneben einen Ordner `bilder/` mit den acht Werkabbildungen anlegen:
   `ohnetitel1981.jpg`, `johnnypump.jpg`, `krone.jpg`, `hollywood.jpg`, `geschichte.jpg`, `polizist.jpg`, `ohnetitel1982.jpg`, `prokopf.jpg`
3. Die HTML-Datei im Browser öffnen und das Passwort eingeben. Sie läuft auch offline.

Fehlt eine Bilddatei, zeigt der Escape-Room an ihrer Stelle einen Hinweis.

## Urheberrecht

Die Werke von Jean-Michel Basquiat sind urheberrechtlich geschützt (© Estate of Jean-Michel Basquiat). Die Abbildungen gehören deshalb nicht in dieses öffentliche Repository und sind über `.gitignore` ausgeschlossen. Sie werden nur lokal zur Veranschaulichung im Unterricht genutzt (§ 60a UrhG). Kronen-, Schädel- und Skelettgrafiken im Spiel sind eigene Zeichnungen.
