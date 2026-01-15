# Finatic Privacy Policy

**Last updated:** 2026-01-14

Finatic (“Finatic”, “we”, “us”) is an iOS app that helps you build and follow a personalized financial action plan. This Privacy Policy explains what data Finatic processes, how it’s used, and the choices you have.

---

## Summary (plain English)

- **Account-based app:** Finatic uses Firebase Authentication so you can sign in with an email and password.
- **Your plan data is stored in the cloud:** Your onboarding answers, plan summary, action plan steps, and a financial health score are stored in Google Firebase (Firestore).
- **AI features are optional:** When you use AI features (for example, generating guidance or a daily step), the text you provide (and relevant plan context) is sent to Google Gemini through Firebase AI Logic.
- **Voice is optional:** If you use voice input, iOS Speech Recognition processes your audio to produce text.
- **Financial accounts are optional:** If you choose to connect accounts, Finatic uses Plaid Link to connect and fetch balances and accounts through your backend.
- **No ads / no tracking SDKs (as implemented in this codebase).**

---

## Data we collect/process

### 1) Account information (Firebase Authentication)
**What:** Email address and authentication data required to sign in.  
**Why:** To create your account, authenticate you, and keep your plan data associated with your account.

### 2) Profile & onboarding inputs (User Content)
Finatic lets you enter information such as your name, age, family status, income/expenses, assets/debts, and other planning details, plus onboarding Q&A and optional debt list entries.

**What:** Free-form text and numbers you enter (e.g., onboarding answers, debt details).  
**Why:** To generate and personalize your plan, show progress, and drive daily recommended steps.

### 3) Plan data (stored in Firebase Firestore)
Finatic stores your plan artifacts in Firestore, including:
- onboarding answers
- plan summary
- action plan steps
- “financial health” score and timestamps

**Why:** So your plan persists across logins and devices, and the app can compute progress and update your plan over time.

### 4) AI processing (Google Gemini via Firebase AI Logic)
When you use AI features, Finatic sends text to Google Gemini via Firebase AI Logic (for example, prompts built from your chat, your plan outline, and recent notes) to generate responses, plan steps, or daily guidance.

**What:** The text you submit, plus context the app includes to fulfill your request (for example, plan outline and recent notes).  
**Why:** To provide AI-generated planning assistance inside the app.

### 5) Voice input (Apple Speech Recognition)
If you enable voice features, Finatic uses iOS Speech Recognition and microphone access to convert your speech to text.

**What:** Audio captured from your microphone (while you are recording) and the transcribed text.  
**Why:** To let you dictate questions or messages.

### 6) Connected financial accounts (Plaid)
If you choose to connect accounts, Finatic uses Plaid Link to connect to your financial institution. The app requests a Plaid link token from your backend and sends a public token back to your backend after a successful link.

**What:** Connection tokens and account/balance information returned through Plaid and your backend.  
**Why:** To display linked accounts and balances inside Finatic.

**Note:** Finatic does not ask for or store your bank login credentials directly. Plaid handles institution authentication during the Link flow.

---

## What we do **not** do

- **No selling of personal data.**
- **No third-party advertising SDKs or tracking for targeted ads** (as implemented in this codebase).
- **No collection of precise location** for app functionality.

---

## Third-party processing (and Apple “same/equal protection” requirement)

Finatic relies on third parties to provide core features:

- **Google Firebase (Authentication + Firestore):** account login and storing plan data.
- **Google Gemini (via Firebase AI Logic):** AI-generated guidance and plan content when you use AI features.
- **Apple iOS Speech Recognition:** optional voice-to-text.
- **Plaid:** optional account linking and balance retrieval (via Plaid Link and your backend).
- **Apple (StoreKit / App Store):** if you purchase subscriptions or in-app purchases, Apple processes payment information.

**Same/equal protection statement:** Any third party that processes user data for Finatic is expected to provide the **same or equal protection of user data** as stated in this policy and as required by Apple’s App Review Guidelines.

---

## Data retention & deletion

### In the app / on your device
Finatic stores some app state locally (for example, daily notes and streak-related data) to support the Daily workflow.

You can remove locally stored data by deleting the app (subject to iOS behavior such as device backups/restores).

### In Firebase (your Finatic account data)
Your plan data is stored in Firestore while your account is active so you can access it across sessions/devices.

**Deleting your cloud data:** If you want your account and associated cloud data deleted, contact us using the email in the “Contact” section below. We may need to verify you own the account.

### Third parties (Apple / Google / Plaid)
- **Gemini retention:** When you use AI features, the text you submit and the model’s output **may be retained by Google for up to 55 days for abuse monitoring**, per Gemini API policies.
- **Speech Recognition:** Audio/text processed by Apple for speech recognition is handled under Apple’s policies.
- **Plaid:** Data processed through Plaid is handled under Plaid’s policies and your financial institution’s policies.

Finatic cannot directly delete data stored by Apple, Google, Plaid, or your financial institution as part of their processing. Please refer to their policies for retention and deletion options.

---

## Your choices (revoke consent / request deletion)

### Revoke consent
- **Voice:** You can deny or revoke microphone and speech recognition permissions in iOS Settings at any time.
- **AI:** You can stop AI processing by not using AI features (for example, “Ask David”, plan regeneration, or other AI generation actions). You can still use the non-AI parts of the app.
- **Linked accounts:** You can choose not to connect accounts (Plaid) or stop using account linking features.

### Request deletion
- **On-device:** Deleting the app removes locally stored app data on your device.
- **Account / cloud data:** Email us to request deletion of your Finatic account and associated Firestore data.
- **Third parties:** For data retained by Apple/Google/Plaid as part of speech recognition, AI processing, or account linking, deletion requests are governed by those providers’ policies.

---

## Security

We aim to minimize data and use reputable providers (Firebase, Apple frameworks, Plaid) for sensitive operations. Data transmitted to third-party services is used to provide the requested app functionality.

---

## Children’s privacy

Finatic is not directed to children under 13, and we do not knowingly collect personal information from children.

---

## Changes to this policy

We may update this policy from time to time. The “Last updated” date at the top reflects the latest version.

---

## Contact

If you have questions or requests about this policy, contact:

**Email:** Simon.Yam227@gmail.com
