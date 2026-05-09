Run-NetworkDiagnosis

A PowerShell network troubleshooting tool that automates common connectivity checks for routers and websites.

Built to practice real-world:

PowerShell scripting
Network diagnostics
Connectivity troubleshooting
Logging
Error handling
Sysadmin automation
Features
DNS resolution testing
Ping latency checks
Router connectivity diagnostics
Port availability testing
Structured warning/error messages
Automatic log generation
Troubleshooting recommendations
What The Script Checks
DNS Resolution

Verifies whether targets can successfully resolve through DNS.

Targets include:

Local router
Google
YouTube
Discord
Ping Diagnostics

Measures average latency using Test-Connection.

Detects:

High latency
Unreachable hosts
Possible network instability
Router Port Testing

Checks common ports on the router using Test-NetConnection.

Ports tested:

80 → HTTP
443 → HTTPS
22 → SSH
Example Usage
Run-NetworkDiagnosis

Or:

.\network diagnosis tool.ps1
Example Output
=== DNS CHECK ===
google.com DNS OK
youtube.com DNS OK

=== PING CHECK ===
google.com average ping: 18 ms
youtube.com average ping: 24 ms

=== PORT CHECK (ROUTER ONLY) ===
Router port 80 OPEN
Router port 22 CLOSED
Logging

The script automatically creates a log file:

Network-Diagnosis_logs.txt

Logged events include:

DNS failures
Slow connections
Closed ports
Troubleshooting recommendations
Skills Demonstrated
PowerShell functions
Loops and conditionals
Error handling with try/catch
Network troubleshooting logic
TCP connectivity testing
Latency calculations
File logging
Structured console output
Future Improvements

Possible future upgrades:

Export results to CSV/JSON
Parallel diagnostics
Better router detection
Automatic gateway discovery
GUI version
Continuous monitoring mode
Multi-device scanning
Purpose

This project was created as a hands-on networking and system administration practice tool to automate common troubleshooting tasks performed in IT support and sysadmin environments.

Author

Created independently as a self-taught PowerShell and networking project.
