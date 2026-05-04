# retail-etl-data-factory
A professional ETL pipeline developed in Excel Power Query to transform, clean, and normalize unstructured retail datasets into automated executive reports
This project demonstrates the implementation of a full ETL (Extract, Transform, Load) pipeline using Power Query. It focuses on converting raw, unstructured CSV data into a refined, high-integrity data model optimized for business intelligence.
​ Technical Implementation
​Data Normalization: Systematic correction of source formats, ensuring all pricing columns are set to Currency ($) and date strings are parsed into standardized Date objects for temporal analysis.
​Data Enrichment (Merge Logic): Integrated a master "Sales Staff" table with the primary dataset through a logical Join (Merge) operation based on Transaction IDs, assigning accountability to every commercial record.
​Conditional Segmentation: Development of logic-based columns to categorize high-value transactions (>$500), enabling immediate identification of critical sales.
​Automated Aggregation: Implementation of "Group By" operations to condense thousands of records into high-level summaries by product category (Beauty, Clothing, Electronics).
​ Key Features
​Step-by-Step Traceability: Every transformation is documented in the "Applied Steps" panel for full auditability.
​Scalability: The pipeline is designed to refresh and process new monthly data automatically without manual reconfiguration.
