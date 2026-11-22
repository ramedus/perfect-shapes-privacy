# Perfect Shapes — Privacy Policy

Last updated: November 22, 2026

## About this policy

Perfect Shapes is a puzzle game by Ramedusa Studios for children aged 6 and older and adults. This policy describes the Android game, including the account and purchase features introduced in our updated builds. Older installed versions may not include all these features. Feature availability depends on the installed version and release configuration. Privacy contact: ramedusastudios.support@gmail.com.

## 1. Local game data

The game stores puzzle progress, stars, unfinished puzzles, coins, owned effects, reward claims, tutorial state, notification preferences, advertising counters and settings in app storage. Recovery copies help restore interrupted saves. Clearing app storage can remove these local records and account credentials. Operating-system backup and transfer settings may affect whether local data returns after reinstallation.

## 2. Anonymous accounts and optional Google connection

Updated builds automatically create an anonymous Supabase account with a unique Player ID. You do not need to enter an email address, sign in with Google or pay to start playing. This account associates supported game records, rewards and purchases with the same player. Account session credentials are stored in the app's private storage to keep that session available. Anonymous does not mean unidentifiable: an account ID is a persistent identifier.

Connect with Google is optional. If you choose it, Google and Supabase process your Google account identifier and the basic profile information you authorize, which may include your name, email address and profile picture. We request basic sign-in scopes (openid, email and profile), not access to Gmail messages, contacts or Google Drive. We use the linked identity to associate and help recover your game account, not for advertising. Playing and purchasing do not require this connection. Account linking does not guarantee restoration of every local save; complete cross-device progress synchronization is not currently available.

## 3. Server game records and calendars

Supabase hosts our authentication and game database. Depending on the features used, records include Player ID, initial and recent app version, platform, build/test information, account activity timestamps, coin and skip-ticket balances and transactions, purchased passes and expiry dates, reward claims, owned effects, and supported level progress. These records support delivery, synchronization, fraud prevention, troubleshooting and prevention of duplicate rewards.

On the first connection in updated builds, an existing local save may be imported once, including coins, effects, progress and reward markers. This helps preserve earlier progress; it is not permission to repeatedly replace server purchase balances with local values. Some game state remains local.

For daily rewards and seasonal calendars, the app sends a randomly generated installation key and the device's configured time zone. The database stores a hash of that key, initial and registered calendar time zones, account association where available, and timestamps. Server time and the registered zone determine eligible days and help prevent device-clock changes from unlocking rewards early. Time-zone names do not establish a player's physical city. We do not request GPS or precise location. Calendar and account records do not currently have an automatic expiry. Optional reminders are scheduled on the device; turning them off does not disable server time checks.

## 4. Google Play purchases

Google Play provides checkout and processes payment information. We do not receive your card number or banking credentials. To verify and deliver purchases, our server processes purchase tokens, token hashes, product and Google order identifiers, quantities, purchase/test/refund status, delivery and acknowledgement state, and related timestamps. Purchase tokens needed for server retries are stored encrypted; they are not simply discarded after hashing.

We use transaction and reward ledgers to prevent duplicate grants and reconcile interrupted deliveries or changed purchase status. Some necessary purchase credentials and pending-operation records are also kept in private app storage for recovery. Pending payments do not grant paid items until Google confirms the purchase. Google Play handles its payment and refund processes under its own terms. Deleting a game account does not itself request a refund or delete your Google account.

## 5. Age grouping and children's privacy

The game asks for age through a neutral age screen, with an option not to say. The entered number is used temporarily to choose an on-device category: under 18, adult or unknown. The game does not retain that number or send it to the services described here. It saves the category locally and passes the relevant advertising treatment flags to the advertising and consent SDKs.

Children and players of unknown age are not required to provide a name, email address or precise location to play. An anonymous account and the technical records described above can still be created. Under-18 and unknown players receive restricted advertising treatment, and optional gameplay Analytics is not enabled for them. The app does not request access to contacts, camera or microphone. A parent or guardian can contact us about access, correction or deletion. An arithmetic gate on some external navigation is a request for adult help, not identity verification or legally verified parental consent.

