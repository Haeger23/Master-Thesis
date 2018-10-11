Abstract
======

Diese Arbeit beschäftigt sich mit dem Thema WebRTC, also der Peer-to-Peer-Datenübertragung im Webbrowser. Es wird untersucht ob diese junge Technologie bereits einen Entwicklungsstand erreicht hat, der einen produktiven Einsatz rechtfertigen würde. 

Dazu ist ein Prototyp entwickelt worden, welcher während einem Live-Event den Ein-satz von Zuschauermikrofonen überflüssig machen soll. Die digitale Aufzeichnung der Zuschauerfragen wird dabei von den mobilen Endgeräten (Smartphone, Tablet, Lap-top, etc.) der Fragenden übernommen, da diese heutzutage weitestgehend mit Mikro-fon und Kamera bestückt sind. Die damit aufgezeichneten Daten werden über eine WebRTC-Verbindung zu einem zentralen Host geleitet und von dort aus weiterverar-beitet.

Die Umsetzung drei unterschiedlich komplexer Szenarien in diesem Open-Source-Projekt hat gezeigt, dass die Technologie bereits einen sehr erwachsenen Stand er-reicht hat und für diese Anwendungsfälle bereits alle Funktionen unterstützt. 

Gefahren liegen in dem unfertigen Standard, der sich noch grundlegende Änderungen vorbehält und bei der noch fehlenden Unterstützung von Internet Explorer und Safari. 

Verbesserungspotenzial gibt es bei der Manipulation von SDP-Paketen während des Verbindungsaufbaus, diese werden in einem JavaScript unfreundlichem Text-Format übertragen, was die Anpassung einzelner Parameter erschwert.

