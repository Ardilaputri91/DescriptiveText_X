MY FAMILY – Descriptive Text Independent Task

IMPORTANT FIX
This version no longer needs a Spreadsheet ID. The Apps Script project should be opened from the target Google Spreadsheet using Extensions > Apps Script. The script uses SpreadsheetApp.getActiveSpreadsheet().

SETUP
1. Create/open the Google Spreadsheet that will store student results.
2. In that spreadsheet choose Extensions > Apps Script. This is important because it binds the script to that spreadsheet.
3. Replace Code.gs with the supplied Code.gs.
4. Create/replace index.html with the supplied index.html.
5. Save.
6. Select setupWorkbook and Run once.
7. Authorize the script.
8. Return to the Apps Script editor and run setupWorkbook again if necessary. You should get “Workbook setup complete”.
9. The spreadsheet will contain SUBMISSIONS, ANSWERS, and SETTINGS.
10. Deploy > New deployment > Web app. Execute as: Me. Who has access: Anyone with the link.
11. Send the Web App URL to students.

STUDENT FLOW
Students type their own Full Name and Class. There is no class dropdown. They get 100 minutes, complete Parts A–E, and submit once.

SCORING
Auto score is 90 points: A=30, B=20, C=20, D=20. Teacher review can add up to 10 points for A10 + Reflection. Final Score is calculated in SUBMISSIONS after teacher_score_10 is entered.

ANTI-COPY / ENGLISH-ONLY
The app disables common copy/select/context-menu shortcuts during the task and marks the document as English/notranslate. These are deterrents, not absolute guarantees against all browser/device methods.
