# Shape Swipa Changelog

## 🇩🇪 Deutsch

### 0.4.4 (Early Access)
- Fehler behoben das die Geistervorschau nicht mehr angezeigt wurde
- Schreibfehler im Tutorial behoben

### 0.4.3
- Kleinere Fehlerbehebungen im Tutorial
- Vorbereitung zum Early Access

### 0.4.2
- Tutorial Dialog scrollen überspringt nicht mehr den Text

### 0.4.1
- Objekt Schriftgröße dynamik angepasst, damit die Zahlen aus der Ferne besser zu erkennen sind

### 0.4.0
- Tutorial hinzugefügt
- Partikelexplosion hat zusätzlich eine visuelle Schockwelle
- Swipe Sprungradius um 5% angehoben und Stärke ganz leich erhöht
- Rückgängig Funktion angepasst
  - Start bei 250 Punkte kosten
  - Erhöhung um 1.6 (250, 400, 640, 1024, 1638, 2621, 4194, 5000)
  - Maximal 5000 Punkte kosten
- Code weiter aufgeräumt und optimiert

### 0.3.13
- Swipe Sprungstärke wieder reduziert auf alten Wert
- Neue UI Buttons
- UI Animation
- FPS Anzeige entfernt
- Maximale FPS in den Einstellung zu Energiesparen umbenannt
- Einstellungen UI überarbeitet
- Songs aktualisiert
- Musik pausiert, wenn deaktiviert
- Punkteberechnung angepasst
  - Augenzahl wird jetzt immer gezählt
  - Combo: Augenzahl * (1.5 ^ Komboschritt)
  - Doppelter Treffer: (Augenzahl * Komboschritt) ^ Objekte
  - Combo auf maximal 10 begrenzt

### 0.3.12
- Ladebildschirm für besseres Gameplay
- Partikeleffekte leuchten
- Partikel haben jetzt die Farbe des nächsten Objektes
- Minimaler impulse verringert, damit Indikatoren früher erscheinen
- Objekt Sprung verringert
- UI Schriftgröße vergrößert (im Spiel)
- Musik hinzugefügt
- Musik über den Optionen an- und ausschaltbar

### 0.3.11
- Aktualisiert auf Godot 4.5 stabil (RC2 offline getestet)
- Mobil Sensor wieder auf Portrait (Test nicht erfolgreich)
- Objekte entfernen, falls diese ungeplant das Level verlassen
- Explosionskraft leicht reduziert
- Highscores im Hauptmenü mit verbesserte Tabelle
- Optimiere Partikel Performance
- Optimierungen im Quellcode
- Swipe angepasst, so dass auch direkt nach links und rechts möglich ist

### 0.3.10
- Optionsmenü öffnen gefixt

### 0.3.9
- UI Optimierungen zwecks Ladezeiten und Performance
- Test Mobil Sensor und Vollbild Modus für API Vorgaben
- Test mit Schatten (sollte keine Auswirkungen auf Android haben)

### 0.3.8
- Randlose Anzeige deaktiviert
- Soundeffekte An / Aus beim Spielstart wieder korrekt herstellen
- HDR Hintergrund durch einfacheren Hintergrund ersetzt

### 0.3.7
- Korrekte Sprache wird direkt gespeichert, wenn die Systemsprache verwendet wird
  - Führt zu korrekter Nummern Anzeige wie z.b. 123.456 anstatt von 123456 bei deutscher Sprache
- Highscores beim Game Over jetzt auch mit korrekter Schreibweise
- Physik der Objekte wird jetzt fortlaufend berechnet
- Leichte Performance verbesserung durch weniger Leistung für den Panorama Hintergrund
- Abständer der unteren Buttons vergrößert für bessere Erreichbarkeit
- Punkte für doppelten Treffer (Objekt löst 2 Objekte gleichzeitig aus) erhöht
  - Augenzahl * Combo * 3 (vorher: Augenzahl * Combo *2)

### 0.3.6
- Aktualisiert auf Godot 4.5 RC1 wodurch bereits viele Probleme behoben wurden
- Wechsel zwischen Flugbahnvorschau und Geistervorschau in den Optionen
- Combo Icon bei höchsten Combo im Game Over Bildschirm nicht mehr "null"
- Übersetzung ändert jetzt alle Texte korrekt, wenn die Sprache gewechselt wird
- Highscores enthalten nun zusätzlich die Spielzeit, Objekte und höchste Nummer; alte Highscores haben für die zusätzlichen Werte eine 0
- Highscores über das Hauptmenü aufrufbar

