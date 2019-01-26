# SwampHacks
### What it does
SafeX provides the user to register a hot-word into the application. The application continuously monitors the voice nearby the phone and tries to match the hot-word to that of the speech. On the word match, it triggers an alarm and a series of messages engraved with the user's current location to the user's trusted contacts. Also, SafeX starts recording audio on the word match, which could later be used as evidence.
### How we built it
We built using the Android Studio taking help of native Android libraries like AudioManager, SpeechRecognizer. We built the UI so that it could accommodate the addition and deletion of trusted contacts. The hot-word can be set/edit by the user at any point in time.
