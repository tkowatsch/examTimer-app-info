# Prüfungstimer - iPad Exam Timer App

![App Icon](ExamTimer/Assets.xcassets/AppIcon.appiconset/exam-timer-icon1024px.png)

## About

**Prüfungstimer** is a specialized iPad application designed for synchronized examination timing at the University of St. Gallen (HSG) medical program. The app ensures fair and coordinated exam procedures across multiple examination zones.

## Features

### 📱 **iPad Optimized Interface**
- Full-screen landscape timer display
- Large, easily readable countdown timers with progress ring
- Split-screen layout with schedule and main timer

### ⏰ **Synchronized Timing**
- Real-time synchronization with central exam database
- Automatic timezone handling (Europe/Zurich)
- Clock drift detection and warnings

### 🔔 **Smart Notifications**
- Pre-exam warnings ("Startposition einnehmen")
- Exam start notifications
- Pre-end warnings ("Noch 2 Minuten")
- Exam end notifications ("Ende der Prüfung")

### 🌟 **Exam Management**
- Multiple zone support (A, B, C, D)
- Today's exam schedule overview
- Live progress tracking during exams
- Offline functionality with cached schedules

### 🎥 **Video Recording** *(New in v1.2)*
- Automatic video recording during exam sessions using the front camera
- H.265/HEVC encoding for efficient video compression
- Audio capture alongside video
- Recordings are stored temporarily on the iPad and automatically deleted before the next exam session
- Recording management: view, play back, and manually delete recordings from settings
- Responsive video player adapting to different iPad sizes
- Independent sound control — recording toggle is separate from exam audio
- Safety controls — recording cannot be toggled during active exam sessions

### 🤖 **AI Assistant** *(Experimental, New in v1.2)*
> **Important:** The AI assistant requires an iPad with Apple Intelligence support — this means iPad Pro (M1 or later), iPad Air (M1 or later), or iPad mini (A17 Pro). The standard iPad does not support Apple Intelligence due to hardware limitations (minimum 8 GB RAM required). iPadOS 26+ is also required. The AI assistant button is automatically hidden on unsupported devices.

- Powered by Apple's local on-device LLM via Apple Intelligence — no cloud AI services are used
- On-device speech-to-text transcription
- WebVTT subtitle generation for recorded videos
- Working Alliance assessment using three dimensions (Bond, Goals, Tasks)
- Interactive chat for follow-up questions about assessments
- Multi-language support (German, English, French, Italian)
- All processing runs entirely on the device's Neural Engine — no data is sent to Apple servers or any other external service

### 🎵 **Custom Audio**
- Professional German audio notifications
- Sound testing in settings
- Optimized audio for exam environments

### 🌙 **Display Optimization**
- Prevents screen sleep during exams
- Automatic brightness management
- Dark mode optimized for extended use

## Technical Specifications

- **Platform:** iPad (iPadOS 26+)
- **Language:** German/English
- **Database:** Firebase Firestore
- **Architecture:** SwiftUI with Combine
- **Video:** H.265/HEVC encoding with AVFoundation
- **AI:** Apple Foundation Models & SpeechAnalyzer (on-device)
- **Audio:** CAF format for reliability

## Privacy

**No personal data is collected or transmitted to external servers.** Exam schedules are retrieved from a secure database. Video recordings, transcriptions, and AI assessments are stored and processed exclusively on your device. See our [Privacy Policy](PRIVACY_POLICY.md) for complete details.

## Installation

Available on the Apple App Store for authorized HSG medical examination use.

## Developer

**Tobias Kowatsch**
Universität Zürich und Universität St. Gallen
tobias.kowatsch@unisg.ch

## License

Developed for University of St. Gallen medical examination purposes.

---

*For technical support or questions, please contact the developer.*