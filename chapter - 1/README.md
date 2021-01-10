# TEKO - Webanwendung mit Python Django

## Vorbereitung
### Python
Um mit Python Django starten zu können, benötigst du Python. Installiere dazu [Python](https://www.python.org/) auf deinem Gerät. 


### PIP

### Django

## Aufbau dieses Tutorial
1. Vorbereitung
   1.1 Python
   1.2 PIP
   1.3 Django


## Begriffserklärung
### HTML
Die Hypertext Markup Language (HTML, englisch für Hypertext-Auszeichnungssprache) ist eine textbasierte Auszeichnungssprache zur Strukturierung elektronischer Dokumente wie Texte mit Hyperlinks, Bildern und anderen Inhalten. HTML-Dokumente sind die Grundlage des World Wide Web und werden von Webbrowsern dargestellt.

#### Beispiele
Um sich ein Bild zu machen, habe ich dir hier einige Beispiele von HTML beigefügt. Stell dir dabei vor, das HTML ohne eine formatierung zu machen nur für den Aubau eines Dokumentes verwendet wird. Etwa so wie du in Word ein Dokument schreibst ohne die Grösse, Position oder Farbe zu verändern.


##### Aufbau
Ein Text in einem Word kann Titel, Überschriften, Links, Tabellen sowie Absätze haben. Dies sieht in HTML so aus:

###### Überschriften
```html
<!-- Überschriften -->
<h1>Überschrift 1</h1>
<h2>Überschrift 2</h2>
<h3>Überschrift 3</h3>
<h4>Überschrift 4</h4>
<h5>Überschrift 5</h5>
<h6>Überschrift 6</h6>

<!-- Absatz -->
<p>
Das ist ein Absatz wie in einem Brief oder einem Word Dokument. Hier kannst du schreieben, solange du kein anderen Absatz benötigst. 
</p>

<!-- Links -->
<a href="www.teko.ch">TEKO </a>

```

Um diese Überschriften, Absätze und Links direkt bearbeiten zu können, müssen diese Elemente unter einem Namen ansprechbar sein. Das können wir in folgenden mit dem Tag selbst, einem Klassenname oder einer eindeutigen ID machen. 

```html
<!-- Klassen -->
<h1 class="ueberschrft">Das ist eine Überschrift<h1>
<h2 class="ueberschrft">Das ist eine Überschrift<h2>
<h3 class="ueberschrft">Das ist eine Überschrift<h3>

<!-- ID's -->
<h1 id="individueller_name3">Das ist eine Überschrift<h1>
<h2 id="individueller_name2">Das ist eine Überschrift<h2>
<h3 id="individueller_name3">Das ist eine Überschrift<h3>

```

Hier siehst du, dass später im CSS die Namen (ID, Klasse oder Tag) verwendet wird um diese Elemente direkt anzusprechen. 

```css
/* Tags in CSS ansprechen */
h1 {
    Schrift...
}

/* Klassenname direkt ansprechen */
.ueberschrift {

}

/* Tags mit jeweiligem Klassenname  in CSS ansprechen */
h1.ueberschrift {
    color: blue;
}
```

### CSS
Cascading Style Sheets (englische Aussprache für gestufte Gestaltungsbögen; kurz: CSS) ist eine Stylesheet-Sprache für elektronische Dokumente und zusammen mit HTML und JavaScript eine der Kernsprachen des World Wide Webs. Sie ist ein sogenannter „living standard“ (lebendiger Standard) und wird vom World Wide Web Consortium (W3C) beständig weiterentwickelt. Mit CSS werden Gestaltungsanweisungen erstellt, die vor allem zusammen mit den Auszeichnungssprachen HTML und XML (zum Beispiel bei SVG) eingesetzt werden.

### JS
JavaScript (kurz JS) ist eine Skriptsprache, die ursprünglich 1995 von Netscape für dynamisches HTML in Webbrowsern entwickelt wurde, um Benutzerinteraktionen auszuwerten, Inhalte zu verändern, nachzuladen oder zu generieren und so die Möglichkeiten von HTML und CSS zu erweitern. Heute findet JavaScript auch außerhalb von Browsern Anwendung, so etwa auf Servern und in Microcontrollern.

### jQuery
jQuery (auch jQuery Core) ist eine freie JavaScript-Bibliothek, die Funktionen zur DOM-Navigation und -Manipulation zur Verfügung stellt.

jQuery ist die meistverwendete JavaScript-Bibliothek. Jede zweite Website und 70 % der 10.000 meistbesuchten Websites nutzen jQuery (Stand: Januar 2018). jQuery wird in vielen Content-Management-Systemen und Webframeworks bereits mitgeliefert, zum Beispiel in Joomla, WordPress, MediaWiki oder Drupal.

### Python
Python ([ˈpʰaɪθn̩], [ˈpʰaɪθɑn], auf Deutsch auch [ˈpʰyːtɔn]) ist eine universelle, üblicherweise interpretierte, höhere Programmiersprache. Sie hat den Anspruch, einen gut lesbaren, knappen Programmierstil zu fördern. So werden beispielsweise Blöcke nicht durch geschweifte Klammern, sondern durch Einrückungen strukturiert.

Python unterstützt mehrere Programmierparadigmen, z. B. die objektorientierte, die aspektorientierte und die funktionale Programmierung. Ferner bietet es eine dynamische Typisierung. Wie viele dynamische Sprachen wird Python oft als Skriptsprache genutzt. Die Sprache weist ein offenes, gemeinschaftsbasiertes Entwicklungsmodell auf, das durch die gemeinnützige Python Software Foundation gestützt wird, die die Definition der Sprache in der Referenzumsetzung CPython pflegt.

# Quelle
[Wikipedia - HTML](https://www.python.org)
[Wikipedia - CSS](https://www.python.org)
[Wikipedia - JS](https://de.wikipedia.org/wiki/JavaScript)
[Wikipedia - jQuery](https://de.wikipedia.org/wiki/JQuery)


