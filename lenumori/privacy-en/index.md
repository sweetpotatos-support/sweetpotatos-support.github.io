---
title: Lenumori Privacy Policy
lang: en
---

# Lenumori Privacy Policy

Effective date: 2026-10-15

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

## 8. Data retention and deletion

Photo-related information and tags created by Lenumori are stored on your device by default.

Photos and videos you take are saved in the same photo folder as your phone's default camera (DCIM/Camera).
Photo files include capture information (EXIF) such as capture time, device model and exposure values; location is not recorded.
Location is not recorded in video files either.

You can delete photos, videos or related tag information using the delete feature in the app.
Deleting a photo or video also deletes the file in your phone's gallery and its tags, and this cannot be undone.

When you uninstall the app, data stored in the app's private storage may be deleted according to Android system policy.
Photos and videos saved to shared photo storage may remain after the app is uninstalled.

## 9. Children's privacy

Lenumori is not intended to knowingly collect personal information from children.
Lenumori is not an app primarily directed at children, and its ads are not directed at children either.

If the app's target age or features change in the future, the relevant Google Play policies will be reviewed and the necessary measures applied.

## 10. Privacy protection

Lenumori's basic design principle is to minimize unnecessary permission requests and external data transfers.

Information that can be processed on the device is processed on the device wherever possible.

## 11. Changes to this privacy policy

This privacy policy may change if the app's features, the SDKs it uses or how it handles data change.

Important changes may be announced in the app or on the distribution page.

## 12. Contact

Questions about privacy or this privacy policy can be sent to the contact below.

- Developer/operator: BoJeong Ko
- Email: sweetpotatos.support@gmail.com
