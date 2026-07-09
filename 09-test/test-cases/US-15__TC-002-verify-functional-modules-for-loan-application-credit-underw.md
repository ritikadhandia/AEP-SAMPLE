# TC-002 — Verify Functional Modules for Loan Application Credit Underwriting and Pricing Navigation

- **User story:** US-15
- **Pass criteria:** All functional modules (Loan Application, Credit/Underwriting, Pricing & Negotiation) are accessible, functional, and properly integrated
- **Preconditions:** app: Loan Application Management; test_data: ["Loan Application record 'LA-001' exists with Status = 'Submitted'"]; user_profile: System Administrator

## Steps

1. **click** — App Launcher
   - _Click the App Launcher (9-dot waffle icon) in the top-left corner to access applications_
   - ⤷ expect: App Launcher menu opens showing available applications
2. **click** — Loan Application Management
   - _Click on the Loan Application Management app to access loan processing modules_
   - ⤷ expect: Loan Application Management app opens showing navigation tabs for all functional modules
3. **verify**
   - _Verify Loan Application module is accessible_
   - ⤷ expect: Loan Applications tab is visible in the navigation bar
4. **click** — Credit Analysis tab
   - _Click on the Credit Analysis tab to access credit/underwriting module_
   - ⤷ expect: Credit Analysis list view displays showing credit evaluation tools
5. **verify**
   - _Verify Credit/Underwriting module functionality is accessible_
   - ⤷ expect: Credit Analysis page shows credit scoring tools and underwriting workflow options
6. **click** — Pricing Engine tab
   - _Click on the Pricing Engine tab to access pricing and negotiation module_
   - ⤷ expect: Pricing Engine dashboard displays showing pricing calculation tools
7. **verify**
   - _Verify Pricing & Negotiation module functionality is accessible_
   - ⤷ expect: Pricing Engine page shows rate calculation tools and negotiation tracking features
8. **click** — Loan Applications tab
   - _Return to Loan Applications tab to verify module integration_
   - ⤷ expect: Loan Applications list view displays
9. **click** — LA-001
   - _Click on loan application record LA-001 to view integration between modules_
   - ⤷ expect: Loan application detail page opens showing record information
10. **click** — Related tab (a[role="tab"][data-label="Related"])
   - _Click the Related tab to view connected module records_
   - ⤷ expect: Related tab displays showing Credit Analysis and Pricing records linked to this loan application

## Assertions

- Loan Application module is accessible and functional
- Credit/Underwriting module is accessible with credit analysis tools
- Pricing & Negotiation module is accessible with rate calculation features
- All three modules are integrated and can reference the same loan application records


---
_Auto-generated from in-app state. Source field: `pipeline_artifacts.test_scripts.test_cases[TC-002]`. Last updated: 2026-07-09T09:40:39.188175+00:00._
