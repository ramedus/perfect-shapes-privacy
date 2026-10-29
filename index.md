# Perfect Shapes — Privacy Policy

Last updated: October 29, 2026

Perfect Shapes is a puzzle game developed by **Ramedusa Studios**, intended for children aged 6 and older and adults. This policy explains how the current pre-release version handles information. It also distinguishes developer test features from features enabled in release builds.

Privacy contact: **ramedusastudios.support@gmail.com**

## 1. Game data stored on your device

The game stores puzzle progress, placed pieces and their rotations, completed levels, virtual coin balances, Special unlocks, collection progress, reward-claim records, tutorial status, advertising-break counters, and game preferences on your device. Recovery copies may be stored to restore an interrupted or damaged save.

These records let you continue an unfinished puzzle, keep earned content and avoid duplicate rewards. No account is required. We do not operate a cloud-save service, and the game's own code does not upload these save files to a developer-operated server. Device backup, transfer and restore behavior may depend on your operating system and device settings.

## 2. Age information

When you first open the game, a neutral age screen asks your age and includes a “Prefer not to say” option. The number entered is used temporarily to select an on-device category: under 18, adult, or unknown. The game does not retain the age number or send it to advertising or crash-reporting services. Only the category is saved on your device.

For advertising, all players under 18 and players whose age is unknown receive the same protective child-directed treatment. The advertising and consent services receive the relevant treatment flags, rather than the entered age. These services may store their own privacy-related settings on the device.

## 3. Internet connection checks

An internet connection is required to play. The game sends small HTTPS requests to Google's `connectivitycheck.gstatic.com` and Microsoft's `www.msftconnecttest.com` to check internet availability.

The receiving service sees your IP address and ordinary network-request information. The game does not attach puzzle saves, coins, age, reward history, email addresses or advertising identifiers to these checks. The providers handle connection logs under their own policies:

- Google: https://policies.google.com/privacy
- Microsoft: https://privacy.microsoft.com/privacystatement

## 4. Advertising and privacy choices

Perfect Shapes integrates Google AdMob through the Google Mobile Ads SDK. Advertising can include optional rewarded advertisements for an in-game benefit and interstitial advertisements at suitable transitions after completed puzzles. No real-world payment is required to receive an advertisement reward; coins are virtual game currency.

**Current pre-release status:** Android developer builds and explicitly marked internal-test builds use Google's demonstration ad units. Production ad requests are disabled in the current release configuration. The child-directed path described below is implemented for these test requests. Advertising availability depends on the SDK's privacy checks, configuration, network connection and ad supply; an internet connection does not guarantee an available advertisement.

### Children, teenagers and players of unknown age

For all under-18 and unknown-age players, the game sets child-directed treatment, requests G-rated ad content and disables publisher advertising personalization before initializing advertisements. It marks these players as under the age of consent in Google's User Messaging Platform (UMP), so they are not asked to consent to personalized advertising. The Android advertising-ID permission is removed for every player. No additional mediation advertising networks are configured.

These requests are intended for contextual, non-personalized advertising, rather than interest-based advertising or remarketing. Non-personalized does not mean that no information is processed: network and advertising services still need some technical information to deliver ads, prevent fraud and measure their operation.

### Adult players

For adult players, UMP checks the applicable privacy requirements and displays a privacy message when required. The game does not initialize or request ads until the privacy update completes without error and UMP reports that requests are permitted. Where applicable, adults can review their choices through **Settings → Privacy Policy → Ad privacy choices**. If the privacy check fails, ads remain unavailable.

### Information handled by Google

Depending on the SDK configuration and applicable restrictions, Google's advertising services may process IP addresses, approximate location derived from IP, app or ad interactions, diagnostics, and device or account identifiers. Child-directed treatment and the removal of the advertising-ID permission restrict advertising-identifier use; they do not eliminate all network or diagnostic processing. We do not give AdMob your entered age, puzzle save files or support emails.

For Google's data-handling information:

- Google Privacy Policy: https://policies.google.com/privacy
- Google Mobile Ads SDK data disclosure: https://developers.google.com/admob/android/privacy/play-data-disclosure

## 5. Crash reporting

