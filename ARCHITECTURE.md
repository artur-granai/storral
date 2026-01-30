# 🏛️ Storral Project Architecture

> Discover how Storral combines an app, physical device, direct network connection, and official support to facilitate and protect your way of using Bitcoin.

---

## 📌 Overview

The **Storral Project** is a modular ecosystem that prioritizes **security, privacy, and financial autonomy in Bitcoin**.
The architecture was designed to be flexible: each person chooses how they want to protect, move, and recover their Bitcoins, combining four main modules — all independent, yet integrable.

---

## 🏗️ System Components

The system is formed by **four main modules**, which work together or independently:

### **1️⃣ Storral Labs (Wallet App)**
An easy, free, and secure app to store, send, and receive Bitcoins, ideal for both daily use and beginners.

### **2️⃣ Storral Engineering (Shield Device)**
A physical device (hardwallet) that keeps your keys protected outside the digital environment, requiring manual confirmation for every transaction — your barrier against scams and virtual intrusions.

### **3️⃣ Storral Orbit (Blockchain Direct)**
Proprietary infrastructure to send and receive transactions directly on the Bitcoin network, ensuring more privacy and eliminating intermediaries. You decide how to connect to the blockchain.

### **4️⃣ Storral Care (Support)**
Simulation of an official support channel (Didactic), modeled to study service flows, access recovery, and warranty logistics (RMA) in critical systems.

---

### 🧩 Modularity and Security

Each module is **independent**, but all **integrate** to offer a complete, flexible, and robust experience.

- Private keys **never leave the physical device**, nor are they exposed to the internet.
- The user has **total control** over their coins and their own degree of protection.

---

## 🔄 How It Works in Practice: Use Flow in Storral

See how simple and secure it is to use Storral, step by step:

1. **Opening the App**
   - You access **Storral Labs (Wallet App)** on your computer or mobile to manage your Bitcoin wallets.

2. **Creating a Transaction**
   - To send Bitcoins, you fill in the data in the app (recipient, amount, etc.) and review all information before confirming.

3. **Confirmation and Signing**
   - **If you use only the app:**
     The transaction signing is done directly in the application.
     (Note: more practical, but with less protection than using the physical device.)

   - **If you also use Storral Engineering (Shield Device):**
     As soon as you request the transfer via the app, the request is sent to the physical device via secure Bluetooth.
     **Storral Engineering (Shield Device)** requires you to **manually confirm** the transaction (by physical button or touch).
     Only after this physical approval does the device securely sign the transaction and return it to the app.
     (The private key never leaves the device!)

4. **Sending to the Blockchain**
   - The signed transaction is broadcast by the app to the Bitcoin network.
   - You can choose whether to broadcast using **Storral Orbit (Blockchain Direct)** (own node, for maximum privacy) or a public node.

5. **Monitoring and Support**
   - **Storral Care (Support)** is always available for questions, access recovery, or support for the physical device.

**Integration in Practice:**
You can choose how to use Storral according to your need: just the app for practicality, the physical device for maximum security, and/or the own node to guarantee total privacy.
Everything works integrated or independently, and official support accompanies you at every stage.

> **Differential:**
> Whenever **Storral Engineering (Shield Device)** is connected, **no transaction can be performed without your manual confirmation on the device itself**. This prevents unauthorized movements and protects your Bitcoins against any attempt at digital fraud or unauthorized access.
>
> **You choose the degree of protection, and have total control of your funds.**

---

## 🔐 Security Architecture

Storral was designed to ensure protection, privacy, and total control at all system layers — not just in the physical device, but also in the app, node infrastructure, and support.
Check out how each module contributes to a truly secure ecosystem:

---

### **1️⃣ Application (Storral Labs — Wallet App)**
- **Local protection:** The app never stores private keys when integrated with the physical device. If used without the device, it follows security best practices and warns about digital environment risks.
- **Authentication and permissions:** Allows authentication by strong password, PIN, and/or **biometrics** (fingerprint, facial recognition), protecting access to the app and sensitive functions.
- **Biometric confirmation for transactions:** Whenever the app is used to sign and send Bitcoins (without the physical device), it may require additional biometric authentication, avoiding accidental or unauthorized operations.
- **Secure synchronization:** All communication with the own node or physical device is encrypted.
- **No sensitive storage:** Critical information (such as seed and private key) is never exposed in the app when used with the physical device.

---

### **2️⃣ Physical Device (Storral Engineering — Shield Device)**
- **Complete isolation:** Never accesses the internet, always acting as a second layer of security.
- **Controlled Bluetooth:** Only activates communication at the moment of signing and turns off automatically after use.
- **TrustZone & Secure Element:** Private keys never leave the secure hardware.
- **Manual confirmation:** Every transaction must be physically approved by the user.
- **Physical and logical protection:** Even with physical access, it is not possible to extract keys or bypass secure operations.

---

### **3️⃣ Own Node (Storral Orbit — Blockchain Direct)**
- **User privacy:** The node can be hosted locally or in the cloud by the user themselves, ensuring transaction information is not exposed to third parties.
- **Encrypted communication:** All exchanges between app and own node are protected.
- **Data isolation:** No private key or seed is processed or stored on the node.
- **VPN compatibility:** The system is compatible with VPNs for maximum privacy in app connections.

---

### **4️⃣ Support Channel (Storral Care — Support)**
- **Secure procedures:** Support only acts according to transparent, auditable routines without access to user keys.
- **No backdoors:** No one in support can access funds, reset passwords without user authorization, or manipulate the device remotely.
- **Recovery support:** Recovery processes require multiple factors and confirmation of user identity, avoiding fraud.

---

### **5️⃣ Integrated Security and Modularity**
- **Independent modules, joint protection:** Even using only one module, the user has proportional security levels — using more modules, protection is maximum.
- **End-to-end encryption:** All critical communications in the system use strong encryption (AES-GCM or higher).
- **Zero Trust:** The system never assumes a module is 100% secure by itself — each layer validates and protects information before passing it on.
- **No backdoors:** There is no hidden mechanism, master password, or shortcut that allows any person, company, or developer to access user funds.

---

> 🔒 **Summary of Storral Differentials:**
> - **Private keys are never exposed** at any point in the system.
> - **Manual authorization** for all relevant movements, whenever the physical device is active.
> - **Real privacy and autonomy:** user control over all modules and connections.
> - **Always encrypted communication** and mutual authentication where necessary.
> - **100% transparent and auditable support and recovery procedures**.

---

## 📜 Conclusion

The **Storral Project** was designed with a reinforced security architecture, ensuring that:

- ✅ **With the physical device, private keys are never exposed.**
- ✅ **All communication between modules is end-to-end encrypted.**
- ✅ **The user maintains total control over their Bitcoins and their privacy.**

By uniting dedicated hardware, robust software, and decentralized infrastructure, the project seeks to provide **the most secure and private experience possible for those who use Bitcoin**.

---

© 2026 Storral · All rights reserved. 

---
