# StyleSense Privacy Policy

**Last Updated:** June 26, 2026

## 1. Introduction

StyleSense ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our mobile application (the "App") and related services.

Please read this Privacy Policy carefully. If you do not agree with our policies and practices, please do not use our App.

---

## 2. Information We Collect

### 2.1 Information You Provide Directly

- **Account Information:** Email address and password when you create or manage your account.
- **Profile Information:** Optional avatar image you upload to personalize your account.
- **Clothing Photos:** Images of your clothing items that you photograph or select from your device's photo library. These are analyzed by AI to generate clothing metadata (category, color, formality, etc.).
- **Voice Recordings:** Audio recordings you create using the voice input feature when requesting outfit suggestions. These are transcribed using OpenAI Whisper API.
- **Outfit Data:** Outfit names, descriptions, occasion tags, and wear-history data you record.

### 2.2 Information Collected Automatically

- **Location Data:** Precise GPS location when you enable location services. We use this to fetch weather data to personalize outfit suggestions. Location data is never stored; it's used in real-time only.
- **Device Information:** Device type, OS version, app version, and crash logs (via Sentry error tracking).
- **Usage Analytics:** Events such as app opens, feature usage, authentication actions (via PostHog analytics). User IDs are pseudonymized.
- **Session Information:** Authentication tokens and session metadata managed by Supabase Auth.

### 2.3 Information from Third Parties

- **Weather Data:** We fetch current weather conditions from Open-Meteo API (no API key required, no data sharing).
- **AI Processing:** Clothing classification and outfit generation are performed by Anthropic's Claude API. Clothing photos are transmitted to Claude for analysis.

---

## 3. How We Use Your Information

| Purpose | Data Used | Legal Basis |
|---------|-----------|------------|
| Account authentication & security | Email, password | Contract (providing the service) |
| Clothing classification | Clothing photos | Consent (you upload photos) |
| Outfit suggestions | Closet data, weather, occasion | Consent (you request suggestions) |
| Voice-to-text transcription | Audio recordings | Consent (you record voice) |
| Wear tracking & statistics | Outfit wear logs | Consent (you log wear history) |
| App analytics & debugging | Usage events, crash logs | Legitimate interest (app improvement) |
| Customer support | All data, if you contact us | Contract (support obligation) |
| Security & fraud prevention | All data | Legitimate interest (protecting service) |

---

## 4. Data Storage & Security

### 4.1 Where Data Is Stored

- **Database:** PostgreSQL via Supabase (US-based, SOC 2 Type II compliant)
- **File Storage:** Supabase Storage (AWS S3 backend, US-based)
- **Backups:** Automatic daily backups managed by Supabase
- **Processing:** Edge Functions (Deno runtime on Supabase infrastructure)

### 4.2 Security Measures

- **Encryption in Transit:** All data transmitted via HTTPS (TLS 1.3+)
- **Encryption at Rest:** Supabase manages encryption of stored data
- **Access Control:** Row-Level Security (RLS) policies ensure you can only access your own data
- **API Keys:** Your clothing images are never sent directly to external AI services; Edge Functions act as a secure server-side proxy
- **Token Management:** Authentication tokens are stored securely in device storage and auto-refresh when needed
- **No Third-Party Selling:** Your clothing photos and personal data are never sold, rented, or shared with advertisers or data brokers

### 4.3 Third-Party Services & Subprocessors

| Service | Purpose | Data Shared | Privacy |
|---------|---------|-------------|---------|
| **Anthropic Claude API** | Clothing classification, outfit generation | Clothing photos, occasion text | [Anthropic Privacy](https://www.anthropic.com/privacy) |
| **OpenAI Whisper API** | Voice-to-text transcription | Audio recordings | [OpenAI Privacy](https://openai.com/privacy) |
| **Open-Meteo API** | Weather data retrieval | Location coordinates (real-time only, not stored) | [Open-Meteo Privacy](https://open-meteo.com/) |
| **Sentry.io** | Error tracking & crash reporting | Error logs, device info, pseudonymized user ID | [Sentry Privacy](https://sentry.io/privacy/) |
| **PostHog** | Usage analytics | Event names, pseudonymized user ID, app version | [PostHog Privacy](https://posthog.com/privacy) |
| **Supabase** | Database, auth, storage | All app data | [Supabase Privacy](https://supabase.com/privacy) |

---

## 5. Data Retention

- **Active Accounts:** Your data is retained as long as your account is active.
- **Inactive Accounts:** We may delete inactive accounts after 12 months of non-use, with 30 days prior notice.
- **After Account Deletion:** All personal data is permanently deleted from our systems within 30 days, including:
  - Clothing items and photos
  - Profile information and avatar
  - Outfit suggestions and wear logs
  - Account credentials
  - Analytics events associated with your user ID

**Exception:** Aggregated, anonymized analytics data (which cannot identify you) may be retained indefinitely for research and product improvement.

---

## 6. Your Privacy Rights

### 6.1 Access & Portability
You have the right to request a copy of your personal data. Contact us and we will provide a JSON export of your account data within 30 days.

### 6.2 Correction & Deletion
- **Correction:** You can update your profile information directly in the app.
- **Deletion:** You can delete individual clothing items. To delete your entire account, use the "Delete Account" option in the Profile tab, or see our [Account Deletion page](./account-deletion).

### 6.3 Marketing Communications
We do not send marketing emails. Any notifications are transactional (password resets, account alerts) and can be disabled in your account settings.

### 6.4 Regional Rights

**California (CCPA/CPRA):**
- Right to know, delete, and correct your personal information
- Right to opt-out of data sales (we do not sell your data)
- Right to submit requests via the contact information below

**European Union / United Kingdom (GDPR / UK GDPR):**
- Right to access, rectify, erase, restrict, and port your data
- Right to object to processing
- Right to withdraw consent at any time
- Right to lodge a complaint with your local Data Protection Authority

**Canada (PIPEDA):**
- Right to access and correct your personal information
- Right to request deletion
- Right to file a complaint with Privacy Commissioner of Canada

---

## 7. Children's Privacy

StyleSense is not intended for users under 13 years old (or the minimum age required by your country). We do not knowingly collect personal information from children under 13. If we become aware that we have collected data from a child under 13, we will delete it immediately.

Parents or guardians who believe their child has provided information to StyleSense may contact us at the address below.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect changes in our practices or for other operational, legal, or regulatory reasons. We will notify you of material changes by:
1. Posting the updated policy in the App
2. Updating the "Last Updated" date at the top of this document
3. Requesting your consent (if required by law)

Your continued use of the App after changes become effective constitutes your acceptance of the updated Privacy Policy.

---

## 9. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or our privacy practices, please contact us:

**Email:** support@stylesense.app

We will respond to your privacy request within 30 days (or within the timeframe required by applicable law in your jurisdiction).

---

## 10. Additional Information

### 10.1 Links to Third-Party Sites
The App may contain links to external websites or services. We are not responsible for the privacy practices of these sites. Please review their privacy policies before providing personal information.

### 10.2 Do Not Track
Some browsers include a "Do Not Track" feature. We do not currently respond to DNT signals, but you can manage data collection preferences in your account settings.

### 10.3 California Privacy Rights (Shine the Light)
If you are a California resident, you have the right to request a list of third parties to whom we disclosed personal information for their direct marketing purposes.

### 10.4 Image & Data Security Best Practices
- We recommend using a strong, unique password
- Do not share your account credentials
- Regularly review your account activity in the Profile tab

---

**End of Privacy Policy**
