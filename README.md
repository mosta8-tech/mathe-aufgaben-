# Kapitel 17 – Abstandsprobleme: Übungsaufgaben

Interaktive Übungswebsite zu **Kapitel 17 (Abstandsprobleme)** der
[Vektorrechnung-Zusammenfassung](https://erikdahlmann.github.io/Vektorrechnung-Zusammenfassung/).
Die Seite greift Stoff, Notation und Gestaltung der Zusammenfassung auf und ergänzt sie um 20 Aufgaben
mit Sofortkorrektur, Tipps und ausführlichen Musterlösungen.

## Inhalt

Eine kompakte Formelsammlung zu allen vier Abstandsfällen samt Entscheidungstabelle
(„welche Frage verlangt welches Verfahren?“) und anschließend fünf Aufgabenblöcke:

| Block | Thema | Aufgaben | Verfahren |
|---|---|---|---|
| A | Abstand Punkt – Ebene | 5 | Hesse'sche Normalenform, Lotfußpunktverfahren, Spiegelpunkt, HNF ohne Betrag (Seitenlage) |
| B | Abstand Punkt – Gerade | 4 | Laufpunkt-Bedingung, Hilfsebene, Flächenformel mit dem Kreuzprodukt |
| C | Abstand paralleler Geraden | 3 | Kollinearitätsprüfung, Punktprobe, Rückführung auf Fall B |
| D | Abstand windschiefer Geraden | 4 | Spatprodukt, Hilfsebene + HNF, geschlossener Vektorzug mit LGS |
| E | Vermischtes & Anwendungen | 4 | Sachaufgaben (Flugbahnen, Dachfläche) und Fragen zur Verfahrenswahl |

Die Aufgaben sind nach Schwierigkeit gekennzeichnet (leicht / mittel / schwer) und decken bewusst auch
die typischen Stolperstellen ab: Vorzeichenfehler in der HNF, identische statt echt paralleler Geraden,
das Mischen von Zähler- und Nennervektor in der Flächenformel und die Fehlvorstellung,
windschiefe Geraden könnten den Abstand 0 haben.

## Funktionen

- **Sofortkorrektur** für Zahlen-, Vektor-, Mehrfeld- und Multiple-Choice-Eingaben; bei mehrteiligen
  Aufgaben wird benannt, welcher Teil noch nicht stimmt
- **Eingabekomfort:** Komma- und Punktschreibweise sowie Brüche wie `9/2` werden akzeptiert
- **Dreistufiges Lernen:** erst selbst rechnen, dann Tipp, dann ausführliche Musterlösung mit allen Zwischenschritten
- **Fortschrittsanzeige** gesamt und pro Block, lokal im Browser gespeichert (localStorage)
- **Filter** nach Block und nach ungelösten Aufgaben
- **Druckansicht:** Bedienelemente werden beim Drucken ausgeblendet

## Technik

Eine einzige, in sich geschlossene Datei: `index.html`.

- kein Build-Schritt, kein Framework, kein Server nötig – die Datei genügt
- [MathJax 3](https://www.mathjax.org/) (CDN) für den Formelsatz, Source Serif 4 als Schrift
- alle Formeln der Seite wurden mit dem TeX-Parser von MathJax auf Syntaxfehler geprüft,
  alle Rechenergebnisse zusätzlich numerisch nachgerechnet

## Nutzung

`index.html` im Browser öffnen. Für Formelsatz und Schrift wird eine Internetverbindung benötigt (CDN).

Als Website veröffentlichen: in den Repository-Einstellungen unter **Settings → Pages** als Quelle
den Branch wählen, der diese Datei enthält (Ordner `/root`). Die Seite ist danach unter
`https://<benutzername>.github.io/mathe-aufgaben-/` erreichbar.
