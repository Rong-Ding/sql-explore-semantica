## 🛒📈 Semantic Layer & Funnel Analysis with SQL and Python
An ongoing data analytics project exploring **user drop-off behaviour in ecommerce funnels** using SQL and Python, followed by a modular implementation of a **semantic layer** prototype for BI-style querying. Designed to demonstrate practical skills in **data modelling, exploratory analysis, and semantic abstraction**, aligning with Analytics Engineering principles.

## Project Highlights
- 🛒 **Funnel Drop-off Analysis**: Identified major user attrition between "View Item" and "Add to Cart" events using BigQuery event-level data.
- 📱 **Factor Impact Exploration**: Quantified device type (mobile, desktop, tablet) as a driver of conversion, using grouped aggregations and visualisations.
- 🧩 **Semantic Layer Simulation**: Built a modular Python class that mimics LookML logic, making SQL queries reusable and interpretable across dimensions.
- 🎯 **BI Readiness**: Prepared analysis logic that could be reused for dashboarding or Looker modelling.

## Key Analyses & Findings
- Conversion Rate Insights:
  - Desktop and mobile devices dominate traffic, while tablets show lower engagement and conversion.
  - Most drop-offs (~82%) occur immediately after the product view stage.
- Semantic Layer Contribution:
  - Created a reusable interface (`ExploreBy` class) to query funnel metrics by any dimension (e.g., device.category).
  - Mirrors LookML logic in Python to promote consistency and scalability.
 
## How to Use / Reproduce
- Requirements: Google Colab, Google Cloud SDK (for authentication)
- To run the code for funnel drop-off analysis, run _SQL+Python_for_GA4_BigQuery_WIP.ipynb_ in Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rong-Ding/sql-explore-semantica/blob/master/SQL%2BPython_for_GA4_BigQuery_WIP.ipynb)
- To run the code for semantic layer simulation, run _SQL+Python_Semantic_layer_building.ipynb_ in Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rong-Ding/sql-explore-semantica/blob/master/SQL%2BPython_Semantic_layer_building.ipynb)

## Future Work
