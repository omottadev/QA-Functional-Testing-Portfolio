# Test Plan - BankingApp

## 1. Document Information

| Field | Information |
|---|---|
| Project | BankingApp |
| Document | Test Plan |
| Testing Type | Functional Testing |
| Tester | Ana Gabriela Ovalle Motta |
| Version | 1.0 |
| Status | In Progress |

---

# 2. Objective

The objective of this test plan is to define the testing approach for BankingApp and verify that the main functionalities operate according to the defined requirements and acceptance criteria.

The testing process will focus on identifying functional defects, validating business rules, verifying data consistency and ensuring that the implemented functionalities meet the expected behavior.

---

# 3. Scope

## 3.1 In Scope

The following functionalities will be tested:

- User login
- Account balance consultation
- Transaction history
- Beneficiary registration
- Bank transfers
- User logout
- Input validation
- Error handling
- Data validation using SQL
- API functionality
- Regression testing

---

## 3.2 Out of Scope

The following areas are outside the scope of this project:

- Performance testing
- Load testing
- Stress testing
- Penetration testing
- Accessibility testing
- Infrastructure testing
- Production environment testing

---

# 4. Testing Types

The project will include the following types of testing:

## Functional Testing

Verify that each functionality behaves according to its requirements and acceptance criteria.

## Positive Testing

Verify that valid inputs produce the expected results.

## Negative Testing

Verify that invalid inputs are rejected appropriately and that the system displays the expected validation or error messages.

## Regression Testing

Verify that previously working functionality continues to work after changes or defect fixes.

## Retesting

Verify that reported defects have been correctly resolved.

## API Testing

Validate API requests, responses, status codes and response data.

## SQL Data Validation

Use SQL queries to verify that application data is stored and updated correctly.

---

# 5. Test Environment

The testing activities will be performed using the following tools:

| Tool | Purpose |
|---|---|
| GitHub | Test documentation and version control |
| Jira | Defect and task management |
| Postman | API testing |
| MySQL | Database validation |
| SQL | Data validation |
| Web Browser | Application testing |
| Excel / Google Sheets | Test case documentation |

---

# 6. Test Data

The following types of test data will be used:

- Valid user credentials
- Invalid user credentials
- Empty fields
- Invalid account numbers
- Valid beneficiary accounts
- Invalid beneficiary accounts
- Positive transfer amounts
- Zero transfer amounts
- Negative transfer amounts
- Transfer amounts greater than available balance
- Valid and invalid API parameters

---

# 7. Entry Criteria

Testing can begin when:

- Requirements have been documented.
- Acceptance criteria have been defined.
- The functionality under test is available.
- Test data is available.
- The test environment is accessible.

---

# 8. Exit Criteria

Testing can be considered complete when:

- All planned test cases have been executed.
- Critical and High severity defects have been resolved or formally accepted.
- Failed test cases have been retested.
- Regression testing has been completed.
- The final test report has been prepared.

---

# 9. Defect Management

Identified defects will be documented with the following information:

- Defect ID
- Title
- Severity
- Priority
- Environment
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Evidence
- Status

Defects will be tracked through their lifecycle:

```text
Open → In Progress → Fixed → Retest → Closed