## 6. Advertising and privacy choices

The Android game integrates Google AdMob and Unity Ads through mediation. Depending on the release, it may show optional rewarded ads and interstitial ads at transitions after completed puzzles. Developer and internal-test configurations use test advertising where configured; production advertising is enabled only in the designated production configuration. Ad availability depends on privacy checks, connectivity and ad supply.

For under-18 and unknown players, the game requests child-directed treatment and G-rated content, disables publisher advertising personalization and marks the user as under the age of consent in Google's User Messaging Platform (UMP). The Android advertising-ID permission is removed for all players. Restricted ads still involve technical processing; non-personalized does not mean no data is processed. Advertising services may process IP addresses, approximate location inferred from IP, device and application information, ad interactions, diagnostics and permitted identifiers to deliver ads, measure operation and prevent fraud.

For adults, UMP checks applicable requirements and offers privacy choices where required. Ads are not requested until the privacy check permits them. Where available, choices can be reviewed through Settings → Privacy Policy → Ad privacy choices. We do not deliberately give advertising services your entered age, Google profile, support emails or puzzle save files. Provider policies explain their own processing.

## 7. Crash reports and optional gameplay Analytics

Firebase Crashlytics is enabled in configured Android builds, including developer test builds, to diagnose crashes. It processes crash traces, installation and session identifiers, app state and technical information such as device model, operating system, app version and crash time. We add diagnostic context such as level, game mode, engine version and build channel. We do not deliberately attach Google profile data, email addresses, the entered age, full save files or Player ID to crash reports. These reports are not fully anonymous. The game currently has no separate crash-reporting switch. Firebase documents a 90-day retention period for Crashlytics crash traces, extracted minidump data and associated identifiers before removal begins from live and backup systems.

Google Analytics for Firebase is integrated but gameplay collection is currently disabled by our release configuration. Internal-test, debug and editor builds are blocked from sending gameplay Analytics. Crash reporting and essential server account/purchase records are separate from gameplay Analytics and can still operate.

If enabled in a future production configuration, optional gameplay Analytics will require an adult's opt-in in Settings → Privacy Policy. It is intended to measure tutorial completion, puzzle starts and outcomes, active playing time, hints, stars, artwork/cut revision, store visits, checkout outcomes, ad operation and virtual-currency activity. The app's gameplay event list excludes names, email addresses, Player IDs, raw purchase tokens and Google order IDs. Firebase may use its own app-instance and technical identifiers. Adults can switch optional gameplay Analytics off; doing so stops future optional collection, not deletion of information already processed. We will update disclosures when collection changes.

The prepared Analytics measurements also cover piece-level failed placements and rotations, interrupted attempts, screen navigation, reward-method choices, remaining tickets, cosmetic previews/equipping, displayed store prices, checkout delivery timing and advertising callbacks. We keep a short local checkpoint to distinguish an interrupted attempt from a confirmed completion; an interruption is not proof that a player was bored or that the app crashed. Test exports disable Analytics at the Android SDK and game layers. Receipt tokens, order IDs, support messages and Supabase account identifiers are not sent as gameplay Analytics parameters.

## 8. Connectivity, notifications, ratings and support

Internet checks send small HTTPS requests to Google's connectivitycheck.gstatic.com and Microsoft's www.msftconnecttest.com. These services receive IP addresses and ordinary request metadata; the app does not attach game saves, coins, age or email to these checks. Other online providers also receive network and request metadata and may retain service logs.

Optional reminders are local Android notifications. Google Play handles optional ratings and reviews; we do not receive your rating, review text or confirmation that you submitted a review. We store whether a review request was attempted to avoid repeated prompts.

