<h1 align="center">
  <br>
  <a><img src="/img/logo.svg" alt="" width="300px;"></a>
  <br>
  <img src="https://img.shields.io/badge/PRs-welcome-blue">
  <img src="https://img.shields.io/github/last-commit/kh4sh3i/THOR-Forensics-Toolkit">
  <img src="https://img.shields.io/github/commit-activity/m/kh4sh3i/THOR-Forensics-Toolkit">
  <a href="https://twitter.com/intent/follow?screen_name=kh4sh3i_"><img src="https://img.shields.io/twitter/follow/kh4sh3i_?style=flat&logo=twitter"></a>
  <a href="https://github.com/kh4sh3i"><img src="https://img.shields.io/github/stars/kh4sh3i?style=flat&logo=github"></a>
</h1>

# 🔍 THOR Forensics Toolkit

This repository contains documentation, automation scripts, and sample outputs related to [THOR Lite](https://www.nextron-systems.com/thor-lite/), the free forensic scanner from Nextron Systems.

> THOR Lite is a free, signature-based incident response scanner using YARA, Sigma, and known IOCs to detect threats and anomalies on Windows, Linux, and macOS systems.

---

## 📦 What’s Included

- 🧰 THOR Lite usage examples
- 🖥️ Windows & Linux scan automation scripts
- 📄 Sample reports (HTML, JSON, CSV)
- ⚙️ Integration with timeline and memory tools
- 📑 IOC feed and YARA/Sigma rule integration

---

## 🚀 Getting Started

1. [Download THOR Lite](https://www.nextron-systems.com/thor-lite/) and request a free license.
2. Extract the zip and copy `license.txt` into your working directory.
3. Run scans using the included scripts below.

---

## ⚡ Example Usage

### ▶️ Windows
```powershell
thor64-lite.exe --htmlfile report.html
thor64-lite.exe --quick --soft --csvfile scan_results.csv
```

### ▶️ Linux
```bash
./thor-linux-lite --htmlfile report.html
```

---

## 🛠 Fast Scan

for scan large file use:

```powershell
thor64-lite.exe --quick --soft --htmlfile report.html
```

<h1 align="center">
  <a><img src="/img/poc.png" alt="" width="100%"></a>
</h1>
---

## 📄 Sample Reports

- Sample HTML Report
- JSON log for SIEM integration
- CSV output for quick triage

---

## 📚 Resources

- [THOR Lite Official Site](https://www.nextron-systems.com/thor-lite/)
- [YARA Rules](https://yara.readthedocs.io/)
- [Sigma Rules](https://github.com/SigmaHQ/sigma)
- [OpenRelik Integration](https://github.com/openrelik)

---

## ✅ Disclaimer

This repository does not contain the THOR Lite binaries or rules. You must obtain them from [Nextron Systems](https://www.nextron-systems.com/thor-lite/) directly.

---

## 📬 Contact

For questions, contact: `kh4sh3i@gmail.com` or open an [Issue](https://github.com/kh4sh3i/thor-lite-forensics/issues)
