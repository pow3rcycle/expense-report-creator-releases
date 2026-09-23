# Expense Report Creator - User Guide

*For Technic SFT employees. Everything runs on your PC, and nothing is uploaded.*

## 1. Install

1. Download `ExpenseReportCreator-<version>-Setup.exe` from the [releases page](https://github.com/pow3rcycle/expense-report-creator-releases/releases/latest).
2. Double-click it. If you see a SmartScreen warning, click **More info → Run anyway**. You don't need admin rights.
3. Choose the install folder if you want to, then click **Install**. The installer adds shortcuts to the desktop and the Start menu.

## 2. First launch

A single welcome screen asks for **your name**. The app writes it on every form as `NAME: <your name>`, and you can change it later in Settings. It also confirms that the **SFT expense form** and **receipt reading (OCR)** are both ready. Click **Get started**.

## 3. Make a report

1. Click **New report** and pick the **week ending (Saturday)**. For travel, add the customer and the purpose.
2. **Add receipts** by dragging files onto the window (JPG, PNG, screenshots or PDF). For an expense with no receipt, add it manually.
3. For each expense, check the **date, category, amount and meal** beside the receipt image. Suggested values are marked. Anything you edit is kept even if the receipt is read again.
4. **Meals:** without a receipt, the allowance is claimed. With a receipt above the allowance, the actual amount is claimed. The two are never added together.
5. **Incidentals ($5/day):** added automatically on the days between your first and last meal day of the trip. Use the per-day tickboxes to override. If a trip spans two report weeks, check the tickboxes by hand.
6. Open **Export preview** to see the form exactly as it will print. Anything that would block the export (a week ending that isn't a Saturday, or a conflict on an Other line) is listed there.
7. Click **Export** to save the `.xls` form and the `.docx` receipt packet, then submit them as usual.

## 4. When HR releases a new form

Go to **Settings → Change company form…** and select the new `.xls`. The app checks the layout before using it. If the layout isn't recognized, it tells you and keeps using the current form. You can always switch back to the bundled SFT form.

## 5. Updates, data and uninstalling

- The app checks for updates when it starts. When one is ready, click **Restart** to apply it.
- Your reports and receipts are stored in `%APPDATA%\expense-report-creator\`. Uninstalling leaves this folder in place.
- To remove the app, go to **Windows Settings → Apps → Expense Report Creator → Uninstall**.

## 6. Questions or problems

Contact Hasan. This app is a helper for filling in the form. It doesn't replace company policy, and the approver's decision is final.
