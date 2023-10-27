# Bachelorarbeit: Vergleich von Gradienten- und Trust-Region-Verfahren für Unrestringierte Optimierungsprobleme

Dieses GitHub-Repository enthält meine Bachelorarbeit und die zugehörigen Mathematica-Codes, die als Teil meiner Abschlussarbeit an der Technischen Hochschule Mittelhessen erstellt wurden.

**Verfasser:** Büsra Karaoglan  
**Akademischer Grad:** Bachelor of Science  
**Abgabedatum:** 14. Februar 2017  
**Referent:** Prof. Dr. Rigger  
**Korreferent:** Prof. Dr. Müller  

## Inhalt der Arbeit

Das Ziel dieser Arbeit war die Lösung unrestringierter nichtlinearer Optimierungsprobleme. Dazu wurden zwei geeignete numerische Verfahren, das Gradientenverfahren und das Trust-Region-Verfahren, vorgestellt und miteinander verglichen. Im Folgenden sind die Hauptpunkte der Arbeit zusammengefasst:

**Gradientenverfahren:** 
Dieses Verfahren zur näherungsweisen Lösung von unrestringierten Optimierungsproblemen setzt sich aus einer Richtungs- und einer Schrittweitenstrategie zusammen. Von einer aktuellen Näherung ausgehend, wird in eine Abstiegsrichtung gegangen. Die Schrittweite wird in dieser Arbeit mit der Armijo-Regel festgelegt.

**Trust-Region-Verfahren:** 
Im Gegensatz dazu besteht der Ansatz des Trust-Region-Verfahrens darin, die Zielfunktion lokal auf einer begrenzten Region um eine aktuelle Näherung herum durch ein einfacheres Modell zu ersetzen, wie eine lineare oder quadratische Approximation der Zielfunktion. Ein Minimum dieses Modells wird auf dieser Region bestimmt. Je nach Ergebnis wird die Region verkleinert oder vergrößert.

Die Arbeit beschäftigt sich insbesondere mit der Frage, welches der beiden Verfahren effizienter arbeitet und in welchen Situationen eines der Verfahren dem anderen überlegen ist. 

## Verwendung der Mathematica-Codes

In diesem Repository finden Sie Mathematica-Codes, die im Rahmen meiner Bachelorarbeit von mir entwickelt wurden. Diese Codes dienen der Umsetzung der beschriebenen Verfahren und ermöglichen es, die numerischen Resultate für die Rosenbrock-Funktion auszuwerten und zu vergleichen.

© 2017 Büsra KARAOGLAN | Technischen Hochschule Mittelhessen
