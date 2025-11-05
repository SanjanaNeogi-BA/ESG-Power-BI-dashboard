# ESG-Power-BI-dashboard : Driving Sustainable Value and Transparency

This repository presents the code and design for a comprehensive Environmental, Social, and Governance (ESG) Reporting Dashboard. This interactive dashboard transforms raw data into actionable insights, providing our organization with a powerful tool for monitoring sustainability performance, meeting disclosure requirements, and driving strategic decision-making in line with leading global frameworks.

## Key Features and Framework Alignment

### This dashboard is strategically designed to gather data that satisfies the disclosure requirements of major ESG frameworks: 
GRI (Global Reporting Initiative), TCFD (Task Force on Climate-related Financial Disclosures), and TOMS (Themes, Outcomes, Measures, and Stakeholders, often used in public sector or outcome-based reporting).
1. TCFD Alignment: Climate Risk & Strategy

* The TCFD focuses on financially material climate-related risks and opportunities across four pillars: Governance, Strategy, Risk Management, and Metrics & Targets.Embedded Forecasting Power: The Environment view includes a forecasted trendline for Scope 1 & 2 Emissions (tCO2e) extending through 2030. This directly addresses the TCFD Metrics & Targets pillar by enabling forward-looking, scenario-based climate risk assessment and strategic planning.
* Metrics & Targets: Tracking total Scope 1, 2, and 3 Emissions and Operational Intensity (Emissions (tnCO2) per sterling mil revenue}) provides the core data required for TCFD reporting.
Governance: The Governance page highlights ESG Board Display (11.03%), which demonstrates the board's oversight of climate-related risks and opportunities (TCFD Governance pillar).
3.  GRI Alignment: Broad Stakeholder Impact.
  
* The GRI Standards focus on the organization's impacts on the economy, environment, and people, serving a broad range of stakeholders.
* Comprehensive Material Disclosures: The dashboard reports on a wide range of metrics, including 14 GRI Metrics and 21 Sub-metrics, covering the essential GRI Topic Standards:Environment (GRI 300 Series): Total Energy Usage (2.77M KWH), Waste Generation (5.00K Tns), and detailed Scope 3 (Category 1 & 15) emissions.Social (GRI 400 Series): Employee Turnover Rate (8.33%), Accident Frequency Rate (AFR - 51.04), Average Training Hours (20.23), and local labor engagement (53.72%).Granular Drill-Through and Filtering: The ability to filter data by Site Name (Social) and to perform drill-downs on emissions by procurement/investment drivers (Environment - Details) ensures completeness and comparability as mandated by the GRI principles.
3.   TOMS Alignment: Outcome-Focused Value Creation

* The dashboard's structure directly supports an outcome-based reporting model by linking internal actions to external goals (a core element of TOMS).Mapping to SDGs: The Governance view shows the Mapping of Policies to Relevant SDGs (e.g., HR29 - Equal Opportunities Policy linked to SDG 8). This connects organizational activity to clear global outcomes, fulfilling the Themes and Outcomes parts of the TOMS model.
* Measurable Performance: Key performance indicators (E Score: 6.08, S Score: 7.34, G Score: 5.97) serve as Measures, allowing for clear tracking against stated organizational objectives and demonstrating social and governance accountability to stakeholders.

## Value Added to the Organization

Value Area,Dashboard Impact & Framework Synergy
Integrated Strategy,"Unified Reporting: Uses a single, verified data set to satisfy the distinct needs of TCFD (investor-focused climate risk), GRI (broad stakeholder impact), and TOMS (outcome-based performance)."
TCFD & Risk Mitigation,Proactive Climate Management: Embedded emissions forecasting enables strategic planning and financially material climate risk assessment as required by TCFD. Continuous monitoring of AFR (Accident Frequency Rate) mitigates operational risk.
GRI & Transparency,"Enhanced Stakeholder Trust: Reporting on 14 GRI Metrics ensures compliance with global standards, providing high transparency to employees, investors, and regulators."
TOMS & Target Setting,"Outcome-Focused Goals: Performance scores (E Score: 6.08, S Score: 7.34, G Score: 5.97) and policy-to-SDG mapping provide the foundation for setting robust, measurable, and time-bound strategic goals aligned with organizational outcomes."
Resource Efficiency,Cost Optimization: Granular drill-down into energy usage (2.77M KWH) and Scope 3 emission drivers pinpoints high-impact areas for resource conservation and cost reduction efforts.

## Data Model Foundation

The dashboard is built upon a robust and efficient data model that integrates data from disparate sources (Procurement, HR, Operations, Finance) into a central hub. This model is critical for ensuring the verifiability and accuracy required by all frameworks.

Fact Tables for Emissions, GVA, Training Hours, and Investment.

Dimension Tables for Material/Subcontractor, Investment Name, Site Name, and Training Type.

A Governance/Policy Mapping Model to link internal policies directly to external frameworks (GRI/SDGs), ensuring the data is not just present, but strategically aligned.

This underlying structure ensures data accuracy, rapid query performance, and the ability to seamlessly extend the dashboard with new metrics to meet evolving regulatory and voluntary framework requirements.
