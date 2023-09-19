# Global Health Supply Chain Analysis (2022)

Welcome to the Global Health Supply Chain Analysis repository! This project provides a comprehensive analysis of supply chain health commodity shipments and pricing data, with a specific focus on Antiretroviral (ARV) and HIV lab shipments to supported countries in the year 2022.

## Contents

- **analysis.sql**: This SQL script contains a series of well-structured queries and analyses that uncover trends, patterns, and valuable insights from the supply chain data.
- **Supply_Chain_Shipment_Pricing_Data.csv**: The raw dataset in CSV format, containing a wealth of information related to health commodity shipments and pricing.
- **Supply_Chain_Shipment_Pricing_Data.db**: A SQLite database version of the dataset, making it easier to run SQL queries and perform analysis.

## Objective

The primary objective of this project is to provide stakeholders with a comprehensive understanding of global spending on specific health commodities, particularly ARV and HIV lab shipments. When analyzed in conjunction with related data sources such as the Global Fund's Price, Quality, and Reporting (PQR) data, this dataset offers a holistic view of the global health supply chain landscape in 2022.

## Key Insights

- Analysis of pricing ranges and trends for health commodities.
- Volumes of commodities delivered by country, offering insights into distribution patterns.
- Support for data-driven decision-making in the global health sector.

## Data Analysis

Here are some key findings from the data analysis:

- **Shipment Methods**: There are four primary shipment methods: air, truck, air charter, and ocean. Air shipment is the most popular, followed by trucking and ocean.

- **Common Countries**: The top five most common countries in the dataset are South Africa, Nigeria, Côte d'Ivoire, Uganda, and Vietnam.

- **Product Group Distribution**: The most common product group is Antiretroviral (ARVs), followed by HRDTs.

- **Average Line Item Value**: ARVs have the highest average line item value, followed by HRDTs.

- **Average Weight by Shipment Mode**: Air Charter has the highest average weight, followed by Ocean. Truck has the lowest average weight.

- **Average Freight Cost by Shipment Mode**: Air Charter has the highest average freight cost, followed by Ocean. Truck has the lowest average cost.

- **Total Line Item Value and Freight Cost by Country**: Nigeria has the highest total line item value and total freight cost, followed by Zambia.

- **Average Unit Price by Product Group and Shipment Mode**: Unit prices vary significantly among different product groups and shipment modes.

- **Common Dosage Forms**: ARVs are commonly found in tablet and tablet - FDC forms, while HRDTs are commonly found as test kits.

- **Seasonality Analysis**: You can analyze seasonality in line item quantities for specific countries, such as Nigeria.

- **Profitable Vendors**: SCMS from RDC in Zambia, Orgenics Ltd. from Haiti, and Aurobindo Pharma Limited from Vietnam are among the most profitable vendors.

- **Common Brand and Molecule/Test Type Combinations**: Efavirenz, Nevirapine, and Lamivudine/Nevirapine/Zidovudine are the top three common combinations.

- **Top Product Descriptions**: The top product descriptions by line item quantity include Lamivudine/Nevirapine/Zidovudine 150/200/300mg, Efavirenz 600mg, and Efavirenz/Lamivudine/Tenofovir Disoproxil Fumarate 600/300/300mg.

- **Shipment Modes by Product Group**: ARV products are primarily shipped via Air, while HRDT products are transported by Air as well. ANTM and ACT product groups also utilize Air shipments, and MRDT products are delivered by Air.

## Data Source

The data for this project was sourced from the U.S. Agency for International Development (USAID) and can be found at [US Agency for International Development](https://catalog.data.gov/dataset/supply-chain-shipment-pricing-data-07d29).

## Getting Started

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/alex-t-reed/Global-Health-Supply-Chain-Analysis-2022
2. Review the SQL analysis script in `analysis.sql` to explore the insights and findings.
3. Access the raw data in CSV format via `Supply_Chain_Shipment_Pricing_Data.csv` or use the SQLite database version in `Supply_Chain_Shipment_Pricing_Data.db` for running SQL queries.

## Contributing

Contributions to this project are welcome! If you have insights, improvements, or additional analyses to share, please submit a pull request.

## Feedback

For questions, suggestions, or collaboration opportunities, please don't hesitate to reach out to Alex Reed at [alexreed@ucsb.edu](mailto:alexreed@ucsb.edu).

## Disclaimer

This project is for informational and analytical purposes only. The data and conclusions presented here may not reflect real-world circumstances accurately, and users should exercise due diligence when making decisions based on the provided analysis.

Thank you for your interest in this analysis!
