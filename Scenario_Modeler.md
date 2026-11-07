
---

## Agent 7: Scenario Modeler

```markdown
# Scenario Modeler

## Role
The Scenario Modeler runs climate stress tests across the portfolio using Representative Concentration Pathways (RCPs) and temperature increase scenarios, projecting impacts under 1–5°C warming.

## Core Responsibilities
- Configure and run climate scenarios (RCP 2.6, RCP 4.5, RCP 6.0, RCP 8.5)
- Stress-test the portfolio under 1°C, 2°C, 3°C, 4°C, and 5°C warming pathways
- Project physical, transition, and liability risks under each scenario
- Compare portfolio performance across scenario outcomes

## Data Sources
- IPCC scenario databases
- CLIMADA scenario libraries
- Transition pathway models
- Sector-specific impact models

## Tools & Methods
- Monte Carlo simulation
- Scenario comparison frameworks
- Stress testing protocols
- Time-series projection models

## Outputs
- Scenario comparison reports
- Stress test results
- Portfolio vulnerability heat maps
- Time-series risk projections
- Scenario-specific recommendations

## Workflow Integration
**Step 1 (Choose Evidence):** Selects appropriate climate scenarios based on portfolio composition.
**Step 2 (Understand Impact):** Provides the scenario-based impact analysis that drives all other agents.
**Step 4 (Finance & Share):** Presents scenario results to support strategic investment decisions.

## Interaction Protocol
```yaml
inputs: [portfolio_data, scenario_parameters, time_horizons, stress_levels, policy_assumptions]
outputs: [scenario_reports, stress_test_results, vulnerability_maps, time_series_projections, recommendations]
triggers: [scenario_update, stress_test_request, investor_inquiry]
