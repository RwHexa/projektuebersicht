<img src="logorw96.png" alt="RwTec Logo" width="72" align="right">

# Projektübersicht — GitHub RwHexa

**Reinhard Wermeling (RwTec)** · erstellt mit Claude Code
**33 Repositories** · Zeitraum **Januar 2025 – Juli 2026** · 7 Themenfelder · Stand 26. Juli 2026

> 🔒 = privates Repository · Sprache in Klammern als Kürzel

| Kennzahl | Wert |
|---|---|
| Projekte gesamt | 33 |
| SmartHome / IoT | 9 |
| Fußball-Turniere | 5 |
| Elektronik | 5 |
| Delphi / TMS | 4 |
| privat 🔒 | 10 |

---

## 🔌 Elektronik & Schaltungstechnik (5)

| Projekt | Zeitraum | Kurzbeschreibung |
|---|---|---|
| **SpsSteuerung** | Jul 2026 | SPS-Programmierung mit **OpenPLC V4.2.9** auf **ESP32 WROOM**: Kontaktplan (KOP), E/A-Pin-Mapping (%IX/%QX → GPIO), Runtime direkt als Firmware geflasht (ohne Windows-Runtime), Live-Debugging. Dokumentierte Inbetriebnahme; Ausbau mit Timern (TON/TOF) und Modbus geplant. |
| **NetzgeraetRw** (HTML) | Jul 2026 | 12-V-Sperrwandler (Flyback) mit PWM-Controller OB2263 — Lehr-/Werkstattbericht: Schaltung verstehen, sicher prüfen (Messungen), simulieren (Falstad + HTML), KiCad-Platine. |
| **GeminiNetz** (TypeScript) 🔒 | Jul 2026 | Schaltnetzteil — begleitendes Arbeits-/Entwurfsrepository. |
| **nf_verstaerker** | Jun 2026 | NF-Verstärker: Aufbau und Dokumentation einer Niederfrequenz-Verstärkerschaltung. |
| **motordrehzahl** | Mai – Jul 2026 | Drehstrom-Motoren elektronisch ansteuern — Drehzahlsteuerung / Frequenzumrichter-Thematik. |

## 🏠 SmartHome, Shelly, MQTT & IoT (9)

| Projekt | Zeitraum | Kurzbeschreibung |
|---|---|---|
| **shelly-waschmaschine-lora-ntfy** (JS) | Jul 2026 | Waschmaschinen-Fertig-Melder: Shelly 1PM Gen3 misst den Strom, meldet das Waschende per LoRa-Add-on an einen Empfänger, der eine Push-Nachricht über ntfy.sh aufs Handy schickt. |
| **shelly-controller** (JS) | Apr 2026 | Shelly-Geräte per MQTT steuern, umgesetzt mit TMS. |
| **shellyweb** (JS) | Apr – Mai 2026 | Shelly-Steuerung als Web-App auf Android. |
| **shwindows** (HTML) | Mai 2026 | SmartHome-Bedienung/Visualisierung unter Windows. |
| **SmartHome-Extern** (C++) 🔒 | Mär – Apr 2026 | Erforderliche Dateien zum Betrieb des SmartHome unter Windows (externe Komponenten). |
| **MqttDelphi** (Pascal) 🔒 | Mär 2026 | MQTT-Anbindung mit Lazarus/Delphi. |
| **MqttLazarus** | Mär 2026 | MQTT-Verbindung zum Broker mit Delphi/Lazarus-Oberfläche. |
| **ESP32Webserver** (JS) 🔒 | Mär 2026 | ESP32 als WLAN-Access-Point mit eigenem Webserver (HTML/CSS/JavaScript). |
| **WaschmGit** (C++) | Dez 2025 | Waschmaschinen-Projekt (Mikrocontroller/Elektronik), frühe Fassung. |

## ⚽ Fußball-Turnier & Manager (5)

| Projekt | Zeitraum | Kurzbeschreibung |
|---|---|---|
| **FussballTurnier** (Pascal) | Jul 2026 | Turnierverwaltung (Delphi/VCL): 2 Gruppen + KO-Runde mit Beamer-Turnierbaum, Tabelle/Ergebnisse, Aushang als HTML/PDF, Veranstalter-Branding. |
| **FtvcsskiV8** (JS) | Aug – Sep 2025 | Fußball-Manager im Browser, über einen Server betrieben. |
| **ftverwaltung** (Pascal) | Jul 2025 | Turnierleitung: Ansichten für Tabelle, Ergebnisliste und aktuelles Spiel. |
| **ftmanager** (JS) | Jul 2025 | Fußball-Turnier im Browser — „alles auf einer Card". |
| **soccer** (JS) 🔒 | Jan 2026 | Fußball-bezogenes Arbeitsrepository (ohne Beschreibung). |

## 🍦 Eisdiele (Kasse & Abrechnung) (3)

| Projekt | Zeitraum | Kurzbeschreibung |
|---|---|---|
| **eisdiele** (Pascal) | Mai 2026 | Abrechnungs-/Kassenprogramm für eine Eisdiele. |
| **eisdielerw** (HTML) | Mai 2026 | Eisdielen-Anwendung als Browser-Version. |
| **eisdielezw** (HTML) | Mai – Jun 2026 | Eisdiele mit Schwerpunkt Sicherheit/Zugriff (Zwischenstand). |

## 🛠️ CAD & Konstruktion (1)

| Projekt | Zeitraum | Kurzbeschreibung |
|---|---|---|
| **konstruktionrw** | Jun 2026 | Konstruieren mit CAD + Künstlicher Intelligenz, ausgelegt für 3D-Druck / Metalldruck. |

## 💻 Delphi-/TMS-Entwicklung & CSS-Layout (4)

| Projekt | Zeitraum | Kurzbeschreibung |
|---|---|---|
| **DelphiSkills** (Pascal) 🔒 | Jul 2026 | KI-gestützte Delphi-Entwicklung: VCL, TMS Web Core und Android-APK — Werkzeugkette und Vorgehensweise. |
| **SiloVisu** (Pascal) | Dez 2025 – Mär 2026 | Anlagen-Visualisierung (z. B. Silo-/Prozessdarstellung). |
| **navicsscard** (JS) | Jul 2025 | CSS-Layout (Karten/Navigation) für Delphi-Web-Oberflächen. |
| **TmsCss** (JS) | Jul 2025 | Delphi/TMS-Basis-Layout mit CSS. |

## 🗂️ Versionierung & Test-/Lern-Repositories (6)

| Projekt | Zeitraum | Kurzbeschreibung |
|---|---|---|
| **gitrepo** 🔒 | Apr 2026 | Versionskontrolle — Übungs-/Ablage-Repository. |
| **gitrw** | Dez 2025 | Git-Test-/Ablage-Repository. |
| **rwversion** (HTML) 🔒 | Jul 2025 | Versionen verwalten — Werkzeug/Übung. |
| **rwtestrepository** (Pascal) 🔒 | Jul 2025 | Zu Testzwecken angelegt. |
| **RwTepoTest** 🔒 | Jan 2025 | Erstes Ausprobieren von Repositories. |
| **desktop-tutorial** 🔒 | Jan 2025 | GitHub-Desktop-Tutorial-Repository. |

---

*Projektübersicht · GitHub RwHexa · erstellt mit Claude Code · Stand 26.07.2026*
