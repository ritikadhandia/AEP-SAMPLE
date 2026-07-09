# TC-003 — Verify System Integration Touchpoints and External System Connectivity

- **User story:** US-16
- **Pass criteria:** Integration monitoring shows active touchpoints, external system connections test successfully, and API usage confirms multi-system data exchange
- **Preconditions:** app: System Administration; test_data: ['Integration monitoring dashboard is configured', 'At least one active integration endpoint exists']; user_profile: System Administrator

## Steps

1. **click** — Gear icon (⚙)
   - _Click the gear icon in the top-right corner of the Lightning header to access Setup_
   - ⤷ expect: Gear icon dropdown menu appears
2. **click** — Setup
   - _Click Setup from the dropdown menu to open the Setup home page_
   - ⤷ expect: Setup home page opens showing administration options
3. **fill** — Quick Find search box (input[placeholder="Search Setup"])
   - _Click in the Quick Find search box and type 'Integration'_
   - `data=Integration`
   - ⤷ expect: Quick Find search box displays 'Integration' and filtered results appear
4. **click** — Integration Monitoring
   - _Click on Integration Monitoring from the search results_
   - ⤷ expect: Integration Monitoring page opens showing system integration dashboard
5. **verify**
   - _Verify integration touchpoints are displayed in the monitoring dashboard_
   - ⤷ expect: Integration dashboard shows active touchpoints with status indicators for external system connections
6. **click** — External Services tab
   - _Click on the External Services tab to view configured external system endpoints_
   - ⤷ expect: External Services tab displays showing list of configured external system integrations
7. **verify**
   - _Verify multiple external systems are configured and accessible_
   - ⤷ expect: External Services list shows multiple system endpoints with connection status and last sync timestamps
8. **click** — Test Connection
   - _Click Test Connection for the first external system endpoint_
   - ⤷ expect: Connection test dialog opens showing test in progress
9. **verify**
   - _Verify external system connection test completes successfully_
   - ⤷ expect: Connection test results show 'Success' status with response time and data exchange confirmation
10. **navigate**
   - _Navigate to API Usage page to verify integration activity_
   - ⤷ expect: API Usage page displays showing integration traffic statistics
11. **verify**
   - _Verify API usage shows active integration touchpoints across multiple systems_
   - ⤷ expect: API Usage dashboard shows data exchange activity across configured touchpoints with multiple external systems

## Assertions

- Integration monitoring dashboard displays configured touchpoints with status indicators
- Multiple external system endpoints are configured and accessible
- Connection tests to external systems complete successfully
- API usage statistics show active data exchange across integration touchpoints
- System demonstrates capability to handle 65 touchpoints across 26 systems


---
_Auto-generated from in-app state. Source field: `pipeline_artifacts.test_scripts.test_cases[TC-003]`. Last updated: 2026-07-09T09:40:39.188253+00:00._
