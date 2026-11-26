# Z9D Cyber Secure Service

**Z9D-CSS** ist eine lokale Windows-Sicherheitsanwendung für Prozess-, Netzwerk- und Systemüberwachung. Die Software wurde für Privatanwender, Unternehmen, Forschung, Behörden und isolierte Umgebungen konzipiert.

- **Offizielle Website:** https://z9d-qai.com/
- **Support:** Z9D-CSS@outlook.com
- **Unterstützte Plattform:** Windows 10 / 11
- **Vertriebsmodell:** lokales EXE-/ZIP-Paket; kein öffentlicher Quellcode

> Z9D-CSS ist eine lokale Sicherheitsanwendung und kein Ersatz für ein professionell betriebenes Enterprise-EDR-System. Kein Schutzsystem kann absolute Sicherheit oder den Schutz vor allen bekannten und unbekannten Angriffen garantieren.

## Inhalt dieses Repository

| Datei | Beschreibung |
|---|---|
| `Z9D-CSS-v5.0-FREE.exe` | Veröffentlichte Free Edition |
| `Z9D-CSS-v5.0.exe` | Veröffentlichte Vollversion |
| `Z9D-CSS-6_0-PRO_Elite-exe-DEUTSCH.zip` | v6.0 PRO Elite-Paket |
| `Z9D-CSS-v5.3-PRO-SRS-EXE.zip` | Veröffentlichtes SRS-EXE-Paket |
| `LICENSE` | Lizenz- und Urheberrechtsbedingungen |

Dateien sind nur als veröffentlichte Pakete gedacht. Prüfen Sie heruntergeladene Dateien vor der Ausführung mit einer aktuellen Windows-Sicherheitslösung.

## Verfügbare Editionslinien

| Edition | Zielgruppe | Verfügbarer Funktionsumfang |
|---|---|---|
| **v5.0 Free** | Privatnutzung und Basisüberwachung | Prozess-, Netzwerk- und Gefahrenanzeige; manuelle Prüfung |
| **v5.0 Full / PRO** | Fortgeschrittene Anwender und kleine Teams | Erweiterte Überwachung, Lizenzbindung, Quarantäne und Incident-Report |
| **v6.0 AB PRO** | Industrie, Behörden und kritische Infrastruktur | Erweiterte Sensorik und Auto-Block-Optionen ohne KI |
| **v6.0 KI PRO** | Organisationen mit KI-gestützter Analyse | Lokale oder API-basierte KI-Analyse und erweiterte Sensorik |
| **v6.0 USB** | USB-/Standortlizenz ohne KI | Lizenzgebundener Betrieb für autorisierte Unternehmenshosts |
| **v6.0 USB-KI** | USB-/Standortlizenz mit KI | Zentrale KI- oder Engine-Anbindung auf einem freigegebenen Host |

Der tatsächlich aktivierte Funktionsumfang hängt von der erworbenen Lizenz und dem bereitgestellten Paket ab.

## Hauptfunktionen

### Prozess- und Systembeobachtung

- laufende Prozesse und Prozessmerkmale;
- CPU-, Handle- und Verhaltensdaten;
- sichere Verwaltung lokaler Logs;
- Hervorhebung auffälliger Prozesse;
- manuelle oder lizenzabhängige Prozessaktionen;
- optionale Bedrohungsanzeige.

### Netzwerkanalyse

- aktive Netzwerkverbindungen;
- Remote-IP- und Portübersicht;
- Verbindungsstatus und bekannte oder unbekannte Besitzer;
- Erkennung auffälliger Ports und Kommunikationsmuster;
- manuelle oder lizenzabhängige Firewall-Regeln;
- lokale Auswertung ohne permanente Cloud-Telemetrie.

Je nach Edition können zusätzliche Module für Router-, ARP-, MITM-, Firmware-, Supply-Chain- und Verhaltensanalyse enthalten sein.

### Quarantäne und Incident-Reports

Lizenzierte Editionen können unterstützen:

- Quarantäne verdächtiger Dateien;
- Erstellung lokaler Incident-Berichte;
- Export sicherheitsrelevanter Ereignisdaten;
- dokumentierte Nachverfolgung von Blockierungs- und Prozessaktionen;
- optionale lokale Meldungs- und Warnfunktionen.

Reports sollten vor Weitergabe auf sensible Informationen geprüft werden.

### KI-Anbindung

Z9D-CSS v6.0 PRO kann je nach Paket mit folgenden Betriebsarten verbunden werden:

