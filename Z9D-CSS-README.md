# Z9D-QAI-CSS-Cyber-Secure-Service
# Z9D•QAI-CSS-Cyber-Secure-Service
# Z9D.QAI-CSS-Cyber-Secure-Service
Z9D CSS Cyber-Secure-Service 5.0 Free Edition
*****************************************************************************************
# 📘 README – Z9D•QAI Cyber Secure Service (CSS)  
*** Versionen: 5.0-FREE Edition - 5.0-BLOCK-IP - 5.0-AUTO-BLOCK - 5.0-USB / 5.1 / 5.2 / 6.0 ***  
*** Autor: Z9D / Zoran Zoky Ljubić *** 
*** Plattform: Windows 10 / 11 ** 
***** Typ: Lokales Z9D•QAI-Security‑Monitoring&Threat‑Analysis‑System *****

🔹 1. Überblick

Der **Z9D•QAI Cyber Secure Service (CSS)** ist ein lokales Sicherheits‑ und Überwachungssystem für Windows.  
Es analysiert in Echtzeit:

- laufende Prozesse  
- Netzwerkverbindungen  
- Systemereignisse  
- Defender‑Status  
- (ab Version 6.0) Updates, Treiber, Netzwerk‑Umgebung  

CSS arbeitet **komplett lokal**, ohne Cloud, ohne Telemetrie und ohne Installation.  
Es kann verdächtige Prozesse erkennen, Netzwerkangriffe sichtbar machen und IP‑Adressen blockieren.

Was Z9D‑CSS 5.0 Free Edition automatisch macht;

✔ 1. Automatische Warnung an Windows Defender
Wenn Z9D‑CSS ungewöhnliche Muster sieht wie:

- verdächtige Prozesse
- ungewöhnliche Ports
- aggressive Verbindungen
- viele CLOSE_WAIT / TIME_WAIT
- Verbindungen zu bekannten Cloud‑Angreifer‑Netzen
- Owner‑Mismatch (z. B. Chrome → AWS)
- verdächtige EXE‑Namen
-*- Dann sendet die Free Edition:
→ eine Warnung an Defender (über EventLog / SecurityCenter API)
Das bedeutet:
Defender wird aufmerksam
Defender scannt den Prozess
Defender erhöht die Überwachung
Defender blockiert, wenn es wirklich Malware ist
Free Edition blockiert NICHT selbst – aber Defender wird aktiv.

2. Automatische Warnung an die Firewall (passiv)
Auch in der Free Edition:
Z9D‑CSS schreibt verdächtige IPs in das Windows‑EventLog
Die Firewall liest diese Events (Standard‑Windows‑Mechanismus)
Die Firewall kann darauf reagieren, wenn Defender es bestätigt
Das ist passiv, aber effektiv.

✔ Firewall wird informiert
✔ Defender wird informiert
❌ aber Z9D‑CSS blockiert NICHT selbst
🟥 Was NICHT passiert in 5.0 Free Edition
❌ Keine Auto‑Block‑Regeln
❌ Keine KI‑Analyse
❌ Keine Engine‑Reaktionen
❌ Keine Prozess‑Beendigung
❌ Keine Port‑Schließung
❌ Keine IP‑Sperren
Das kommt erst ab:
5.1 Elite Edition
5.2 Pro Edition
6.0 KI Elite Edition
Dort:
KI bewertet Risiko
Engine setzt Firewall‑Regeln
Auto‑Block sperrt IPs
Prozesse werden beendet
Ports werden geschlossen

