# Expense Report Creator: User Guide

*For Technic SFT employees. Windows 10 and 11. Everything runs on your PC and nothing is uploaded.*

## 1. Install

1. Download `ExpenseReportCreator-<version>-Setup.exe` from the [website](https://pow3rcycle.github.io/expense-report-creator-releases/) or the [latest release](https://github.com/pow3rcycle/expense-report-creator-releases/releases/latest).
2. Double-click it. If Windows shows **"Windows protected your PC"**, click **More info**, then **Run anyway**. The app isn't code-signed yet; each release lists SHA-256 checksums in `SHA256SUMS.txt`.
3. It installs for your Windows user only (no admin rights) and adds desktop and Start menu shortcuts.

## 2. First launch

The welcome screen asks for **your name**. It goes on every form as `NAME: <your name>`, and you can change it later in **Settings**. The SFT form and the receipt reader are built in, so there is nothing else to set up.

## 3. Start a report

A report is **one work order and one week** (HR closes out weekly). On **Reports**, click **New report** and fill in, in order:

- **Work order** (required)
- **Week ending**: any day you pick snaps to its Saturday
- **Trip folder** (required): the folder where you keep this trip's files. The app saves into it and never creates folders for you.
- **Customer** and **Purpose** (optional). They go on the form's trip line with the work order.

If receipts are already in the trip folder, the app offers to add them.

## 4. The three steps

1. **Receipts and trip.** Drag in photos, screenshots or PDFs, click **Choose files**, or paste a screenshot with **Ctrl+V**. Each receipt is read on this PC. Answer the trip questions (did you travel, which days). Flight, hotel and rental car receipts fill in the trip days for you; any change you make wins.
2. **Check.** Go through each expense beside its receipt: amount, day, and what it was. Your edits are never overwritten. Use **Crop** to straighten a photo.
   - **Meals** follow the SFT policy: the allowance ($16 breakfast, $19 lunch, $28 dinner), or the receipt when it is higher, never both. The meal grid suggests allowance meals for your trip days; nothing is added until you say so.
   - **Incidentals:** $5.00 for each full day away.
   - **Mileage:** set your rate once in **Settings > Mileage**, then type the miles driven on a mileage expense.
   - Delta Sky Club receipts count as **Airfare / baggage**, not meals.
3. **Save.** Check the form as it will print and the receipt document, then click **Save the form and receipt document**. Two files land in your trip folder:
   - `Expense form WO <n> week ending <YYYY-MM-DD>.xls`
   - `Receipts WO <n> week ending <YYYY-MM-DD>.docx`

Warnings ("Worth a look") never block saving. Everything saves as you go.

## 5. Handy extras

- **Continue this trip into next week** (from a report's menu or after saving) starts next week's report for the same work order.
- **Folders** lists what's in your expense folder (choose it in **Settings > Your expense folder**): past forms with their totals, receipt packets and loose receipts, all searchable. The app only reads that folder.
- **Text size** (**A-** / **A+** at the top right) and **Light / Dark** (in the left rail).

## 6. When HR sends a new form

Go to **Settings > Company form** and choose the new `.xls`. The app checks the layout before using it. If it isn't recognised, it says so and keeps the current form. You can always go back to the built-in SFT form.

## 7. Updates, your data and uninstalling

- The app checks this repository for updates when it starts. When one is ready, restart to apply it.
- Your reports are stored in `%APPDATA%\Expense Report Creator\`. Uninstalling leaves this folder in place.
- To remove the app: **Windows Settings > Apps > Installed apps > Expense Report Creator > Uninstall**.

## 8. Questions or problems

Contact Hasan. The app fills in the form you already hand in. It doesn't replace company policy, and your approver's decision is final.
