# Apideck Sage 50 US agent: Windows releases

Release files for the Apideck Sage 50 US agent. No source code lives here.

## Install

On the Windows PC where Sage 50 US runs, open **PowerShell as Administrator** and paste:

```powershell
irm https://github.com/apideck-io/sage50-us-win-exe/releases/latest/download/install.ps1 | iex
```

It asks for your pairing code (from Apideck) and your Sage 50 company. Then open Sage 50 on that company and choose **Always Allow** when Sage asks about "Apideck Sage 50 Agent".

The agent updates itself. Every release is signed by Apideck, and the agent refuses files without that signature.