### 0.3.5
- Erstellt mit Godot 4.5 beta 7 um aktuelle PlayStore Anforderungen zu entsprechen
  - Bekannte Performance Probleme
- Senke Objekt Berührungslautstärke (nicht das plop)
- Combo Icon bei höchsten Combo nicht mehr "null"
- Kleine Linien mittig am Bildschirmrand für Swipe und Kamera Trennung
- ScriptManager für dynamisches Laden von Scripts erstellt
- Neue Flugbahn Anzeige
- Tada Sound, wenn ein Objekt mindestens 2 andere Objekte auf einmal entfernt
- Changelog in den Optionen verlinkt
- Sensor zurück zu Portrait (Landscape desktiviert)

### 0.3.4
- Übersetzung für die "Neues Spiel" Warnung ins englische inkl. der Buttons
- Sensor nicht länger auf Portrait fixiert
- Versuch Android API Level 35 vollständig zu unterstützen (Android 15)

### 0.3.3
- UI aufgeräumt
- UI Elemente in eigenständige Prozesse ausgelagert
- Undo Button erzeugt kein Undo: behoben
- Undo Button erscheint nur, wenn Undo möglich
- Anzeige der Spielzeit
- Anzeige der Combos mit Punkten
- Game Over Screen zeigt nun auch Combos und Spielzeit an
- Fehler behoben, wenn Spielwürfel zerstört wird; erzeugt jetzt Game Over
- Sounds fürs ploppen und berühren eingebaut
- Sounds in den Optionen an und aus schaltbar
- kleinere Bugs gefixt
- UI benötigt neues Spiel für korrekte Darstellung

### 0.3.2
- Kamera mit dynamischen Ziel verbessert, so dass wieder mehr vom Display genutzt wird.
- Berechnung der nächsten Zahl nicht mehr ganz so markant auf die Kleinste.

### 0.3.1
- Sprachwahl im Hauptmenü
- Kameraposition etwas nach hinten korrigiert

### 0.3.0
- Performance weiter verbessert 
- Akku Verbrauch verringert 
- Freie Kamera mit reset
- Undo Funktion
- Verbessere Kollisionserkennung
- Verbesserte Logik der Berechnung der nächsten Zahl; Priorität von klein nach groß
- Verbesserung in der Anzeige der Zahlen; wirklich immer aktuelle Werte
- Übersetzung nach Gerätesprache

### 0.2.1
- mehr Optionen in den Einstellungen
- weitere Performance optimierungen
- neues Icon

### 0.2.0
- Bessere Berechnung des nächsten Würfels (Objekts), damit auch niedrige - Zahlen öfter kommen können.
- Grafikoptimierungen
- Performance Optimierungen bis zu 150%
- Einige Fehlerbehebungen

### 0.1.1
Erste Shape-Swipa Version mit folgenden Features
- Würfel Objekt
- Ghost Vorschau bei Swipe
- Glow für verfügbare Treffer nach 5 Sekunden
- Score und Highscore
- Speichern und fortfahren eines Spielstandes
- Daten werden in App gespeichert
- Datenschutz hinzugefügt

---

## 🇬🇧 English

### 0.4.4 (Early access)
- Bug fixed that the ghost preview was no longer displayed
- Fix some typos in tutorial

### 0.4.3
- Minor bug fixes in the tutorial
- Preparation for Early Access

### 0.4.2
- Tutorial dialog scrolling no longer skips the text

### 0.4.1
- Object font size dynamically adjusted so that the numbers are easier to see from a distance

### 0.4.0
- Tutorial added
- Particle explosion has an additional visual shockwave
- Swipe jump radius increased by 5% and strength slightly increased
- Undo function adjusted
  - Start at 250 points cost
  - Increase by 1.6 (250, 400, 640, 1024, 1638, 2621, 4194, 5000)
  - Maximum cost 5000 points
- Code further cleaned up and optimized

