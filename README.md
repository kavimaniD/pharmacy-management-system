# Pharmacy Management System

Command-line pharmacy system: medicine inventory, customers, billing, sale
cancellation, stock/expiry alerts and sales reports. Python 3 + SQLite
(standard library only).

## Run
    python main.py

## Test
    python -m unittest -v

## Business rules
- GST 12% on the amount after discount; 10% discount when subtotal is Rs. 1000 or more.
- Quantity 1-100 per medicine per bill; cannot exceed stock; expired medicines cannot be sold.
- Prescription medicines need a doctor name on the bill.
- Cancelling a Completed sale restores stock; a medicine with sales records cannot be removed.
- Low-stock alert at 10 units or fewer; expiry alert within 30 days.

(Add: problem statement, sample inputs/outputs, team details, limitations, future work.)
