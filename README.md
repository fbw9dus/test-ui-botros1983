# Phone company site
Projekt für Test im UI Modul

- Schreib das HTML und CSS für die abgebildete Seite
- Die Seite soll responsive sein und sich auf unterschiedlichen Bildschirmbreiten entsprechend der Abbildungen verhalten.

## Anforderungen HTML
- Die Seite soll auf dem Handy bzw. im DevTools-Simulator nicht kleiner skaliert/kleiner gezoomt werden.
- Einrückung der Kinder-Elemente im Code
- Korrekte Dateipfade
- Beschreibende Klassen- oder ID-Namen für Elemente vergeben
## Anforderungen CSS
- Selektoren so speizifisch schreiben, dass unabsichtliche Auswirkungen auf andere Teile der Seite vermieden werden.
- Kein float zum Anordnen von Block-Elementen
- Style-Werte, die sowieso standardmäßig vom Browser gesetzt werden, nicht im CSS deklarieren.

![](drafts/mobile.JPG)
![](drafts/tablet.JPG)
![](drafts/desktop.JPG)
![](drafts/desktop-button-hover.JPG)

###   40/60 Punkten
#### Punktabzüge für:
- [x] (10) Elemente passen sich nicht an Fensterbreite an
```diff
- Kein Abstand des Formulars zum Fensterrand bei mobile
- Scrollleiste am unteren Fensterrand
```
- [_] (10) Tags nicht geschlossen oder falsch verschachtelt
- [_] (5) Block-Tag in Inline-Tag
- [_] (5) Kinder-Tags im Code nicht eingerückt
- [_] (10) Zweckfremde Tags verwendet
- [x] (5) Fehlende essetielle Tags (z.B. Meta-Tags)
```diff
- title-Tag fehlt
- <meta charset="UTF-8"> fehlt
```
- [_] (5) Falsche Datei-Pfade
```diff
- Die Bilder werden nur geladen, wenn die Seite in einem (Live-)Server läuft. Das ist kein Fehler.
```
- [x] (5) CSS-Selektoren, die bei Änderungen im HTML sehr leicht fehlschlagen können
```diff
- Der Selektor h1+p ist sehr unzuverlässig, da er nicht mehr funktionieren würde, sobald es mehrere Paragraphen gibt oder ein anderes Element nach h1 steht
```
- [_] (5) Fehlende essentielle Tag-Attribute
