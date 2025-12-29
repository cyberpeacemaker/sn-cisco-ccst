Here are the **most important / exam-worthy key points to remember about the IEEE 802.11 (Wi-Fi) series**, organized so they’re easy to memorize and understand.

---

## 1. What IEEE 802.11 is

* **IEEE 802.11** = standard for **Wireless LAN (WLAN / Wi-Fi)**
* Defines:

  * **Physical layer (PHY)** → frequencies, modulation, data rates
  * **MAC layer** → frame format, access method, security basics
* Uses **CSMA/CA** (not CSMA/CD like Ethernet)

---

## 2. Frequency bands (very important)

| Band    | Frequency           | Notes                           |
| ------- | ------------------- | ------------------------------- |
| 2.4 GHz | 802.11b / g / n     | Longer range, more interference |
| 5 GHz   | 802.11a / n / ac    | Faster, shorter range           |
| 6 GHz   | 802.11ax (Wi-Fi 6E) | Very fast, low interference     |

---

## 3. Major 802.11 standards (memorize this)

| Standard | Name         | Band        | Max Speed | Key Feature                |
| -------- | ------------ | ----------- | --------- | -------------------------- |
| 802.11a  | –            | 5 GHz       | 54 Mbps   | Early 5 GHz                |
| 802.11b  | –            | 2.4 GHz     | 11 Mbps   | Long range                 |
| 802.11g  | –            | 2.4 GHz     | 54 Mbps   | Backward with b            |
| 802.11n  | Wi-Fi 4      | 2.4 / 5     | 600 Mbps  | **MIMO**                   |
| 802.11ac | Wi-Fi 5      | 5 GHz       | ~6.9 Gbps | **MU-MIMO**, wide channels |
| 802.11ax | Wi-Fi 6 / 6E | 2.4 / 5 / 6 | ~9.6 Gbps | **OFDMA**, efficiency      |

📌 **Mnemonic**:
**b → g → n → ac → ax = slow → fast → faster → fastest**

---

## 4. Channel width (speed booster)

* 20 MHz (basic)
* 40 MHz (802.11n)
* 80 / 160 MHz (802.11ac/ax)

Wider channels = **higher speed, more interference**

---

## 5. Non-overlapping channels (exam favorite)

### 2.4 GHz:

* **Only 3 non-overlapping channels**:

  ```
  1, 6, 11
  ```

### 5 GHz:

* Many non-overlapping channels (less interference)

---

## 6. MAC method: CSMA/CA

* **Carrier Sense Multiple Access with Collision Avoidance**
* Wi-Fi devices:

  * Listen before transmitting
  * Use **ACKs** instead of collision detection
* No collision detection because wireless can’t transmit & listen at the same time

---

## 7. Wi-Fi security evolution (very important)

| Security   | Status      |
| ---------- | ----------- |
| WEP        | ❌ Broken    |
| WPA        | ⚠️ Legacy   |
| WPA2 (AES) | ✅ Standard  |
| WPA3       | ✅ Strongest |

* **WPA2 uses AES (CCMP)** → important to remember
* Avoid **TKIP** and **WEP**

---

## 8. Wi-Fi devices & components

* **AP (Access Point)** → connects wireless to wired network
* **SSID** → network name
* **BSSID** → MAC address of AP
* **Beacon frames** → AP advertisement
* **Association / Authentication** → client connection steps

---

## 9. Wi-Fi frame types (often overlooked)

1. **Management frames**

   * Beacon, Probe, Auth, Assoc
2. **Control frames**

   * RTS, CTS, ACK
3. **Data frames**

   * Actual user data

---

## 10. Range vs speed tradeoff

* Lower frequency (2.4 GHz) → **longer range, slower**
* Higher frequency (5 / 6 GHz) → **shorter range, faster**

---

## 11. Key terms you should recognize instantly

* **MIMO / MU-MIMO**
* **OFDMA**
* **Roaming**
* **Hidden node problem**
* **RTS / CTS**
* **Throughput vs data rate**

---

## 12. One-line exam summary

> **IEEE 802.11 defines wireless LAN standards using CSMA/CA, operating mainly in 2.4, 5, and 6 GHz bands, with increasing speeds from 802.11b to 802.11ax and modern security via WPA2/WPA3.**

---

If you want, I can:

* Give you a **1-page memorization cheat sheet**
* Explain **hidden node vs exposed node** with diagrams
* Help you **prepare specifically for an exam (CCNA / Network+ / university)**

Just tell me 👍
