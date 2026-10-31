# Object-Oriented ATM Simulator

A console-based ATM simulation application built using Python to demonstrate fundamental Object-Oriented Programming (OOP) concepts, such as class construction, method handling, encapsulating state variables (`self.pin`, `self.balance`), and clean variable scope management.

## Features
* **Secure PIN Setup:** Prompt-driven initialization to securely establish a new user PIN.
* **Cash Deposits:** Instantly adds validated numerical funds directly to the tracking balance.
* **Cash Withdrawals:** Securely processes cash deductions with operational checking against insufficient funds.
* **Real-time Balance Tracking:** Simple verification tool to query and output your account status securely.
* **Persistent Application Loop:** Operates continuously using internal control-flow routing to return users back to the dashboard panel automatically after transactions.

## Setup & Running the Code

### Pre-requisites
* Make sure Python (v3.x or above) is installed on your operating system.

### Execution Steps
1. Clone or download the repository to your local directory machine.
2. Launch your command-line interface terminal inside the target directory.
3. Run the application script execution command:
   ```bash
   python atm.py
   ```

## Key Code Highlights
* **Type Conversion Safeguards:** Explicitly processes functional mathematical user inputs through casting transformations (`int(input())`) to guarantee stable numerical evaluations inside transaction pipelines.
* **Integrated Variable Structure:** Avoids state errors by consolidating memory tracking fields entirely into shared structural class elements.
