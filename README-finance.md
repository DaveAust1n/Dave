# MetroDEVOPS Finance

A lightweight finance dashboard for MetroDEVOPS, built as a standalone HTML/CSS/JavaScript app.

## Features
- Tracks cash received separately from total contracted project value.
- Calculates outstanding balances from project records and linked income transactions.
- Includes income/expense ledger, monthly cash-flow chart, reports, and CSV export.
- Saves data in the current browser using localStorage.
- Responsive layout and Nigerian naira formatting.

## Run
Open `index.html` in a browser or deploy this branch as a static site.

## Important privacy note
This first version stores records only in the browser where it is used. It has no login or cloud database yet. Do not treat it as a secure multi-device financial system until authentication and server-side storage are implemented.

## Initial sample records
- Mobzenox: ₦90,000 project, ₦45,000 deposit, ₦45,000 outstanding.
- Gabs Furniture & Interiors: ₦80,000 project, ₦40,000 deposit, ₦40,000 outstanding.
