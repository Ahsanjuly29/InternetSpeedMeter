# 🌐 Advanced Network Dashboard

> Real-time browser-based network and system info dashboard  
> Built with **HTML**, **Bootstrap 5**, **Chart.js**, and **JavaScript**

---

## 🚀 Live Demo

🟢 [Click here to open the dashboard](https://ahsanjuly29.github.io/InternetSpeedMeter/)

---

## 📸 Screenshot

<!-- Replace the link below with your actual screenshot image URL -->
<img src="https://ahsanjuly29.github.io/InternetSpeedMeter/ism.png" alt="Dashboard Preview" width="100%">

---

## 📋 Features

<ul>
  <li>📡 Browser Network Info via Network Information API</li>
  <li>💻 System Info (CPU cores, memory, user agent)</li>
  <li>📊 Simulated Download/Upload speeds + Ping/Jitter</li>
  <li>📈 Real-time Charts with Chart.js</li>
  <li>⏱️ Estimated Download Times for Common File Sizes</li>
</ul>

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td>📄 HTML5</td>
    <td>📦 Bootstrap 5.3</td>
  </tr>
  <tr>
    <td>📉 Chart.js</td>
    <td>🧠 JavaScript (ES6+)</td>
  </tr>
  <tr>
    <td>🔁 jQuery 3.7</td>
    <td>🌐 Network Information API</td>
  </tr>
</table>

---

## 🧪 How It Works

<details>
<summary><strong>Click to expand</strong></summary>

- Uses `navigator.connection` (Network Information API) to get:
  - Effective connection type
  - Downlink (Mbps)
  - Round-trip time (RTT)
  - Save Data setting
- Pulls device memory and logical CPU cores using:
  - `navigator.deviceMemory`
  - `navigator.hardwareConcurrency`
- Simulates realistic fluctuating values for:
  - Download speed
  - Upload speed
  - Ping
  - Jitter
- Real-time data visualized using Chart.js line graphs
- Estimated download times are calculated based on simulated speeds (1MB to 1GB)

</details>

---
