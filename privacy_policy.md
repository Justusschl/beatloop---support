# Privacy Policy

**Effective Date:** February 15, 2026
**Last Updated:** November 12, 2026

## 1. Data Controller Information

**BeatLoop** (referred to as "we," "us," or "our") operates the BeatLoop application for iOS, Android and the web at app.beatloop.eu (the "App") and the website beatloop.eu (the "Website").

**Data Controller:**
OnBeat HQ UG (haftungsbeschränkt)
Wichterichstraße 4
50937 Köln, Germany
Email: privacy@on-beat.de

For all privacy-related inquiries, data protection requests, or exercise of your rights under applicable data protection laws, please contact us at the above email address.

## 2. Introduction and Scope

This Privacy Policy explains how we collect, use, process, and protect your personal data when you use the BeatLoop App or visit our Website. What happens on the Website is described in Section 4.5; unless a section says otherwise, the rest of this policy describes the App. This policy applies to all users worldwide and complies with the EU General Data Protection Regulation (GDPR), California Consumer Privacy Act (CCPA), and other applicable data protection laws.

**BeatLoop** is a music practice application designed for dancers and musicians to create audio loops, adjust playback speed, record video, and manage practice sessions. The App allows users to access music from local device storage, YouTube, and Apple Music, and maintains user accounts for premium features and session synchronization.

## 3. Legal Basis for Data Processing (GDPR Article 6)

We process your personal data based on the following legal grounds:

- **Contract Performance** (Article 6(1)(b)): To provide App services, account management, and premium features, and to sell subscriptions and event tickets on our Website
- **Legitimate Interests** (Article 6(1)(f)): Security, fraud prevention, crash and error diagnostics (Sentry), customer support, hosting and delivering our Website, redirecting our short links, **measuring the reach of our Website without cookies** (Section 4.5), and crediting affiliate codes
- **Consent** (Article 6(1)(a)): **Push notifications and marketing communications** (Article 6(1)(a) GDPR together with § 7(2) UWG — see Section 6), **product and usage analytics in the App (PostHog)**, and certain optional third-party integrations. Product analytics in the App is collected **only** after you give explicit opt-in consent and can be withdrawn at any time.
- **Legal Obligation** (Article 6(1)(c)): Compliance with applicable laws, tax obligations, and legal requests

## 4. Information We Collect

### 4.1 Information You Provide Directly

**Account Information:**
- Email address (required for account creation)
- Authentication credentials (when using email/password login)
- Premium subscription status and payment information
- Account preferences and settings

**User-Generated Content:**
- Audio files you import from your device's local storage
- Music accessed via YouTube or Apple Music integrations (metadata only; see Section 5)
- Video recordings of practice sessions (stored locally only)
- Session metadata (markers, segments, loops, practice notes)
- Project organization and naming data

**Communications:**
- Support inquiries and feedback
- Correspondence regarding your account or the App

### 4.2 Information Collected Automatically

This section describes the App. What is collected automatically when you visit our Website is described in Section 4.5.

**Usage and Analytics Data:**
- Product/feature-usage analytics in the App (which features are used and how) and, on Android, which of our links you installed the App from (see Section 14.2) — collected via PostHog **only after you give explicit opt-in consent** (see Section 10.1); never collected if you decline or have not yet consented
- Session duration and frequency of use (part of the consent-gated analytics above)
- Device performance metrics related to audio/video processing
- Error reports and crash logs (via Sentry — see Section 10.1, processed under legitimate interest, independent of analytics consent)

**Device and Technical Information:**
- Device model, operating system, and version
- App version and installation identifier
- IP address and general location (country/region level)
- Network connection type

**Authentication Data:**
- Login timestamps and authentication events
- OAuth tokens from Google and Apple (when using social login)
- Account creation and last activity timestamps
- Terms of Service and Privacy Policy acceptance timestamps (stored in our backend systems for legal compliance)

### 4.3 Information from Third Parties

**Social Authentication Providers** (in the App and on our Website):
- Google OAuth: Name, email address, profile picture (optional)
- Apple Sign-In: Name, email address, or private relay email

**Payment Processing:**
- On iOS: Apple processes payment information via In-App Purchase
- On Android: Google processes payment information via Google Play Billing
- On our Website: subscriptions are sold through a checkout page operated by **RevenueCat** (RevenueCat Web Billing), and the payment is processed by **Stripe**. Event tickets on our Website are sold through Stripe (see Section 4.5)
- **RevenueCat** receives confirmation of your purchases from Apple, Google and Stripe and reports your entitlement status back to us (see Section 10)
- If you buy with an affiliate code, the code and the related purchase are passed to **Insert Affiliate** so that the affiliate who shared it can be credited (see Section 10.1)
- We receive transaction confirmations, product identifier, price, currency, store, and subscription status only. **We never receive or store payment card details.**

### 4.4 Local Media Access on Android

To let you choose a track, BeatLoop's file browser enumerates audio and video files across your device's shared storage. On Android this includes commonly used media folders such as `Music`, `Downloads`, `DCIM` and `Documents`, and the media folders created by other apps (for example WhatsApp, Telegram, Instagram, Facebook, Snapchat and TikTok), as well as SD card storage.

