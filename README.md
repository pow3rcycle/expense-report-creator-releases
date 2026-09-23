<p align="center"><img src="media/logo.svg" width="112" alt="Expense Report Creator logo"></p>

# Expense Report Creator - Releases

Installer downloads and the auto-update feed for **Expense Report Creator**, an offline Windows desktop app that turns your receipts into a finished weekly expense report.

> **For Technic SFT (Surface Finishing Technologies) employees only.** The app ships with the SFT weekly expense form and follows the SFT meal and incidentals policy. It is not a general-purpose expense tool, and it is not an official HR or accounting system. Your manager and accounting still review and approve every report.

## What it does

You drop in your receipts. The app gives you back the two files you normally build by hand:

| Output | What you get |
|---|---|
| **Weekly expense form (`.xls`)** | The genuine SFT weekly form, filled in: week ending, your name, daily amounts per category, totals, advances and net due. It opens in Excel with no repair prompt and prints on one page. |
| **Receipt packet (`.docx`)** | A Word document with your receipts laid out two per row, each captioned (for example `Lunch 09/02/26` or `Flight Receipt`). |

## How it works

Each report walks you through four steps:

1. **Receipts** - drop in photos, screenshots or PDFs. They are read automatically on your PC (PaddleOCR, offline).
2. **Expenses** - check each expense beside its receipt. Values read from the receipt are marked "From receipt"; your edits always win. Meals follow the SFT policy (allowance, or the actual amount when a receipt is higher - never both).
3. **Trip and incidentals** - trip details, advances, and the $5/day incidentals for the in-between days of a trip (auto, with a per-day override).
4. **Review and export** - Total, Less advances and **Net due**, the form as it will print, then one click exports the `.xls` form and `.docx` packet.

Everything autosaves, and unsaved work is offered back after a crash.

## Install

1. Download **`ExpenseReportCreator-<version>-Setup.exe`** from the [latest release](../../releases/latest). It's the only file you need.
2. Run it. If Windows shows **"Windows protected your PC"**, click **More info → Run anyway**. The app isn't code-signed yet, and every release lists SHA-256 checksums in `SHA256SUMS.txt`.
3. On first launch, enter your name and you're ready. The SFT form and the OCR data are already included, so there's nothing else to download.

No admin rights are needed. The app installs for your Windows user only and updates itself: when a new version is out, you'll see a small "restart to update" prompt.

Full walkthrough: [USER-GUIDE.md](USER-GUIDE.md).

## Privacy

- **Fully offline.** Receipts, reports and exports stay on your PC. There's no account, no cloud, no AI service and no telemetry.
- The only network call is the update check against this repository. If you're offline, everything still works.
- Your data lives in `%APPDATA%\expense-report-creator\` and is kept when you uninstall.

No source code and no user data are stored here.
