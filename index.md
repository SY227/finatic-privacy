# FINATIC PRIVACY POLICY
**Last Updated:** January 24, 2026

Finatic (“Finatic,” “we,” “us”) is an iOS app that helps you build and follow a personalized financial action plan. This Privacy Policy explains what data we collect and process, how we use it, and your rights.

---

## Summary (Plain English)

- **Account required:** Finatic requires an account (email + password) to work.
- **Cloud storage:** Your plan data is stored in **Google Firebase** (Firestore).
- **Backend sync / SQL storage:** Some plan data may also be stored in a **Google Cloud SQL** database through our backend synchronization services.
- **AI is optional:** AI features use **Google Gemini** to generate guidance **only when you request it**.
- **Voice is optional:** Voice input uses **Apple Speech Recognition** **only if you enable it**.
- **No selling / no ad tracking:** We do **not** sell your data and we do **not** use advertising trackers.
- **Deletion controls:** You can request deletion at any time.
- **Inactivity deletion:** If your account is **inactive for 12 months**, we delete or de-identify your stored Finatic account data (unless we must retain certain records for legal or security reasons).

---

## Data We Collect / Process

### 1) Account Information (Firebase Authentication)
**What we collect:** Email address and authentication credentials (handled by Firebase Authentication).  
**Why:** To create and manage your account and associate your plan data with you.

### 2) User Content and Profile Information
**What you provide:** Information you enter such as name, age, household/family status, income, expenses, assets, debts, onboarding answers, notes, and free-form text.  
**Why:** To generate your personalized plan, daily action steps, and progress views.

### 3) Plan Data Stored in Firebase Firestore
**Includes (examples):**
- Onboarding answers
- Plan summaries
- Action plan steps and completion status
- Financial health scores / progress history
- Timestamps and progress history

**Why:** To persist your plan across sessions and devices and support progress/history.

### 4) Plan Data Stored in Google Cloud SQL (Backend Sync)
Finatic may store certain plan artifacts (such as plan summaries and action plan steps) in a **Google Cloud SQL** database through backend synchronization services.

**Why:** To keep your plan consistent across sessions/devices and support server-side syncing and reliability.

### 5) AI Processing (Google Gemini via Firebase AI Logic)
When you use AI features, we send text data to **Google Gemini** (through Firebase AI Logic).

**What may be sent:**
- Your input text (questions, onboarding responses, chat messages)
- Relevant plan context (e.g., onboarding Q&A, plan outline, action steps)
- Recent notes or questions (when needed to fulfill your request)

**Why:** To generate AI responses and planning guidance you request.

**Gemini retention:** Google may retain submitted text and outputs for up to **55 days** for abuse monitoring, per Gemini API policies.

### 6) Voice Input (Apple Speech Recognition)
If enabled, we process audio through Apple’s Speech Recognition.

**What is processed:**
- Microphone audio while recording
- Transcribed text

**Why:** To allow voice input.

Speech/audio processing is governed by Apple’s privacy policies.

---

## What We Do Not Collect

- **No precise location** data.
- **No financial institution login credentials.**
- **No advertising identifiers** used for targeted advertising.
- **No third-party tracking SDKs** for ads.
- **No sale of personal data.**

---

## How We Use Your Data

We use your data to:
- Provide app functionality (account login, plan storage, progress tracking)
- Generate your financial plan and action steps
- Show progress, reminders, and daily recommended steps
- Enable AI features **when requested**
- Provide customer support (if you contact us)
- Maintain security and prevent abuse

We do **not** use your data for advertising.

---

## Legal Basis for Processing (US)

We process your data based on:
- **Your consent** (voice and AI features)
- **Performance of a contract** (providing the services you request)
- **Legitimate business interests** (security, fraud prevention, service reliability)

---

## AI and Financial Guidance Disclaimer

AI-generated content is **informational only**. It is **not** financial, tax, or legal advice.  
Finatic is **not** a registered investment advisor. You remain responsible for your financial decisions.  
No fiduciary relationship is created.

---

## Data Sharing and Third Parties

We use trusted providers, such as:
- **Google Firebase** (authentication and storage)
- **Google Gemini** (AI processing)
- **Apple** (Speech Recognition and App Store payments, if applicable)

These providers process data to provide their services and protect data under their own privacy and security policies.

**Same/equal protection statement (Apple requirement):** Any third party that processes user data for Finatic is expected to provide the **same or equal protection of user data** as stated in this policy and required by Apple’s guidelines.

We do not sell or rent personal data.

---

## Data Retention

### On Your Device
Some app state may be stored locally to support app features. Deleting the app removes local data (subject to iOS backups/restores).

### In Firebase (Firestore) and Google Cloud SQL (Backend Sync)
Your plan data is stored while your account is active to provide the service.

### Inactivity Deletion (12 months)
If your account is **inactive for 12 months** (no sign-in activity), we delete or de-identify your stored Finatic account data, including related Firestore/SQL records, unless we must retain certain records for legal or security reasons.

### Deletion Requests
You may request deletion of your account and stored Finatic data by contacting us (see **Contact**). We verify ownership before deletion.

### Third-Party Retention
Google and Apple may retain data according to their own policies (including Gemini abuse monitoring retention). We cannot directly delete data retained by those providers; please refer to their policies.

---

## Your Privacy Rights (California & US)

You have the right to:
- Access your personal data
- Correct your data
- Delete your data
- Request a copy of your data
- Opt out of sale or sharing (we do not sell data)

To exercise your rights, email us at the address below. We will verify your request before responding. We will not discriminate against you for exercising your rights.

---

## Contact

For privacy questions or data requests:

**Email:** privacy@finaticapp.com
