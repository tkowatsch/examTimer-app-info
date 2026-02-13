# Datenschutzerklärung für Prüfungstimer

**Gültig ab: 13. Februar 2026**

## Über diese App

Prüfungstimer ist eine iPad-Anwendung, die speziell für medizinische Prüfungen an der Universität St. Gallen (HSG) entwickelt wurde. Die App bietet synchronisierte Prüfungszeitmessung, Benachrichtigungen, Terminverwaltung, optionale Videoaufzeichnung von Prüfungssitzungen sowie einen experimentellen KI-Assistenten zur Bewertung — alles um faire und koordinierte Prüfungsabläufe zu gewährleisten.

## Kontaktinformationen

**Entwickler:** Tobias Kowatsch
**E-Mail:** tobias.kowatsch@unisg.ch
**Institution:** Universität Zürich und Universität St. Gallen

## Datenerhebung und Datenschutz

### Keine Erhebung persönlicher Daten
**Prüfungstimer erhebt, speichert oder überträgt keine persönlichen Daten an externe Server.** Die App wurde mit dem Grundsatz des Datenschutzes entwickelt.

### App-Funktionalität
Die App funktioniert durch:
- Verbindung zu einer Firestore-Datenbank zum Abrufen von Prüfungsplänen
- Lokale Anzeige von Prüfungszeiten auf Ihrem Gerät
- Abspielen von Benachrichtigungstönen während Prüfungszeiten
- Verwaltung der Bildschirmhelligkeit für optimale Sichtbarkeit
- Optionale Aufzeichnung von Video und Audio während Prüfungssitzungen (nur lokal auf dem Gerät gespeichert)
- Optionale Transkription aufgezeichneter Audiodaten und Erstellung KI-basierter Bewertungen mittels geräteeigener Apple Intelligence (keine Daten werden an externe Server gesendet)

### Datenverwendung
- **Prüfungspläne:** Die App ruft Prüfungszeitdaten von einer sicheren Firestore-Datenbank ab. Diese Daten enthalten nur Prüfungszeiten, Zonen und Terminplaninformationen — keine persönlichen oder identifizierenden Informationen.
- **Lokale Speicherung:** Die App kann Prüfungspläne lokal auf Ihrem Gerät zwischenspeichern für Offline-Funktionalität. Diese zwischengespeicherten Daten verbleiben auf Ihrem Gerät und werden nicht weitergegeben.
- **Videoaufzeichnungen:** Wenn die Aufnahmefunktion aktiviert ist, werden Video und Audio über die Frontkamera und das Mikrofon des Geräts aufgenommen und ausschließlich lokal auf dem Gerät gespeichert. Aufzeichnungen werden niemals auf externe Server hochgeladen. Benutzer können Aufzeichnungen jederzeit in den App-Einstellungen ansehen, abspielen und löschen.
- **Transkriptionen und KI-Bewertungen:** Bei Nutzung der KI-Assistentenfunktion (erfordert iPadOS 26+ mit Apple Intelligence) wird Audio auf dem Gerät mithilfe von Apples SpeechAnalyzer-Framework transkribiert. KI-Bewertungen werden auf dem Gerät mithilfe von Apple Foundation Models erstellt. Keine Audio-, Transkriptions- oder Bewertungsdaten werden an externe Server übertragen.
- **Keine Analytik:** Die App verwendet keine Analyse-, Tracking- oder Werbedienste.
- **Keine Benutzerkonten:** Die App erfordert keine Benutzerregistrierung oder Anmeldung.

### Geräteberechtigungen
Die App fordert folgende Berechtigungen ausschließlich für ihre Kernfunktionalität an:
- **Benachrichtigungen:** Zur Anzeige von Prüfungszeitalerts
- **Audiowiedergabe:** Zum Abspielen von Benachrichtigungstönen
- **Kamera:** Zur Videoaufzeichnung während Prüfungssitzungen (nur wenn die Aufnahme vom Benutzer aktiviert ist)
- **Mikrofon:** Zur Audioaufnahme bei Prüfungs-Videoaufzeichnungen (nur wenn die Aufnahme vom Benutzer aktiviert ist)
- **Netzwerkzugriff:** Zum Abrufen von Prüfungsplänen aus der Datenbank

### Drittanbieterdienste
Die App verwendet Firebase Firestore (Google) ausschließlich zum Abrufen von Prüfungsplanadaten. Es werden keine persönlichen Informationen an diese Dienste übertragen oder dort gespeichert. Die Funktionen für Videoaufzeichnung, Transkription und KI-Bewertung arbeiten vollständig auf dem Gerät und verwenden keine Drittanbieterdienste.

### Datensicherheit
- Alle Prüfungsplanadaten werden über sichere HTTPS-Verbindungen übertragen
- Es werden keine Benutzerdaten auf externen Servern gespeichert
- Videoaufzeichnungen und Transkriptionen werden nur lokal auf dem Gerät gespeichert
- KI-Verarbeitung erfolgt vollständig auf dem Gerät mittels Apple Intelligence
- Die App arbeitet im Nur-Lese-Modus bezüglich Prüfungsdaten

### Datenschutz für Minderjährige
Diese App ist für den Bildungsbereich konzipiert und sammelt wissentlich keine Informationen von Benutzern unter 13 Jahren.

## Änderungen dieser Datenschutzerklärung

Wir können diese Datenschutzerklärung von Zeit zu Zeit aktualisieren. Änderungen werden durch Aktualisierung des Gültigkeitsdatums am Anfang dieser Erklärung bekannt gegeben.

## Kontakt

Bei Fragen zu dieser Datenschutzerklärung oder zur Prüfungstimer-App wenden Sie sich bitte an:

**Tobias Kowatsch**
Universität Zürich und Universität St. Gallen
E-Mail: tobias.kowatsch@unisg.ch

---

*Diese Datenschutzerklärung wurde zuletzt am 13. Februar 2026 aktualisiert*