**This scan runs entirely on your device.** File names, paths and folder contents are **never transmitted to us or to any third party**. It requires the media permission you grant at the operating system level, which you can revoke at any time in your device settings.

### 4.5 Our Website (beatloop.eu)

This section covers visits to our Website beatloop.eu, including the short links that start with `beatloop.eu/go/`.

**Hosting and server logs.** Our Website is hosted by **Vercel** (see Section 10.1). Whenever a page or link is requested, Vercel's servers automatically process the technical data your browser sends: IP address, date and time, the requested address, the referring page, and your browser's user-agent string (browser and operating system). This is necessary to deliver the Website and keep it secure (Art. 6(1)(f) GDPR). We do not store these logs ourselves; Vercel keeps them for a limited period for operation and security.

**Short links (`beatloop.eu/go/…`).** The links we post on social media lead through a short redirect. It reads your browser's user-agent string only to decide where to send you: to the App Store on an iPhone, to Google Play on an Android phone, and to our Website otherwise. It adds a campaign label that names the profile or post the link was shared in (for example `ig-beatloop-bio`). The label describes the link, not you. To learn how often each link is used, the redirect also sends one count to PostHog (see below): the campaign label, the kind of device (iPhone, Android or other) and where it sent you. This count contains no IP address, no user-agent string and no identifier, sets no cookie and stores nothing on your device; every click is counted on its own and cannot be linked to other clicks or visits. Link previews that apps generate are not counted, and neither are clicks from browsers that send Global Privacy Control or Do Not Track. Apart from this count and Vercel's server logs, nothing about the redirect is stored.

**Campaign labels on store buttons.** If you arrive through one of our links, the App Store and Google Play buttons on that page carry the same campaign label. Apple and Google then show us aggregated download numbers per campaign. We receive no information about you personally.

**Reach measurement without cookies (PostHog).** To learn which pages and campaigns lead to downloads and purchases, we count visits to our Website with **PostHog** (PostHog Cloud EU, Frankfurt, Germany):
- **What is recorded:** the page you view (its address without personal parameters; sign-in, account, administration and cancellation pages are not recorded at all), the referring website (its domain only), the campaign values in the link you followed, browser, operating system, device type and screen size, and clicks on our App Store and Google Play buttons, on the buttons that open the web app or a course, and on the "Start free trial" button. For our short links, only the count described above is recorded.
- **No cookies, nothing kept on your device:** the measurement sets no cookies and keeps no identifier in your browser's storage.
- **Daily visitor key:** to count visitors, PostHog's servers derive a key from your IP address and user-agent string, combined with a secret value that changes every day. **Your IP address is not stored.** Because the secret value changes daily, visits on different days cannot be linked to each other. No profile is created, and the data is not linked to your BeatLoop account.
- **Legal basis:** our legitimate interest in measuring the reach of our Website and our marketing (Art. 6(1)(f) GDPR).
- **Retention:** 12 months.

**Your right to object (Art. 21 GDPR).** You can object to this reach measurement at any time. The simplest way is to switch on **"Global Privacy Control"** or **"Do Not Track"** in your browser: when your browser sends one of these signals, our Website does not start the measurement at all and our short links do not count your click. Common content blockers also prevent it. You can also object by writing to privacy@on-beat.de; because the measurement does not recognise individual visitors, the browser setting is what makes your objection effective on your device.

**Your account on the Website.** You can create or sign in to your BeatLoop account on the Website, with email and password or with Google or Apple. It is the same account as in the App (see Sections 4.1 and 4.3). If you tick the newsletter box when signing up, we record your consent with a timestamp (see Section 6.6). If you open the web app from the Website while signed in, we hand over a one-time sign-in token so that you do not need to sign in again.

**Buying Premium on the Website.** Subscriptions sold on the Website use a checkout page operated by RevenueCat (RevenueCat Web Billing); the payment itself is processed by Stripe. We pass on your BeatLoop account identifier, the plan you selected and, to prefill the form, your email address. If you buy with an affiliate code, the code is passed on so that the purchase can be credited to the affiliate (Insert Affiliate, see Section 10.1). Legal basis: performance of the contract (Art. 6(1)(b) GDPR); for crediting affiliates, our legitimate interest in paying commissions correctly (Art. 6(1)(f) GDPR).

**Cancellation form.** Our cancellation form at beatloop.eu/premium/cancel (§ 312k BGB) asks for your name and email address and, optionally, a reference and a reason. We send your request to our support team and a confirmation to you by email (via Resend, see Section 10.1), and keep it as proof of your cancellation like other support correspondence (Section 13.4). Legal basis: Art. 6(1)(b) and (c) GDPR.

**Event tickets.** When we sell tickets for events on the Website, payment is handled by Stripe. We process your name, email address, the ticket you booked, the payment status and, at the event, your check-in status, in order to issue your ticket, admit you and handle refunds (Art. 6(1)(b) GDPR). Your tickets are sent to you by email with a QR code for admission (via Resend, see Section 10.1). Payment records are kept for the statutory periods (Section 13.3).

