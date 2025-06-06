
---

# compare-speed.md

## Module 6: Comparing Browsing Speed and Responsiveness With and Without VPN

---

### Objective

This module guides you through evaluating and comparing your internet browsing performance while connected to ProtonVPN versus your regular, unprotected connection.

The aim is to understand the performance impact VPN encryption and server routing have on internet speed and overall browsing experience.

---

### Why Compare Speed?

VPNs introduce additional overhead because:

* Traffic is encrypted before leaving your device.
* It is routed through a VPN server (often in another region) before reaching the destination website.
* The distance to the VPN server and its current load can affect latency and speed.

Understanding this trade-off is essential for choosing the right VPN server for your needs.

---

### Step-by-Step Speed Comparison Procedure

#### Step 1: Test Browsing Speed Without VPN

1. **Disconnect** ProtonVPN if currently connected.
2. Open your web browser.
3. Visit [https://www.speedtest.net](https://www.speedtest.net) or [https://fast.com](https://fast.com).
4. Run the speed test.
5. Note and record the following values:

   * **Ping (ms)**
   * **Download Speed (Mbps)**
   * **Upload Speed (Mbps)**
6. Take a screenshot of the results (e.g., `speed_before.png`).

---

#### Step 2: Test Browsing Speed With VPN

1. **Reconnect** ProtonVPN to the same server you used earlier.
2. Visit the same speed testing website.
3. Run the speed test again.
4. Note and record the new:

   * **Ping (ms)**
   * **Download Speed (Mbps)**
   * **Upload Speed (Mbps)**
5. Take a screenshot of the VPN-protected results (e.g., `speed_after.png`).

---

#### Step 3: Browse and Compare Website Loading

To subjectively compare real-world browsing performance:

1. Note the loading times for frequently visited websites (like YouTube, Gmail, or a news site) **with and without VPN**.
2. Observe any noticeable delays or buffering differences.
3. Take screenshots for visual reference:

   * `website_before.png` — browsing without VPN
   * `website_after.png` — browsing with VPN

---

### Summary of Findings

Create a brief table like this to summarize your results:

| Test Condition       | Ping (ms) | Download (Mbps) | Upload (Mbps) | Observations            |
| :------------------- | :-------- | :-------------- | :------------ | :---------------------- |
| Without VPN          | 116       | 5               | 0.70          | Fast, no noticeable lag |
| With VPN (ProtonVPN) | 100       | 1               | 0.10          | Slightly slower, secure |

*Note:* VPN speed impact depends on server distance, load, and protocol used.

---

### Conclusion

You should now understand how VPN encryption and routing affect your connection performance. While some reduction in speed and increase in latency is normal, it’s often an acceptable trade-off for enhanced privacy and security.

---
