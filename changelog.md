# Shape Swipa Changelog

## 🇩🇪 Deutsch

### 0.7.1 (release) - 29.08.26
- Schriftart global angepasst (danke an nerdfonts.com); Schrift nun besser lesbar und Icons werden überall korrekt angezeigt
- Spielstatistik eingeführt
- Kombos sind nun unbegrenzt stapelbar, die Punktzahl ist jedoch auf das 10-Fache begrenzt
- Menü für Breitbild weiter angepasst
- Weitere Code Optimierungen

### 0.7.0 (release) - 14.08.26
- Bildschirmausrichtung orientiert sich jetzt am Endgerät
- UI Elemente für unterschiedliche Darstellungen angepasst (weitere Anpassungen folgen)
- Windows Export auf Itch.io bereit gestellt
- Linux Export auf Itch.io bereit gestellt
- Licht und Schatten für Desktop optimiert
- Highscore Anzeige im Spiel korrigiert, wenn anderes Spiel geladen wird
- Swipe und Kamera Bereich neu definiert
- Leuchtener Punkt zeigt Gefahr an der Grenze
- Beleuchtung für den Browser etwas optimiert
- Changelog URL nach Sprachwahl angepasst

### 0.6.4 (release) - 12.08.26
- Repariere Impuls zu anderen Objekten
- Minimaler Impuls etwas erhöht, damit beim Springen auch was sichtbar ist
- Tutorial Fehler behoben wo der Würfel mal die Zahl 2 bekommt

### 0.6.3 (release) - 11.08.26
- Schriftarten Update

### 0.6.2 (release) - 10.08.26
- Spieldaten beim beenden komplett zurücksetzen; Spielstände sind nicht betroffen
- Pyramiden Form hinzugefügt
- Verfügbare Objekte aufleuten lassen wenn mehr als 1 Objekt vorhadnen behoben

### 0.6.1 (release) - 08.08.26
- Nächste Zahl unter minimum Zahl behoben; bereits angezeigte nächste Zahlen werden dadurch beeinflusst
- Neues Objekt und nächste Zahl nun als Event ausgelagert für mehr und bessere Dynamik
- Rückgängig Button Logik als Event ausgelagert
- Spiel beenden Button in den Einstellungen ausgeblendet wenn das Spiel im Browser ausgeführt wird
- MSAA und SSAA deaktiviert
- Objekt Materialien (Farben) cachen
- Hintergrund auf einfarbig geändert (großer Performance Schub)
- Jeglicher Schatten auf Zahlen ignoiert für bessere Lesbarkeit
- Beta Hinweis auf Kapseln entfernt; läuft jetzt

### 0.6.0 (release) - 04.08.26
- Szenen Manager hinzugefügt für schnelleres Wechseln der Ansichten und schnellere Ladezeiten
- Markiere Kapseln als Beta, weil diese noch intabil in der Physik sind
- Kugeln und Kapseln haben mehr Kanten

### 0.5.12 (release) - 04.08.26
- Kugeln und Kapseln Formen vereinfacht für schnellere berechnung
- Flugbahnvorschau Cache für Performance
- Preloader optimiert für schnelleres Laden
- Objektexplosion als Event ausgelagert

### 0.5.11 (release) - 03.08.26
- Test mit weniger Komplexen Objekten (Kugeln und Kapseln)

### 0.5.10 (release) - 03.08.26
- Kleinere Bugfixes und Feintuning

### 0.5.9 (release) - 02.08.26
- Korrigiere Kollisionsmatrix für Kugeln und Kapseln
- Cache für Kollisionsmatrix hinzugefügt

### 0.5.8 (release) - 02.08.26
- Kollisionserkennung bei den Explosionen gründlich überarbeitet, so dass nun die Schockwelle spürbar realistischer ist
- Partikeleffekte aus dem Preloader entfernt, da nach dem Start bereits mehrere in den Speicher geladen werden
- Geistervorschau nach Umbau korrigert
- Zahlen auf Kugeln und Kapseln mehr hervorgehoben, damit sie besser lesbar sind
- Spielstände gefixt, damit keine leeren Spielstände erkannt werden

### 0.5.7 (release) - 02.08.26
- Weiteren Flag zu den Partikel hinzugefügt um mögliche Abstürze zu vermeiden

### 0.5.6 (release) - 01.08.26
- Partikel Pool erhöht und als Fallback einen neue Partikel Instanz hinzugefügt
- Partikel reseten sich nun selbst und nicht mehr von einem Objekt was eventuell nicht mehr vorhanden ist

