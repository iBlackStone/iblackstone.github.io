---
layout: default
title: "Knit & Crochet Privacy Policy"
---

# Knit & Crochet Privacy Policy

**Last updated: August 17, 2026**<br>
**Effective date: August 17, 2026**

Thank you for using Knit & Crochet (the “App”). This Privacy Policy explains how the App handles information and how you can manage related data and permissions. Please read it before using the App.

Most knitting and crochet content is stored locally on your device. Data is sent to the relevant service provider only when you choose to use features such as iCloud backup, feedback, Ravelry, in-app purchases, notifications, or other network-based functions. We do not sell or rent your personal information.

## 1. Information We Process

### 1.1 Local projects and files

The following content that you create or import is generally stored in the App sandbox:

- yarn records, projects, counters, progress, project dates, and notes;
- knitting charts, crochet charts, pixel charts, and their editing data;
- names, body-measurement snapshots, target garment measurements, gauge, and pattern projects created in Smart Pattern Drafting;
- photos, PDFs, imported files, and export records that you select;
- App settings, cached entitlement information, and feature state.

Creating or editing this local content does not automatically upload it to the developer. Uninstalling the App will generally remove local data from the device, but existing iCloud backups must be deleted separately in the App or through Apple's iCloud management tools.

Smart Pattern Drafting V1 uses a separate local database. People, body measurements, and pattern data are not included in the current iCloud database backup or exported in `.lineopus` packages. If pattern sync or archiving is added later, the relevant disclosure and user choices will be updated before it is enabled.

### 1.2 iCloud backup and file selection

When you intentionally create an iCloud backup, the App uses Apple iCloud to store a snapshot of the local database and PDF resources so that you can view, restore, rename, or delete backups. This data is stored in the iCloud space associated with your Apple ID, and Apple provides the storage and transfer services.

When you use the system document picker to import or export a file, the App accesses only the file you explicitly select or save. Apple's handling of iCloud and system file services is governed by the [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

### 1.3 Feedback and support

When you intentionally submit feedback, the App sends the following to the developer through Apple CloudKit:

- your feedback message;
- contact details that you voluntarily provide;
- up to three screenshots that you voluntarily attach;
- device type, iOS version, App version, and submission time;
- membership status and, where applicable, entitlement expiration information;
- a randomly generated identifier used to distinguish the record.

This information is used to respond to requests, diagnose problems, and improve the product. It is not displayed as public content. Do not include passwords, Ravelry tokens, payment card numbers, or other unnecessary sensitive information in feedback.

## 2. Ravelry Features

Ravelry is an optional third-party service. You can use the App's local features without connecting a Ravelry account.

### 2.1 Authorization and access

When you connect Ravelry, the App requests authorization through Ravelry's official OAuth 2.0 page. Your Ravelry password is submitted directly to Ravelry; the App does not read or store it.

Within the permissions you grant, the App may access:

- your Ravelry username and remote content identifiers;
- your Projects and Library;
- project status, progress, dates, public notes, and related pattern information;
- pattern name, designer, craft, categories, languages, cover image, and available file list;
- project photos that you choose to import;
- PDFs that you are entitled to access and explicitly choose to download;
- keywords and filters that you submit to Ravelry search.

Standard access and PDF download access may use different authorization scopes. Access tokens, refresh tokens, authorization scopes, and your username are stored in the iOS Keychain to keep you signed in and refresh authorization.

### 2.2 Free patterns and your Library

Free-pattern search sends the keyword, craft, category, language, and sort filters to Ravelry. Search results do not by themselves grant download rights. For a free pattern hosted by Ravelry, the App adds it to your Ravelry Library only after you explicitly confirm. Any subsequent local project or PDF import remains subject to your choices and the App's entitlement rules. The App does not bypass Ravelry access controls or scrape files hosted on a designer's external website.

### 2.3 Local storage and disconnection

After you choose to import content, related project data, source identifiers, cover links, photos, and PDFs are stored locally as needed. They may also be included if you intentionally create an iCloud backup.

You can disconnect Ravelry in the App settings. Disconnecting deletes the Ravelry authorization tokens and connection state from the Keychain, but it does not automatically delete local projects, PDFs, photos, or source information that you already imported. You may continue to use or manually delete that content. A Ravelry username and source identifiers stored with an imported project remain until you delete the corresponding local content.

