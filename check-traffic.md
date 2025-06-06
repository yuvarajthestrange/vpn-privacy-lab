
---

# check-traffic.md

## Module 5: Checking Encrypted Web Traffic Through ProtonVPN on Windows

---

### Objective

This module focuses on verifying that your web traffic is encrypted and securely routed through ProtonVPN after establishing a connection. It helps confirm that your online communications are protected from potential eavesdropping and surveillance.

---

### Why Check Encrypted Traffic?

When connected to a VPN:

* Your internet traffic should be encapsulated inside an encrypted tunnel.
* Third parties (like ISPs, network admins, or attackers on public Wi-Fi) should not be able to inspect your data.
* Only the VPN server and your device know the details of your web activity.

---

### Step-by-Step Traffic Check Procedure

#### Step 1: Ensure VPN Connection is Active

* Confirm ProtonVPN is connected to your chosen server (refer to `03-connect-server.md` if needed).
* Look for the **“Connected”** status in the ProtonVPN client window.

---

#### Step 2: Access a Secure Website

* Open your web browser (e.g., Chrome, Edge, Firefox).
* Visit a secure, HTTPS-enabled website such as:

  * [https://example.com](https://example.com)
  * [https://protonvpn.com](https://protonvpn.com)

**Note:** Modern browsers display a lock icon (`🔒`) in the address bar for secure connections.

---

#### Step 3: Check for Secure (HTTPS) Connection

* In the browser’s address bar, confirm:

  * The URL begins with **https\://**
  * A **lock icon** is visible next to the URL
* Click the lock icon → **Connection is secure** message should appear.

**This indicates your connection to the website is encrypted via HTTPS.**

---

#### Step 4: Use a Packet Sniffer (Optional — Advanced)

For users wanting technical validation:

* Install **Wireshark** (a free network protocol analyzer): [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)
* Start capturing packets on your active network interface.
* Browse the same HTTPS website while connected to ProtonVPN.
* Observe that packet content is encrypted (appears as **TLS** or **Encrypted Application Data** in Wireshark).
* This confirms that even though traffic passes through your ISP or Wi-Fi network, the content is inaccessible without decryption keys.

---

#### Step 5: Take a Screenshot

* Capture a screenshot showing the browser with the **lock icon** and HTTPS connection visible (e.g., `website_after.png`).
* Optionally, capture a Wireshark view displaying encrypted traffic.

---

### Summary

At this stage:

* Web traffic between your device and the VPN server is encrypted by ProtonVPN.
* The lock icon and HTTPS ensure that traffic between the VPN server and the destination website is also encrypted.
* ISPs and network snoopers cannot read your actual browsing content.

---

### Screenshots

* `website_after.png` — Secure website open in browser with HTTPS lock icon

---


