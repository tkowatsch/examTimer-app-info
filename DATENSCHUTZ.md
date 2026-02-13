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
- **Videoaufzeichnungen:** Wenn die Aufnahmefunktion aktiviert ist, werden Video und Audio über die Frontkamera und das Mikrofon des Geräts aufgenommen und ausschließlich lokal auf dem Gerät gespeichert. Aufzeichnungen sind für die kurzfristige Nutzung während des Prüfungszeitraums vorgesehen — sie werden vor Beginn der nächsten Prüfungssitzung automatisch gelöscht, und Benutzer können sie jederzeit auch manuell in den App-Einstellungen löschen. Aufzeichnungen werden niemals auf externe Server hochgeladen oder dort gespeichert.
- **Transkriptionen und KI-Bewertungen:** Bei Nutzung der KI-Assistentenfunktion wird Audio auf dem Gerät mithilfe von Apples SpeechAnalyzer-Framework transkribiert. KI-Bewertungen werden auf dem Gerät mithilfe von Apples lokalem Large Language Model (LLM) über Apple Foundation Models erstellt. **Die gesamte KI-Verarbeitung läuft vollständig auf der Neural Engine des Geräts — es werden keine Daten an Apple-Server oder andere Cloud-Dienste gesendet.** Keine Audio-, Transkriptions- oder Bewertungsdaten verlassen das Gerät. Hinweis: Diese Funktion erfordert ein iPad mit Apple-Intelligence-Unterstützung (iPad Pro M1+, iPad Air M1+ oder iPad mini A17 Pro) mit iPadOS 26 oder neuer. Das Standard-iPad unterstützt diese Funktion nicht. Der KI-Assistent wird auf nicht unterstützten Geräten automatisch ausgeblendet.
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
- Videoaufzeichnungen werden temporär lokal auf dem Gerät gespeichert und vor der nächsten Prüfung automatisch gelöscht
- KI-Verarbeitung erfolgt vollständig auf dem Gerät mittels Apples lokalem LLM (es werden keine Cloud-KI-Dienste verwendet)
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