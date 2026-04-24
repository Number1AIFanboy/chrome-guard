# 🛡️ Chrome Guard

**Browser security that fights back.**

Built by **Level3ID**, a Tennessee-based security company focused on Proof-of-Human (PoH), BioAuth, and real-time browser protection.

Chrome Guard protects your browser with:

* Encrypted BioAuth verification
* Sensitive page protection (login / checkout flows)
* Real-time shutdown detection and alerts
* Edge-enforced security validation

> Chrome Guard is currently distributed through Developer Mode for direct access, evaluation, and early release use.
> Distribution method does not define security posture.

---

## 🚀 Install Chrome Guard

1. Download this repo as a ZIP
2. Extract the folder
3. Open Chrome and go to:

```
chrome://extensions
```

4. Turn on **Developer Mode** (top right)
5. Click **Load unpacked**
6. Select the `/dist` folder

✅ Chrome Guard is now active.

---

## 📖 Visual Install Guide

For a full interactive walkthrough, open: docs/index.html

This guide provides a step-by-step visual install experience with system flow, security explanations, and setup instructions.

---

## 🔐 What Chrome Guard Does

Chrome Guard is designed as an **active browser defense system**.

### Core Capabilities

* ⚡ **Real-time Shutdown Detection**
  Detects when browser protection is disabled and alerts immediately

* 🔒 **Sensitive Page Protection**
  Adds protection layers to login, checkout, and high-risk pages

* 🧠 **Proof-of-Human (PoH)**
  Helps prevent automated abuse and scripted interactions

* 🧬 **BioAuth Verification**
  Confirms identity using encrypted biometric reference data

* 📡 **Security State Monitoring**
  Continuously validates extension integrity and browser state

---

## 🧬 BioAuth Privacy Model

Chrome Guard uses **encrypted BioAuth verification**:

* A reference image is securely stored
* Reference data is encrypted
* Live verification captures are processed **ephemerally**
* Live captures are **not stored after matching**
* No continuous biometric tracking
* No biometric data selling

> Chrome Guard uses encrypted reference data with ephemeral verification — no live capture data is stored. 

---

## ✅ User Consent & Control

Chrome Guard uses BioAuth verification with **explicit user consent**.

Before enabling BioAuth, users are informed that:

* A reference image will be securely stored
* Reference data is encrypted
* Camera access is used for **event-based verification only**
* Verification captures are processed **ephemerally** and not stored
* BioAuth can be disabled at any time

### Your Controls

You can:

* Disable BioAuth
* Remove stored verification data
* Uninstall Chrome Guard at any time

Chrome Guard does **not** perform continuous biometric tracking or background capture.

---

## 🛡️ Security Architecture (High-Level)

Chrome Guard uses a **layered security model**:

### Extension Layer

* Monitors browser state
* Detects shutdowns and tampering
* Applies protection to sensitive pages

### BioAuth Layer

* Uses encrypted reference images
* Performs identity checks with ephemeral verification captures
* No live biometric data is stored after matching

### Backend Enforcement

* Validates requests and tokens
* Applies origin-bound security controls
* Enforces rate limits and verification decisions

> Critical security decisions are enforced outside the client.

---

## 📬 Support & Feedback

For bug reports, issues, or page update requests:

📧 **[support@level3id.com](mailto:support@level3id.com)**
Subject line: **Chrome Guard**

---

## 👤 Account & Recovery

Chrome Guard accounts are tied to:

* The browser environment
* The registered user email

If the extension is removed, account recovery may be available depending on configuration and verification status.

---

## 💳 Premium Features

Chrome Guard offers optional premium features:

* 📱 SMS Alerts
* 🛡️ Beta Rogue Guard

Pricing: **$5.95/month**

Payments are handled securely through **Stripe Checkout**.
SMS messaging is delivered via **Twilio** infrastructure.

👉 Premium features are optional and not required for core protection.

---

## ⚠️ Usage Notice

Chrome Guard is provided for **security enhancement and evaluation**.

Do not use Chrome Guard to:

* Monitor individuals without consent
* Capture biometric data without permission
* Misrepresent its purpose or capabilities

---

## 🚀 Chrome Guard

**Real-time protection. BioAuth verification. Proof-of-Human security.**

Built by **Level3ID**


## 🏢 Built by Level3ID

Chrome Guard is developed by **Level3ID**, a Tennessee-based security company focused on:

* Proof-of-Human (PoH) systems
* BioAuth verification technology
* Browser-level protection
* Real-time security monitoring

Chrome Guard is part of a broader system designed to bring **verifiable human identity and active protection into web interactions**.

---

## 🛡️ Final Note

Chrome Guard is built to protect real users in real environments.

**Level3ID — Verifying humans. Securing interactions.**

