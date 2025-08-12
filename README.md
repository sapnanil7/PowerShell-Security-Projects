# PowerShell-Security-Projects

A curated ladder of **10 security-focused PowerShell projects** from beginner → advanced. Built to learn by doing and to prepare for **upper‑mid PowerShell interview** questions.

## Projects

| # | Project | Focus | Status |
|---|--------|-------|--------|
| 01 | [EventLog Threat Detector](01---EventLog-Threat-Detector/README.md) | Get-WinEvent, parsing, alerting | 🚧
| 02 | TBD | | ⏳
| 03 | TBD | | ⏳
| 04 | TBD | | ⏳
| 05 | TBD | | ⏳
| 06 | TBD | | ⏳
| 07 | TBD | | ⏳
| 08 | TBD | | ⏳
| 09 | TBD | | ⏳
| 10 | TBD | | ⏳

## Prerequisites
- Windows PowerShell 5.1 **or** PowerShell 7+
- Execution policy suitable for running local scripts (`Set-ExecutionPolicy -Scope CurrentUser RemoteSigned`)
- (Optional) Access to Security event logs and admin privileges for certain scripts

## Linting
All scripts are checked with **PSScriptAnalyzer** via GitHub Actions. Run locally:
```powershell
Install-Module PSScriptAnalyzer -Scope CurrentUser
Invoke-ScriptAnalyzer -Path . -Settings .\PSScriptAnalyzerSettings.psd1 -Recurse
