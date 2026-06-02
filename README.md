# CartFlow QA Suite — Manual Testing Project

**Tester:** Purva Rawale
**Project Duration:** April 2026 – May 2026
**Type:** Manual Testing (Frontend)
**Application:** Open-source e-commerce web application
**Test Environment:** Windows 10 | Chrome (latest) | Firefox (latest)

---

## What this project is about

This is a manual testing project I did on a frontend e-commerce application as part of building my QA portfolio. The goal was to test all the major user-facing features — from registering an account to completing a checkout — and document everything the way it would be done in a real testing project.

I created all the documents myself: FRS, Test Plan, Test Scenarios, Test Cases, RTM, Bug Report, and a final Test Summary Report. The project covers the full Software Testing Life Cycle (STLC) — from requirement analysis to test closure.

---

## Objectives

- Check whether all main features work correctly for the end user
- Find and document bugs with proper steps to reproduce
- Write test cases covering both expected and unexpected user behaviour
- Make sure requirements are traced to test coverage using an RTM
- Practice the full manual testing lifecycle from planning to reporting

---

## Modules Tested

| Module | Scenario ID | Test Cases | Bugs Found |
|---|---|---|---|
| Register Account | TS_001 | 24 | 4 |
| Login | TS_002 | 23 | 7 |
| Logout | TS_003 | 11 | 1 |
| Forgot Password | TS_004 | 25 | 1 |
| Product Search | TS_005 | 22 | 5 |
| Product Compare | TS_006 | 24 | 1 |
| Product Display Page | TS_007 | 37 | 1 |
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

---

## Documents in This Repository

| # | Document | Location | What it contains |
|---|---|---|---|
| 1 | FRS | /docs | Functional requirements — what each feature is supposed to do |
| 2 | Test Plan | /docs | Scope, approach, schedule, tools, roles, entry/exit criteria |
| 3 | Test Scenarios | /test-artifacts | 31 high-level scenarios covering all modules |
| 4 | Test Cases | /test-artifacts | Detailed step-by-step test cases with test data |
| 5 | Test Execution | /test-artifacts | Test cases with actual results filled in after execution |
| 6 | RTM | /test-artifacts | Requirement traceability — maps each requirement to test cases |
| 7 | Bug Report | /defects | 20 bugs with full details: steps, severity, priority, expected vs actual |
| 8 | Test Summary Report | /reports | Final results with pass/fail numbers and key observations |

---

## Types of Testing Performed

- **Functional Testing** — checked each feature against what the FRS says it should do
- **Negative Testing** — tested with invalid data, empty fields, boundary values, wrong formats
- **UI Testing** — checked field labels, placeholders, error messages, page headings, breadcrumbs
- **Smoke Testing** — quick sanity check that core flows work before going into detailed testing
- **Regression Testing** — re-tested impacted areas after finding session-related and login bugs
- **Cross-browser Testing** — Chrome and Firefox on Windows 10

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Test scenarios, test cases, execution results, RTM, bug report |
| Chrome DevTools | Inspecting page source, checking network behaviour during testing |
| Firefox DevTools | Cross-browser verification |
| GitHub | Version control and portfolio hosting |

---

## Key Bugs Found

Here are four of the most important bugs found during testing:

| Bug ID | Module | Summary | Severity |
|---|---|---|---|
| CF_BUG_9 | Login | User can still log in with old password after changing it | Critical |
| CF_BUG_20 | Wish List | Add to Cart from wish list redirects to product page instead of adding | Critical |
| CF_BUG_5 | Login | Browser back button logs the user out unexpectedly | Critical |
| CF_BUG_8 | Login | Password is visible in the browser's page source | Major |

Full details with steps to reproduce are in `/defects/07_Bug_Report_CartFlow.xlsx`

---

## Execution Summary

| Status | Count | Percentage |
|---|---|---|
| Passed | 194 | 75.8% |
| Failed | 20 | 7.8% |
| Blocked | 42 | 16.4% |
| **Total Executed** | **256** | **100%** |

> Two modules had blocked test cases — Forgot Password (email system not functional on demo) and Product Compare (navigation bug CF_BUG_17 blocked the comparison page). Both are documented clearly in the Test Summary Report.

---

## How to Navigate This Repository

1. Start with this **README** for a project overview
2. Open `/docs/FRS_CartFlow.docx` to understand what was being tested
3. Read `/docs/Test_Plan_CartFlow.docx` for how testing was planned
4. Browse `/test-artifacts/Test_Scenarios_CartFlow.xlsx` for a module-wise view
5. Open `/test-artifacts/Test_Cases_CartFlow.xlsx` for detailed test steps
6. Check `/test-artifacts/RTM_CartFlow.xlsx` for requirement-to-test mapping
7. Open `/defects/Bug_Report_CartFlow.xlsx` to see all 20 defects
8. Read `/reports/Test_Summary_Report_CartFlow.docx` for final results

---

## About Me

**Purva Rawale**
Fresher — Manual QA Tester
Actively looking for QA / Software Testing opportunities

This project was done independently to build hands-on testing skills and create a portfolio that shows real testing work. I followed the full STLC — requirement analysis, test planning, test design, execution, defect reporting, and test closure.

- 📧 purva.rawale09@gmail.com
  
