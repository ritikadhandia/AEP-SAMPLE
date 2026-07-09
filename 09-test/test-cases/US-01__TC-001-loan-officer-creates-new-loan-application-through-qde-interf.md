# TC-001 — Loan Officer Creates New Loan Application Through QDE Interface

- **User story:** US-01
- **Pass criteria:** Loan application is successfully created with all required fields populated and confirmation message appears
- **Preconditions:** app: Loan Application Management; test_data: ['No specific test data required - creating new application']; user_profile: Loan Officer

## Steps

1. **click** — App Launcher
   - _Click the App Launcher (9-dot waffle icon) in the top-left corner of the Lightning header_
   - ⤷ expect: App Launcher menu opens showing available applications
2. **click** — Loan Application Management
   - _Click on the Loan Application Management app tile_
   - ⤷ expect: Loan Application Management app opens showing the main dashboard
3. **click** — Loan Applications tab
   - _Click on the Loan Applications tab in the navigation bar_
   - ⤷ expect: Loan Applications list view displays
4. **click** — New button (button[name="New"])
   - _Click the New button to create a new loan application_
   - ⤷ expect: New Loan Application modal opens showing the loan application form
5. **fill** — Applicant First Name field (input[name="Applicant_First_Name__c"])
   - _Click in the Applicant First Name field and enter the first name_
   - `data=John`
   - ⤷ expect: Applicant First Name field displays 'John'
6. **fill** — Applicant Last Name field (input[name="Applicant_Last_Name__c"])
   - _Click in the Applicant Last Name field and enter the last name_
   - `data=Doe`
   - ⤷ expect: Applicant Last Name field displays 'Doe'
7. **fill** — Social Security Number field (input[name="SSN__c"])
   - _Click in the Social Security Number field and enter the SSN_
   - `data=123-45-6789`
   - ⤷ expect: Social Security Number field displays '123-45-6789'
8. **fill** — Loan Amount field (input[name="Loan_Amount__c"])
   - _Click in the Loan Amount field and enter the requested loan amount_
   - `data=250000`
   - ⤷ expect: Loan Amount field displays '250000'
9. **select_picklist** — Loan Type picklist (button[role="combobox"][aria-label="Loan Type"])
   - _Open the Loan Type picklist and select a loan type_
   - `value=Conventional`
   - ⤷ expect: Loan Type shows 'Conventional'
10. **click** — Save button (button[name="SaveEdit"])
   - _Click the Save button to save the loan application_
   - ⤷ expect: Success toast shows 'Loan Application "John Doe - Conventional" was created.' and the loan application detail page displays
11. **verify**
   - _Verify the loan application record was created with all entered data_
   - ⤷ expect: Loan application detail page shows Applicant Name 'John Doe', SSN '123-45-6789', Loan Amount '$250,000', and Loan Type 'Conventional'

## Assertions

- Loan officer can access the loan application form through the New button
- All customer data fields (First Name, Last Name, SSN, Loan Amount, Loan Type) accept input correctly
- Required field validation prevents saving incomplete applications
- Successfully created loan application displays confirmation and shows entered data


---
_Auto-generated from in-app state. Source field: `pipeline_artifacts.test_scripts.test_cases[TC-001]`. Last updated: 2026-07-09T09:38:29.043144+00:00._
