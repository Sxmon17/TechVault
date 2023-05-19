#Informatik 
## Eigenschaften

- Speicherzellen einzeln adressierbar
- Normalerweise als RAM (Random Access Memory) ausgelegt
- Typischerweise Wort- oder Byte-Grenzen ➔ Beim Auslesen werden gleich mehrere Byte übertragen → Prefetch
- Zugriff sowohl durch CPU als auch durch I/O Geräte (DMA = Direct Memory Access) möglich
- Ausführbare Programme befinden sich (zumindest teilweise) im Arbeitsspeicher
- CPU greift normalerweise nicht direkt auf Sekundärspeicher zu (sondern nur auf Daten im AS)

## Aufgaben

- Buchhaltung: Welche Speicherbereiche sind benutzt?
- Speichervergabe und –Rücknahme für Prozesse (= Memory Allocation / Memory Deallocation)
- Programme in den Arbeitsspeicher laden
- Gemeinsame Nutzung von Codebibliotheken (DLL, Shared Library) → nur 1 mal im HS
- Speicherschutz (Memory Protection)

![[CPU.gif]]

