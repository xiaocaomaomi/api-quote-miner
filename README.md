# 🐱 API Quote Miner v1.0

**API Quote Miner** is a professional, single-file automated data harvester designed for text-based APIs. It allows you to collect massive datasets while monitoring the estimated size of the source database in real-time.

## 🌟 Key Features

* **Standalone HTML**: A lightweight "Single-file Application" (SFA). Zero dependencies, zero installation—just open in any browser.
* **Multi-key Round-Robin**: Input multiple API endpoints (with different keys) line by line. The tool automatically cycles through them to bypass rate limits and avoid IP bans.
* **High-Efficiency Deduplication**: Built-in real-time hashing using the Set algorithm. Every line exported is guaranteed to be 100% unique.
* **Database Size Estimation**: Uses a statistical collision model to predict the total capacity of the target API's database based on the repetition rate.
* **Auto-Protection**: Features an "Error Circuit Breaker." It automatically stops and saves your data if it detects consecutive API failures.

## 🛠️ How to Use

1.  Download the `index.html` file from this repository.
2.  Open the file using a modern web browser (Chrome, Edge, Firefox, or Safari).
3.  Paste your API URLs into the input box (one per line).
4.  Adjust the fetch frequency (Recommended: ≥ 0.5s per request).
5.  Click **Start Mining**.

## 📖 Pro Tips

* **Data Import**: You can import your existing `.txt` files. The miner will cross-reference them to ensure no duplicates are added during new sessions.
* **Real-time Logs**: Monitor the "Status Bar" and "Console Log" to see the content being fetched and identify any network issues immediately.
* **Manual Export**: Click the Export button anytime to download your collection as a clean, line-separated text file.

## 🌐 Official Help Center

For more tools and detailed documentation, visit our official site:
👉 [grasscatweb.xiaocaomaomi.cn/help](https://grasscatweb.xiaocaomaomi.cn/help)

---
© 2026 **GrassCatWeb**. All Rights Reserved.
