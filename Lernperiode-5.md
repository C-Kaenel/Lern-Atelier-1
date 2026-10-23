# Lern-Periode 5

- Name: C-Kaenel
- Zeitraum: 14.08.2026 bis 25.09.2026

## Grob-Planung

### Noten

Die letzte Lernperiode ist gut abgeschlossen. In Programmierung und Systemtechnik bin ich weiterhin stark. Ich möchte in dieser Periode besonders die theoretischen Module nicht vernachlässigen und den Fokus auf praxisnahe Webentwicklung und Backend-Kenntnisse legen, die sich direkt auf Modulinhalte anwenden lassen.

### Veränderungen

Im Vergleich zur letzten Lernperiode möchte ich weniger auf systemnahe Programmierung (OS, Kernel) und mehr auf anwendungsorientierte Entwicklung setzen. APIs und Webentwicklung sind Fähigkeiten die ich in fast jedem Projekt einsetzen kann. Ausserdem möchte ich von Anfang an mehr mit echten Tools wie Postman, Swagger und Datenbanken arbeiten statt nur Konzepte zu lernen.

### Projekte / neue Technologien

In dieser Lernperiode konzentriere ich mich auf:
- Programme miteinander verbinden: APIs als Schnittstelle zwischen verschiedenen Systemen und Sprachen einsetzen
- API-Implementierung in verschiedenen Sprachen: Python, Node.js und weitere Ansätze vergleichen
- Produktions-Linux-Umgebung: APIs auf einem echten Linux-Server deployen und betreiben
- Interoperabilität: verstehen wie verschiedene Programme, Dienste und Sprachen über APIs kommunizieren
- Deployment und Betrieb: Prozessmanagement, Logging und Monitoring auf Linux

### Generelle Ziele

- Dieselbe API in mindestens zwei verschiedenen Programmiersprachen implementieren und vergleichen
- Eine API in einer echten Linux-Produktionsumgebung deployen und zum Laufen bringen
- Verstehen wie verschiedene Programme über APIs miteinander kommunizieren
- Alle Lernatelier-Tage mit klaren Arbeitspaketen dokumentieren

## Tagesplanungen

### Planung 14.08.2026

- [x] Recherche: Was ist eine API, was ist REST, welche HTTP-Methoden gibt es (GET, POST, PUT, DELETE)
- [x] Erste einfache REST-API lokal aufsetzen (Node.js mit Express oder Python mit FastAPI)
- [x] Mindestens 3 Endpunkte implementieren und mit curl oder Postman testen
- [x] Grundlagen von JSON als Datenaustauschformat verstehen und anwenden

Heute habe ich die Grundlagen von REST-APIs erarbeitet. FastAPI in Python ist schnell eingerichtet und die automatische Swagger-Dokumentation ist sehr hilfreich. Die ersten drei Endpunkte laufen und ich kann sie mit Postman testen. JSON als Datenaustauschformat ist intuitiv und macht sofort Sinn.

### Planung 21.08.2026

Abwesend

### Planung 28.08.2026

- [x] API-Implementierung in Python (FastAPI) und Node.js (Express) oder Go vergleichen: dieselben Endpunkte in beiden Sprachen bauen
- [x] Recherche: Wie funktioniert eine Linux-Produktionsumgebung, was braucht man (nginx, systemd, Prozessmanagement)
- [x] Erste API auf einer lokalen Linux-VM oder WSL deployen und von aussen erreichbar machen
- [x] Zwei verschiedene Programme über eine selbst gebaute API miteinander kommunizieren lassen

Ich habe gut gearbeitet und grosse Fortschritte gemacht. Der Vergleich zwischen Python und Node.js zeigt klar die Unterschiede in Syntax und Performance. Die API läuft auf WSL und ist von aussen erreichbar.

### Planung 04.09.2026

- [x] Bisherige API-Kenntnisse wiederholen: REST-Konzepte, HTTP-Methoden und JSON-Struktur festigen
- [x] Spezialisierte Fälle anschauen: Authentication (API Keys, JWT), Rate Limiting und Fehlerbehandlung
- [x] Externe Produktions-APIs untersuchen: GitHub API, OpenWeather API oder Stripe API analysieren und ansprechen
- [x] Eigene API um einen spezialisierten Endpunkt erweitern basierend auf dem Gelernten