Ravelry requests are sent directly to Ravelry. The App does not forward Ravelry tokens or imported content to a developer-operated server. Ravelry may process account details, IP addresses, request logs, and information required by its website or API under the [Ravelry Privacy Policy](https://www.ravelry.com/about/privacy).

Ravelry interaction analytics record only low-sensitivity, low-cardinality states such as opening an entry point, applying a filter, or whether an import succeeded. They do not include your Ravelry username, search terms, project or pattern names, remote IDs, filenames, tokens, client secrets, or download links.

## 3. Subscriptions and Purchases

In-app purchases are processed by the Apple App Store and StoreKit. The developer does not receive your card number or complete payment details. The App processes product identifiers, transaction state, entitlements, and the App Store receipt, and sends the receipt directly to Apple for purchase validation, purchase restoration, and entitlement decisions.

Apple's handling of payments, transaction records, and receipt validation is governed by the [Apple Privacy Policy](https://www.apple.com/legal/privacy/). You can manage or cancel a subscription in iOS Settings > Apple ID > Subscriptions.

## 4. Analytics, Performance Monitoring, and Push Notifications

The App uses Umeng+ for usage analytics, crash and performance monitoring, and push notifications. Depending on the feature, iOS permission status, and Umeng configuration, Umeng may process:

- device and App environment information, such as device type, iOS version, App version, language, and network status;
- IP address and device or installation identifiers required to operate the service;
- product interaction events, page visits, and feature results;
- crash, freeze, launch, network request, and other performance diagnostics;
- push token, notification authorization status, and delivery or interaction information;
- IDFA, where available and only after authorization through App Tracking Transparency.

This information is used to understand feature usage, diagnose problems, improve reliability, and deliver notifications. Denying tracking authorization does not prevent use of the App's core local features, and IDFA is available only when iOS permits it and you authorize it. You can manage tracking and notification permissions in iOS Settings. See the [Umeng Privacy Policy](https://www.umeng.com/page/policy) for its data practices.

## 5. System Permissions

The App may request the following permissions when needed:

| Permission | Purpose | Your choice |
|---|---|---|
| Camera | Take photos of projects, yarn, or charts | You may deny it; only capture features are affected |
| Photos | Select images or save exported images and charts | You may deny or limit access |
| Notifications | Receive reminders, service messages, or feature updates | You may deny or disable it later in Settings |
| Tracking | Make IDFA available, when permitted by iOS, for analytics | You may deny it; core local features remain available |
| Files/iCloud | Access files you explicitly select and backups you intentionally create | You choose files individually or enable iCloud |

You can change permissions at any time in iOS Settings. The presence of a permission description in the App configuration does not itself cause access; the App accesses relevant data only when you use the feature and the system grants permission.

## 6. Third-Party Services and External Content

The App may communicate with the following services to provide the functions described above:

| Service | Purpose | Policy |
|---|---|---|
| Apple iCloud / CloudKit / App Store / APNs | Backup, feedback, purchase validation, and system notifications | [Apple Privacy Policy](https://www.apple.com/legal/privacy/) |
| Umeng+ | Usage analytics, performance diagnostics, and push notifications | [Umeng Privacy Policy](https://www.umeng.com/page/policy) |
| Ravelry | OAuth, Projects/Library, search, images, and PDFs | [Ravelry Privacy Policy](https://www.ravelry.com/about/privacy) |
| YouTube | Official web player when you choose to open a learning video | [Google Privacy Policy](https://policies.google.com/privacy) |

When you open a Ravelry source page, YouTube video, help page, or another external link, the third party may process IP address, browser/device information, cookies, or access logs under its own rules. The App does not control the independent data practices of third-party websites, so please review their policies before using them.

## 7. Retention

- Local projects and files: until you delete them in the App, clear App data, or uninstall the App;
- iCloud backups: until you delete them in the App or through Apple's iCloud management tools;
- Ravelry authorization tokens: until they expire, you disconnect Ravelry, or the system clears Keychain data;
- imported Ravelry content: until you delete the related local project, PDF, photo, or source information;
- feedback: for as long as needed to handle support requests, diagnose problems, and improve the product; you may contact us to request deletion;
- analytics, diagnostics, push, and purchase records: for the periods determined by Umeng or Apple under their policies and applicable law.

We may retain relevant records for a necessary period where required by law, to resolve disputes, prevent abuse, or maintain security.

## 8. Security

The App uses the iOS App sandbox for local data, the Keychain for Ravelry authorization tokens, and HTTPS when communicating with supported network services. We take reasonable measures to limit access and protect information, but no storage or transmission method can guarantee absolute security.

## 9. Your Choices and Rights

You can:

- delete projects, photos, PDFs, charts, and iCloud backups in the App;
- disconnect Ravelry in Settings and manage your account or authorization through Ravelry;
- manage camera, photo, notification, and tracking permissions in iOS Settings;
- choose not to submit feedback, connect Ravelry, or create iCloud backups;
- contact us to request access, correction, or deletion of feedback that you intentionally submitted to the developer.

To locate a feedback record, we may ask for its submission time, contact information, or other necessary details. Do not email passwords, tokens, full receipts, or payment card information. For data independently controlled by Apple, Umeng, Ravelry, or Google, use the account, privacy, or deletion tools provided by that company.

## 10. Children

The App is not specifically designed for children. A user who is below the age at which they can independently consent under local law should use network, upload, or purchase features only with a parent or guardian's consent and guidance. If you believe a child submitted personal information without appropriate consent, please contact us.

## 11. International Processing

Service providers such as Apple, Umeng, Ravelry, and Google may process data outside your country or region. Processing locations, safeguards, and available rights are governed by the relevant provider's policy and applicable law.

## 12. Changes to This Policy

We may update this policy when features, third-party services, or legal requirements change. We will provide notice of material changes through an in-App notice, an updated policy page, or another appropriate method. The date at the top identifies the current version.

## 13. Contact Us

For questions about this policy, data handling, or deletion requests, contact:

**Email:** gao375976821@gmail.com

We will respond within a reasonable time after verifying the request and confirming that we are authorized to act on the relevant record.

## 14. Support and Subscription Information

- Support: review the help content in the App first; if the problem remains, contact us at the email above.
- Cancel a subscription: open iOS Settings > Apple ID > Subscriptions, select the App, and cancel.
- Terms of use: [Apple Standard End User License Agreement (EULA)](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)