### 0.5.5 (release) - 01.08.26
- Menüpunkte schweben nicht komplett aus dem Sichtbereich ist behoben
- Partikeleffekte Pool erzeugt für schnellere Ergebnisse
- Zahlen auf den Kugeln und Kapseln korrigiert
- Nicht mehr benötigte Shader entfernt
- Korrekte physikalische Eigenschaften auf Kugeln und Kapseln hinzugefügt

### 0.5.4 (release) - 31.07.26
- Game Over, wenn Objekt die rote Linie überquert wurde fälschlich entfernt ist behoben
- Sporadische Startprobleme behoben

### 0.5.3 (release) - 31.07.26
- Höchster Combo wird nun korrekt nach Punktzahl gemessen
- Partikel Anzahl von 300 auf 100 reduziert für bessere Performance
- Performance bei vielen Objekten verbessert indem Eigenschaften der Kollisionserkennung angepasst wurden
- Objekte (WÜrfel, Kugeln, Kapseln) als eigenständiges Objekt um Resourcen zu sparen
- Übersetzung für "BACK" Button hinzugefügt
- Code aufgeräumt (alte Scripte und Scenen entfernt)

### 0.5.2 (release) - 29.07.26
- Early Access verlassen
- Shader baking aktiviert (verbessertes laden der Shader)
- Android API Level auf 36 erhöht

### 0.5.1 (Early Access) - 24.10.25
- Schriftgröße der Zahlen auf Kugeln und Kapseln vergrößert
- Geistervorschau führt zu Spielabsturz bei Kugeln und Kapseln wurde behoben
- Highscores werden bei anderen Spielmodi außer Würfel nicht korrekt gespeichert behoben

### 0.5.0 (Early Access) - 23.10.25
- Objekte mit Kugeln und Kapseln erweitert
- Hauptmenü für weitere Spielmodi erweitert
- Highscores für wetiere Spielmodi erweitert
- Neues Spiel Buttons bekommen eine andere Farbe, wenn ein Spielstand vorhanden ist
- Zurücksetzen der minimalen und maximal Zahl bei Spielende
- Sprachdateien angepasst / erweitert

### 0.4.6 (Early Access) - 19.10.25
- Anpassung des Spielstandspeichers; aktuell laufendes Spiel kann einmalig nicht fortgeführt werden
  - Vorbereitung für weitere Spielmodi
- Objekt Vorschau oben mittig

### 0.4.5 (Early Access) - 16.10.25
- Sprachwahl in den Optionen verschoben und vom Hauptmenü entfernt
- Spiel kann abstürzen, wenn Geistervorschau über das Hauptmenü aktiviert wird wurde behoben
- Versionsinfo zum Ladebild hinzugefügt
- ZombAI.dev-Begrüßungsbildschirm hinzugefügt

### 0.4.4 (Early Access) - 15.10.25
- Fehler behoben das die Geistervorschau nicht mehr angezeigt wurde
- Schreibfehler im Tutorial behoben

### 0.4.3 (closed) - 15.10.25
- Kleinere Fehlerbehebungen im Tutorial
- Vorbereitung zum Early Access

### 0.4.2 (closed) - 14.10.25
- Tutorial Dialog scrollen überspringt nicht mehr den Text

### 0.4.1 (closed) - 14.10.25
- Objekt Schriftgröße dynamik angepasst, damit die Zahlen aus der Ferne besser zu erkennen sind

### 0.4.0 (closed) - 14.10.25
- Tutorial hinzugefügt
- Partikelexplosion hat zusätzlich eine visuelle Schockwelle
- Swipe Sprungradius um 5% angehoben und Stärke ganz leich erhöht
- Rückgängig Funktion angepasst
  - Start bei 250 Punkte kosten
  - Erhöhung um 1.6 (250, 400, 640, 1024, 1638, 2621, 4194, 5000)
  - Maximal 5000 Punkte kosten
- Code weiter aufgeräumt und optimiert

### 0.3.13 (closed) - 01.10.25
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

### 0.3.12 (closed) - 28.09.25
- Ladebildschirm für besseres Gameplay
- Partikeleffekte leuchten
- Partikel haben jetzt die Farbe des nächsten Objektes
- Minimaler impulse verringert, damit Indikatoren früher erscheinen
- Objekt Sprung verringert
- UI Schriftgröße vergrößert (im Spiel)
- Musik hinzugefügt
- Musik über den Optionen an- und ausschaltbar

### 0.3.11 (closed) - 27.09.25
- Aktualisiert auf Godot 4.5 stabil (RC2 offline getestet)
- Mobil Sensor wieder auf Portrait (Test nicht erfolgreich)
- Objekte entfernen, falls diese ungeplant das Level verlassen
- Explosionskraft leicht reduziert
- Highscores im Hauptmenü mit verbesserte Tabelle
- Optimiere Partikel Performance
- Optimierungen im Quellcode
- Swipe angepasst, so dass auch direkt nach links und rechts möglich ist

### 0.3.10 (closed) - 10.09.25
- Optionsmenü öffnen gefixt

### 0.3.9 (closed) - 10.09.25
- UI Optimierungen zwecks Ladezeiten und Performance
- Test Mobil Sensor und Vollbild Modus für API Vorgaben
- Test mit Schatten (sollte keine Auswirkungen auf Android haben)

### 0.3.8 (closed) - 09.09.25
- Randlose Anzeige deaktiviert
- Soundeffekte An / Aus beim Spielstart wieder korrekt herstellen
- HDR Hintergrund durch einfacheren Hintergrund ersetzt

### 0.3.7 (closed) - 07.09.25
- Korrekte Sprache wird direkt gespeichert, wenn die Systemsprache verwendet wird
  - Führt zu korrekter Nummern Anzeige wie z.b. 123.456 anstatt von 123456 bei deutscher Sprache
- Highscores beim Game Over jetzt auch mit korrekter Schreibweise
- Physik der Objekte wird jetzt fortlaufend berechnet
- Leichte Performance verbesserung durch weniger Leistung für den Panorama Hintergrund
- Abständer der unteren Buttons vergrößert für bessere Erreichbarkeit
- Punkte für doppelten Treffer (Objekt löst 2 Objekte gleichzeitig aus) erhöht
  - Augenzahl * Combo * 3 (vorher: Augenzahl * Combo *2)

### 0.3.6 (closed) - 07.09.25
- Aktualisiert auf Godot 4.5 RC1 wodurch bereits viele Probleme behoben wurden
- Wechsel zwischen Flugbahnvorschau und Geistervorschau in den Optionen
- Combo Icon bei höchsten Combo im Game Over Bildschirm nicht mehr "null"
- Übersetzung ändert jetzt alle Texte korrekt, wenn die Sprache gewechselt wird
- Highscores enthalten nun zusätzlich die Spielzeit, Objekte und höchste Nummer; alte Highscores haben für die zusätzlichen Werte eine 0
- Highscores über das Hauptmenü aufrufbar

### 0.3.5 (closed) - 03.09.25
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

### 0.3.4 (closed) - 24.08.25
- Übersetzung für die "Neues Spiel" Warnung ins englische inkl. der Buttons
- Sensor nicht länger auf Portrait fixiert
- Versuch Android API Level 35 vollständig zu unterstützen (Android 15)

### 0.3.3 (closed) - 23.08.25
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

### 0.3.2 (closed) - 18.08.25
- Kamera mit dynamischen Ziel verbessert, so dass wieder mehr vom Display genutzt wird.
- Berechnung der nächsten Zahl nicht mehr ganz so markant auf die Kleinste.

### 0.3.1 (closed) - 17.08.25
- Sprachwahl im Hauptmenü
- Kameraposition etwas nach hinten korrigiert

### 0.3.0 (closed) - 17.08.25
- Performance weiter verbessert 
- Akku Verbrauch verringert 
- Freie Kamera mit reset
- Undo Funktion
- Verbessere Kollisionserkennung
- Verbesserte Logik der Berechnung der nächsten Zahl; Priorität von klein nach groß
- Verbesserung in der Anzeige der Zahlen; wirklich immer aktuelle Werte
- Übersetzung nach Gerätesprache

### 0.2.1 (closed) - 14.08.25
- mehr Optionen in den Einstellungen
- weitere Performance optimierungen
- neues Icon

### 0.2.0 (closed) - 13.08.25
- Bessere Berechnung des nächsten Würfels (Objekts), damit auch niedrige - Zahlen öfter kommen können.
- Grafikoptimierungen
- Performance Optimierungen bis zu 150%
- Einige Fehlerbehebungen

### 0.1.1 (intern) - 10.08.25
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

### 0.7.1 (release) - 08/29/26
- Global font adjustment (thanks to nerdfonts.com); text is now more readable and icons are displayed correctly everywhere
- Game statistics added
- Combos can now be stacked indefinitely, but the score is capped at 10 times the base value
- Widescreen menu further adjusted
- Additional code optimizations

### 0.7.0 (release) - 08/14/26
- Screen orientation now adapts to the device
- UI elements adjusted for different display modes (further adjustments to follow)
- Windows export made available on Itch.io
- Linux export made available on Itch.io
- Lighting and shadows optimized for desktop
- Fixed high score display in-game when another game is loaded
- Swipe and camera areas redefined
- A glowing dot indicates danger at the edge
- Lighting slightly optimized for the browser
- Updated the changelog URL based on the language selection

### 0.6.4 (release) - 08/12/26
- Fixed the impulse effect on other objects
- Slightly increased the minimum impulse so that something is visible when jumping
- Fixed a tutorial bug where the cube would sometimes display the number 2

### 0.6.3 (release) - 08/11/26
- Fonts update

### 0.6.2 (release) - 08/10/26
- Completely reset game data upon exit; save files are not affected
- Added pyramid shape
- Fixed an issue where available objects would highlight when more than one object was present

### 0.6.1 (release) - 08/08/26
- Fixed an issue where the next number was set to a value below the minimum; this affects numbers that have already been displayed
- New object and next number are now handled as events for greater and improved dynamism
- Undo button logic is now handled as an event
- “Quit Game” button hidden in Settings when the game is running in a browser
- MSAA and SSAA disabled
- Caching object materials (colors)
- Background changed to solid color (major performance boost)
- All shadows on numbers ignored for better readability
- Beta notice on capsules removed; now running

### 0.6.0 (release) - 08/26/26
- Added Scene Manager for faster switching between views and faster load times
- Mark capsules as beta because their physics are still unstable
- Spheres and capsules now have more edges

### 0.5.12 (release) - 8/4/26
- Simplified sphere and capsule shapes for faster calculations
- Trajectory preview cache for improved performance
- Optimized preloader for faster loading
- Object explosion moved to an event

### 0.5.11 (release) - 8/3/26
- Test using less complex objects (spheres and capsules)

### 0.5.10 (release) - 8/3/26
- Minor bug fixes and fine-tuning

### 0.5.9 (release) - 8/2/26
- Fixed the collision matrix for spheres and capsules
- Added a cache for the collision matrix

### 0.5.8 (release) - 8/2/26
- Thoroughly overhauled collision detection for explosions, so the shockwave now feels noticeably more realistic
- Removed particle effects from the preloader, since several are already loaded into memory after launch
- Fixed ghost preview after restructuring
- Numbers on balls and capsules are now more prominent, making them easier to read
- Fixed save data so that empty save files are no longer detected

### 0.5.7 (release) - 8/2/26
- Added another flag to the particles to prevent potential crashes

### 0.5.6 (release) - 8/1/26
- Increased the particle pool and added a new particle instance as a fallback
- Particles now reset themselves rather than being reset by an object that may no longer exist

### 0.5.5 (release) - 8/1/26
- Fixed an issue where menu items did not completely disappear from view
- Pool now generates particle effects for faster results
- Corrected the numbers on the spheres and capsules
- Removed shaders that are no longer needed
- Added correct physical properties to spheres and capsules

### 0.5.4 (release) - 7/31/26
- Fixed an issue where the game would end when an object that had crossed the red line was incorrectly removed
- Fixed sporadic startup issues

### 0.5.3 (release) - 7/31/26
- The highest combo is now correctly calculated based on score
- Particle count reduced from 300 to 100 for better performance
- Performance with many objects has been improved by adjusting collision detection properties
- Objects (cubes, spheres, capsules) are now treated as separate objects to conserve resources
- Translation added for the “BACK” button
- Code cleaned up (old scripts and scenes removed)

### 0.5.2 (release) - 7/29/26
- leave early access
- Shader baking enabled (improved shader loading)
- Android API level increased to 36

### 0.5.1 (Early Access) - 10/24/25
- Increased font size of numbers on spheres and capsules
- Ghost preview leads to game crash with balls and capsules has been fixed
- Highscores are not saved correctly in game modes other than dice fixed

### 0.5.0 (Early Access) - 10/23/25
- Objects with spheres and capsules expanded
- Main menu expanded for additional game modes
- Highscores for wetiere game modes extended
- New game buttons get a different color when a score is available
- Reset the minimum and maximum number at the end of the game
- Language files adapted / extended

### 0.4.6 (Early Access) - 10/19/25
- Adjustment of the savegame memory; currently running game cannot be continued once
  - Preparation for further game modes