Alles würde Erflüllt vieles lehrreiches wurde gelernt und alle Ziele bestnden.

### Planung 11.09.2026

- [x] 45 Minuten Repetition: REST-Konzepte, HTTP-Methoden, Authentication und alles vom letzten Mal zusammenfassen
- [x] Go installieren und erste Schritte: Syntax, Module und HTTP-Paket kennenlernen
- [x] Eine vollständige REST-API in Go bauen: dieselben Endpunkte wie in Python/Node.js umsetzen
- [x] Go-API mit Python/Node.js vergleichen: Performance, Code-Lesbarkeit und Developer Experience bewerten

Heute musste ich den Ablauf etwas umstrukturieren, da ich anfangs kein WLAN hatte und deshalb nicht sofort mit Go starten konnte. Die Repetitionsphase habe ich genutzt um Notizen durchzugehen und Konzepte schriftlich zusammenzufassen. Später konnte ich Go einrichten und habe mit dem Standard `net/http` Paket eine erste REST-API gebaut. Der Vergleich mit Python ist interessant: Go ist deutlich expliziter und erfordert mehr Code, läuft dafür aber sehr schnell und ohne Runtime. Nächstes Mal möchte ich das Go-Framework `Gin` ausprobieren, die API um Datenbankanbindung erweitern und einen direkten Performance-Vergleich mit FastAPI durchführen.

### Planung 18.09.2026

- [x] Go API mit Gin Framework neu aufsetzen und mit dem Standard net/http Ansatz vergleichen
- [x] Datenbankanbindung in Go implementieren: SQLite oder PostgreSQL mit GORM einbinden
- [x] Performance-Vergleich: Go (Gin) vs Python (FastAPI) mit einfachen Lasttests messen
- [x] Erkenntnisse dokumentieren: welche Sprache für welchen Anwendungsfall besser geeignet ist

Heute habe ich Gin mit dem Standard net/http Ansatz verglichen. Gin ist deutlich angenehmer zu verwenden, die Routing-Syntax ist sauber und Middleware lässt sich einfach einbinden. Die Datenbankanbindung mit GORM funktioniert gut, braucht aber etwas Einarbeitung. Der Performance-Vergleich zeigt Go klar vor FastAPI bei hoher Last, für kleinere Projekte ist der Unterschied aber kaum spürbar.

### Planung 25.09.2026

- [x] Lernperiode abschliessen: alle Projekte dokumentieren und auf GitHub pushen
- [x] Go und Python APIs zu einem kleinen System zusammenführen: beide über eine gemeinsame Schnittstelle ansprechen
- [x] Reflexion der gesamten Lernperiode schreiben: was gelernt, was überraschend war, was als nächstes kommt
- [x] Ausblick planen: welche API-Themen oder Sprachen in der nächsten Lernperiode vertieft werden

## Lernperiode Reflexion

In dieser Lernperiode habe ich einen grossen Schritt in Richtung praxisorientierter Backend-Entwicklung gemacht. Der Einstieg in REST-APIs mit Python und FastAPI war schnell und produktiv, die automatische Swagger-Dokumentation hat mir von Anfang an geholfen, sauber zu arbeiten. Der Wechsel zu Go war eine bewusste Herausforderung: die Sprache ist expliziter, erfordert mehr Disziplin, belohnt das aber mit hervorragender Performance und klarer Struktur. Das Gin-Framework hat sich dabei als deutlich angenehmer erwiesen als das Standard-Paket. Die Datenbankanbindung mit GORM und der direkte Performance-Vergleich zwischen Go und Python haben mir ein realistisches Bild davon gegeben, wann welche Technologie sinnvoll ist. Was ich besonders mitnehme: Verschiedene Sprachen für dasselbe Problem einzusetzen schärft das Verständnis für Konzepte, weil man zwingt wird, zwischen Implementierung und Idee zu unterscheiden.