Contact buttons open an email app. If you send a message, we receive your email and its contents in our support mailbox, hosted by Gmail. Support information may include Player ID, a short support code, product name, app version and, when known and relevant, Google order ID. We use it to resolve the request. Do not send passwords, card information, service keys, refresh tokens or raw purchase tokens.

## 9. Retention, deletion and your choices

We retain account and game information while needed to provide the game, resolve deliveries and prevent duplicate or fraudulent rewards. Weekly maintenance removes session diagnostics and save-operation retry receipts older than 30 days and checkout locks expired for more than a day. Current saves, balances, purchase and earned reward records are not erased by this routine maintenance. There is no blanket automatic expiry of inactive accounts.

Updated builds provide Settings → Request account deletion → Send request for both anonymous guests and Google-connected players. This records a request for the currently signed-in game account. Where the deletion processor has been deployed and enabled, the server processes queued requests and removes the Auth account, its Google link and associated game records, including progress, balances, benefits, supported saves, calendar associations and known purchase delivery records. Sending a request is not confirmation of completed deletion. Failed processing is retried; contacting support remains available. Once the server acknowledges a deletion request, updated builds leave that account, clear its local profile and recovery copies, and start a fresh separate guest game without waiting for server deletion to finish. If a request cannot be submitted, the existing game is kept. Other offline devices may retain their local copies until they reconnect and check deletion status. Older builds may require clearing app storage.

A minimal SHA-256 purchase-token hash and Play account hash, with deletion time, may be retained to prevent previously used purchases being granted again. These hashes are not guaranteed anonymous and currently have no automatic expiry. A minimal request receipt and processing timestamps are retained; the old Player ID is removed from the completed request. Raw/encrypted purchase tokens, order IDs and game save contents are not kept in these retained anti-fraud records.

If you cannot access the game, email ramedusastudios.support@gmail.com with the subject 'Perfect Shapes account/data deletion'. Include the Player ID if available. If Google is linked, sending from that email can help verify the request. Parents or guardians may request on a child's behalf. We may request proportionate ownership information, never passwords or card credentials. Email requests require manual verification and handling.

Deleting the game account does not delete your Google account or automatically request a Google Play refund. Provider-held payment records, Firebase or advertising logs, support emails and backup retention cycles are separate from the game-account deletion transaction. We handle applicable provider deletion requests separately. Uninstalling or revoking Google's connection permission does not itself delete server records. Depending on your location, you may have rights to access, correct, delete, restrict or object to processing and to contact a data-protection authority. We respond subject to applicable law and reasonable verification.

## 10. Providers, security and changes

We use Supabase for accounts and game records; Google Play for purchases and reviews; Google AdMob, UMP and Unity for advertising; Firebase for crash reporting and configured optional Analytics; Google and Microsoft for connectivity checks; and Gmail for support. These providers may process information outside your country under their applicable terms and safeguards. We do not sell your Google profile, puzzle save files or support messages.

Online requests use HTTPS. Purchase credentials used for server reconciliation are encrypted at rest, and game server permissions restrict access. Local app storage, save recovery copies and transaction deduplication help protect records, but no system guarantees complete security or recovery.

This public site is a static GitHub Pages site. We have not added advertising, Analytics scripts, external fonts or tracking cookies to it. GitHub can process IP addresses and request logs to host and secure the site. Visiting Google Play or sending email involves those providers.

We will update the date and relevant disclosures when practices change. Publisher: Ramedusa Studios. Game: Perfect Shapes. Contact: ramedusastudios.support@gmail.com.

## Provider information

- Google privacy: https://policies.google.com/privacy
- Google Mobile Ads SDK disclosure: https://developers.google.com/admob/android/privacy/play-data-disclosure
- Unity privacy: https://unity.com/legal/privacy-policy
- Firebase privacy and retention: https://firebase.google.com/support/privacy
- Supabase privacy: https://supabase.com/privacy
- Microsoft privacy: https://privacy.microsoft.com/privacystatement
- GitHub privacy: https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement
