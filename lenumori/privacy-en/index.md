---
title: Lenumori Privacy Policy
lang: en
---

# Lenumori Privacy Policy

Effective date: 2026-10-16

This is an English translation of the Korean Lenumori privacy policy. If the two versions differ, the Korean version prevails.

Lenumori ("the app") cares about your personal information and your photos.
This privacy policy explains what information Lenumori accesses, why it uses that information,
and how it protects it.

## 1. Basic principles

Lenumori is designed to work Offline First.

The app's core features, including taking photos and videos, applying filters, organizing photos, and saving and searching tags,
are processed on your device wherever possible.

As a basic principle, the app does not upload or store your photos on servers run by the Lenumori operator.

The app is free and shows ads (Google AdMob).
For advertising, Google may collect device information and the advertising ID. Your photos, videos and tags are never used for ads and never leave your device.
If you buy Premium, no ads are shown.

## 2. Information the app can access

### Camera

Used for:
- Taking photos
- Recording videos
- Camera preview
- Switching between front and back cameras
- Flash and zoom

Camera access is used to provide the features you need when taking photos or recording videos.

### Microphone

Used for:
- Recording sound together with a video

The microphone is used only while you record a video by holding the shutter button on the camera screen.
The recorded sound is stored only inside the video file and is never sent off your device.
If you do not allow microphone access, you can still take photos and record videos without sound.

### Photos and media

Used for:
- Saving photos and videos taken with Lenumori
- Showing the list of photos and videos in the app
- Showing, playing and organizing photos and videos taken with Lenumori
- Linking tags to photos to provide search
- Deleting photos and videos taken with Lenumori when you ask
- Sharing photos and videos when you ask

Lenumori is designed not to access your photos beyond what is needed.
On Android 10 and later, the app does not request photo access permission and saves and manages only photos and videos taken with Lenumori.
On Android 9 and earlier, the app requests storage write permission to save photos and videos to the Pictures folder.
Videos are not analyzed by AI.

### On-device AI analysis

On supported devices, the app can analyze photo content and create tags such as:

Examples:
- cat
- ocean
- sunset
- food
- travel

This analysis is done on your device using Google ML Kit (image labeling, GenAI image description / Gemini Nano).
Photos used for analysis are never sent off your device.

The tags and analysis results are stored on your device by default.

On devices that are not supported, only AI tags are unavailable; taking, saving and organizing photos work as usual.
If the AI model is not on your device, the Android system (AICore) may download it from Google.

When the app language is Korean, the English photo description created by AI is translated into Korean on your device using Google ML Kit Translation.
The language model needed for translation (about 30 MB) is downloaded once from Google, and the text being translated is never sent off your device.
When the app language is English, nothing is translated and the translation model is not downloaded.

## 3. Sending data to external servers

In Lenumori's current design, the following data is not sent to servers run by the Lenumori operator:

- Photos and videos you take (including recorded sound)
- Photos in your gallery
- Photo tags created by AI
- Photo search history

### Sharing photos yourself

When you tap "Share" on the photo screen, the Android share sheet opens.
Photos and videos are sent only to the app you choose in the share sheet,
and Lenumori never sends your photos to external servers or anywhere else on its own.
After sharing, the app you chose handles the content under its own privacy policy.

### Google ML Kit usage statistics

Google ML Kit, used for on-device AI analysis, sends the following usage information to Google
to improve features and diagnose problems (sent encrypted over HTTPS):

- Device information: manufacturer, model, OS version, AI acceleration hardware information
- App information: app package name, app version
- A per-installation identifier (not used to identify you personally)
- Performance information: processing time, error codes, input and output sizes and other API usage information

This information does not include photos, photo description results (including translations) or tags.
For details, see Google's ML Kit data disclosure (https://developers.google.com/ml-kit/android-data-disclosure).

### Ads (Google AdMob)

The app shows banner ads at the bottom of the library and photo screens, and rewarded ads you choose to watch (to use a locked filter for 24 hours).
Ads are provided by Google's Google Mobile Ads SDK. For serving ads, measuring ad performance, preventing invalid clicks and (if you consent) personalized ads,
Google and Google's advertising partners may collect and process the following information:

- Advertising ID (Android advertising ID), app set ID (a per-device ID that groups apps from the same developer)
- Device information: manufacturer, model, OS version, screen size, language
- IP address and approximate location estimated from it (precise location and GPS are not used)
- App and ad usage information: app launches, taps, ad impressions and clicks, whether a rewarded ad was watched
- App and diagnostic information: app name and version, performance information such as app launch time, error information

This information does not include photos, videos, recorded sound, tags or AI analysis results.
Google's use of data follows https://policies.google.com/technologies/partner-sites.

About personalized ads (behavioral information):
- For personalized ads, the advertising ID and app and ad usage information (behavioral information) may be provided to Google.
- If you do not want personalized ads, you can delete or reset your advertising ID in your phone's Settings > Google > Ads.
- In regions that require consent, such as the European Economic Area (EEA) and the UK, the app shows a consent form the first time it prepares ads,
  and you can change your consent at any time in the app's "Settings > Ad privacy settings".
- For Premium users, the ad SDK is not started, so no information is sent for advertising.

### Payments (Google Play)

Premium (no ads + all filters) is purchased through Google Play billing.
Payment information such as card numbers is handled by Google; the Lenumori operator does not receive it.
To check whether you bought Premium, the app queries your purchase history on Google Play (whether you purchased, purchase verification information)
and stores only the result (whether you have Premium) on your device.

If features such as cloud sync, external AI or analytics SDKs are added in the future,
this privacy policy and the Google Play Data safety information will be updated to match.

## 4. Information stored on your device

To provide its features, the app may store the following information on your device:

- Photo and video files or URIs
- Photo and video capture dates, video length
- The filter used and filter strength
- Per-filter strength, favorites and recently used filters
- AI-generated tags
- AI photo descriptions (English original, and a Korean translation when the app language is Korean)
- Tags you add yourself
- Favorites
- App settings (shutter sound, appearance, language, etc.)
- Filters unlocked by rewarded ads and until when they can be used
- Whether you bought Premium (the result checked with Google Play)

This information is used to provide the app's features.

## 5. Location information

The Lenumori MVP does not collect your location or send it to a server.

If a GPS-based place tag feature is added in the future,
the app will clearly explain in advance why location is used and how it is handled, and request the necessary permission.

## 6. Accounts and sign-up

Lenumori currently does not require sign-up.

Therefore, the Lenumori operator does not collect account information such as names, email addresses or passwords.

If an account feature is added in the future, this privacy policy will be updated
to explain why related data is collected, how long it is kept and how to delete it.

## 7. Third-party SDKs and open source libraries

Lenumori may use open source libraries or third-party SDKs to implement app features.

License and copyright notices for each library are provided in the app's
"Settings > App info > Open source licenses" or related notice documents.

If a third-party SDK includes features that send user data externally,
its actual behavior is checked and reflected in this privacy policy and the Google Play Data safety section.

Third-party SDKs currently included that send data externally:
- Google ML Kit GenAI image description, ML Kit image labeling, ML Kit Translation — see "3. Sending data to external servers > Google ML Kit usage statistics" above
- Google Mobile Ads SDK (AdMob), Google User Messaging Platform (ad consent) — see "3. Sending data to external servers > Ads" above
- Google Play Billing Library — see "3. Sending data to external servers > Payments" above

## 8. Processing and retention period

The Lenumori operator does not run servers and does not keep information created while you use the app on any server run by the operator.

- Information stored on your device (see "4. Information stored on your device" above): kept only on your device until you delete it in the app or uninstall the app.
- Information Google collects through its SDKs (see "3. Sending data to external servers" above): kept by Google for the period set out in Google's privacy policy.
- Email inquiries: your email address and message are used only to reply, and are deleted one year after the inquiry is resolved.

Photos and videos you take are saved in the same photo folder as your phone's default camera (DCIM/Camera).
Photo files include capture information (EXIF) such as capture time, device model and exposure values; location is not recorded.
Location is not recorded in video files either.

## 9. Destruction procedure and method

- When you delete a photo or video in the app, the file in your phone's gallery and the tags and descriptions stored in the app are deleted immediately, and this cannot be undone.
- When you uninstall the app, information stored in the app's private storage (tags, settings, filter history, etc.) is deleted by the Android system.
  Photos and videos saved to the shared photo folder remain after the app is uninstalled, and you can delete them in your phone's gallery.
- Email inquiry records are permanently deleted from the mailbox when the retention period ends.
- The operator keeps no other personal information, so there is nothing else to destroy.

## 10. Provision to third parties and outsourcing

The Lenumori operator does not provide your personal information to third parties and does not outsource the processing of personal information.

However, Google's SDKs included in the app (ML Kit, ads, Google Play Billing) send the information described in "3. Sending data to external servers" directly to Google.
This transfer is explained in "11. Transfer of personal information overseas" below.

Lenumori does not process sensitive information, unique identification information or pseudonymized information.

## 11. Transfer of personal information overseas

Through the Google SDKs included in the app, information is transferred overseas as follows.
(Basis: Article 28-8(1)(iii)(a) of the Korean Personal Information Protection Act — necessary to provide the service and disclosed in this privacy policy)

- Recipient: Google LLC (1600 Amphitheatre Parkway, Mountain View, CA 94043, USA; privacy inquiries: https://policies.google.com/privacy)
- Countries: the United States and other countries where Google has data centers
- When and how: from time to time while you use the app, sent over the internet with encryption (HTTPS)
- Items and purposes:
  - Google ML Kit: device information, app information, a per-installation identifier, performance and error information — improving features and diagnosing problems
  - Google ads (AdMob): advertising ID, app set ID, device information, IP address, app and ad usage information, diagnostic information — serving ads, measuring ad performance, preventing invalid clicks and (if you consent) personalized ads
  - Google Play Billing: whether you purchased and purchase verification information — processing and checking Premium purchases
- Retention period: as set out in Google's privacy policy
- How to refuse and what happens if you do:
  - Ads: if you buy Premium, the ad SDK is not started and no information is sent for advertising. You can also delete your advertising ID in your phone's Settings > Google > Ads.
  - ML Kit and billing: nothing is sent if you turn off your phone's internet connection. In that case you cannot buy Premium or download some AI models, but taking, saving and organizing photos and other features still work.

## 12. Your rights and how to exercise them

You (or your legal guardian, for children under 14) may at any time request access to, correction of, deletion of, or suspension of processing of your personal information.

- Information stored on your device: you can view, edit and delete photos, videos and tags directly in the app, and uninstalling the app deletes everything stored in it.
- Ad information collected by Google: you can delete or reset your advertising ID in your phone's Settings > Google > Ads,
  and in regions that require consent you can change your consent in the app's "Settings > Ad privacy settings".
- Other requests: email the privacy officer listed in "16. Privacy officer" below and we will reply within 10 days.

## 13. Automatic data collection tools and how to refuse them

The app includes Google's ad SDK, which uses the advertising ID to recognize a device, similar to a cookie on a website.
What it collects and why is described in "3. Sending data to external servers > Ads" above.

How to refuse:
- Delete or reset your advertising ID in your phone's Settings > Google > Ads.
- Buy Premium, so the ad SDK is not started.

## 14. Security measures

- There is no operator server, so your photos, videos, tags and other information are not collected on a server.
- App information is stored in Android's app-private storage, which other apps cannot read.
- The app itself does not send information over the internet, and unencrypted connections (HTTP) are blocked. The included Google SDKs send data encrypted (HTTPS).
- The app requests only the permissions it needs and does not request location permission.
- Before adding a new SDK or permission, we check whether it sends data and update this privacy policy.

## 15. Children's privacy

Lenumori is not intended to knowingly collect personal information from children.
Lenumori is not an app primarily directed at children, and its ads are not directed at children either.

If the app's target age or features change in the future, the relevant Google Play policies will be reviewed and the necessary measures applied.

## 16. Privacy officer

For privacy questions, complaints, remedies or requests to exercise your rights, contact the privacy officer below.

- Privacy officer: BoJeong Ko (developer and operator)
- Email: sweetpotatos.support@gmail.com

## 17. Remedies for privacy violations (Korea)

If you need to report or get advice about a privacy violation, you can contact the following Korean agencies.

- Personal Information Dispute Mediation Committee: 1833-6972, www.kopico.go.kr
- Personal Information Infringement Report Center: 118, privacy.kisa.or.kr
- Supreme Prosecutors' Office: 1301, www.spo.go.kr
- Korean National Police Agency: 182, ecrm.police.go.kr

## 18. Changes to this privacy policy

This privacy policy may change if the app's features, the SDKs it uses or how it handles data change.

Important changes may be announced in the app or on the distribution page.
