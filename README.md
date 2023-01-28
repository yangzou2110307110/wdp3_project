# CSS Container Queries

**Neues Konzept für Responsive Web Design**  
Container Queries sind eine neue Funktion in CSS, die ein Gamechanger im Bereich des Responsive Web Designs ist. Mit Container Queries kann man Komponenten einer Website so gestalten, dass sie sich je nach Größe des übergeordneten Elements anpassen.  

## Projektteam
- Christopher Nobis
- Yang Zou

## Grundstruktur der Präsentation
1.  Einleitung

    Das heutige Web besteht hauptsächlich aus Komponenten,
    wo der Einsatz von Media Queries Flexibilität vermissen lässt. Container Queries schaffen
    Abhilfe, indem sie Elemente nicht relativ zum Viewport, sondern relativ zu ihrem Container
    charakterisieren.

    **Ziel**: Kurze und prägnante Erklärung, warum Container Queries ein nützliches Feature sind.

2. Persönliche Erfahrung und Meinung zum Thema

    Primär soll aufgezeigt werden, dass der Einsatz von Media Queries im Widerspruch zur hierarchischen Struktur von CSS steht.

    **Ziel**: Beleuchtung des persönlichen Backgrounds und Darlegung eigener (frustrierender)
    Erfahrungen aus der Vergangenheit.


3. Einfaches Beispiel

    Idee: Mehrere Komponenten, die dynamisch in Abhängigkeit von der Größe ihres Containers ihre
    Farbe wechseln. Verwendung des Responsive Modes aus den DevTools.

    **Ziel**: Verdeutlichung der Unterschiede gegenüber Media Queries.

4. Komplexeres Beispiel

    Idee: Zwei identische Komponenten, die an unterschiedlichen Orten verwendet werden und sich daher
    unterschiedlich verhalten sollen (z. B. "stacked" vs. Anzeige als zwei Spalten). Container Queries
    sind in solchen Fällen viel flexibler als Media Queries.

    **Ziel**: Verdeutlichung der Vorteile gegenüber Media Queries.

5. Mögliche Probleme

    Aufzeigen von zu berücksichtigenden Aspekten bzw. möglichen Problemen, z. B. wenn Container
    Queries im Zusammenspiel mit Flexbox oder Grid verwendet werden.

    **Ziel**: Darstellung der Auswirkungen von Containern-Definitionen (z. B. auf die Breite von Flex-Kindelementen oder Collapsing Margins).

6. Abschließende Reflektierung

    Zum Abschluss werden die Vorteile von Container Queries den potenziellen Nachteilen kritisch gegenübergestellt.

    **Ziel**: Zusammenfassende "Key Takeaways" und Rückblick auf die gesammelten Erfahrungen.

## Ressourcen
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Container_Queries
- https://mxb.dev/blog/container-queries-web-components/
- https://kulturbanause.de/blog/css-container-queries-mit-container/
- https://ishadeed.com/article/container-queries-are-finally-here/
- https://www.youtube.com/watch?v=3_-Je5XpbqY 