# CartFlow QA Suite — Manual Testing Project

**Tester:** Purva Rawale
**Project Duration:** April 2026 – May 2026
**Type:** Manual Testing (Frontend)
**Application:** Open-source e-commerce web application
**Test Environment:** Windows 10 | Chrome | Firefox



## What this project is about

This is a manual testing project I did on a frontend e-commerce application as part of building my QA portfolio. The goal was to test all the major user-facing features — from registering an account to completing a checkout — and document everything the way it would be done in a real testing project.

I created all the documents myself: FRS, Test Plan, Test Scenarios, Test Cases, RTM, Bug Report, and a final Test Summary Report.



## Objectives

- Check whether all main features work correctly for the end user
- Find and document bugs with proper steps to reproduce
- Write test cases covering both expected and unexpected user behaviour
- Make sure requirements are traced to test coverage using an RTM
- Practice the full manual testing lifecycle from planning to reporting



## Modules tested

| Module | Test Scenarios | Test Cases | Bugs Found |
|---|---|---|---|
| Register Account | TS_001 | 24 | 4 |
| Login | TS_002 | 23 | 7 |
| Logout | TS_003 | 11 | 1 |
| Forgot Password | TS_004 | 25 | 1 |
| Product Search | TS_005 | 22 | 5 |
| Product Compare | TS_006 | 24 | 1 |
| Product Display | TS_007 | 37 | 1 |
| Add to Cart | TS_008 | 9 | 1 |
| Wish List | TS_009 | 21 | — |
| Shopping Cart | TS_010 | 33 | — |
| Home Page | TS_011 | 10 | — |
| Checkout | TS_012 | 20 | — |
| My Account | TS_013 | 9 | — |
| Change Password | TS_015 | 13 | — |
| Newsletter | TS_026 | 13 | — |
| Contact Us | TS_027 | 13 | — |
| Currencies | TS_031 | 3 | — |

**Total:** 31 scenarios | 516 test cases planned | 256 executed | 20 bugs logged



## Documents in this repository

| # | Document | Folder | Description |
|---|---|---|---|
| 1 | FRS | /docs | Functional Requirements — what the app is supposed to do |
| 2 | Test Plan | /docs | Scope, approach, schedule, tools, roles |
| 3 | Test Scenarios | /test-artifacts | 31 high-level scenarios covering all modules |
| 4 | Test Cases | /test-artifacts | Detailed step-by-step test cases with test data |
| 5 | Test Execution | /test-artifacts | Test cases with actual results filled in |
| 6 | RTM | /test-artifacts | Requirement traceability — maps requirements to test coverage |
| 7 | Bug Report | /defects | 20 bugs with steps, severity, priority, expected vs actual |
| 8 | Test Summary Report | /reports | Final summary with pass/fail numbers and observations |



## Types of testing done

- **Functional Testing** — checked each feature against what the FRS says it should do
- **Negative Testing** — tested with invalid data, empty fields, wrong formats
- **UI Testing** — checked field labels, error messages, placeholders, breadcrumbs
- **Smoke Testing** — quick check that core flows work before going into detailed testing
- **Regression Testing** — re-tested impacted areas after bug fixes
- **Cross-browser Testing** — Chrome and Firefox on Windows 10



## Tools used

- Microsoft Excel (test cases, test scenarios, RTM, bug report)
- Browser DevTools (Chrome and Firefox)
- GitHub (version control and portfolio)



## Key bugs found

A few bugs worth highlighting from this project:

1. **CF_BUG_9** — User can still log in with their old password after changing it (Critical)
2. **CF_BUG_8** — Password text is visible in the browser page source (Major)
3. **CF_BUG_20** — Clicking "Add to Cart" from wish list doesn't actually add to cart (Critical)
4. **CF_BUG_5** — Browser back button logs the user out unexpectedly (Critical)

Full details with steps to reproduce are in /defects/Bug_Report_CartFlow.xlsx



## How to navigate this repository

1. Start with the **README** (you're here)
2. Read the **FRS** to understand what was being tested
3. Check the **Test Plan** for how testing was approached
4. Browse **Test Scenarios** for a high-level view of coverage
5. Open **Test Cases** for detailed step-by-step cases
6. See **RTM** to check requirement traceability
7. Open **Bug Report** to see all 20 defects
8. Read **Test Summary Report** for the final results

____

## About me

**Purva Rawale**
Fresher — Manual QA Tester
Looking for QA / Software Testing opportunities

This project was done independently to build hands-on QA skills and create a portfolio that shows real testing work, not just theory.

📧 purva.rawale09@gmail.com


