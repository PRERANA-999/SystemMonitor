# 🧠 System Monitoring Tool

A real-time, Python-based system monitoring dashboard that tracks **CPU**, **Memory**, **Disk**, and **Network** usage. The tool uses `psutil` for fetching system metrics and `matplotlib` for plotting a live usage graph — perfect for learning system internals and showcasing on resumes.

---

## 📊 Features

- ✅ Real-time resource monitoring (CPU, RAM, Disk, Network)
- ✅ Visualized graph using `matplotlib`
- ✅ Logs usage spikes and updates every second
- ✅ Lightweight, easy to run on Windows or Linux
- ✅ Fully customizable thresholds and intervals

---

## 🛠️ Tech Stack

| Component     | Usage                     |
|---------------|---------------------------|
| Python 3.x     | Main programming language |
| `psutil`       | System metrics            |
| `matplotlib`   | Real-time plotting        |
| `prettytable`  | Optional: Terminal table  |

---

## 🚀 Setup & Run Instructions

### 📦 Install dependencies (via Anaconda or terminal):

```bash
pip install psutil matplotlib prettytable
