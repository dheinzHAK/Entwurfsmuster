# Entwurfsmuster
DOKUMENTATION DES ARBEITSPROZESSES

1. Chain of Responsibility
Zentrale Charakteristika
Verkettung mehrerer Handler
Jeder Handler:
bearbeitet die Anfrage oder
reicht sie an den nächsten weiter
Sender kennt nicht den konkreten Bearbeiter
Vermeidet große if-else-Ketten
Schlüsselbegriff: Weiterreichen der Verantwortung

2. Template Method
Zentrale Charakteristika
Algorithmus als Schablone
Bestimmte Schritte sind fix
Andere Schritte sind variabel (abstract)
Umsetzung über Vererbung
Schlüsselbegriff: Algorithmus-Struktur vorgeben

3. Decorator
Zentrale Charakteristika
Objekte dynamisch erweitern
Gleiche Schnittstelle wie das Original
Keine Vererbungsexplosion
Dekoratoren werden verschachtelt
Schlüsselbegriff: Wrapper

4. Builder
Zentrale Charakteristika
Schrittweiser Aufbau komplexer Objekte
Trennung von Konstruktion und Repräsentation
Lesbarer Code
Kein riesiger Konstruktor
Schlüsselbegriff: Fluent Interface

5. Adapter
Zentrale Charakteristika
Macht inkompatible Interfaces kompatibel
Umhüllt bestehende Klasse
Keine Änderung am Original
Schlüsselbegriff: Übersetzer

6. Observer
Zentrale Charakteristika
1:n Abhängigkeit
Observer werden automatisch informiert
Lose Kopplung
Schlüsselbegriff: Publish–Subscribe
