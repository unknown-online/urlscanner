# urlscanner
  installation instructions and setting up a virtual environment (`venv`) for installing dependencies.  

---

### **`README.md`**
```md
# URLSCANNER

api documentation visit:

https://urlscan.io/docs/api/

Get api key:
https://urlscan.io/user/login/
---

## 🚀 Installation Guide

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/unknown-online/urlscanner.git
cd urlscanner```

### 2️⃣ **Create a Virtual Environment**
```bash
python -m venv venv
```
Activate the virtual environment:
- **Linux/macOS**:  
  ```bash
  source venv/bin/activate
  ```
- **Windows**:  
  ```powershell
  venv\Scripts\activate
  ```

### 3️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

---

## ⚙️ Configuration
1. Open `config.yaml` and set your API key :
```yaml
apikey: "your_api_key"

```

---

## ▶️ Running the Script
```bash
python3 urlscanner.py
```

---

## 🛠 Troubleshooting
- If `requests` or `pyyaml` is missing, reinstall:
  ```bash
  pip install requests pyyaml
  ```
- If the script doesn't run, check Python version:
  ```bash
  python --version
  ```

---
