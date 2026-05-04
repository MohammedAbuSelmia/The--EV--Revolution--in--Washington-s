# The EV Revolution in Washington State

## Project Overview
This project dives into the **Electric Vehicle (EV) ecosystem of Washington State, USA** — analyzing vehicle types, geographic distribution, and usage patterns across every county and city in the state. The data was sourced from the **Washington State Open Data Portal** and processed through a full analytics pipeline using SQL, Power BI, DAX, and M Language.

>  **Fully Dynamic** — Every visual and metric responds instantly to your selections across County, City, Vehicle Type, and Model — giving you complete control over the entire dataset in real time.

---


## 🛠️ Tools & Technologies
`SQL (SSMS)` · `Power BI` · `Power Query (M Language)` · `DAX` · `Data Modeling`

##  Step 1 — Defining the Analytical Plan
Before touching the data, I started with a clear plan: *What exactly do I want to learn from this dataset, and which columns will get me there?*

This step ensured every decision made afterward — from SQL queries to Power BI visuals — was purposeful and aligned with the project's goals.

---

##  Step 2 — Data Retrieval and Cleaning (SQL)
Using **SQL in SSMS**, I retrieved the raw dataset and began the cleaning and transformation process:

- Selected only the columns relevant to the analysis.
- Encountered a challenge: **latitude and longitude were stored in a single column**, mixed with additional text. I resolved this using SQL string functions to extract clean, usable coordinate values.
- Discovered another data quality issue: a small number of records belonged to states other than Washington, with percentages too low to be statistically meaningful. These records were removed, narrowing the focus entirely to **Washington State**.

---

##  Step 3 — Data Modeling in Power BI
With a clean dataset in hand, I imported it from SSMS into **Power BI** and built the data model. Using **DAX** for custom measures and **M Language** in Power Query for additional transformations, the data was shaped into a structure ready for deep analysis.

---

##  Step 4 — Geographic Deep Dive
One of the most compelling aspects of this project is the **geographic layer**. Using the extracted coordinates, I plotted every vehicle on an interactive map — accurate to its real-world location.

Users can:
- Select any **county** in Washington State on the map
- Instantly see the **number of cities** within that county
- Drill down into **vehicle-level details**, each pinned to its exact latitude and longitude

---

##  Step 5 — EV Insights & Rankings
The final layer of analysis answers the critical business questions:

- **Which EV models are most popular in each county?**
- **What are the top EV models overall** across Washington State?
- **How are EV types distributed** — Battery Electric Vehicles (BEV) vs. Plug-in Hybrid Electric Vehicles (PHEV)?

These insights are presented clearly and interactively, making it easy to identify trends and patterns at both the state and local level.

---
