# SauceDemo Manual Testing

Manual testing project on [SauceDemo](https://www.saucedemo.com), a practice e-commerce website. I built this to learn the full testing process, from requirements to defect reporting.

**Tested by:** Vijayalakshmi T

## What I did

- Wrote 10 requirements (assumed, since SauceDemo has no requirement document)
- Prepared a Test Plan
- Wrote 31 test scenarios and 40 test cases (positive, negative, functional and UI)
- Executed the test cases with 6 user types: standard_user, locked_out_user, problem_user, performance_glitch_user, error_user and visual_user
- Logged 19 defects with steps, severity, priority and screenshots
- Built a Requirements Traceability Matrix (RTM) and a Test Summary Report
- Tracked high-severity defects in Jira

## Results

| Item | Result |
|---|---|
| Test cases | 40 |
| Total executions (test cases x users) | 65 |
| Passed | 46 (71%) |
| Failed | 19 (29%) |
| Defects found | 19 (High: 7, Medium: 10, Low: 2) |
| Requirements passed / failed | 5 / 5 |

**Key findings**
- All runs with standard_user passed.
- All 19 failures came from problem_user, error_user and visual_user: wrong product images and prices, broken sorting, Add to cart not working, the last name field not accepting input, and the Finish button not working.
- Conclusion: the core flow works for the standard user, but the application is not ready for release because several users cannot complete a purchase.

## Scope

- **In scope:** Login, Inventory, Sorting, Cart, Checkout, Logout
- **Out of scope:** Performance, security and automation testing
- **Cross-browser:** Key test cases were also checked on Edge with the same results (no separate results recorded)

## Files

| File | Content |
|---|---|
| `01_Requirements.xlsx` | 10 requirements |
| `02_Test_Plan.docx` | Test plan |
| `03_Test_Scenarios.xlsx` | 31 test scenarios |
| `04_Test_Cases.xlsx` | 40 test cases with execution results, including runs with other user types |
| `05_Bug_Report.xlsx` | 19 defects with steps, severity, priority and Jira IDs |
| `06_RTM.xlsx` | Requirements traceability matrix |
| `07_Test_Summary_Report.xlsx` | Test summary report |
| `Screenshots/` | Defect screenshots (BUG_001.png and so on) |

## Tools

Microsoft Excel, Jira, Google Chrome, Microsoft Edge, GitHub

## Process followed

Requirement analysis, test planning, scenario and test case design, test execution, defect reporting and test closure.
