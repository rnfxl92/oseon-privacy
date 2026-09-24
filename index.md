---
title: Oseon Privacy Policy
---

# Oseon 개인정보 처리방침

시행일: 2026년 9월 25일 (문제 진단 정보 추가로 개정)

Oseon(이하 "앱")은 iPad와 iPhone용 악보 앱입니다. 앱이 자동으로 보내는 정보로는 개발자가 앱을 쓰는 사람이 누구인지 알 수 없습니다.

**개발자가 받는 정보.** 앱에는 개발자가 운영하는 서버, 계정, 광고, 추적 기능이 없습니다. 앱이 자동으로 개발자에게 보내는 것은 아래 "문제 진단 정보"뿐이며, 이 정보는 신원과 연결되지 않습니다. 사용자가 직접 문의 메일을 보내면 개발자는 그 메일을 받습니다(아래 "문의"). 제3자 서비스(Google)를 거치는 것은 푸시 알림과 문제 진단 정보 두 가지입니다.

**iCloud.** 가져온 악보, 필기, 셋리스트는 기기와 사용자 본인의 iCloud 계정(iCloud Drive·CloudKit)에만 저장됩니다. 개발자는 이 데이터를 볼 수 없습니다. iCloud 데이터는 [Apple 개인정보 처리방침](https://www.apple.com/kr/legal/privacy/)을 따릅니다.

**카메라.** 종이 악보를 스캔할 때, 그리고 사용자가 "핸즈프리 넘김"를 켰을 때만 제스처(입 벌리기·눈 깜빡임)를 감지하려고 카메라를 씁니다. 제스처 감지 영상은 기기 안에서만 처리되고 저장하거나 전송하지 않습니다.

**악보 인식.** 사용자가 "악보 인식"을 실행하면 해당 페이지 이미지가 Apple의 Private Cloud Compute로 보내져 처리됩니다. 이 처리는 Apple이 수행하며 개발자에게 전달되지 않습니다. 자세한 내용은 [Apple Private Cloud Compute](https://security.apple.com/blog/private-cloud-compute/)를 참고하세요.

**푸시 알림(Firebase Cloud Messaging).** 새 기능 소식("오선 새 소식")을 보내려고 Google의 Firebase Cloud Messaging을 씁니다. 앱이 실행되면 기기의 푸시 토큰, Firebase 설치 식별자, 앱 버전·OS 버전 같은 기본 정보가 Google에 전달되어 알림을 받을 기기로 등록됩니다. 이 식별자는 이름·이메일 같은 신원 정보와 연결되지 않고, 광고나 추적에 쓰이지 않습니다. 알림 권한을 허용하고 설정 → 알림의 "오선 새 소식"이 켜져 있을 때만 공지 대상에 포함되며, 이 스위치나 iOS 설정에서 언제든 끌 수 있습니다. Google의 처리는 [Firebase 개인정보 보호](https://firebase.google.com/support/privacy)를 따릅니다. iCloud 동기화를 위한 푸시는 Apple이 직접 처리합니다.

**문제 진단 정보(Firebase Crashlytics·Performance Monitoring).** 앱이 제대로 동작하도록 오류를 고치고, 어떤 기능이 느린지 분석하려고 Google의 Firebase Crashlytics와 Performance Monitoring을 씁니다. Google로 전송되는 정보는 다음과 같습니다.
- 비정상 종료 기록: 오류가 난 코드 위치, 앱·OS 버전, 기기 모델
- 성능 기록: 악보 열기·가져오기·조판·페이지 그리기·악보 인식 같은 동작이 걸린 시간과 그 결과(성공·실패·취소), 악보의 페이지 수 범위, 앱 시작 시간
- 이를 묶기 위한 앱 설치 단위의 임의 식별자와 앱 사용 세션(앱을 연 시각과 순서) 정보

Google은 국가별 통계를 위해 IP 주소로 대략적인 국가를 추정할 수 있습니다. 앱은 이 정보에 악보의 제목이나 내용을 넣지 않습니다. 이 정보는 이름·이메일 같은 신원 정보와 연결되지 않으며, 광고나 추적에 쓰이지 않습니다. 출시 버전에서는 문제 진단 정보가 자동으로 수집되며, 앱 안에 이를 끄는 설정은 없습니다. 알림을 꺼도 진단 수집은 계속됩니다. Google의 처리는 [Firebase 개인정보 보호](https://firebase.google.com/support/privacy)를 따릅니다.

**문의.** rnfxl92@gmail.com — 앱의 설정 → 문의하기로 메일을 쓰면 본문 끝에 앱 버전, 기기 모델 식별자(예: iPad16,3), OS 버전, 메일 창을 연 시각(UTC, 시 단위)이 미리 채워집니다. 보내기 전에 지우거나 고칠 수 있습니다. 보내 주신 이메일 주소와 내용은 답변과 문제 해결에만 쓰고, 문제 진단 정보를 특정 개인과 연결하는 데 쓰지 않습니다.

이 방침이 바뀌면 이 페이지를 고치고 시행일을 갱신합니다.

---

# Oseon Privacy Policy

Effective date: September 25, 2026 (revised for diagnostics)

Oseon ("the app") is a sheet-music app for iPad and iPhone. Nothing the app sends automatically lets the developer tell who you are.

**Information the developer receives.** The app has no developer-run server, no accounts, no ads and no tracking. The only thing the app sends to the developer automatically is the "Diagnostics" described below, which is not linked to your identity. If you write to the developer yourself, the developer receives that email (see "Contact"). Two things go through a third-party service (Google): push notifications and diagnostics.

**iCloud.** Scores, annotations and setlists you add are stored only on your device and in your own iCloud account (iCloud Drive and CloudKit). The developer cannot see this data. iCloud data is covered by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

**Camera.** The app uses the camera to scan paper sheet music and, only when you turn on Hands-Free Turn, to detect a page-turn gesture (holding your mouth open or blinking). Gesture video is processed on the device and is never stored or sent.

**Score recognition.** When you run Recognize Score, the page images are sent to Apple's Private Cloud Compute for processing. Apple performs this processing; nothing is sent to the developer. See [Apple Private Cloud Compute](https://security.apple.com/blog/private-cloud-compute/).

**Push notifications (Firebase Cloud Messaging).** The app uses Google's Firebase Cloud Messaging to send occasional news about new features ("New from Oseon"). When the app runs, the device's push token, a Firebase installation identifier and basic information such as the app and OS version are sent to Google to register the device for notifications. These identifiers are not linked to your name, email or any other identity and are not used for advertising or tracking. Your device receives announcements only if you allow notifications and "New from Oseon" is on in Settings > Notifications; you can turn it off there or in iOS Settings at any time. Google's processing is covered by [Privacy and Security in Firebase](https://firebase.google.com/support/privacy). Push messages for iCloud sync are handled by Apple directly.

**Diagnostics (Firebase Crashlytics and Performance Monitoring).** To keep the app working by fixing errors, and to analyze which features are slow, the app uses Google's Firebase Crashlytics and Performance Monitoring. The following is sent to Google:
- Crash reports: where in the code the error happened, app and OS version, device model
- Performance records: how long actions such as opening, importing, engraving, drawing a page or recognizing a score took and how they ended (success, failure or cancelled), the page-count range of the score, and app start time
- A random per-installation identifier and app session information (when and in what order the app was opened) used to group them

Google may estimate your approximate country from your IP address for country-level statistics. The app does not put the titles or contents of your scores into this information. It is not linked to your name, email or any other identity and is not used for advertising or tracking. Diagnostics are collected automatically in release versions; the app has no setting to turn them off, and turning off notifications does not stop diagnostics. Google's processing is covered by [Privacy and Security in Firebase](https://firebase.google.com/support/privacy).

**Contact.** rnfxl92@gmail.com — If you write through Settings > Contact Support in the app, the end of the message is pre-filled with the app version, device model identifier (for example iPad16,3), OS version and the time you opened the message (UTC, to the hour). You can delete or change these before sending. Your email address and message are used only to reply and solve the problem, and are never used to link diagnostics to a particular person.

If this policy changes, this page will be updated along with its effective date.
