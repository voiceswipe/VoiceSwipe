# Privacy Policy — Voice Swipe

*Last updated: October 2026*

## 1. What stays on your phone

Voice Swipe does not ask you to register or create an account. We do not operate our own servers. Microphone audio, camera images, face information, and what the accessibility service observes are processed on your phone and are not sent to us.

## 2. Microphone

The microphone permission is used only in Voice mode, to recognize commands. Audio is processed on the phone as it is captured, using Vosk and Silero VAD. It is not saved to a file and it is not sent to any server.

## 3. Camera: hand gestures and head control

The front camera is used in Gestures mode and in Head control, only while that mode is active. Each frame is analyzed immediately and is not saved or sent.

- **Gestures:** MediaPipe recognizes a hand gesture (for example, next, previous, or pause).
- **Head control:** MediaPipe Face Landmarker computes face landmarks and the head angle to detect a tilt (next video, previous video, or pause). It does not identify who you are, it does not build a face template to recognize you later, and it does not save photos.

The calibration and practice previews also stay on the phone.

## 4. Accessibility

The accessibility service swipes the feed and pauses or resumes playback in supported apps (TikTok, Instagram Reels, Facebook Reels, and YouTube Shorts). It performs those gestures only after one of the following: a voice command recognized on the phone, a hand gesture, a head movement, or the Autoscroll interval you chose.

We also read which app or window is in the foreground, so the microphone, the camera, and Autoscroll turn on or off accordingly.

We do not read messages, conversations, posts, or text from other apps. We do not offer remote control of the phone. We do not change files or saved data inside other apps.

## 5. Usage access

On some phones, such as Xiaomi, Android does not reliably report which app is in front. In that case we ask for Usage Access and read only the package name of the foreground app, on the phone, to decide whether the microphone or the camera should be active. We do not read your usage history and we do not send that information.

## 6. Purchases

Purchases that unlock supported apps are processed by Google Play. We do not receive your card number or billing address. We only learn whether a purchase for this app is active on this device. Google handles payment data under its own policy: [policies.google.com/privacy](https://policies.google.com/privacy).

## 7. Internet

After setup, Voice Swipe works offline. Internet is used for two things:

- Downloading a Vosk language pack when one is needed. Spanish is included in the app. English is downloaded from GitHub and Portuguese from the Vosk project site (alphacephei.com).
- Completing a purchase through Google Play.

We do not upload audio, images, or accessibility data.

## 8. Analytics and ads

There is no analytics, advertising, or diagnostic reporting that leaves the phone. The persistent notification is shown by the phone itself while the service is running. It is not a message sent from a server of ours.

## 9. Libraries

- Vosk: speech recognition, on the phone.
- Silero VAD, with ONNX Runtime: detects whether someone is speaking, on the phone.
- MediaPipe: hand gestures and face landmarks, on the phone.
- CameraX: camera access, on the phone.
- Google Play Billing: talks to Google Play only for the purchase.

The recognition libraries do not transmit your audio, your images, or your face information.

## 10. Changes

If this policy changes, you will see it in an app update on Google Play and on this page.

## 11. Contact

For questions or comments regarding this privacy policy: [voiceswipe@gmail.com](mailto:voiceswipe@gmail.com)
