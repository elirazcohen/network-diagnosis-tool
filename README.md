# ⚡ Run-NetworkDiagnosis 


A PowerShell-based network troubleshooting and diagnostics tool built to automate common connectivity checks used in IT support and system administration workflows.## 🔍 Features- DNS resolution testing- Ping and latency diagnostics- Router connectivity validation- Common port scanning- Structured console output- Automatic log generation- Error handling and warnings---## 🌐 Diagnostics Performed### DNS ResolutionChecks whether targets can successfully resolve through DNS.### Connectivity TestingMeasures latency and verifies host availability using ping requests.### Port ScanningTests common router ports including:- **80**  HTTP- **443** HTTPS- **22** SSH---## 🖥 Example Usage```powershellRun-NetworkDiagnosis

or

.\network diagnosis tool.ps1

📄 Example Output
=== DNS CHECK ===google.com DNS OKyoutube.com DNS OK=== PING CHECK ===google.com average ping: 18 ms=== PORT CHECK ===Router port 443 OPENRouter port 22 CLOSED

📁 Log File
The script automatically generates:
Network-Diagnosis_logs.txt
Logs may include:


DNS failures


High latency warnings


Closed ports


Connectivity recommendations



🛠 Skills Demonstrated


PowerShell scripting


Network troubleshooting


TCP connectivity testing


Error handling


Logging automation


Sysadmin workflow automation



🚀 Future Improvements


CSV / JSON export


Parallel diagnostics


GUI version


Continuous monitoring mode


Automatic gateway discovery


Multi-device support



👨‍💻 Purpose
Created as a self-taught networking and system administration project focused on automating real-world troubleshooting tasks using PowerShell.
