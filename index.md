# FINATIC PRIVACY POLICY
**Last Updated:** January 24, 2026

Finatic (“Finatic,” “we,” “us”) is an iOS app that helps you build and follow a personalized financial action plan. This Privacy Policy explains what data we collect/process, how we use it, and your rights.

---

## SUMMARY (PLAIN ENGLISH)

- Finatic **requires an account** to work (email + password).
- Your plan data is stored securely in **Google Firebase** (Firestore).
- Some plan data may also be stored in a **Google Cloud SQL database** (via a backend service that syncs plan summaries and action steps).
- **AI features** use **Google Gemini** to generate guidance when you request it.
- **Voice input** (if you enable it) uses **Apple Speech Recognition**.
- We do **not** sell your data.
- We do **not** use advertising trackers.
- You can request deletion at any time.
- If your account is **inactive for 12 months**, we delete or de-identify your stored Finatic account data (unless we must retain it for legal/security reasons).

---

## DATA WE COLLECT / PROCESS

### 1) Account Information (Firebase Authentication)
**What we collect:** Email address and authentication credentials (handled by Firebase Authentication). fileciteturn9file13 fileciteturn11file10  
**Why:** To create and manage your account and associate your data with you.

---

### 2) User Content and Profile Information
**What you provide:** Name, age, household/family status, income, expenses, assets, debts, onboarding answers, notes, and free‑form text. fileciteturn9file16 fileciteturn10file12 fileciteturn9file15  
**Why:** To generate your personalized plan, daily action steps, and progress views.

---

### 3) Plan Data Stored in Firebase Firestore
**Includes (examples):**
- Onboarding answers (stored under your user document) fileciteturn11file19
- Plan summaries and action plan steps fileciteturn9file6
- Financial health score and “Fin Scores” (metrics) fileciteturn9file1 fileciteturn10file0
- Login metadata such as last login timestamp (to support account management) fileciteturn11file6

**Why:** To persist your plan across sessions and devices, and support plan progress/history.

---

### 4) Plan Data Stored in Google Cloud SQL (via backend sync)
Finatic may store plan summaries and action steps in a **Google Cloud SQL database** through a backend service. This is used to keep the plan consistent across sessions/devices and to support server-side syncing.

**What is stored (examples):**
- Action plan step rows (phase/title/detail/status and stable step_id) synced to an `action_plan_steps` SQL table via a Cloud Run endpoint. fileciteturn9file19  
- Plan summary + steps may be fetched back from the backend (e.g., a `/fullPlan` endpoint returning `summary_md` and `steps`). fileciteturn9file6

---

### 5) AI Processing (Google Gemini via Firebase AI Logic)
When you use AI features, we send text data to Google Gemini (through Firebase AI Logic). fileciteturn9file1

**What is sent (examples):**
- Your input text (questions, onboarding responses, chat messages)
- Relevant plan context (e.g., onboarding Q&A, plan outline, action steps) fileciteturn11file15  
- Recent notes (for Daily guidance) fileciteturn10file3

**Why:** To generate AI responses, planning guidance, and plan artifacts.

**Gemini retention:** Google may retain submitted prompts/context and outputs for **up to 55 days** for abuse monitoring, per Gemini API policies. citeturn0search1 citeturn0search2

---

### 6) Voice Input (Apple Speech Recognition)
If enabled, we process audio through Apple’s Speech Recognition. fileciteturn9file0

**What is collected/processed:**
- Microphone audio while recording
- Transcribed text

**Why:** To allow voice input.

Audio/speech processing is governed by Apple’s privacy policies.

---

## WHAT WE DO NOT COLLECT

- No precise location data.
- No advertising identifiers or cross‑app tracking identifiers.
- No third‑party tracking SDKs for ads (as implemented in this codebase).
- No sale of personal data.

---

## HOW WE USE YOUR DATA

We use your data to:
- Provide app functionality (account login, plan storage, progress tracking). fileciteturn11file10
- Generate your financial plan and action steps (when requested). fileciteturn9file6
- Enable AI features when requested (Gemini). fileciteturn9file1
- Provide customer support (if you contact us).
- Maintain security and prevent abuse (including abuse monitoring by providers). citeturn0search1

We do **not** use your data for advertising.

---

## LEGAL BASIS FOR PROCESSING (US)

We process your data based on:
- **Your consent** (voice and AI features; you can revoke permissions in iOS Settings or by not using AI features).
- **Performance of a contract** (providing the app services you request).
- **Legitimate business interests** (security, fraud prevention, service reliability).

---

## AI AND FINANCIAL GUIDANCE DISCLAIMER

AI-generated content is informational only. It is **not** financial, tax, or legal advice.
Finatic is **not** a registered investment advisor. You remain responsible for your financial decisions.
No fiduciary relationship is created.

---

## DATA SHARING AND THIRD PARTIES

We use trusted providers:
- **Google Firebase** (authentication and storage) fileciteturn11file13
- **Google Gemini** (AI processing via Firebase AI Logic) fileciteturn9file1
- **Apple** (Speech Recognition; and App Store payments if applicable)

These providers process data only to provide their services and protect your data under their policies.

**Apple “same/equal protection” requirement:** Any third party that processes user data for Finatic is expected to provide the **same or equal protection of user data** as stated in this policy and required by Apple’s App Review Guidelines. citeturn0search0

We do not sell or rent personal data.

---

## DATA RETENTION

### On your device
Some app state may be stored locally (e.g., daily notes and streak-related state) using on‑device storage. fileciteturn10file3  
Deleting the app removes local data (subject to iOS backups/restores).

### In Firebase (Firestore)
Your data is stored while your account is active (for example: onboarding answers, plan summary, action steps, and metrics). fileciteturn11file13

### In Google Cloud SQL (via backend sync)
Plan summaries and/or action steps may also be stored in a Google Cloud SQL database through our backend sync. fileciteturn9file19 fileciteturn9file6

### Inactivity deletion (12 months)
If your account is inactive for **12 months** (no sign-in activity recorded), we delete or de-identify your stored Finatic account data (including related Firestore/SQL records), unless we must retain certain records for legal/security reasons.

### Deletion requests
You may request deletion of your account and associated data by contacting us (see Contact). We verify ownership before deletion.

### Third-party retention
Google and Apple may retain data according to their own policies (e.g., Gemini abuse monitoring retention). citeturn0search1  
We cannot directly delete data retained by those providers; please refer to their policies.

---

## YOUR PRIVACY RIGHTS (CALIFORNIA & US)

You have the right to:
- Access your personal data
- Correct your data
- Delete your data
- Request a copy of your data
- Opt out of sale or sharing (we do not sell data)

To exercise your rights, email us at the address below. We will verify your request before responding, and we will not discriminate against you for exercising your rights.

---

## SECURITY

We use industry-standard safeguards and reputable providers. No system is completely secure.
If a data breach occurs, we will notify affected users as required by law.

---

## CHILDREN’S PRIVACY

Finatic is not intended for children under 13. We do not knowingly collect data from children.
If we discover such data, we delete it promptly. Parents may contact us to request removal.

---

## CHANGES TO THIS POLICY

We may update this policy from time to time. The “Last Updated” date reflects the current version.

---

## CONTACT

For privacy questions or data requests:

**Email:** privacy@finaticapp.com
