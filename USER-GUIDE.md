# Expense Report Creator - User Guide

*For Technic SFT employees. Everything runs on your PC, and nothing is uploaded.*

## 1. Install

1. Download `ExpenseReportCreator-<version>-Setup.exe` from the [releases page](https://github.com/pow3rcycle/expense-report-creator-releases/releases/latest).
2. Double-click it. If you see a SmartScreen warning, click **More info → Run anyway**. You don't need admin rights.
3. Click **Install**. The app installs for your Windows user and adds desktop and Start-menu shortcuts.

## 2. First launch

A single welcome screen asks for **your name**. The app writes it on every form as `NAME: <your name>`, and you can change it later in **Settings**. It also confirms that the **SFT expense form** and **receipt reading (OCR)** are both ready. Click **Get started**.

## 3. Make a report

The app is organised as a left sidebar (**Reports**, **Settings**, **Help**) and, inside each report, four steps shown as tabs. Each step ends with a **Next** button, so you can simply follow them in order.

1. On **Reports**, click **New report** and pick the **week ending (Saturday)**. The title defaults to "Week ending <date>"; rename it if you like (for example "Customer visit").
2. **1 Receipts** - drag photos, screenshots or PDFs onto the window, or click **Add files**. Receipts are read automatically on this PC (PaddleOCR, fully offline).
3. **2 Expenses** - pick each expense on the left and check it beside the receipt image. Values read from the receipt are marked **From receipt**; anything you type is marked **Edited** and is never overwritten, even if the receipt is read again. Click the receipt image to enlarge it. Changes save automatically ("All changes saved").
   - **Meals:** without a receipt the allowance is claimed; with a receipt above the allowance the actual amount is claimed - never both. The row shows what is claimed, e.g. "Claims $16.00 (allowance)".
4. **3 Trip and incidentals** - trip purpose, customer, advances, and the **$5/day incidentals** list (ticked automatically for the days between your first and last meal day; tick or untick any day to override).
5. **4 Review and export** - see **Total expenses**, **Less advances** and **Net due**, the weekly form exactly as it will print, and any checks. Click **Export form and receipts** to save the `.xls` form and the `.docx` receipt packet, then **Open** or **Show in folder**.

The **Claim total** in the report header updates as you work.

## 4. When HR releases a new form

Go to **Settings -> Company expense form** and click **Change company form...**, then select the new `.xls`. The app checks the layout before using it; if it isn't recognised it tells you and keeps using the current form. You can always switch back to the built-in SFT form.

## 5. Updates, data and uninstalling

- The app checks for updates when it starts. When one is ready, click **Restart** to apply it.
- Your reports and receipts are stored in `%APPDATA%\expense-report-creator\`. Uninstalling leaves this folder in place.
- To remove the app, go to **Windows Settings → Apps → Expense Report Creator → Uninstall**.

## 6. Questions or problems

Contact Hasan. This app is a helper for filling in the form. It doesn't replace company policy, and the approver's decision is final.
