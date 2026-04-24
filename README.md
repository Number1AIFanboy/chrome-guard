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

## 📖 Visual Install Guide

For a full interactive walkthrough, open: docs/index.html

This guide provides a step-by-step visual install experience with system flow, security explanations, and setup instructions.

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

