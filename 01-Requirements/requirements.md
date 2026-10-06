# Requirements - BankingApp

## 1. Project Overview

BankingApp is a simulated banking application created for educational and QA portfolio purposes.

The application allows customers to securely access their accounts, consult balances and transactions, manage beneficiaries and perform bank transfers.

---

# 2. Functional Requirements

## REQ-LOGIN-001 - User Login

### Description

The system must allow registered users to access the application using valid credentials.

### Acceptance Criteria

- CA-01: The user must enter a registered username.
- CA-02: The user must enter a password.
- CA-03: The system must validate the provided credentials.
- CA-04: Valid credentials must allow access to the Dashboard.
- CA-05: Invalid credentials must display an appropriate error message.
- CA-06: The password must be displayed as masked characters.

---

## REQ-ACCOUNT-001 - Account Balance

### Description

The system must allow authenticated users to view the available balance of their accounts.

### Acceptance Criteria

- CA-01: The user must be authenticated.
- CA-02: The system must display the accounts associated with the user.
- CA-03: The system must display the available balance for each account.
- CA-04: The displayed balance must correspond to the stored account information.

---

## REQ-TRANSACTION-001 - Transaction History

### Description

The system must allow authenticated users to view the transactions associated with their accounts.

### Acceptance Criteria

- CA-01: The user must be authenticated.
- CA-02: The system must display the transaction history.
- CA-03: Each transaction must display its date, type and amount.
- CA-04: Transactions must be associated with the correct account.
- CA-05: The user must be able to identify recent transactions.

---

## REQ-TRANSFER-001 - Bank Transfer

### Description

The system must allow authenticated users to transfer money from one of their accounts to a registered beneficiary.

### Acceptance Criteria

- CA-01: The user must be authenticated.
- CA-02: A valid source account must be selected.
- CA-03: A registered beneficiary must be selected.
- CA-04: The transfer amount must be greater than zero.
- CA-05: The transfer amount must not exceed the available balance.
- CA-06: The system must request confirmation before processing the transfer.
- CA-07: A successful transfer must generate a transaction record.
- CA-08: The source account balance must be updated after a successful transfer.

---

## REQ-BENEFICIARY-001 - Beneficiary Registration

### Description

The system must allow authenticated users to register a new beneficiary for future transfers.

### Acceptance Criteria

- CA-01: The user must be authenticated.
- CA-02: The beneficiary name must be required.
- CA-03: The beneficiary account number must be required.
- CA-04: The account number must have a valid format.
- CA-05: The system must confirm successful beneficiary registration.
- CA-06: The registered beneficiary must appear in the beneficiary list.

---

## REQ-LOGOUT-001 - User Logout

### Description

The system must allow authenticated users to securely end their session.

### Acceptance Criteria

- CA-01: The user must be authenticated.
- CA-02: Selecting "Logout" must terminate the active session.
- CA-03: After logout, the user must be redirected to the login page.
- CA-04: The user must not be able to access protected pages using the previous session.