- Object preview top center

### 0.4.5 (Early Access) - 10/16/25
- Moved language selection in options and removed from main menu
- Fixed game crashing when ghost preview is activated from the main menu
- Added version info to the loading screen
- Added ZombAI.dev splash screen

### 0.4.4 (Early access) - 10/15/25
- Bug fixed that the ghost preview was no longer displayed
- Fix some typos in tutorial

### 0.4.3 (closed) - 10/15/25
- Minor bug fixes in the tutorial
- Preparation for Early Access

### 0.4.2 (closed) - 10/14/25
- Tutorial dialog scrolling no longer skips the text

### 0.4.1 (closed) - 10/14/25
- Object font size dynamically adjusted so that the numbers are easier to see from a distance

### 0.4.0 (closed) - 10/14/25
- Tutorial added
- Particle explosion has an additional visual shockwave
- Swipe jump radius increased by 5% and strength slightly increased
- Undo function adjusted
  - Start at 250 points cost
  - Increase by 1.6 (250, 400, 640, 1024, 1638, 2621, 4194, 5000)
  - Maximum cost 5000 points
- Code further cleaned up and optimized

### 0.3.13 (closed) - 10/1/25
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

### 0.3.12 (closed) - 9/28/25
- Loading screen for better gameplay
- Particle effects glow
- Particles now have the color of the next object
- Minimum impulse reduced so that indicators appear earlier
- Object jump reduced
- UI font size increased (in-game)
- Added music
- Music can be switched on and off via the options

### 0.3.11 (closed) - 9/27/25
- Updated to Godot 4.5 stable (RC2 tested offline)
- Mobile sensor back to portrait (test not successful)
- Remove objects if they leave the level unplanned
- Explosive power slightly reduced
- Highscores in main menu with improved table
- Optimize particle performance
- Optimizations in the source code
- Swipe adjusted so that direct left and right is also possible

### 0.3.10 (closed) - 9/10/25
- Open options menu fixed

### 0.3.9 (closed) - 9/10/25
- UI optimizations for loading times and performance
- Test mobile sensor and full screen mode for API defaults
- Test with shadows (should have no effect on Android)

### 0.3.8 (closed) - 9/9/25
- Borderless display deactivated
- Restore correct sound effects on / off at game start
- HDR background replaced by simpler background

### 0.3.7 (closed) - 9/7/25
- Correct language is saved directly when the system language is used
  - Leads to correct number display e.g. 123.456 instead of 123456 in German language
- Highscores at game over now also with correct spelling
- Physics of objects is now calculated continuously
- Slight performance improvement due to less performance for the panorama background
- Distance between the lower buttons increased for better accessibility
- Points for double hit (object triggers 2 objects at the same time) increased
  - Number of points * combo * 3 (previously: number of points * combo * 2)

### 0.3.6 (closed) - 9/7/25
- Updated to Godot 4.5 RC1 which has already fixed many issues
- Switch between trajectory preview and ghost preview in the options
- Combo icon at highest combo in Game Over screen no longer “null”
- Translation now changes all texts correctly when the language is changed
- Highscores now also contain the playing time, objects and highest number; old highscores have a 0 for the additional values
- Highscores can be accessed via the main menu

### 0.3.5 (closed) - 9/3/25
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

### 0.3.4 (closed) - 8/24/25
- Translation for the “New game” warning into English including the buttons
- Sensor no longer fixed to portrait
- Attempt to fully support Android API level 35 (Android 15)

### 0.3.3 (closed) - 8/23/25
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

### 0.3.2 (closed) - 8/18/25
- Camera with dynamic target improved so that more of the display is used again.
- Calculation of the next number is no longer quite as prominent on the smallest.

### 0.3.1 (closed) - 8/17/25
- Language selection in the main menu
- Camera position corrected slightly backwards

### 0.3.0 (closed) - 8/17/25
- Performance further improved
- Battery consumption reduced
- Free camera with reset
- Undo function
- Improved collision detection
- Improved logic for calculating the next number; priority from small to large
- Improvement in the display of the numbers; really always current values
- Translation according to device language

### 0.2.1 (closed) - 8/14/25
- more options in the settings
- further performance optimizations
- new icon

### 0.2.0 (closed) - 8/13/25
- Better calculation of the next cube (object), so that low numbers can come up more often.
- Graphics optimizations
- Performance optimizations up to 150
- Some bug fixes

### 0.1.1 (intern) - 8/10/25
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
