# Lern-Periode 4

- Name: C-Kaenel
- Zeitraum: 24.04.2026 bis 26.06.2026

## Grob-Planung

### Noten

In den meisten Modulen liege ich im guten bis sehr guten Bereich. Besonders stark bin ich in Programmierung und Systemarchitektur. In theoretischen Fachern wie Mathematik besteht noch etwas Verbesserungspotenzial, diese sind aber nicht kritisch. Insgesamt bin ich mit meinen Noten zufrieden und mochte den Stand halten.

### Veränderungen

Im Vergleich zur letzten Lernperiode mochte ich meine Tagesplanung konsequenter einhalten und realistische, klar messbare Arbeitspakete formulieren. Ausserdem lege ich mehr Wert auf Dokumentation: jeder Arbeitstag soll mit einem kurzen Tageseintrag abgeschlossen werden, damit Fortschritte und Probleme nachvollziehbar bleiben.

### Projekte / neue Technologien

In dieser Lernperiode verfolge ich folgende Schwerpunkte:
- Umbrella OS: Eigenes Betriebssystem auf Rust-Basis weiterentwickeln
- Rust: Systemprogrammierung vertiefen, insbesondere Speicherverwaltung und Concurrency
- AI Development: Lokale KI-Modelle einrichten und eigene Werkzeuge mit LLM-APIs bauen
- SSH/VPN App: Sicheres Netzwerktool in Rust implementieren

### Generelle Ziele

- Umbrella OS auf einen stabilen, bootfahigen Zustand mit einfacher Shell bringen
- Rust-Kenntnisse so weit ausbauen, dass eigenstaendige Projekte damit umsetzbar sind
- Ein erstes eigenes AI-Projekt erfolgreich implementieren und dokumentieren
- Alle 8 Lernatelier-Tage aktiv nutzen und vollstandig dokumentieren

## Tagesplanungen

### Planung 24.04.2026

- [x] Arduino-Entwicklungsumgebung einrichten und testen
- [x] Tetris-Spiellogik fuer Arduino implementieren und auf Hardware testen
- [x] GitHub-Repository fuer Umbrella OS anlegen und Projektstruktur definieren
- [x] Grob-Planung fuer die Lernperiode ausfuellen

Heute habe ich die Grundlage fuer die ganze Lernperiode gelegt. Das Arduino-Setup lief ohne grosse Probleme, und das Tetris-Spiel zeigt die erste spielbare Version auf dem Display. Das Umbrella-OS-Repository ist angelegt und die Ordnerstruktur steht. Die Grob-Planung hilft mir, einen roten Faden durch die naechsten Wochen zu behalten.

### Planung 08.05.2026

- [x] Tetris: Kollisionserkennung und Game-Over-Logik fertigstellen
- [x] Umbrella OS: Bootloader-Konzept recherchieren und skizzieren
- [x] Rust installieren und erste Programme schreiben (Hello World, Variablen, Funktionen)
- [x] Rust Ownership und Borrowing verstehen und in Uebungen anwenden

Heute habe ich Tetris auf dem Arduino abgeschlossen, das Spiel laeuft stabil. Rust ist eine grosse Umstellung, das Ownership-System ist anfangs verwirrend, macht aber nach einigen Stunden Sinn. Das Bootloader-Konzept fuer Umbrella OS ist auf dem Papier, die Umsetzung beginnt naechstes Mal.

### Planung 22.05.2026

- [x] Umbrella OS: Ersten eigenen Kernel-Code in Rust schreiben und kompilieren
- [x] Rust: Structs, Enums und Pattern Matching in Uebungen vertiefen
- [x] SSH/VPN App: Anforderungen definieren und Systemarchitektur skizzieren
- [x] Alle bisherigen Projekte auf GitHub pushen und README aktualisieren

Heute war ein sehr produktiver Tag. Der erste eigene Kernel-Code fuer Umbrella OS kompiliert erfolgreich, das ist ein wichtiger Meilenstein. Rust-Kenntnisse wachsen spuerbar. Die Architektur fuer die SSH/VPN App ist klar, naechstes Mal beginnt die Implementierung. Alle Projekte sind auf GitHub aktuell.

### Planung 29.05.2026

- [x] SSH/VPN App: Basisstruktur in Rust aufsetzen und erstes TCP-Socket implementieren
- [x] Umbrella OS: Grundlegende Speicherverwaltung (Heap-Allocator) implementieren
- [x] Rust: Fehlerbehandlung mit Result und Option gruendlich durcharbeiten
- [x] Code der bisherigen Rust-Projekte reviewen und refaktorieren

Heute habe ich die SSH-App in Rust gestartet. Netzwerkprogrammierung in Rust ist maechtig, aber die Typsicherheit hilft, Fehler frueh zu finden. Der Heap-Allocator im Kernel laeuft in einem Basis-Test korrekt. Das Rust-Fehlerbehandlungssystem mit Result ist elegant und sicherer als Exceptions.

### Planung 05.06.2026

- [x] SSH/VPN App: Verbindungsaufbau und einfache Authentifizierung implementieren
- [x] Umbrella OS: Interrupt-Handling einbauen und testen
- [x] Lokale KI-Modelle recherchieren: Ollama installieren und erstes Modell laden
- [x] Ersten Prompt an ein lokales LLM senden und Antwort verarbeiten

Heute habe ich zum ersten Mal mit lokalen KI-Modellen gearbeitet. Ollama ist einfach einzurichten, und Llama 3 lauft auf dem Laptop erstaunlich gut. Die Moeglichkeiten fuer eigene Werkzeuge sind riesig. Der Verbindungsaufbau in der SSH-App funktioniert grundlegend. Das Interrupt-Handling im Kernel ist nach mehreren Debugging-Sessions stabil.

### Planung 12.06.2026

- [x] AI Development: Anthropic API anbinden und erstes Python-Skript schreiben
- [x] Kleines AI-Werkzeug bauen: automatische Code-Kommentierung per API
- [x] Umbrella OS: Einfache Shell-Schnittstelle einbauen, die Textbefehle verarbeitet
- [x] Projektdokumentation aktualisieren und alle Commits pushen

Heute habe ich die Anthropic API erfolgreich eingebunden. Das Werkzeug zur automatischen Code-Kommentierung funktioniert und spart schon jetzt Zeit. Im OS-Projekt verarbeitet die Shell einfache Textbefehle korrekt. Es wird klar, dass AI-Integration ein eigenes grosses Thema ist, dem ich die naechsten Tage mehr Zeit widmen mochte.

### Planung 19.06.2026

- [ ] AI-Projekt planen: Anforderungen und Scope fuer ein eigenes AI-Tool definieren
- [ ] AI-Tool implementieren: Grundstruktur mit Python und LLM-API aufsetzen
- [ ] Umbrella OS: Dateisystem-Grundstruktur entwerfen und ersten Code schreiben
- [ ] SSH/VPN App: Verschluesselungslogik mit einem etablierten Rust-Crate ausbauen

### Planung 26.06.2026

- [ ] AI-Tool: Funktionalitat erweitern, testen und dokumentieren
- [ ] Umbrella OS: Stand zusammenfassen und Ausblick auf naechste Lernperiode schreiben
- [ ] SSH/VPN App: Abschlusstest und Dokumentation
- [ ] Reflexion der gesamten Lernperiode verfassen und ins Dokument eintragen

## Lernperiode Reflexion

(Wird am Ende der Lernperiode am 26.06.2026 ausgefuellt.)
