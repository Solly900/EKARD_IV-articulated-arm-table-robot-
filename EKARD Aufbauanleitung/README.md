# EKARD Aufbauanleitung

Die Aufbauanleitung ist für die Version 3 des EKARD konzipiert. Falls gewünscht, kann ebenfalls die Software Version 3 (unter Arduino IDE) verwendet werden, in diesem Fall ist einfach Schritt für Schritt der Anleitung zu folgen. 
Soll die Software Version 4 verwendet werden, sind alle Instruktionen der Anleitung bezüglich der Software-Inbetriebnahme zu ignorieren und stattdessen die Anweisungen in der EKARD-Software Dokumentation zu befolgen. 

-> WICHTIG: Nur die Einstellung aller Servos auf die 90°-Position vor dem Einbau ist auch in diesem Fall vorzunehmen! 

-> WICHTIG: Die Software EKARD_V4 muss zur Inbetriebnahme einmal im One-Time-Initialisierungs-Modus aufgespielt werden, dies ist vorzunehmen, __bevor__ der eigentliche Arm auf den Unterbau montiert wird! Nach dem Aufspielen im Initialisierungsmodus ist ein erneutes Aufspielen der Software mit __deaktiviertem__ Initialisierungsmodus nötig, ansonsten werden gepspeicherte Werte immer wieder überschrieben!

-> Außerdem ist darauf zu achten, dass die verwendete Spannungsquelle genug Strom liefern kann, ansonsten kann es zu einem Brown-Out-Reset im Betrieb kommen, wenn zu viele Bewegungen gleichzeitig (besonders von den beiden größeren Motoren) ausgeführt werden!