- lokale Laufzeitumgebungen;
- OpenAI-kompatible APIs;
- Azure OpenAI / Foundry;
- NVIDIA NIM;
- Anthropic;
- Ollama, LM Studio und andere lokale OpenAI-kompatible Dienste;
- separater Z9D-Engine-Prozess.

Lokale KI-Dienste und API-Zugänge müssen separat installiert oder autorisiert werden. KI-Ergebnisse sind unterstützende Analysen und keine automatisierte Rechts- oder Sicherheitsentscheidung.

### USB-Enterprise-Betrieb

USB-basierte Editionen können eine Lizenz, einen Host-Heartbeat und eine freigegebene Netzwerkfreigabe verwenden. Die Clients prüfen dabei lizenzabhängig, ob:

- der autorisierte USB-Host erreichbar ist;
- die USB-Bindung gültig ist;
- der konfigurierte Lizenzstatus weiterhin aktiv ist;

Ein abgezogenes oder nicht autorisierterweise kopiertes Medium darf geschützte Funktionen nicht freischalten.

## Installation und Start

Z9D-CSS benötigt in der Regel keine klassische Installation.

1. Laden Sie die gewünschte Edition aus diesem Repository herunter.
2. Prüfen Sie Archiv und Datei mit Windows Defender oder einer autorisierten Sicherheitsschnittstelle.
3. Entpacken Sie ZIP-Pakete in einen eigenen lokalen Ordner.
4. Kopieren Sie keine Dateien aus alten oder fehlerhaften Testpaketen.
5. Starten Sie die original gelieferte EXE-Datei per Doppelklick.
6. Prüfen Sie im Hauptfenster Lizenz-, Schutz- und Aktivierungsstatus.

Falls Windows SmartScreen oder die Ausführungsrichtlinie eine Datei blockiert, behandeln Sie die Meldung als Prüfhinweis. Nur freigegebene Originaldateien von Z9D verwenden.

## Hinweise zur sicheren Anwendung

- Beenden Sie keine kritischen Windows-Prozesse oder systemrelevanten Dienste.
- Prüfen Sie jede manuelle Prozess- oder Firewallaktion vor der Ausführung.
- Verwenden Sie Quarantäne- und Blockierungsfunktionen gezielt und dokumentiert.
- Aktivieren Sie keine unbekannten KI-Endpunkte oder externen Modelle.
- Schützen Sie Lizenzdateien, Host-ID, USB-Medien und lokale Logs.
- Entfernen Sie ältere Pakete, wenn eine aktuelle, freigegebene Version bereitgestellt wurde.

Z9D-CSS arbeitet lokal und soll Datenübertragung und Cloud-Abhängigkeit reduzieren. Die konkrete Datenschutz- und Telemetrieeinstellung wird durch die gelieferte Edition und deren Konfiguration bestimmt.

## Downloadübersicht

Direkte veröffentlichte Downloads aus diesem Repository:

- [Z9D-CSS v5.0 Free](./Z9D-CSS-v5.0-FREE.exe)
- [Z9D-CSS v5.0 Vollversion](./Z9D-CSS-v5.0.exe)
- [Z9D-CSS v6.0 PRO Elite](./Z9D-CSS-6_0-PRO_Elite-exe-DEUTSCH.zip)
- [Z9D-SRS v5.3 PRO](./Z9D-CSS-v5.3-PRO-SRS-EXE.zip)

EXE- und ZIP-Dateien wurden als Anwendungspakete bereitgestellt. Dieses Repository ist kein Ersatz für eine separat freigegebene Lizenz oder Aktivierung.

## Support

Bei Aktivierungs-, Lizenz-, Paket- oder technischen Fragen:

- **E-Mail:** Z9D-CSS@outlook.com
- **Website:** https://z9d-qai.com/
- **SRS-Support:** https://z9d-srs-v5.3-pro.z9d-qai.com/support

Bitte nennen Sie Edition, Betriebssystem, Geräte-ID und eine konkrete Fehlerbeschreibung. Senden Sie keine Passwörter oder nicht benötigte personenbezogene Daten.

## Haftung und Lizenz

Z9D-CSS wird als experimentelle bzw. projektbezogene Sicherheitslösung bereitgestellt. Es besteht keine Garantie für absolute Sicherheit, Schäden durch unbekannte Angriffe oder unbeabsichtigte Auswirkungen von Blockierungs-, Beendigungs- oder Firewall-Regeln.

Copyright (c) 2026 Zoran Ljubic - Z9D-QAI / Matrixworld

All rights reserved. Die Nutzung unterliegt [`LICENSE`](./LICENSE) und den Bedingungen des jeweiligen Lizenzpakets.
