# FINATIC PRIVACY POLICY

**Last Updated:** January 24, 2026

Finatic (“Finatic,” “we,” “us”) is an iOS app that helps you build and follow a personalized financial action plan. This Privacy Policy explains what information we collect or process, how we use it, how we share it, and your rights and choices.

## Summary (Plain English)

- Finatic requires an account to work (email + password).
- Your plan data is stored securely in **Google Firebase (Firestore)**.
- Some plan data may also be stored in a **Google Cloud SQL** database via a backend service that syncs plan summaries and action steps.
- AI features use **Google Gemini** to generate guidance when you request it.
- Voice input (if you enable it) uses **Apple Speech Recognition**.
- We do **not** sell your data.
- We do **not** use advertising trackers.
- You can request deletion at any time.
- If your account is inactive for **12 months**, we delete or de-identify your stored Finatic account data (unless we must retain it for legal/security reasons).

---

## Information We Collect / Process

### 1) Account Information (Firebase Authentication)
**What:** Email address and authentication credentials (handled by Firebase Authentication).  
**Why:** To create and manage your account and associate your data with you.

### 2) User Content and Profile Information
**What you provide:** Name, age, household/family status, income, expenses, assets, debts, onboarding answers, notes, and free-form text you enter into the app.  
**Why:** To generate your personalized plan, daily action steps, progress views, and related features.

### 3) Plan Data Stored in Firebase Firestore
**What:** Onboarding answers, plan summaries, action plan steps, financial health / “Fin Scores” metrics, and account-related metadata such as last login timestamp (for account management).  
**Why:** To persist your plan across sessions/devices and support plan history/progress.

### 4) Plan Data Stored in Google Cloud SQL (via backend sync)
Finatic may store plan summaries and action steps in a Google Cloud SQL database through a backend service. This is used to keep plan data consistent across sessions/devices and support server-side syncing.

**Examples of what may be stored:** Action plan steps (e.g., phase/title/detail/status and a stable step identifier), and plan summary/steps returned by backend endpoints (e.g., a full plan fetch).

### 5) AI Processing (Google Gemini via Firebase AI Logic)
When you use AI features, we send relevant text to Google Gemini (through Firebase AI Logic) to generate outputs.

**What may be sent:**  
- Your input text (questions, onboarding responses, chat messages)  
- Relevant plan context (e.g., onboarding summary, plan outline, action steps)  
- Recent notes (for daily guidance)

**Why:** To generate AI responses, planning guidance, and plan artifacts you request.

**Provider retention:** Google may retain submitted prompts/context and outputs for a limited period for abuse monitoring and service improvement as described in Google’s applicable policies. We do not control provider retention for data processed by Google once transmitted.

### 6) Voice Input (Apple Speech Recognition)
If you enable voice input, Finatic processes audio via Apple’s Speech Recognition.

**What is processed:** Microphone audio while recording and the resulting transcript text.  
**Why:** To provide voice-to-text input.  
Apple’s processing is governed by Apple’s policies and your iOS permission choices.

---

## What We Do Not Collect

- No precise location data.
- No advertising identifiers or cross-app tracking identifiers.
- No third-party ad tracking SDKs.
- No sale of personal data.

---

## How We Use Information

We use information to:
- Provide app functionality (account login, plan storage, progress tracking).
- Generate your financial plan and action steps when requested.
- Enable AI features when you request them.
- Provide customer support if you contact us.
- Maintain security and prevent fraud/abuse.

We do not use your data for advertising.

---

## Legal Bases (Where Applicable)
Depending on your location, we process information under one or more of the following bases:
- **Consent** (e.g., voice input, optional AI features; you can stop using features and adjust iOS permissions).
- **Performance of a contract** (to provide the app services you request).
- **Legitimate interests** (security, fraud prevention, service reliability).

---

## AI and Financial Guidance Disclaimer
AI-generated content is for informational purposes only and is not financial, tax, or legal advice. Finatic is not a registered investment advisor. You remain responsible for your financial decisions. No fiduciary relationship is created.

---

## Sharing and Third Parties

We use trusted service providers to operate Finatic, such as:
- **Google Firebase** (authentication and data storage)
- **Google Gemini** (AI processing via Firebase AI Logic)
- **Apple** (Speech Recognition; App Store services including payments, if applicable)

These providers process data to provide their services and protect it under their own policies and contractual obligations. We do not sell or rent personal data.

---

## Data Retention

### On your device
Some app state may be stored locally (for example, daily notes or streak-related state). Deleting the app removes local data, subject to iOS backup/restore behavior.

### In Firebase (Firestore)
We store your data while your account is active to provide the service (e.g., onboarding answers, plan summary, action steps, and metrics).

### In Google Cloud SQL (backend sync)
Plan summaries and/or action steps may also be stored to support syncing and consistency across devices/sessions.

### Inactivity deletion (12 months)
If your account is inactive for 12 months (no sign-in activity recorded), we delete or de-identify your stored Finatic account data (including related Firestore/SQL records), unless we must retain certain records for legal/security reasons.

### Deletion requests
You may request deletion of your account and associated data by contacting us (see **Contact**). We verify account ownership before deletion.

### Third-party retention
Google and Apple may retain certain data according to their own policies. We cannot directly delete data retained by those providers; please refer to their policies.

---

## Your Rights and Choices
Depending on your location, you may have rights to:
- Access your personal data
- Correct your data
- Delete your data
- Request a copy of your data
- Opt out of sale/sharing (we do not sell data)

To exercise your rights, contact us using the email below. We will verify your request before responding and will not discriminate against you for exercising your rights.

---

## Security
We use industry-standard safeguards and reputable providers. No system is completely secure. If a data breach occurs, we will notify affected users as required by law.

---

## Children’s Privacy
Finatic is not intended for children under 13. We do not knowingly collect data from children. If we discover such data, we delete it promptly.

---

## Changes to This Policy
We may update this policy from time to time. The “Last Updated” date above reflects the current version.

---

## Contact
For privacy questions or data requests:

**Email:** privacy@finaticapp.com
