# ⚡ Run-NetworkDiagnosis

PowerShell network troubleshooting and connectivity diagnostic tool built to automate common IT and sysadmin checks.

---

## 🔍 Features

- DNS resolution testing
- Ping & latency diagnostics
- Router connectivity validation
- Common port scanning
- Structured console output
- Automatic logging
- Error handling

---

## 🌐 Diagnostics Included

| Check | Purpose |
|---|---|
| DNS Resolution | Verifies domains resolve correctly |
| Ping Testing | Measures latency and connectivity |
| Port Checks | Tests common service ports |
| Logging | Saves troubleshooting results |

---

## 🔌 Ports Tested

- **80** → HTTP
- **443** → HTTPS
- **22** → SSH

---

## 🖥 Usage

```powershell
Run-NetworkDiagnosis
```

or

```powershell
.\network diagnosis tool.ps1
```

---

## 📄 Example Output

```text
=== DNS CHECK ===
google.com DNS OK
youtube.com DNS OK

=== PING CHECK ===
google.com average ping: 18 ms

=== PORT CHECK ===
Router port 443 OPEN
Router port 22 CLOSED
```

---

## 📁 Log File

```text
Network-Diagnosis_logs.txt
```

Stores:
- DNS failures
- High latency warnings
- Closed ports
- Connectivity issues

---

## 🛠 Skills Demonstrated

- PowerShell scripting
- Network troubleshooting
- TCP connectivity testing
- Logging automation
- Error handling
- Sysadmin workflow automation

---

## 🚀 Future Improvements

- CSV / JSON export
- Parallel diagnostics
- GUI version
- Continuous monitoring
- Automatic gateway discovery

---

## 👨‍💻 Purpose

Created as a self-taught networking and system administration project focused on automating real-world troubleshooting tasks using PowerShell.