**Venue maps (OpenStreetMap).** Event pages show a map of the venue from OpenStreetMap. To display it, your browser loads the map from the servers of the OpenStreetMap Foundation, which receive your IP address, browser information and the map area shown (Art. 6(1)(f) GDPR; our legitimate interest in showing where an event takes place). See Section 10.1.

**Demo video (YouTube).** Our homepage shows a demo video from YouTube. **It is loaded only when you press play**; until then no connection to YouTube is made and our own preview image is shown. When you press play, the video is loaded from YouTube in privacy-enhanced mode (youtube-nocookie.com). YouTube then receives your IP address and browser information and may store information in your browser. See Section 10.1.

**Cookies on the Website.** Our Website only uses cookies that are strictly necessary: when you sign in, session cookies keep you signed in (§ 25(2) No. 2 TDDDG). We do not use advertising, social media or analytics cookies, which is why the Website shows no cookie banner. The demo video only loads YouTube, and with it YouTube's own storage, after you press play.

## 5. Third-Party Music Service Integrations

BeatLoop integrates with the following third-party music services to allow users to access and practice with music. Each integration involves specific data collection and processing:

### 5.1 YouTube (YouTube API Services)

BeatLoop uses YouTube API Services to allow users to search for and play music from YouTube.

- **Data collected:** Video metadata (title, artist, duration), playback interaction data
- **Data NOT collected:** BeatLoop does NOT download, store, or cache YouTube audio or video content. All playback occurs via the YouTube API.
- **YouTube Terms of Service:** [https://www.youtube.com/t/terms](https://www.youtube.com/t/terms)
- **Google Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

**Google API Services User Data Policy Compliance:** BeatLoop's use of information received from YouTube API Services will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

Users may revoke BeatLoop's access to their YouTube data via the Google security settings page at [https://security.google.com/settings/security/permissions](https://security.google.com/settings/security/permissions).

### 5.2 Apple Music (MusicKit)

BeatLoop uses the Apple MusicKit API to allow users to search for and stream music from Apple Music.

- **Data collected:** Track metadata (title, artist, album, duration), library access (with user permission)
- **Data NOT collected:** BeatLoop does NOT download, store, or cache Apple Music audio content. Audio is streamed via Apple Music.
- **Requirement:** Users must have an active Apple Music subscription to use this feature.
- **Apple Media Services Terms and Conditions:** [https://www.apple.com/legal/internet-services/itunes/](https://www.apple.com/legal/internet-services/itunes/)

### 5.3 Local Files

Users may import audio files from their device's local storage.

- Local files are processed entirely on-device and are never uploaded to our servers.
- BeatLoop does not monitor, scan, or validate the content or copyright status of local files.

### 5.4 Google Drive

BeatLoop allows users to import audio files from their Google Drive.

- **Access Type:** Read-only access to files the user explicitly selects via the Google Picker
- **Data Collected:** File metadata (name, type, size) and audio file content for playback
- **Data Storage:** Imported audio is processed and stored locally on the user's device only. BeatLoop does NOT upload, cache, or store Google Drive files on its servers
- **Data Sharing:** Google Drive file data is not shared with any third parties
- **Revocation:** Users can revoke BeatLoop's access at any time via [https://myaccount.google.com/permissions](https://myaccount.google.com/permissions)
- **Google API Services User Data Policy Compliance:** BeatLoop's use of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.
- **Google Terms of Service:** [https://developers.google.com/terms](https://developers.google.com/terms)

### 5.5 Metadata Storage

Streaming music metadata (song title, artist, tempo markers, loop points) may be stored locally on your device for session management purposes. Actual audio content from streaming services is NOT stored by BeatLoop.

### 5.6 Casting to External Displays (Chromecast and AirPlay)

When you cast a recorded video to a Chromecast or AirPlay device, BeatLoop starts a **temporary HTTP server on your local Wi-Fi network** and serves the selected video file to the receiving device. To do this the App reads your device's local network address and uses Bonjour and Bluetooth to discover nearby cast targets.

- The server runs **only while casting is active** and is reachable **only from your local network** — never from the internet, and never by us.
- It does not require authentication. Anyone else on the same Wi-Fi network could, in principle, reach the served file while a cast is in progress. **Avoid casting on untrusted public networks.**
- No cast data is transmitted to our servers.

### 5.7 On-Device File Visibility (iOS)

On iOS, BeatLoop's documents folder is exposed to the Files app and to Finder/iTunes over USB, so that you can retrieve your own recordings. Anyone with physical access to your unlocked computer while your device is connected can therefore reach those files. This is a device-level feature and involves no transmission to us.

## 6. Push Notifications and Marketing Communications

### 6.1 What We Send

With your consent, BeatLoop sends push notifications to your device. These fall into two categories:

- **Product notifications** — new features and important service information
- **Promotional notifications** — offers, price changes, and subscription promotions

Tapping a notification may open the App at the home screen, a practice session, or the subscription screen.

### 6.2 Legal Basis and Consent

Push notifications, and in particular **promotional** notifications, are sent **only on the basis of your prior, explicit consent** under **GDPR Article 6(1)(a)** and **§ 7(2) UWG** (German Act Against Unfair Competition).

- Consent is requested through a **separate, dedicated in-app prompt**. It is **not** bundled into your acceptance of our Terms of Service or Privacy Policy, and there are no pre-ticked boxes.
- Two independent gates must both be satisfied before any notification can reach you: your **in-app consent** and your **operating system notification permission**. Withdrawing either one stops delivery.
- **Declining has no effect on your ability to use BeatLoop.** Every feature remains available.
- We record the timestamp of your consent in your user profile so that we can demonstrate it, as required by GDPR Article 7(1).

### 6.3 How Delivery Works

We use **Firebase Cloud Messaging (FCM)**, a service of Google Ireland Limited, as our delivery processor. Firebase Cloud Messaging is the **only** Firebase product we use — we do not use Firebase Analytics, Crashlytics, Firebase Authentication, Firestore, or Firebase Storage.

Delivery is **topic-based, not individually addressed**. When you consent, your device subscribes to broadcast topics. The only two attributes used to select an audience are your **subscription tier** (premium or free) and your **app language**. Campaigns are sent to a whole topic at once. **We do not send notifications to individuals, and we do not build behavioural profiles for notification targeting.**

**Device registration token.** For Firebase Cloud Messaging to function, the Firebase SDK registers your device with Google, and Google issues a device registration token. **BeatLoop never reads, receives, or stores this token, and we store no device identifiers for notification purposes.** Google processes the token under its own privacy policy. This registration happens when the App starts, before you are asked for notification consent; you can prevent it by denying BeatLoop notification permission at the operating system level.

### 6.4 Information Stored on Your Device (§ 25 TDDDG)

With your consent, BeatLoop stores your notification consent choice and the list of topics your device is subscribed to, so that only changes need to be issued rather than re-subscribing on every launch. Under **§ 25 TDDDG** this on-device storage requires your consent, which is obtained by the prompt described in Section 6.2.

### 6.5 Withdrawing Consent

You can withdraw consent at any time, and doing so is **as easy as giving it** (GDPR Article 7(3)):

- **In the App:** Account → Settings → notifications toggle. Switching it off immediately unsubscribes your device from every topic.
- **On your device:** revoke the notification permission in your iOS or Android system settings.
- **By email:** privacy@on-beat.de

When you sign out, your device is unsubscribed from all topics automatically.

### 6.6 Email Communications

Transactional emails (password reset, account confirmation, purchase receipts) are sent on the basis of contract performance. **Newsletter and marketing emails are sent only with your separate, explicit consent**, recorded with a timestamp, and every such email contains an unsubscribe link.

## 7. How We Use Your Information

### 7.1 Core App Functionality
- Account creation, authentication, and access management
- Premium feature activation and usage tracking
- Local audio processing, looping, speed adjustment, and session management
- Video recording synchronized with audio playback
- Cross-device session synchronization (metadata only)
- Customer support and technical assistance

### 7.2 Service Improvement
- App performance optimization and bug fixes
- Feature development based on usage patterns
- Security monitoring and fraud prevention
- Quality assurance and testing

### 7.3 Communications
- Service-related notifications and updates
- Premium subscription management
- Response to support inquiries
- Important policy or service changes (where legally required)

### 7.4 Analytics and Business Operations
- Measuring which Website pages and marketing campaigns lead to downloads and purchases, without cookies (Section 4.5)
- Monthly Active User (MAU) metrics and engagement analysis
- Subscription conversion and retention analytics
- General usage statistics for business planning
- Compliance with legal obligations and tax requirements

### 7.5 Product Experiments (A/B Testing)

We occasionally run experiments in which different users see different versions of a screen — most commonly the subscription screen — so that we can evaluate which version works better. Assignment to an experiment group is recorded as an analytics event, so **experiment participation is only measured if you have consented to analytics**. If you have not consented, no experiment data is recorded about you. Experiments never change the price you are charged; the applicable price is always shown before any purchase is confirmed.

## 8. User Content and Copyright Liability

### 8.1 User Responsibility for Content

**IMPORTANT:** BeatLoop is a tool that enables users to access music from multiple sources (local files, YouTube, Apple Music) for practice purposes. By using the App, you acknowledge and agree that:

1. **You are solely responsible** for all audio files, music, and other content you import, access, or create using BeatLoop
2. **You warrant** that you own or have obtained all necessary rights, licenses, and permissions to use any copyrighted material in your content
3. **You indemnify and hold harmless** OnBeat HQ UG (haftungsbeschränkt), its affiliates, and service providers from any claims, damages, or liabilities arising from your use of copyrighted or otherwise protected content
4. **Content accessed via streaming services** (YouTube, Apple Music) remains subject to those platforms' respective licensing terms and your subscription agreements with them

### 8.2 Copyright Compliance

- BeatLoop does **not** provide, host, cache, or redistribute any music, audio tracks, or copyrighted content
- BeatLoop does **not** monitor, review, or validate the copyright status of user content
- Content from streaming services is played via those services' official APIs and is not downloaded or stored by BeatLoop
- Users must comply with all applicable copyright laws in their jurisdiction
- BeatLoop reserves the right to terminate accounts that repeatedly violate copyright policies

### 8.3 Digital Millennium Copyright Act (DMCA) Compliance

If you believe content in BeatLoop infringes your copyright, please contact us at support@on-beat.de with:
- Your contact information and electronic signature
- Identification of the copyrighted work claimed to be infringed
- Identification of the allegedly infringing material
- A statement of good faith belief that the use is not authorized
- A statement that the information is accurate and you are authorized to act

### 8.4 No Liability for User Content

**BeatLoop explicitly disclaims all liability** for:
- Copyright infringement by users
- Unauthorized use of protected audio or video content
- Any legal claims arising from user-generated content
- Damages resulting from users' failure to obtain proper licenses
- Copyright claims arising from videos recorded and shared by users

## 9. Data Storage and Security

### 9.1 Local Data Storage
- **Audio and video files** imported from local storage are stored exclusively on your device
- **Streaming content** from YouTube and Apple Music is NOT stored on your device or our servers
- **Practice sessions and projects** remain local to your device
- **No user content** is uploaded to our servers without explicit action
- If you use the **share feature**, sessions built from a local audio or video file include a copy of that media file in the exported `.beatloop` bundle, which is sent **directly via your device's share options** — it is not uploaded to, transmitted through, or stored on our servers

### 9.2 Cloud Data Storage
- **Account information** is securely stored using Supabase infrastructure
- **Session metadata** (markers, timestamps, loop points, project names) may be synchronized
- **Authentication tokens** are encrypted and stored securely
- **Payment information** is processed and stored by Apple (iOS), Google (Android) or Stripe (purchases on our Website), never by BeatLoop

### 9.3 Security Measures
- Industry-standard encryption for data transmission (TLS/HTTPS)
- Secure authentication protocols and token management
- Regular security assessments and vulnerability monitoring
- Access controls and audit logs for administrative functions
- Data breach response procedures and user notification protocols

### 9.4 Remote Configuration and Required Updates

BeatLoop reads a small configuration record from our backend at startup to determine the minimum supported App version. If your installed version is below that minimum, the App will require you to update before continuing. This request contains no personal data and is not used for tracking.

## 10. International Data Transfers

BeatLoop operates globally and may transfer your personal data outside your country of residence, including to countries that may not provide the same level of data protection as your home country.

### 10.1 Third-Party Service Providers

The following services may process your data outside the EU:

**Supabase (Database & Authentication):**
- Data location: EU region (Frankfurt/London) or US with Standard Contractual Clauses
- Purpose: Account management and authentication
- Safeguards: GDPR-compliant hosting and data processing agreements

**Vercel (Website Hosting):**
- Operator: Vercel Inc., 440 N Barranca Ave #4133, Covina, CA 91723, USA
- Purpose: Hosting and delivering our Website and its short links (see Section 4.5)
- Data processed: IP address, date and time, requested address, referring page, browser user-agent string
- Legal basis: Art. 6(1)(f) GDPR (legitimate interest in delivering a secure Website)
- Data location: United States and Vercel's global network
- Safeguards: Data Processing Addendum including Standard Contractual Clauses
- Vercel Privacy Policy: [https://vercel.com/legal/privacy-policy](https://vercel.com/legal/privacy-policy)

**Apple (In-App Purchase & MusicKit):**
- Data location: United States and EU
- Purpose: Payment processing (iOS) and Apple Music integration
- Safeguards: Apple's privacy commitments and data processing agreements

**Google (Play Billing, YouTube API & Google Drive):**
- Data location: United States and EU
- Purpose: Payment processing (Android), YouTube integration, and user-selected audio file import via Google Drive
- Data (Drive): File metadata and audio content (read-only, local processing only)
- Safeguards: Standard Contractual Clauses and Google's data processing terms

**Google — Firebase Cloud Messaging (Push Notification Delivery):**
- Operator: Google Ireland Limited
- Data location: European Union and United States
- Purpose: Delivery of push notifications to your device (see Section 6)
- Data processed: device registration token, topic subscriptions, notification content
- Safeguards: Google Cloud Data Processing Addendum, Standard Contractual Clauses, EU-US Data Privacy Framework

**RevenueCat (Subscription Management and Website Checkout):**
- Operator: RevenueCat, Inc., United States
- Purpose: Validating purchases with Apple and Google, providing the checkout page for subscriptions bought on our Website (RevenueCat Web Billing), and determining your premium entitlement
- Data processed: your BeatLoop account identifier (transmitted as the RevenueCat app user ID), purchase and renewal events, product identifier, price, currency, store, offer code, and country; for purchases on our Website also your email address and, if you use one, your affiliate code
- Note: In the App, RevenueCat does not process payments and never receives your payment card details. For purchases on our Website, payments are processed by Stripe
- Safeguards: Data Processing Addendum, Standard Contractual Clauses

**Stripe (Payments on our Website):**
- Operator: Stripe Payments Europe, Limited, 1 Grand Canal Street Lower, Grand Canal Dock, Dublin, D02 H210, Ireland
- Purpose: Processing payments for subscriptions bought on our Website and for event tickets
- Data processed: name (for event tickets), email address, payment details such as card data, billing country, and transaction data
- Note: Stripe also processes certain data as an independent controller, for example to prevent fraud and to meet its legal obligations as a payment service provider
- Safeguards: transfers to Stripe, Inc. in the United States are based on Standard Contractual Clauses
- Stripe Privacy Policy: [https://stripe.com/privacy](https://stripe.com/privacy)

**Insert Affiliate (Affiliate Attribution):**
- Purpose: Crediting purchases made with an affiliate code to the affiliate who shared the code, so that commissions are paid correctly
- Data processed: the affiliate code you used and the related purchase information (product, price, date), received from our payment provider
- Legal basis: Art. 6(1)(f) GDPR (legitimate interest in paying our affiliates correctly)
- Applies only if you buy with an affiliate code

**YouTube (Demo Video on our Website):**
- Operator: Google Ireland Limited, Gordon House, Barrow Street, Dublin 4, Ireland
- Purpose: Playing our demo video on the homepage, in privacy-enhanced mode, only after you press play (see Section 4.5)
- Data processed: IP address, browser information, and information YouTube stores in or reads from your browser once the video is loaded
- Legal basis: Art. 6(1)(f) GDPR; the video is loaded only at your request
- Safeguards: transfers to Google LLC in the United States are based on the EU-US Data Privacy Framework and Standard Contractual Clauses
- Google Privacy Policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)

**OpenStreetMap (Venue Maps on Event Pages):**
- Operator: OpenStreetMap Foundation, St John's Innovation Centre, Cowley Road, Cambridge, CB4 0WS, United Kingdom
- Purpose: Displaying a map of the venue on event pages (see Section 4.5)
- Data processed: IP address, browser information, and the map area shown
- Legal basis: Art. 6(1)(f) GDPR (legitimate interest in showing where an event takes place)
- Safeguards: the United Kingdom is covered by an adequacy decision of the European Commission
- OpenStreetMap Foundation Privacy Policy: [https://osmfoundation.org/wiki/Privacy_Policy](https://osmfoundation.org/wiki/Privacy_Policy)

**Resend (Email Communications):**
- Data location: United States
- Purpose: Transactional email delivery, including confirmations of cancellation requests submitted on our Website and event tickets with their QR codes
- Safeguards: Standard Contractual Clauses and GDPR compliance measures

**Sentry (Crash and Error Reporting):**
- **Data location:** European Union (Frankfurt am Main)
- **Operator:** Sentry GmbH, Krausenstraße 9-10, 10117 Berlin, Germany (parent company: Functional Software, Inc., 45 Fremont Street, 8th Floor, San Francisco, CA 94105, USA)
- **Purpose:** Detection and resolution of application errors and crashes to improve stability
- **Data processed:** Error messages, stack traces, app version, device type, operating system version. Personally identifiable information (email addresses, user IDs, file paths) is removed before transmission through technical safeguards (PII scrubbing).
- **Legal basis:** Art. 6(1)(f) GDPR (legitimate interest in the stability and error-free operation of our application)
- **Retention period:** 90 days
- **Safeguards:** Data Processing Agreement (DPA) signed pursuant to Art. 28 GDPR, including Standard Contractual Clauses
- **Sentry Privacy Policy:** [https://sentry.io/privacy/](https://sentry.io/privacy/)
- **List of Sub-processors:** [https://sentry.io/legal/subprocessor-list/](https://sentry.io/legal/subprocessor-list/)

**PostHog (Product Analytics):**
- **Data location:** European Union — PostHog Cloud EU (`eu.i.posthog.com`), hosted on AWS in Frankfurt, Germany (`eu-central-1`)
- **Operator:** PostHog, Inc. (US parent; EU Cloud data stored in the EU)
- **Purpose:** In the App, product and feature-usage analytics to understand how the App is used and improve it, and, on Android, which of our links the App was installed from. On our Website, reach measurement without cookies (see Section 4.5)
- **Data processed (App):** A **pseudonymous app-instance identifier** (a random ID, not linked to your name or email), in-app feature-usage events, session duration, device/OS type, and subscription tier (free/premium). On Android, also the **install source**: the campaign label of the store link the App was installed from (see Section 14.2). **No name, email, IP address, or GeoIP-derived location is collected** (IP and GeoIP enrichment are disabled), and **session replay is not used**.
- **Data processed (Website):** page views, clicks and short-link counts as described in Section 4.5. Your IP address is used only to derive a daily visitor key on PostHog's servers and is **not stored**; no GeoIP-derived location, no cookies, no profiles, and no session replay.
- **Legal basis (App):** **Consent (Art. 6(1)(a) GDPR)**. Analytics is **off by default**; it is enabled only after you give explicit opt-in consent via the in-app prompt, and you can withdraw consent at any time in **Account → Privacy Settings** (German § 25 TDDDG is also satisfied by this prior consent).
- **Legal basis (Website):** Art. 6(1)(f) GDPR (legitimate interest in measuring the reach of our Website). You can object at any time (see Section 4.5).
- **Retention period:** 12 months
- **Safeguards:** Data Processing Agreement (DPA) concluded pursuant to Art. 28 GDPR, including Standard Contractual Clauses for any onward transfer to the United States
- **PostHog Privacy Policy:** [https://posthog.com/privacy](https://posthog.com/privacy)
- **List of Sub-processors:** [https://posthog.com/subprocessors](https://posthog.com/subprocessors)

### 10.2 Legal Safeguards
All international data transfers are protected by appropriate safeguards including:
- Standard Contractual Clauses approved by the European Commission
- Adequacy decisions where applicable
- Binding Corporate Rules for multinational service providers
- Additional technical and organizational measures as required

## 11. Data Sharing and Disclosure

### 11.1 We Do Not Sell Personal Data
BeatLoop does not sell, rent, or trade your personal information to third parties for their marketing purposes.

### 11.2 Limited Data Sharing
We may share your information only in the following circumstances:

**Service Providers:** With trusted third-party service providers who assist in operating our App, processing payments, or providing customer support, under strict confidentiality agreements.

**Legal Requirements:** When required by law, legal process, or government request, or when we believe disclosure is necessary to protect our rights, property, or safety, or that of our users or the public.

**Business Transfers:** In connection with any merger, acquisition, or sale of company assets, where personal data may be transferred as part of the business assets.

**Consent:** With your explicit consent for specific purposes not covered by this policy.

### 11.3 Data Protection in Sharing
All data sharing arrangements include:
- Contractual data protection obligations
- Purpose limitation and use restrictions
- Security and confidentiality requirements
- User rights preservation mechanisms

## 12. Your Rights Under Data Protection Laws

### 12.1 GDPR Rights (EU Users)

You have the following rights regarding your personal data:

**Right of Access (Article 15):** Request a copy of your personal data we hold
**Right to Rectification (Article 16):** Correct inaccurate or incomplete data
**Right to Erasure (Article 17):** Request deletion of your personal data ("right to be forgotten")
**Right to Restrict Processing (Article 18):** Limit how we use your data
**Right to Data Portability (Article 20):** Receive your data in a portable format
**Right to Object (Article 21):** Object to processing based on legitimate interests
**Right to Withdraw Consent:** Where processing is based on consent

### 12.2 CCPA Rights (California Users)

California residents have additional rights including:
- Right to know what personal information is collected
- Right to delete personal information
- Right to opt-out of the sale of personal information (Note: We do not sell personal information)
- Right to non-discrimination for exercising privacy rights

### 12.3 Exercising Your Rights

To exercise your privacy rights:

**In-App:** Use the account settings and privacy controls within the BeatLoop app
**Account Deletion:** To delete your personal data, delete your account through the app's account settings. This will permanently remove all your personal information from our systems within 30 days
**Email:** Contact privacy@on-beat.de with your request
**Identity Verification:** We may require verification of your identity for security purposes
**Response Time:** We will respond within 30 days (GDPR) or 45 days (CCPA)
**No Fee:** Rights requests are generally processed free of charge

### 12.4 Right to Lodge a Complaint

If you believe we have not adequately addressed your privacy concerns, you have the right to lodge a complaint with your local data protection authority. For EU users, you can find your local authority at: https://edpb.europa.eu/about-edpb/about-edpb/members_en

### 12.5 Account Deletion — What Actually Happens

Deletion happens in stages, and we want you to know exactly how:

1. **Immediately:** your account is marked deleted and deactivated. Your profile and session data are no longer accessible through the App.
2. **Within 30 days:** your personal data is permanently erased from our production systems by an automated cleanup process.
3. **Reactivation during those 30 days:** if you sign in again with the same credentials before permanent erasure, **your account and data are restored**. This grace period protects you against accidental deletion. If you want immediate, irreversible erasure with no grace period, email privacy@on-beat.de and we will carry it out manually.
4. **Data we must retain:** payment and invoicing records are kept for 7 years under German tax and commercial law, regardless of account deletion.

## 13. Data Retention

### 13.1 Account Data
- **Active accounts:** Retained for the duration of your account plus 30 days
- **Inactive accounts:** Automatically deleted after 24 months of inactivity
- **Deleted accounts:** Permanently removed within 30 days of deletion request

### 13.2 Usage and Analytics Data
- **Login records:** Retained for 12 months for security purposes
- **Product analytics in the App (PostHog):** Individual event data retained for 12 months (see Section 10.1); only aggregated/derived insights may be retained longer. Collected only with your consent.
- **Website reach measurement (PostHog):** Retained for 12 months (see Section 4.5)
- **Website server logs (Vercel):** Kept by Vercel for a limited period for operation and security; we do not store them ourselves
- **Error logs:** Retained for 12 months for debugging and improvement

### 13.3 Legal and Compliance Data
- **Payment records:** Retained for 7 years to comply with tax and accounting requirements
- **Legal correspondence:** Retained as long as necessary for legal purposes
- **DMCA notices:** Retained for 3 years as required by law

### 13.4 User Content
- **Local files:** Under your complete control on your device
- **Session metadata:** Retained while account is active, deleted with account deletion
- **Support communications:** Retained for 3 years for quality and training purposes

## 14. Cookies and Tracking Technologies

### 14.1 In the App
The App uses minimal tracking technologies:
- **Authentication tokens:** For secure login and session management
- **App preferences:** Stored locally to remember your settings
- **Error tracking:** Basic crash reporting for app stability

### 14.2 Product Analytics in the App (PostHog)
We use **PostHog** (EU Cloud) for product/usage analytics to understand how the App is used and improve it. This analytics:
- Is **off by default** and runs **only after you give explicit opt-in consent** (Art. 6(1)(a) GDPR; German § 25 TDDDG)
- Uses a **pseudonymous app-instance identifier** only — no name, email, IP, or GeoIP location, and no session replay
- On **Android**, records once which of our links you installed the App from: the three campaign values of the Google Play link (platform, placement and content, for example `instagram · dm · r001`, or Google's own `google-play · organic` for an install found in the store), read through Google Play's Install Referrer API, which keeps this information for 90 days after installation. Nothing else from it is kept. It is read only if you agreed to the consent text that names this purpose ("which link you came to BeatLoop from"). This is not available on iPhone or in the web app
- Stores its opt-out/consent preference on your device

See Section 10.1 (PostHog) for hosting, retention, sub-processors, and safeguards.

### 14.3 Your Control
- **Analytics opt-out in the App:** Analytics is opt-in; you can grant or withdraw consent at any time in **Account → Privacy Settings**
- **Reach measurement on the Website:** switch on "Global Privacy Control" or "Do Not Track" in your browser (see Section 4.5)
- **Third-party tracking:** We do not use advertising or social media tracking pixels, and we do not track you across other apps or websites

### 14.4 On our Website
Our Website only uses cookies that are strictly necessary to keep you signed in (§ 25(2) No. 2 TDDDG). Its reach measurement works without cookies and keeps nothing on your device (see Section 4.5). For this reason the Website shows no cookie banner. The demo video on our homepage loads YouTube only after you press play (see Section 4.5).

## 15. Children's Privacy

### 15.1 Age Restriction
BeatLoop is not intended for users under 16 years of age. We do not knowingly collect personal information from children under 16. If you are under 16, please do not use BeatLoop or provide any personal information.

### 15.2 Parental Notice
If we become aware that we have collected personal information from a child under 16 without verified parental consent, we will take steps to remove that information immediately.

### 15.3 Parent Rights
Parents who believe their child under 16 has provided personal information to BeatLoop may contact us at privacy@on-beat.de to request deletion of such information.

## 16. Changes to This Privacy Policy

### 16.1 Policy Updates
We may update this Privacy Policy from time to time to reflect changes in our practices, technology, legal requirements, or other factors.

### 16.2 Notification of Changes
**Minor Changes:** Updated "Last Updated" date at the top of this policy
**Material Changes:** Email notification to registered users and in-app notification
**Continued Use:** Your continued use of BeatLoop after changes constitutes acceptance

### 16.3 Change History
We maintain a record of significant policy changes for transparency and compliance purposes.

## 17. Contact Information

### 17.1 Privacy Inquiries
For questions about this Privacy Policy or our data practices:

**Email:** privacy@on-beat.de
**Postal Address:**
OnBeat HQ UG (haftungsbeschränkt)
Wichterichstraße 4
50937 Köln, Germany

### 17.2 Data Protection Requests
For exercising your data protection rights, please use the email above and include:
- Your full name and email address associated with your account
- Specific right you wish to exercise
- Any additional information needed to verify your identity

### 17.3 Response Commitment
We are committed to responding to privacy inquiries promptly and professionally. We typically respond within 3-5 business days for general inquiries and within the legally required timeframes for formal rights requests.

## 18. Additional Legal Information

### 18.1 Governing Law
This Privacy Policy is governed by the laws of Germany and the European Union. Any disputes arising from this policy shall be subject to the jurisdiction of German courts.

### 18.2 Severability
If any provision of this Privacy Policy is found to be unenforceable or invalid, that provision will be limited or eliminated to the minimum extent necessary so that the Privacy Policy will otherwise remain in full force and effect.

### 18.3 Language
This Privacy Policy is published in English, German and Spanish. **The English version is the authoritative version**; the German and Spanish versions are convenience translations, and in case of any discrepancy the English version prevails. This does not affect your rights under mandatory data protection law.

---

**This Privacy Policy was last updated on November 12, 2026, and becomes effective immediately upon posting.**

For the most current version of our Privacy Policy, please check this document regularly or contact us at privacy@on-beat.de.
