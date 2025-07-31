# Project Background

This dashboard was developed for the partners of a dental clinic in Lajeado, Brazil. With the aim of solving a common challenge: the difficulty in consolidating and analyzing the vast amount of clinic performance data. Using a real-world dataset of patient appointments, procedures, revenue, and patient acquisition, this project provides a, easy-to-use interface to explore operational and financial trends, optimizing strategic decision-making and driving the clinic's growth.

## Skills Showcased

  - **Data Transformation (ETL) with Power Query**: Cleaning, shaping, and preparing raw clinic data for analysis,including handling null/blank values, and changing data types.
  - **DAX Measures**: Creation of explicit measures for crucial insights and KPIs, such as the Conversion Rate (%) from initial consultations to treated patients and utilization of implicit measures for basic aggregations (sums, counts) present in the visuals.
  - **Core Charts**: Use of Line Charts to track trends over time (Revenue, New Patients). Utilization of Column and Bar Charts to compare volumes (Procedures by Year, Acquisition Channels, Contribution by Specialty).
  - **KPI Indicators & Tables:** Employment of Cards to display key metrics and important summaries (Total Revenue, Treated Patients, Conversion Rate,Executed procedures).
  - **Dashboard Design:** Development of an intuitive and visually appealing layout, focused on clarity and ease of reading for clinic managers. Visual organization of elements to present key information in a hierarchical and coherent manner.
  - **Interactive Reporting:** Slicers to dynamically filter data by period (e.g., year in trend charts) and other dimensions. Ability to interact with visuals for detailed information.
  - **Buttons & Bookmarks:** To change between pages.

## Data Source

The data used in this project originates from the LAJEADO Dental Clinic MySQL database. The most relevant tables for analysis were directly imported, in addition to four custom SQL Views created in the database to facilitate the retrieval of consolidated information and streamline the analysis process.

- ### Imported Tables:

  - **clinicalajeado_initial_consultations:** Records of initial consultations.
  - **clinicalajeado_patient_visits:** Details of patient visits to the clinic.
  - **clinicalajeado_orthodontic_payments:** Payments related to orthodontic procedures.
  - **clinicalajeado_orthodontic_installations:** Information about orthodontic appliance installations.
  - **clinicalajeado_orthodontic_appointments:** Details of orthodontic appointments.
  - **clinicalajeado_patients:** Patient registration data.
  - **clinicalajeado_payments:** General payment records.
  - **clinicalajeado_direct_payments:** Direct payments.
  - **clinicalajeado_executed_procedures:** Information about executed procedures.

- ### Custom SQL Views:

  - **acquisitionchannel:** For analyzing patient acquisition channels.
  - **clinicalajeado_totalsales:** Presents the total volume of sales/services.
  - **clinicalajeado_totalpatients:** Contains the consolidated patient count.
  - **clinicalajeado_revenue_by_specialty:** Provides aggregated revenue by each dental specialty.
 
The data model was developed to optimize analysis performance and clarity. The complete structure of the data model, including the relationships between the tables and views imported from MySQL, can be visualized in the diagram below:

![erdoficial](https://github.com/user-attachments/assets/92935e63-8fe8-4004-b67a-ad13eb9ff025)

## Dashboard Overview

### Page 1 Revenue & Services

This page serves as the executive control panel for LAJEADO Dental Clinic . It showcases the most important KPIs, such as Total Revenue, Number of Treated Patients, Volume of General Procedures, and Orthodontic Procedures. Furthermore, it provides a detailed overview of Revenue Trends of general and orthodontics, and Revenue Contribution by Specialty, offering an immediate understanding of the clinic's overall performance and its most financially significant areas.

![pagina 1](https://github.com/user-attachments/assets/5cb2e271-972a-4ac5-8c09-9297e4d91d94)

### Page 2: Patients Insights

This page provides a detailed look into the clinic's patient dynamics and acquisition strategies. It highlights key metrics such as New Patients Over Time (both general and orthodontic), Initial Consultations, and the crucial Conversion Rate. Furthermore, it offers insights into the Total Orthodontic Patients and Active Ortho Patients, along with a breakdown of Acquisition Channels and the Most Performed General Procedures, enabling a deeper understanding of patient growth and service demand.

![pagina 2](https://github.com/user-attachments/assets/496c629f-1023-44e2-9cc0-d9c7ebe3a0b9)

## Conclusion

This dashboard demonstrates how Power BI can transform raw data from LAJEADO Dental Clinic  into a powerful tool for clinic performance analysis and management. It allows managers and teams to segment, filter, and explore data to make informed decisions about operations, patient acquisition strategies, and procedure optimization, directly contributing to the business's success and growth.


  