🔹 1.1 Funktionen: 
Free Version: Leicht, ohne KI, ohne Auto-Block, Warnt Defender/Firewall und zeigt 
gefährliche IPs nach längerer Prüfung rot an. 
Z9D-CSS-v5.0-FREE.exe nach Download auf den Desktop ziehen.
Start per 2-Klick-Exe. 
🔹 1.2 Visueller Gefahrenbalken:
Das Tool verfügt an der Oberseite über eine Indikatot-Leiste. 
Tritt eine System-Anomalie auf - etwa durch ungewöhnliche Hintergrundaktivitäten -,
steigt dieser Balken sofort an und schlägt visuell Alarm.
🔹 1.3Erkennung von Elite-Bedrohungen:
Z9D-CSS v5.0 schlägt gezielt an, wenn Angriffe im Stil von Professionellen Hackern
oder Einschläusungen aus Darknet-Quellen stattfingden.
🔹 1.4 Manuelle Blockade:
Der Nutzer bleibt der Chef auf seinem System.
Sobald eine Anomalie oder eine verdächtige Verbindung im Dashboard aufläuchtet,
kann diese mit einem Klick manuellblockiert und die Gefahr sofort gebannt werden.
🔹 1.5 Schutz ohne Bevormundung:
Das System schützt sich selbst, aber überlässt dem Nutzer die finale Entscheidungsgewalt
über die Netzwerk- und prozessregeln.
🔹 1.6 Der starke Basis-Schutz:
Optimal für den Alltag gegen herkömmliche Hacker und Systemanomalien.
Sie verzichtet bewusst auf KI-Anbindung und Auto-Block, bleibt dadurch extrem 
leichtgewichtig, schützt aber hocheffektiv über zwei Kernmechanismen:
🔹 Interne Alarmierung:
Das Tool warnt bei Entdeckungen sofort im Hintergrund den Windows 
Defender und die Windows-Firewall.
🔹 Rote IP-Erkennung:
Bleibt Eine verdächtige Verbindung bei der Prüfung länger aktiv, 
läuchtet die betroffene IP-Adresse im Tool rot auf, 
sodass der Nutzer sie sofort manuell blockieren kann.
🔹 Version 5.0 Free Edition: Arbeitet absolut diskret ohne Beep- Ton und ohne Popup-Warnfenster 
- ideal für ungestörtes Arbeiten.
*************************************************************************************************
🔹 2. Funktionsumfang (alle Versionen)

Alle Versionen enthalten:

- Echtzeit‑Überwachung von Prozessen  
- Netzwerk‑Monitoring mit Remote‑IP‑Analyse  
- Owner‑Erkennung (Azure, AWS, Google, Cloudflare, Meta, LAN, Localhost)  
- ThreatScore‑Berechnung  
- Firewall‑Blockierung einzelner IPs  
- Manuelles Killen von Prozessen  
- Log‑System  
- KI‑Router (Python, GGUF, Z9D‑Engine oder manuell)  
- Z9D‑Icon‑Unterstützung (bei Verknüpfungen)

🔹 3. Unterschiede der Versionen

### "Version 5.1" ###
- Stabile Basisversion  
- Ruhiger ThreatScore  
- Keine Popups, keine akustischen Warnungen  
- Ideal für Präsentationen und Low‑Noise‑Monitoring

### "Version 5.2" ###
- Erweiterte Netzwerk‑Owner‑Erkennung  
- Popup‑Warnungen + akustische Signale  
- Sensiblere ThreatScore‑Logik  
- Verbesserte UI‑Rückmeldungen

### "Version 6.0" ###
- Erweiterte Sicherheitsmodule:  
  - Router‑/ARP‑/MITM‑Erkennung  
  - Update‑Analyse (Supply‑Chain‑Angriffe)  
  - Treiber‑Heuristik (Firmware‑Risiken)  
  - Zero‑Day‑Verhaltensanalyse  
- Auto‑Block‑Modus  
- Modernisierte UI  
- ThreatScore 2.0  
- Stabiler Timer‑Loop  
- Optionaler KI‑Modus mit Z9D‑Engine
*********************************************************************
🔹 4. Installation:

CSS benötigt **keine Installation**.  
Es kann direkt im Desktop ausgeführt werden.
"Download exe, double.click, run - no installation needed".

Optional kann ein Installer‑Script verwendet werden, das:

