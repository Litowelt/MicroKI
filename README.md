![HierSollteEigentlichEinFotoSein...](https://github.com/Litowelt/MicroKI/blob/main/MicroKI.png)

# MicroKI

Das "MicroKI" ist ein Projekt, das sich mit digitalen Zusatzanzeigen befasst. Das MicroKI ermöglicht den Anschluss von bis zu 6 Zusatzanzeigen (0.96" OLED LCDs) an ein System. Die Daten für diese Anzeigen können entweder über den CAN-Bus (1x) oder über externe Sensor-Eingänge bezogen werden. Es stehen verschiedene externe Sensor-Eingänge zur Verfügung, darunter Batterie Spannung und Öldruck. Jede der 6 Anzeigen kann separat angesteuert werden und die Daten können über Tasten auf der Platine oder externe Tasten umgeschaltet werden.

# Anschluss Übersicht
Digitale Zusatzanzeigen (0.96" OLED LCDs):

- Bis zu 6 dieser Displays können an das MicroKI angeschlossen werden.

Datenquelle:

- Die Daten können über den CAN-Bus (1x) oder über externe Sensor-Eingänge bezogen werden.
  
Externe Sensor-Eingänge:

- 1x Batterie Spannung
- 1x Öldruck Sensor (VDO)
  
Steuerung und Umschaltung:

- Alle 6 Anzeigen können separat angesteuert werden.
- Die Umschaltung zwischen den Anzeigen und die Steuerung erfolgen entweder über die Buttons auf der Platine oder über externe Buttons.

# Unterstütze Fahrzeuge und Nachrichten

- VW T5.1
  - Öl Temperatur (wenn der Sensor verbaut ist) - ✓
  - Kühlwasser Temperatur - ✓
  - Ladeluft Temperatur - ✓
  - Außentemperatur (wenn der Sensor verbaut ist) - ✓
  - Ladedruck - ✓
 
- Universal (Analoge Eingänge)
  - Öl Temperatur - X
  - Kühlwasser Temperatur - X
  - Außentemperatur - X
  - Öldruck - X
  - Ladedruck - X
 
# ToDo
- Code fertig schreiben. - in Arbeit
- Prototypen V2 bauen (Bauteile und Platinen sind bestellt).
- CAN Nachrichten für T5.2 heraus finden. - Müssen nur noch final getestet werden
- CAN Support für Haltech ECU hinzufügen - in Arbeit
- CAN Support für Ecumaster EMU ECU hinzufügen - in Arbeit
- CAN Support für Maxx ECU hinzufügen - in Arbeit
