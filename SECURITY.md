# Security Policy

**Abc's Noob Open Social**

## 1. Security Philosophy

Security in **Abc's Noob Open Social** is based on these principles:

* **No central authority**
* **No trusted third party**
* **No master keys**
* **No backdoors**
* **No server to seize**

Security is achieved through:

* cryptography
* decentralization
* transparency
* user-held keys

Not through trust in developers, companies, or governments.

---

## 2. Threat Model

This project explicitly assumes the following adversaries:

* Governments attempting censorship, shutdown, or coercion
* Corporations attempting surveillance or control
* Compromised developers or maintainers
* Network failures (internet shutdowns, solar storms, disasters)
* Partial or total offline environments

The system is designed so that **no single entity can compromise the network**.

---

## 3. What This Project Does *Not* Protect Against

Users must understand the limits:

* ❌ Physical access to your device
* ❌ Malware already running on your device
* ❌ Weak or leaked passphrases
* ❌ User mistakes (lost keys, deleted data)

Lost keys **cannot** be recovered.
This is a deliberate design decision.

---

## 4. Cryptographic Guarantees

* Identity is derived from:

  * cryptographic key pairs
  * passphrase + secret key
  * optional IPv6-based addressing
* No passwords are stored
* No password recovery exists
* Developers **cannot** access user data

If you control your keys, you control your data.

---

## 5. Backdoor Policy (Zero Tolerance)

The following are **strictly forbidden**:

* Hidden access mechanisms
* Undocumented remote control
* Kill switches
* Silent data exfiltration
* Centralized override logic

Any confirmed backdoor:

* will be publicly disclosed
* will be permanently rejected
* may result in a permanent ban from contribution

---

## 6. Vulnerability Reporting

Because this is a decentralized project:

* There is **no private security email**
* There is **no security team with special powers**

### How to report a vulnerability

You may:

1. Open a **public issue** with clear technical details
2. Provide a **proof of concept** if possible
3. Clearly label the issue as **SECURITY**

> Transparency is preferred over secrecy.

If you believe public disclosure would cause immediate harm, redact exploit details while still describing the issue.

---

## 7. Responsible Disclosure (Community-Based)

* Contributors are encouraged to:

  * report issues early
  * avoid exploiting users
  * cooperate on fixes
* There is **no NDA**
* There is **no embargo enforced by authority**

Fixes happen through:

* public discussion
* open patches
* visible review

---

## 8. Security Updates

* There is **no forced update**
* Nodes choose when and how to upgrade
* Forks are allowed and expected

Security evolves through:

* diversity
* independent implementations
* natural selection of better code

---

## 9. Supply Chain Security

* Only **GPLv3-compatible dependencies** are allowed
* Binary blobs are discouraged
* Dependencies must be auditable
* Vendoring is preferred where practical

---

## 10. Legal & Coercion Resistance

* Developers **cannot comply** with requests to:

  * reset accounts
  * recover keys
  * shut down the network
  * censor content
* Such requests are technically impossible by design

---

## 11. Disclaimer

This project is provided **AS IS**, without warranty of any kind.

You are responsible for:

* securing your device
* backing up your keys
* understanding the risks

---

## 12. Final Statement

> “Security does not come from power.
> It comes from the absence of power.”

