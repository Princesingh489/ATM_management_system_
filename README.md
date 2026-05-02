# ATM Simulation

A desktop ATM simulation built with Python. Uses Tkinter for the UI and SQLite to persist account data and transaction history across sessions.

## What it does

- Login with an account number and PIN
- Register new accounts from the login screen
- Check balance, deposit, withdraw
- Transfer funds to other accounts
- Change your PIN
- View last 15 transactions
- Full input validation + error messages

---
## Project structure

```
├── atm.py          # main app
├── create_db.py    # db setup + sample user
├── atm.db          # generated after running create_db.py
```

---

## Getting started

**1. Initialize the database**
```bash
python create_db.py
```

**2. Run the app**
```bash
python atm.py
```

No external dependencies. Just Python 3.

---

## Test account

```
Account Number : 123456
PIN            : 1234
Balance        : ₹10,000
```

Or click **Create New Account** on the login screen to register your own.

---

## Stack

- Python 3
- Tkinter
- SQLite3
