# 🌐 Advanced Network Dashboard

> Real-time browser-based network and system info dashboard  
> Built with **HTML**, **Bootstrap 5**, **Chart.js**, and **JavaScript**

---

## 🚀 Live Demo

🟢 [View Live Dashboard (via GitHub Pages / Codepen / Netlify)](https://your-demo-link.com)

---

## 📸 Screenshot

<img src="https://your-screenshot-link.com/dashboard.png" alt="Dashboard Preview" width="100%">

---

## 📋 Features

<ul>
  <li>📡 Browser Network Info via Network Information API</li>
  <li>💻 System Info (CPU cores, memory, user agent)</li>
  <li>📊 Simulated Download/Upload speeds + Ping/Jitter</li>
  <li>📈 Real-time Charts (Chart.js)</li>
  <li>⏱️ File Download Time Estimations</li>
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

- Uses `navigator.connection` to get:
  - Effective connection type
  - Downlink (Mbps)
  - Round-trip time (RTT)
  - Data-saving preferences
- Pulls CPU and memory info via `navigator.hardwareConcurrency` and `navigator.deviceMemory`
- Simulates fluctuating speeds every second
- Charts are live-updated with Chart.js
- Download time estimates are based on simulated speeds (1MB - 1GB)

</details>

---

## 📦 Usage 🚀 Live Demo

🔗 [Click here to open the dashboard](https://yourusername.github.io/network-dashboard/)

