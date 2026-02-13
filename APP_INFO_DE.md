# Prüfungstimer - iPad Prüfungs-Timer App

![App Icon](ExamTimer/Assets.xcassets/AppIcon.appiconset/exam-timer-icon1024px.png)

## Über die App

**Prüfungstimer** ist eine spezialisierte iPad-Anwendung für synchronisierte Prüfungszeitmessung an der Universität St. Gallen (HSG) im Medizinstudium. Die App gewährleistet faire und koordinierte Prüfungsabläufe in mehreren Prüfungszonen.

## Funktionen

### 📱 **iPad-optimierte Benutzeroberfläche**
- Vollbild-Querformat-Timer-Anzeige
- Große, gut lesbare Countdown-Timer mit Fortschrittsring
- Geteilte Bildschirmansicht mit Zeitplan und Haupt-Timer

### ⏰ **Synchronisierte Zeitmessung**
- Echtzeitsynchronisation mit zentraler Prüfungsdatenbank
- Automatische Zeitzonenverwaltung (Europe/Zurich)
- Uhrzeit-Drift-Erkennung und Warnungen

### 🔔 **Intelligente Benachrichtigungen**
- Vorprüfungswarnungen ("Startposition einnehmen")
- Prüfungsstart-Benachrichtigungen
- Vorabschluss-Warnungen ("Noch 2 Minuten")
- Prüfungsende-Benachrichtigungen ("Ende der Prüfung")

### 🌟 **Prüfungsverwaltung**
- Unterstützung mehrerer Zonen (A, B, C, D)
- Heutiger Prüfungsplan-Überblick
- Live-Fortschrittsverfolgung während Prüfungen
- Offline-Funktionalität mit zwischengespeicherten Plänen

### 🎥 **Videoaufzeichnung** *(Neu in v1.2)*
- Automatische Videoaufnahme während Prüfungssitzungen über die Frontkamera
- H.265/HEVC-Kodierung für effiziente Videokomprimierung
- Audioaufnahme zusammen mit Video
- Aufnahmenverwaltung: Ansehen, Abspielen und Löschen von Aufzeichnungen in den Einstellungen
- Responsiver Videoplayer, der sich an verschiedene iPad-Größen anpasst
- Unabhängige Soundsteuerung — Aufnahme-Schalter ist getrennt von den Prüfungstönen
- Sicherheitskontrollen — Aufnahme kann während aktiver Prüfungssitzungen nicht umgeschaltet werden

### 🤖 **KI-Assistent** *(Experimentell, Neu in v1.2)*
- Spracherkennung auf dem Gerät (erfordert iPadOS 26+ mit Apple Intelligence)
- WebVTT-Untertitelerstellung für aufgezeichnete Videos
- Working-Alliance-Bewertung anhand dreier Dimensionen (Bindung, Ziele, Aufgaben)
- Interaktiver Chat für Folgefragen zu Bewertungen
- Mehrsprachige Unterstützung (Deutsch, Englisch, Französisch, Italienisch)
- Alle KI-Verarbeitung läuft vollständig auf dem Gerät — keine Daten werden an externe Server gesendet

### 🎵 **Benutzerdefiniertes Audio**
- Professionelle deutsche Audio-Benachrichtigungen
- Sound-Tests in den Einstellungen
- Optimiertes Audio für Prüfungsumgebungen

### 🌙 **Display-Optimierung**
- Verhindert Bildschirmruhezustand während Prüfungen
- Automatische Helligkeitsverwaltung
- Dark Mode für längere Nutzung optimiert

## Technische Spezifikationen

- **Plattform:** iPad (iPadOS 26+)
- **Sprache:** Deutsch/Englisch
- **Datenbank:** Firebase Firestore
- **Architektur:** SwiftUI mit Combine
- **Video:** H.265/HEVC-Kodierung mit AVFoundation
- **KI:** Apple Foundation Models & SpeechAnalyzer (auf dem Gerät)
- **Audio:** CAF-Format für Zuverlässigkeit

## Datenschutz

**Es werden keine persönlichen Daten erhoben oder an externe Server übertragen.** Prüfungspläne werden von einer sicheren Datenbank abgerufen. Videoaufzeichnungen, Transkriptionen und KI-Bewertungen werden ausschließlich auf Ihrem Gerät gespeichert und verarbeitet. Siehe unsere [Datenschutzerklärung](DATENSCHUTZ.md) für vollständige Details.

## Installation

Verfügbar im Apple App Store für autorisierte HSG-Medizinprüfungsnutzung.

## Entwickler

**Tobias Kowatsch**
Universität Zürich und Universität St. Gallen
tobias.kowatsch@unisg.ch

## Lizenz

Entwickelt für Prüfungszwecke der Universität St. Gallen im Medizinstudium.

---

*Für technischen Support oder Fragen wenden Sie sich bitte an den Entwickler.*