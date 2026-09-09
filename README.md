# AEGIS

### AI Security Incident Response Lab

> When the model is manipulated, the architecture must still hold.

AEGIS is an interactive AI security incident-response lab built around a Prompt Injection Incident.

The project focuses on one core idea:

**We don't secure AI by trusting the model. We secure the system so it doesn't have to be trusted.**

---

## 🚨 The Incident

A production AI assistant is manipulated through Prompt Injection and attempts to reach protected instructions, tools, and sensitive resources.

The challenge is not only detecting the attack, but designing an architecture that limits the damage even when the model is manipulated.

---

## 🛡️ Response Framework

### FREEZE → FENCE → FIX → PROVE

- **FREEZE** — Stop active damage and preserve evidence.
- **FENCE** — Isolate the affected system and restrict privileged access.
- **FIX** — Harden guardrails, policies, tools, and access boundaries.
- **PROVE** — Reproduce the attack safely and verify that the breach is prevented.

---

## 🏗️ Secure Architecture

**Untrusted Input → Input Defense → LLM → Policy Engine → Tool Gateway → Secret Vault**

### Core Security Rules

- **NO SECRETS**
- **LEAST PRIVILEGE**
- **POLICY FIRST**

The LLM does not receive direct access to secrets or privileged capabilities.

---

## 🔬 Attack & Retest

AEGIS includes an interactive attack simulation that reproduces the original Prompt Injection scenario.

The system then verifies that:

- The attack is detected.
- Privileged access is restricted.
- Secret access is blocked.
- The architecture contains the attack.

### Expected Result

**ATTACK REPRODUCED — BREACH PREVENTED**

---

## ✅ Security Gate

**8/8 CHECKS PASSED**

- Logs Reviewed
- Attack Identified
- Tools Isolated
- Guardrails Hardened
- Rate Limits Active
- Budget Alerts Active
- Regression Test Passed
- Secret Access Denied

### RELEASE GATE

**APPROVED FOR STAGED RELEASE**

**SECURE**

---

## 🚀 Live Demo

🔗 **Live Demo:** [AEGIS Live Demo](https://kinzykassem.github.io/AEGIS/)

---

## 🛠️ Built With

- HTML
- CSS
- JavaScript

---

## 📌 PROVE IT — Day 04

**Mission: The Prompt Injection Incident**

AEGIS was created as an interactive response to the mission, turning the security analysis into a practical incident-response experience.

---

## Core Principle

> **The model may fail. The architecture must not.**