### 0.3.13
- Swipe jump strength reduced to old value again
- New UI buttons
- UI animation
- Removed FPS display
- Maximum FPS in the settings renamed to energy saving
- Settings UI revised
- Songs updated
- Music paused when disabled
- Point calculation adjusted
  - Score is now always counted
  - Combo: Number of points * (1.5 ^ combo step)
  - Double hit: (number of points * combo step) ^ objects
  - Combo limited to a maximum of 10

### 0.3.12
- Loading screen for better gameplay
- Particle effects glow
- Particles now have the color of the next object
- Minimum impulse reduced so that indicators appear earlier
- Object jump reduced
- UI font size increased (in-game)
- Added music
- Music can be switched on and off via the options

### 0.3.11
- Updated to Godot 4.5 stable (RC2 tested offline)
- Mobile sensor back to portrait (test not successful)
- Remove objects if they leave the level unplanned
- Explosive power slightly reduced
- Highscores in main menu with improved table
- Optimize particle performance
- Optimizations in the source code
- Swipe adjusted so that direct left and right is also possible

### 0.3.10
- Open options menu fixed

### 0.3.9
- UI optimizations for loading times and performance
- Test mobile sensor and full screen mode for API defaults
- Test with shadows (should have no effect on Android)

### 0.3.8
- Borderless display deactivated
- Restore correct sound effects on / off at game start
- HDR background replaced by simpler background

### 0.3.7
- Correct language is saved directly when the system language is used
  - Leads to correct number display e.g. 123.456 instead of 123456 in German language
- Highscores at game over now also with correct spelling
- Physics of objects is now calculated continuously
- Slight performance improvement due to less performance for the panorama background
- Distance between the lower buttons increased for better accessibility
- Points for double hit (object triggers 2 objects at the same time) increased
  - Number of points * combo * 3 (previously: number of points * combo * 2)

### 0.3.6
- Updated to Godot 4.5 RC1 which has already fixed many issues
- Switch between trajectory preview and ghost preview in the options
- Combo icon at highest combo in Game Over screen no longer “null”
- Translation now changes all texts correctly when the language is changed
- Highscores now also contain the playing time, objects and highest number; old highscores have a 0 for the additional values
- Highscores can be accessed via the main menu

### 0.3.5
- Created with Godot 4.5 beta 7 to meet current PlayStore requirements
  - Known performance issues
- Lower object touch volume (not the plop)
- Combo icon at highest combo no longer “zero”
- Small lines in the center of the screen for swipe and camera separation
- ScriptManager created for dynamic loading of scripts
- New trajectory display
- Tada sound when an object removes at least 2 other objects at once
- Changelog linked in the options
- Sensor back to portrait (landscape deactivated)

### 0.3.4
- Translation for the “New game” warning into English including the buttons
- Sensor no longer fixed to portrait
- Attempt to fully support Android API level 35 (Android 15)

### 0.3.3
- UI tidied up
- UI elements moved to independent processes
- Undo button does not generate undo: fixed
- Undo button only appears if undo is possible
- Display of playing time
- Display of combos with points
- Game over screen now also shows combos and game time
- Bug fixed when game cube is destroyed; now generates Game Over
- Added sounds for popping and touching
- Sounds can be switched on and off in the options
- Minor bugs fixed
- UI requires new game for correct display

### 0.3.2
- Camera with dynamic target improved so that more of the display is used again.
- Calculation of the next number is no longer quite as prominent on the smallest.

### 0.3.1
- Language selection in the main menu
- Camera position corrected slightly backwards

### 0.3.0
- Performance further improved
- Battery consumption reduced
- Free camera with reset
- Undo function
- Improved collision detection
- Improved logic for calculating the next number; priority from small to large
- Improvement in the display of the numbers; really always current values
- Translation according to device language

### 0.2.1
- more options in the settings
- further performance optimizations
- new icon

### 0.2.0
- Better calculation of the next cube (object), so that low numbers can come up more often.
- Graphics optimizations
- Performance optimizations up to 150
- Some bug fixes

### 0.1.1
First Shape Swipa version with the following features
- Cube object
- Ghost preview on swipe
- Glow for available hits after 5 seconds
- Score and highscore
- Save and continue a score
- Data is saved in the app
- Data protection added

---

translated with [https://www.deepl.com/](https://www.deepl.com/)
