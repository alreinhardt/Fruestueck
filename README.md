# Fruestueck
Beispiel Aufgabe

@startuml
title Frühstückszubereitung

actor Benutzer

Benutzer -> "Kaffeemaschine": Kaffee machen
"Kaffeemaschine" --> Benutzer: Kaffee bereit

Benutzer -> "Toaster": Toast machen
"Toaster" --> Benutzer: Toast bereit

Benutzer -> "Pfanne": Ei braten
"Pfanne" --> Benutzer: Ei bereit

Benutzer -> "Frühstückstisch": Frühstück vorbereiten
"Frühstückstisch" --> Benutzer: Frühstück genießen

@enduml
