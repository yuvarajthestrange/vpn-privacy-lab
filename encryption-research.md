
---

# encryption-research.md

## Module 7: VPN Encryption Technologies and Privacy Features

---

### Objective

The purpose of this module is to research and understand the encryption protocols and privacy-enhancing features provided by ProtonVPN, alongside general VPN security mechanisms. This will help you appreciate how a VPN secures internet communications and protects user privacy.

---

### What is VPN Encryption?

**VPN encryption** is the process of converting readable data (plaintext) into an unreadable format (ciphertext) to protect it from unauthorized access during transmission between your device and the VPN server.

Encryption ensures:

* Confidentiality: Prevents interception and reading of your data.
* Integrity: Guarantees the data isn't altered in transit.
* Authenticity: Verifies data source identity.

---

### ProtonVPN Encryption Technologies

ProtonVPN uses multiple robust, modern VPN protocols with strong encryption standards:

| Protocol        | Encryption Method                                                             | Use Case                                                  |
| :-------------- | :---------------------------------------------------------------------------- | :-------------------------------------------------------- |
| **OpenVPN**     | AES-256-GCM encryption, 4096-bit RSA key exchange, HMAC SHA-384 for integrity | Highly secure and flexible; suitable for most devices     |
| **WireGuard®**  | ChaCha20 encryption with Poly1305 for authentication                          | Fast, lightweight, and secure modern protocol             |
| **IKEv2/IPSec** | AES-256 encryption with SHA-384 and 4096-bit RSA key exchange                 | Reliable for mobile devices; handles network changes well |

> ✅ **ProtonVPN by default uses AES-256 encryption**, a standard used by governments, militaries, and security experts worldwide.

---

### ProtonVPN Privacy and Security Features

ProtonVPN offers additional built-in privacy protections beyond encryption:

| Feature                  | Purpose                                                                |
| :----------------------- | :--------------------------------------------------------------------- |
| **NetShield Ad-blocker** | Blocks malware, trackers, and intrusive ads before they load           |
| **Kill Switch**          | Instantly blocks internet traffic if VPN connection drops unexpectedly |
| **VPN Accelerator**      | Enhances VPN speeds without compromising security                      |
| **Moderate NAT**         | Improves connectivity in restrictive networks                          |
| **Custom DNS**           | Prevents DNS leaks by using secure, private DNS servers                |
| **IPv6 Leak Protection** | Ensures IPv6 traffic doesn’t bypass the VPN tunnel                     |
| **Auto-Connect**         | Automatically connects to a secure server on system startup            |

---

### VPN Security Mechanisms Summary

| Security Concern              | How ProtonVPN Protects                                |
| :---------------------------- | :---------------------------------------------------- |
| **Data Interception**         | Encrypted VPN tunnel using AES-256 or ChaCha20        |
| **IP Address Exposure**       | Masks your public IP with a VPN server’s IP           |
| **Man-in-the-Middle Attacks** | Strong authentication protocols and secure encryption |
| **DNS Leaks**                 | Uses ProtonVPN’s secure DNS resolvers                 |
| **Connection Drops**          | Kill Switch feature                                   |

---

### Conclusion

ProtonVPN combines world-class encryption standards with privacy-enhancing features to create a highly secure and private online experience. Its use of OpenVPN, WireGuard®, and IKEv2 protocols ensures flexibility and safety across various devices and networks.

---

### References

* [ProtonVPN official website](https://protonvpn.com)
* [OpenVPN Security Overview](https://openvpn.net)
* [WireGuard Documentation](https://www.wireguard.com/protocol/)

---