Starting with version 1.0.1, Firebase Crashlytics is enabled in the configured Android Play release to diagnose crashes and improve reliability. Version 1.0.0 submitted before this update had release crash collection disabled. Developer test builds can also send crash reports. Google Analytics for Firebase is not included, and we do not send Firebase gameplay analytics events.

Crashlytics automatically processes crash traces, application state at the time of a crash, installation and session identifiers, and technical information such as device model, operating-system and app version, crash time and native crash diagnostics. These reports help identify failures and measure how many installations are affected. We add the displayed level number, Normal/Special mode, engine version and build channel to help reproduce a crash. We do not deliberately attach your age, age category, name, email, puzzle save files or a developer-assigned player ID. Crashlytics reports are not fully anonymous because installation identifiers are involved. Crash collection is enabled automatically in these builds; the game currently has no separate switch to turn it off.

Google processes this information to provide crash reporting and management services for us. It documents a 90-day retention period for crash traces, extracted native-crash information and associated identifiers before beginning removal from live and backup systems. Raw native minidumps are held temporarily for processing.

Firebase privacy information: https://firebase.google.com/support/privacy

Any future addition of Firebase gameplay analytics would require a further policy and store disclosure update before distribution.

## 6. Contacting us

The **Contact Us** button opens an email application addressed to **ramedusastudios.support@gmail.com**. Sending an email is optional. If you contact us, we receive your email address and the information you include and use them to answer your inquiry or handle a privacy request. Our contact mailbox uses Google Gmail.

Please do not include passwords, payment details or unnecessary personal information. For children and players of unknown age, the Contact Us navigation asks for an adult's help through a short arithmetic gate. This gate is not identity verification or parental consent for advertising or data collection. The in-game Privacy Policy can be read without completing it.

## 7. Children's privacy

Children aged 6 and older are part of the intended audience. We do not require children to create an account, provide a name, supply an email address or share precise location to play. The game does not request access to contacts, camera or microphone. Local age grouping and child-directed advertising treatment are described above.

Connectivity checks and enabled child-directed ad services still involve the limited technical processing described in this policy. Parents or guardians can contact us with questions about their child's information or to request review or deletion of information they have provided to us. Please avoid sending additional sensitive information to identify a request.

## 8. Retention, deletion and security

Local game data remains in app storage until it is cleared or removed. You can remove it using Android's app-storage controls. Doing so also removes local progress, coins, unlocks, age category, preferences and recovery copies. Device backup or transfer features may affect whether information returns after reinstallation. We cannot recover a local save that we do not hold on our servers.

We retain support correspondence while it is needed to respond and follow up, or where a legal obligation requires retention. You can contact us to request deletion; we will review and act on the request subject to applicable requirements and our ability to identify the information. Clearing app storage does not automatically erase information already held by Google, Microsoft or an email service. Their retention rules and available privacy controls also apply.

Online requests use HTTPS. Local saves are kept in the operating system's app storage, with checksums and recovery copies to help detect interrupted writes. These safeguards are not a guarantee against every security incident or device failure.

### Optional Google Play ratings

Adult players may be offered Google's optional in-app review form after completing enough normal puzzles. Google Play handles any rating or review under its own terms and privacy policy. The game does not receive your rating, review text, or confirmation that you submitted a review. It stores only whether a review request has already been attempted, to avoid repeated requests. Reviews are not rewarded or required to continue playing.

## 9. Service providers and international processing

The services described above may process information outside your country, including in the United States, according to their applicable terms and privacy policies. We use them for connectivity, advertising, developer crash diagnosis and support communications. We do not operate an account database or a marketplace for player information, and we do not sell your puzzle save files or support messages.

Depending on your location, you may have rights to request access, correction or deletion of personal information, or to object to or restrict certain uses. Contact **ramedusastudios.support@gmail.com** for requests concerning information held by Ramedusa Studios. Google's and Microsoft's policies explain their own privacy controls. Where applicable, you may also contact your local data-protection authority.

## 10. Changes and contact

We will update this policy when our data practices change and show the revised date above. Changes to production advertising, child-directed services, crash collection or analytics must be reflected in the published policy and store disclosures.

**Publisher:** Ramedusa Studios  
**Game:** Perfect Shapes  
**Privacy and support email:** ramedusastudios.support@gmail.com
