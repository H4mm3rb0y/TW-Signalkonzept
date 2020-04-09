---
# Blöcke
- Ein Block ist ein Gleisabschnitt in dem sich genau ein Zug befinden kann. 
- In einem Block kann ein Zug anhalten.
- Die automatisierte Ausfahrt aus einem Block ist nur möglich, 
  - wenn eine Fahrstraße mit all ihren Bedingungen geblockt werden kann.
  - wenn der nachfolgende Block frei ist
- Ein Block verfügt in jede Richtung, in der automatisiert ein- und ausgefahren werden kann, einen Gleiskontakt
---
# Fahrstraße
- Eine Fahrstraße ist ein Gleisabschnitt, die genau zwei Blöcke direkt miteinander verbindet. 
- Eine Fahrstraße besteht aus Weichen, die für die Fahrstraße gesperrt werden müssen
- Kann eine der Weichen nicht gesperrrt werden, kann die Fahrstraße nicht eingelegt werden.
- Aufeinanderfolgende Blöcke ohne Weichen können eine Fahrstraße ohne Weichen enthalten
- Eine Fahrstraße mit all Ihren komponenten kann erst dann aufgehoben werden, wenn der Zug vollständig im Zielblock angekommen ist
---
# Weiche
- Eine Weiche kann nur zwischen zwei Blöcken liegen.
- Wird eine Weiche geblockt, kann sie nur von dem Blockenden Zug befahren werden
- Bei Sperrfahrten wird die Weiche manuell geblockt, damit eine Fahrstraße über sie nicht mehr eingelegt werden kann
- Erst nach beendigung der Sperrfahrt darf die Blockierung aller überfahrenden Weichen aufgehoben werden
- Der Block aus dem die Sperrfahrt begang, darf erst freigegeben werden, wenn die Sperrfahrt abgeschlossen ist und der Zug sich in einem regulären Block befindet
- Weichen werden in Kilometrierungsrichtung hochnummeriert.
---
# Abstellgleise
- Abstellgleise stellen nichts anderes wie Blöcke dar
---
# Signale
- Erfolgt eine Fahrt über Sperrsignale, so muss diese Fahrt als Sperrfahrt deklariert sein.
- Befinden sich Sperrsignale unmittelbar in einer Fahrstraße, so müssen diese beim Einlegen der Fahrstraße erlischen
- Die Ausfahrt aus Blöcken erfolgt immer mithilfe eines Signals.
- Ist bei einer Sperrfahrt kein Sperrsignal vorhanden oder die Signalanlage gesperrt, erfolgt die Ausfahrt in jedem Fall nur 
manuel nach zusage eines Stellwerkers
- 

Bezeichnungen:
- Einfachsignale in Kilometrierungsrichtung: A1, A2, A3..
- Ausfahrsignale in Kilometrierungsrichtung: P1, P2, P3..
- Einfahrsignale gegen Kilometrierungsrich.: F1, F2, F3..
- Ausfahrsignale gegen Kilometrierungsrich.: N1, N2, N3..
- Zwischensignale in Kilometrierungsrichtung: ZR, ZS, ZT..
- Zwischensignale gegen Kilometrierungsrichtung: ZU, ZV, ZW..
- Blocksignale in Kilometrierungsrichtung: A1, A3, A5, A7..
- Blocksignale gegen Kilometrierungsrichtung B2, B4, B6, B8.. (Dabei ist A1 immer neben B2, A3 neben B4 usw.)
- Vorsignale erhalten ein v vor der Berzeichnung und heißen so wie das zugehörige Hauptsignal in Kleinschrift.
- Sperrsignale werden so wie das gleich nummeriert mit einem Ls davor. In kilometrierungsrichtung wird ein X ergänzt, gegen ein Y. Bsp: Ls 32X
---
# Kontakte
- Gleiskontakte sind Mikrocontroller, die melden sobald Ein  Zug einen bestimmten Abschnitt betreten oder vollständig verlassen hat.
- Die Detektion, ob ein Zug einen Block vollständig verlassen hat erfolgt nach einer Verzögerung
- Die Detektion, ob ein Zug einen Block betreten hat, folgt unmittelbar
- Ein Kleiskontakt kann bei in beide Richtungen automatisiert befahrbahren blöcken beide Detektionen durchführen
   - ist ein Gleiskontakt für beide Richtungen zuständig, muss dieser bei aktivierung abfahren welche Art von Detektion durchgeführt werden soll
---

# TODO:
- Komponentenbenennungskonventionen hinzufügen
- Stellwerke (autom. Manuell)
- Tatsöchliche Realisierung mit Computern im Spiel planen