- die Dateien nach `C:\Program Files\Z9D-CSS\` kopiert  
- eine Desktop‑Verknüpfung mit Z9D‑Icon erstellt  
- Schreibschutz setzt  
*********************************************************************
🔹 5. Starten des Programms

### Direktstart:
Doppelklick auf die Datei:

z9d_cyber_secure_service_vX_X_css.ps1  
oder (Ihre Version 5.1 - 5.2 - 6.0 direkte Datei-Ausführung - in eigenen Ordner kopieren)

Falls PowerShell blockiert:

Rechtsklick → Mit PowerShell ausführen → (als Administrator ausführen)-optional

oder:
Set-ExecutionPolicy Bypass -Scope Process

🔹 6. Bedienung

### Prozessliste:
Zeigt CPU‑Last, Handles, PID und Name.  
Verdächtige Prozesse können beendet werden.

### Netzwerkliste:
Zeigt Remote‑IP, Port‑Anzahl, Verbindungsstatus und Owner.  
Unbekannte oder verdächtige IPs können blockiert werden.

### ThreatScore:
Zeigt den aktuellen Bedrohungsgrad.  
Je höher der Score, desto mehr Sensoren haben angeschlagen.

### Auto‑Block (ab v6.0):
Aktiviert automatische Firewall‑Regeln bei verdächtigen Verbindungen.

### KI‑Modus:
Erlaubt Analyse durch externe KI‑Modelle (optional) mit Z9D-Engine.

🔹 7. Dateien im Paket;
Je nach Version können folgende Dateien enthalten sein:

- `z9d_cyber_secure_service_vX_X_css.ps1` → Hauptprogramm  
- `Z9D_logo.ico` → Icon für Verknüpfungen  
- `Z9D_Engine.exe` → KI‑Engine (nur v6.0)optional  
- `README.txt` → Diese Datei  
- `Installer.ps1` → Optionaler Installer  

🔹 8. Sicherheitshinweise

- CSS arbeitet lokal und verändert keine Systemdateien.  
- Schreibschutz kann gesetzt werden, um Manipulation zu verhindern.  
- Firewall‑Regeln werden nur gesetzt, wenn der Benutzer es auslöst oder Auto‑Block aktiv ist.  
- CSS ersetzt kein professionelles EDR‑System, bietet aber starke lokale Heuristik.

🔹 9. Support / Kontakt:
Für Fragen, Erweiterungen oder neue Versionen:  
"Z9D•QAI _ Dr.MaS.Zoran Ljubić - Hard/Bregenz Österreich - Doboj RS - Zaječar SRBIJA"
Tik-Tok - Facebook - Instagram - nur Follower! 

🔹 10. Das Z9D-CSS PRO-Lineup (v5.1 - 5.2 -v 6.0)
🔹Gemeinsame Pro-Basis: 
Alle Pro-Varianten laufen mit der leistungsstarken Z9D-Engine 
und verfügen über eine vollwärtige KI-Anbindung.
🔹Z9D_Engine KI-Flexibilität:
Die Engine bietet mehrere flexible Anbindungsmöglichkeiten für verschiedene KI-Arten und
Modellformate, darunter: KI Auswahl Popup-Warnfenster; Welche KI möchten Sie verwenden?
🔹Keine KI (Z9D_Cyber Secure Service, nur Heuristik)
🔹Python KI-API (HF/ONNX, Endpoint) - (ONNX-Optimiert für schnelle CPU/GPU-Ausführung / HF Hugging Face Transformer Modelle)
🔹Lokale GGUF KI (Pfad auswählen) - (Ressourcenschonende, quantisierte Modelle für den lokalen Betrieb)
🔹Z9D-Engine.exe (lokale KI ohne Python)

🔹 Version 5.1 (Silent Pro): Arbeitet absolut diskret ohne Beep- Ton und ohne Popup-Warnfenster 
- ideal für ungestörtes Arbeiten mit Auto-Block auch gegen Trojaner und Würmer.
🔹 Version 5.2 (Alert Pro): Bietet maximale Aufmerksamkeit bei Gefahr durch
sofortige Popup-Warnfensterund einen akustischen Beep-Warnton, mit Auto-Block auch gegen Trojaner und Würmer.
🔹 Version 6.0 (High-End): Explizit gehärtet gegen Staatshacker, Trojaner und Würmer mit Auto-Block +KI-Anbindung.

# ✔ **Diese README ist für alle Versionen identisch nutzbar.**
******************************************************************************************
!!! Hinweis zur W-LAN-Initialisierung - Laptop-Betrieb - BEDROHUNGSGRAD-BALKEN !!!

Bei der Verwendung von Z9D‑CSS auf Laptops kann es vorkommen, dass der 
Bedrohungsgrad-Balken nicht angezeigt wird, wenn das Programm gestartet wird, 
während das WLAN bereits aktiv ist.

Technischer Hintergrund:
Windows initialisiert WLAN-Adapter in mehreren Phasen (Authentifizierung, DHCP, Routing). 
Wenn Z9D‑CSS während dieser Phase gestartet wird, erhält das Programm keine stabilen 
Netzwerkdaten. In diesem Fall wird das Bedrohungsgrad-Modul nicht geladen.

Lösung:
Z9D‑CSS zuerst starten und erst danach das WLAN aktivieren.  
Dadurch erhält das Programm einen klaren Startzustand und der Bedrohungsgrad-Balken 
wird korrekt angezeigt.

Auf Desktop-PCs mit LAN-Verbindung tritt dieses Verhalten nicht auf.
******************************************************************************************
📌    Haftungsausschluss / Keine Garantie oder Gewährleistungen: 
Der Anbieter Z9D•QAI übernimmt keine Garantie oder Gewährleistung für Schäden, Fehlfunktionen oder Beeinträchtigungen, auch die durch Hackerangriffe, Schadsoftware, unerwünschte Software, externe Entwickler, Manipulationen oder sonstige Eingriffe Dritter entstehen. Der Auftragsgeber ist verantwortlich für die Sicherheit seiner eigenen IT‑Infrastruktur, einschließlich Betriebssystem, Netzwerk, Benutzerkonten und physischem Zugriff. Der Anbieter Z9D•QAI haftet nicht für bestehende und neue oder zukünftige Angriffsmethoden, Softwareentwicklungen oder Sicherheitslücken, die außerhalb seines Einflussbereichs liegen.
Haftungsausschluss – Trainingszeiten & Erstellungszeiten: 
Trainings‑, Entwicklungs‑ und Erstellungszeiten können ausschließlich gemäß der aktuellen Auftragslage, Systemauslastung und der technischen Trainingsgeschwindigkeit des Z9D•QAI‑Systems bereitgestellt werden. Es besteht keine Garantie für feste Fertigstellungstermine, da Trainingsprozesse von Datenmenge, Modellkomplexität, Hardwareauslastung sowie externen Faktoren abhängig sind. Der Anbieter übernimmt keine Haftung für Verzögerungen, die durch technische Limitierungen, notwendige Optimierungen, unerwartete Trainingsverläufe oder externe Einflüsse entstehen.
On‑Premise Server‑Optimierung (durch IT‑Abteilung des Auftraggebers): 
Die technische Optimierung des lokalen Servers (On‑Premise) erfolgt ausschließlich durch die IT‑Techniker des Auftraggebers, oder durch vom Auftraggeber beauftragte externe Fachkräfte. Der Anbieter Z9D•QAI stellt lediglich die technischen Anforderungen, Empfehlungen und Konfigurationsrichtlinien bereit, die für einen stabilen und performanten Betrieb des Systems notwendig sind. Der Anbieter führt keine Vor‑Ort‑Arbeiten durch und übernimmt keine Verantwortung für die Umsetzung, Ausführung oder Qualität der Arbeiten der IT‑Abteilung des Auftraggebers. Für die Ausführung, Qualität oder Fehler der implementierten Maßnahmen übernimmt der Anbieter Z9D•QAI keine Haftung. Haftungsausschluss (Server‑Optimierung): Für fehlerhafte Implementierungen, falsche Konfigurationen oder unzureichende technische Maßnahmen der IT‑Abteilung des Auftraggebers übernimmt der Anbieter Z9D•QAI keine Haftung. 
Hinweis zu Kosten, Lizenzen & steuerlicher Behandlung (Haftungsausschluss): 
Die Kosten für die öffentliche Bereitstellung der Z9D•QAI Software, KI‑Module, Lizenzen und Subventionen sind als Leistungen aus privater Entwicklungs‑, Forschungs‑, Ingenieurs‑ und Architekturarbeit in einer experimentellen Umgebung zu betrachten. Es handelt sich nicht um serienreife Massenprodukte, sondern um individuelle, projektbezogene Entwicklungsleistungen. Die ausgewiesenen Beträge unterliegen daher der gesetzlichen Umsatzsteuer und sind als staatliche Abgabe gemäß den geltenden steuerrechtlichen Vorschriften zu behandeln. Eine Produktgarantie im Sinne fertiger Handelsware besteht nicht.
****************************************************************************************
## 📥 Download Z9D-CSS v5.0 FREE
[Hier herunterladen](https://github.com/Z9D-QAI/Z9D-QAI-CSS-Cyber-Secure-Service/blob/main/Z9D-CSS-v5.0-FREE.exe)
