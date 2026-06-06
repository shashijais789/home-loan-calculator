# Home Loan Calculator

An interactive home loan EMI calculator with support for:

- **EMI Calculation** — Compute monthly EMI from loan amount, interest rate, and tenure
- **Fixed EMI** — Optionally set a higher fixed EMI to pay off the loan faster
- **Prepayments** — Add lump-sum prepayments on specific dates
- **Rate Changes** — Simulate interest rate changes over the loan lifecycle
- **Amortization Schedule** — Month-wise breakdown showing EMI, principal, interest, prepayments, and balance
- **Currency Selection** — Choose from USD, INR, GBP, EUR, JPY, BRL
- **Persistent Storage** — All values are saved to browser localStorage
- **PDF Export** — Download the full schedule as a PDF

## Usage

Open `index.html` in any modern browser. Fill in the loan details, add events (prepayments/rate changes) if any, and click **Calculate**. The amortization table and summary cards update automatically.

All values are saved automatically — close and reopen the page to pick up where you left off.

## Tech Stack

Pure HTML + CSS + JavaScript. No build tools or frameworks required.
