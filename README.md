🥗 Supply Planning & Ingredient Shortage Analysis (HelloFresh Job Application Project
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
***Exception-Based Production Planning Model (Excel & Tableau)***

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="1601" height="881" alt="Screenshot 2026-02-02 at 17 17 45" src="https://github.com/user-attachments/assets/8a8e43df-cd02-4d18-9dff-335ec572738b" />

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***🎯Portfolio Question***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This project addresses the following planning question:

How can a production planning team identify and prioritise ingredient shortages while ensuring that production capacity remains operationally feasible?

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***🧩Project Overview***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This project demonstrates an end-to-end supply and production planning workflow comparable to those used in fast-paced food manufacturing and meal-kit operations such as HelloFresh.

Using representative order, recipe, inventory, and production capacity data, the model converts weekly customer demand into ingredient-level requirements, identifies inventory shortages, and validates production capacity. The outputs are presented through an exception-focused Tableau dashboard designed to support efficient and practical planning decisions.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***🏭Business Context***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Production planning teams are required to translate customer demand into executable production plans while maintaining high service levels and operational efficiency. This includes ensuring ingredient availability, validating production capacity, and responding quickly to supply risks.

This project simulates a short-term planning scenario and demonstrates how structured data preparation and planning logic can support proactive, data-driven decision-making in an operational environment.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***🧹Data Preparation and Excel Modelling Process***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="1195" height="899" alt="Screenshot 2026-02-02 at 17 21 03" src="https://github.com/user-attachments/assets/87bd98e6-6dd6-4ff1-acc7-c2dd92dc2392" />




All data preparation and planning logic were developed in Microsoft Excel to reflect real-world planning workflows.

Raw input data covering customer orders, recipes, ingredient requirements, inventory levels, and production line capacity were first reviewed and structured into clean, consistently formatted tables. Column naming conventions and data types were standardised to ensure reliable aggregation and analysis.

Pivot tables were then used to aggregate weekly customer orders by recipe, creating a clear production demand baseline. Additional pivot tables were built to support ingredient-level demand calculations and capacity validation.

Lookup functions were applied to map recipes to their ingredient requirements and to link ingredient demand to available inventory levels. This allowed ingredient demand to be calculated accurately and compared directly against stock levels.

Exception logic and conditional formatting were used to clearly flag ingredient shortages and highlight only those items requiring planner attention. This reduced noise and ensured the model remained focused on actionable outcomes.

Finally, a dedicated, flat output table was created to serve as a Tableau-ready data source. This ensured that all calculations were completed in Excel, while Tableau was used purely for visualisation and decision support.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***⚙️Planning Logic and Methodology***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Weekly customer orders were aggregated by recipe and planning week to establish a baseline production demand.

Each recipe was decomposed into its ingredient components using bill-of-materials logic. Ingredient-level demand was calculated by multiplying recipe order volumes by the corresponding ingredient quantities.

Total ingredient demand was compared against available inventory levels to identify potential shortages. Any ingredient where demand exceeded available stock was flagged as a supply risk.

Exception-based logic was applied to isolate only those ingredients requiring planner intervention. This approach reduces planning noise and allows focus on actionable issues rather than reviewing all items.

Total weekly production volumes were subsequently compared against available production line capacity to confirm that the plan was operationally feasible. Within the defined planning horizon, no capacity constraints were identified.

Results were then visualised in Tableau through an interactive dashboard designed to support rapid identification and prioritisation of ingredient shortages.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***📊Key Insights***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***The planning model identified six ingredient shortages across the planning horizon. No production capacity constraints were observed, indicating that demand could be met from a production perspective if supply issues were addressed. Shortages were concentrated within specific ingredients and weeks, enabling targeted and timely corrective action. This was shown through the use of a dashboard on Tableau, and will be further shown in detail.***

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


***📈Tableau Dashboard Overview***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="1363" height="763" alt="Screenshot 2026-02-02 at 17 26 13" src="https://github.com/user-attachments/assets/0c4ba0dd-0007-44c0-bb62-67b08f962f8d" />



The Tableau dashboard was designed as an exception-based planning tool to support operational decision-making. It allows planners to quickly identify ingredient shortages, understand their severity and timing, and filter results by planning week and supply status.

Dashboard Features

***🔥 Heatmap:*** Ingredient × Week shortages

***📊 Bar chart:*** Total shortages by ingredient

***🧮 KPI tile:*** Number of shortages

***🎛 Filters:*** Week and supply status

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***🧰Tools and Techniques Used***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***Microsoft Excel*** was used for data cleaning, structuring, aggregation, planning logic, and capacity validation.

***Tableau*** was used for visualisation, dashboarding, and interactive analysis.

***GitHub*** was used to properly portray the timeline/story of the project and why the project is important.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***📌Assumptions and Simplifications***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Demand was assumed to be fixed within each planning week. Ingredient usage followed standard recipe specifications, and inventory was assumed to be available at the start of each week. Production lines were assumed to operate at consistent daily capacity. These assumptions reflect a simplified but realistic short-term planning scenario.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***🚀Project Outputs***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The project outputs include an Excel-based supply planning model, a Tableau ingredient shortage planning dashboard, and supporting project documentation.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***🔮Potential Enhancements***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Future enhancements could include incorporating demand forecasting, supplier lead times, and safety stock logic. Additional what-if scenarios, such as demand spikes or changes in capacity, could also be introduced. The model could further be extended to support multi-site production planning.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

***✅Conclusion***
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This project demonstrates practical capability in Excel-based data preparation, supply and production planning, exception-based analysis, and data-driven decision support. The approach reflects real-world planning challenges and aligns closely with operational workflows commonly found in food production and meal-kit environments.
