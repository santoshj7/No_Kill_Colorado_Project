
# Data-Driven Animal Welfare Analytics for No Kill Colorado

## Overview:
This project presents a comprehensive analytical study conducted for [**No Kill Colorado**](https://www.nokillcolorado.org/), a nonprofit organization devoted to transforming the animal welfare ecosystem through **advocacy**, **education**, and **data-informed reform**. Unlike traditional rescue operations, No Kill Colorado operates at a systemic level — driving humane policy shifts, promoting the **No Kill Equation**, and collaborating with over **300 licensed shelters and rescues** statewide.

I had the privilege of contributing to this mission through a data storytelling project on the [**Data Change Makers**](https://www.datachangemakers.org/event-details/no-kill-colorado-2) platform — a space that connects **Nonprofits and Social Impact Organizations** with **Data Professionals and Enthusiasts** to deliver data-driven solutions and create meaningful impact.

The primary objective of this analysis was to identify and track complex, longitudinal trends spanning nearly a **decade (2015–2024)** across Colorado's animal shelter statistics. The state’s licensed shelter system, comprising over 300 entities, generates a substantial volume of data. By understanding the patterns in intake, outcomes, transfers, and community impacts, this project aims to equip No Kill Colorado with the rigorous evidence needed to strategically define, support, and advocate for programs that ensure **every treatable pet achieves a safe outcome.**
## Dataset Description:

The foundation of this analysis rests upon highly regulated and publicly available government statistics, augmented by internal data systems:
* **Core Data Source:** The core shelter statistics data is published for public consumption by the **State of Colorado Department of Agriculture** from the **Pet Animal Care Facilities Act (PACFA)** Division. This data is collected through a structured process followed by licensed teams and volunteers.
* **Data Augmentation:** We hoped to enhance the PACFA data with the addition of publicly available information, such as licensee details, mapped from sources like the official *Colorado Active PACFA Facilities* database.

The consolidated dataset spans 2015–2024 and tracks the complete operational lifecycle of animals within the system, focusing on:
* **Intake Data:** The source of animals entering the system (e.g., Owner Surrender, Stray, Seized, Transfer In).
* **Outcome Data:** The disposition of animals leaving the system (e.g., Adoption, Return to Owner, Euthanasia, Transfer Out).
* **Temporal & Identifier Data:** Date fields enabling longitudinal trend analysis and unique identifiers for entity mapping.
* **Augmented Facilities Data:** Licensee information mapped to the core statistics, providing geographical and facility-type context.

## Analytical Tools:
To transition this raw, multi-source data into a cohesive, policy-grade narrative, a specialized set of tools was employed for each stage of the data lifecycle:

* **Python (Jupyter Notebook):** Utilized for the initial data wrangling phase, enabling robust cleaning, transformation, and the merging of separate yearly PACFA statistics into a unified dataset.
* **Microsoft Power BI:** Selected as the primary visualization platform, facilitating the development of a dynamic, interactive, and shareable dashboard for stakeholder consumption.
* **DAX (Data Analysis Expressions):** Leveraged within Power BI to construct complex measures and key performance indicators (KPIs) necessary for tracking adoption rates, intake patterns, and live-release metrics across the multi-year study period.

## Workflow & Process Chronicle:
The project followed a **structured two-phase lifecycle**, ensuring analytical integrity and communicative clarity:

**1. Data Wrangling (Python & Google Sheets):**

- Combined annual PACFA datasets (2015–2024) into a single structured table.
- Standardized variable naming, normalized shelter identifiers, and validated numeric consistency.
- Integrated facility-level metadata from ColoradoActive PACFA Facilities.
- Exported the unified, cleaned dataset for Power BI ingestion.

**2. Data Visualization (Power BI):**

- Designed an interactive dashboard visualizing intake vs. outcome patterns, adoption trends, and regional performance.
- Implemented DAX measures for live release rates, year-over-year trends, and categorical segmentation.
- Delivered the final dashboard on the Data Change Makers platform, where it was selected among the Top 5 visualizations by the No Kill Colorado team for live showcase.

## Dashboard & Visualization Highlights:
The resulting **Power BI dashboard** serves as the primary analytical asset, translating complex, multi-year PACFA statistics into an accessible, high-impact format. It is designed to showcase **key performance metrics**, **intake and outcome trends over time**, and **geographical breakdowns**, allowing stakeholders to explore the data dynamically.

[**Click here to View Interactive Power BI Dashboard**](https://project.novypro.com/WuOn20)
## Screenshots:

![Report](https://github.com/santoshj7/No_Kill_Colorado_Project/blob/main/Final%20Report/2.png)


## Key Insights & Outcome Summary:
The depth of the multi-year analysis and resulting dashboard were designed to empower No Kill Colorado with the ability to:

* **Identify** longitudinal shifts in pet intake sources, providing evidence to prioritize community-based prevention programs.
* **Monitor** live-release rates and other key outcome metrics, enabling performance benchmarking across different regions and shelter types.
* **Analyze** the flow of animal transfers, highlighting opportunities for improved collaborative pipelines and resource allocation between organizations.
* **Provide** clear, data-driven evidence to strategically support advocacy for the programs and services necessary to achieve a No Kill state.
## Acknowledgements

I am immensely grateful to **No Kill Colorado** and the **Data Change Makers** platform for providing this profoundly meaningful learning opportunity and the space to apply technical skills toward systemic change. Having my dashboard selected among the **top 5 visualizations** to be showcased live at the organization's event was a genuine honor and a validating moment in my data journey.

A sincere thank you to all participants and the organizers for the certificate of appreciation and for fostering a collaborative environment. Feedback and connections are always welcome.

## Feedback:

If you have any feedback, please reach out to me at jsantosh7296@gmail.com


## 🔗 Links:
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://datascienceportfol.io/santoshjportfolio)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jsanthosha/)


