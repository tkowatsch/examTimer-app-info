# Privacy Policy for Prüfungstimer (Exam Timer)

**Effective Date: February 13, 2026**

## About This App

Prüfungstimer (Exam Timer) is an iPad application designed specifically for medical examinations at HSG (University of St. Gallen). The app provides synchronized exam timing, notifications, schedule management, optional video recording of exam sessions, and an experimental AI assistant for assessment — all to ensure fair and coordinated examination procedures.

## Contact Information

**Developer:** Tobias Kowatsch
**Email:** tobias.kowatsch@unisg.ch
**Institution:** Universität Zürich and Universität St. Gallen

## Data Collection and Privacy

### No Personal Data Collection
**Prüfungstimer does not collect, store, or transmit any personal data to external servers.** The app is designed with privacy as a fundamental principle.

### App Functionality
The app operates by:
- Connecting to a Firestore database to retrieve exam schedules
- Displaying exam timing information locally on your device
- Playing notification sounds during exam periods
- Managing display brightness for optimal visibility
- Optionally recording video and audio during exam sessions (stored locally on the device only)
- Optionally transcribing recorded audio and generating AI-based assessments using on-device Apple Intelligence (no data is sent to external servers)

### Data Usage
- **Exam Schedules:** The app retrieves exam timing data from a secure Firestore database. This data contains only exam times, zones, and scheduling information — no personal or identifying information.
- **Local Storage:** The app may cache exam schedules locally on your device for offline functionality. This cached data remains on your device and is not transmitted elsewhere.
- **Video Recordings:** When the recording feature is enabled, video and audio are captured using the device's front camera and microphone and stored exclusively on the local device. Recordings are never uploaded to external servers. Users can view, play back, and delete recordings at any time from the app's settings.
- **Transcriptions and AI Assessments:** When the AI assistant feature is used (requires iPadOS 26+ with Apple Intelligence), audio is transcribed on-device using Apple's SpeechAnalyzer framework. AI assessments are generated on-device using Apple Foundation Models. No audio, transcript, or assessment data is transmitted to external servers.
- **No Analytics:** The app does not use any analytics, tracking, or advertising services.
- **No User Accounts:** The app does not require user registration or login.

### Device Permissions
The app requests the following permissions solely for its core functionality:
- **Notifications:** To display exam timing alerts
- **Audio Playback:** To play notification sounds
- **Camera:** To record video during exam sessions (only when recording is enabled by the user)
- **Microphone:** To capture audio during exam video recordings (only when recording is enabled by the user)
- **Network Access:** To retrieve exam schedules from the database

### Third-Party Services
The app uses Firebase Firestore (Google) solely for retrieving exam schedule data. No personal information is transmitted to or stored in these services. The video recording, transcription, and AI assessment features operate entirely on-device and do not use any third-party services.

### Data Security
- All exam schedule data is transmitted over secure HTTPS connections
- No user data is stored on external servers
- Video recordings and transcriptions are stored only on the local device
- AI processing is performed entirely on-device using Apple Intelligence
- The app operates in a read-only mode regarding exam data

### Children's Privacy
This app is designed for educational use and does not knowingly collect any information from users under 13 years of age.

## Changes to This Privacy Policy

We may update this privacy policy from time to time. Any changes will be reflected by updating the effective date at the top of this policy.

## Contact Us

If you have any questions about this privacy policy or the Prüfungstimer app, please contact:

**Tobias Kowatsch**
Universität Zürich and Universität St. Gallen
Email: tobias.kowatsch@unisg.ch

---

*This privacy policy was last updated on February 13, 2026*