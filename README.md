# ATM System 💸

A simple Python ATM project that allows a user to debit and credit money from an account after entering the correct PIN.

## Features

- Create an account with balance, account number, and PIN
- Debit money after PIN verification
- Credit money after PIN verification
- Show updated balance after each transaction
- Cancel the transaction if the PIN is incorrect

## Technologies Used

- Python 3

## Project Structure

```text
ATM_system/
|-- main.py
|-- README.md
```

## How It Works

1. The program creates an account object.
2. The user enters the amount to debit.
3. The program asks for the 4-digit PIN.
4. If the PIN is correct, the amount is debited.
5. The user then enters the amount to credit.
6. The program again asks for the PIN.
7. If the PIN is correct, the amount is credited.

## Default Account Details

- Account Number: `389894125`
- Initial Balance: `125000`
- PIN: `2004`

## How To Run

1. Open a terminal in the project folder.
2. Run:

```bash
python main.py
```

## Example

```text
Enter the amount you want to debit: 1000
Enter the 4 digit PIN code: 2004
Dear Customer Rs.1000 has been debited from account no. 389894125
Remaining balance in your account: Rs.124000
```

## Future Improvements

- Add balance check option
- Add transaction history
- Add menu system
- Add input validation
- Prevent withdrawal when balance is insufficient
- Support multiple accounts

## Author

Made as a basic Python practice project.
- Wriddhiman Dey 🧑‍💻
