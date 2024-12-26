# 🌍 Global Renewable Energy Analysis Platform

An End-To-End data engineering solution for analyzing renewable energy adoption, economic factors, and climate patterns across different countries.

![Renewable Energy](https://img.shields.io/badge/Energy-Renewable-brightgreen)
![Azure](https://img.shields.io/badge/Platform-Azure-blue)
![PowerBI](https://img.shields.io/badge/Visualization-PowerBI-yellow)

## 📊 Project Overview

This project analyzes the relationship between renewable energy adoption, economic growth, and climate factors worldwide. By leveraging cloud technologies and advanced data processing techniques, we provide interactive visualizations and insights to help stakeholders make informed decisions about renewable energy initiatives.

### Key Analysis Areas:
- Renewable Energy Share vs. GDP Growth
- Temperature Analysis by Country and Season
- Renewable Energy Efficiency Comparisons
- Impact on Sustainable Development
- Weather Severity and CO₂ Emissions
- Seasonal Financial Flows

## 🏗️ Architecture

The solution implements a modern data platform using Azure services:

1. **Data Sources**
   - Population Data (AWS S3)
   - Weather Data (Azure SQL Database)
   - Energy Data (GitHub)

2. **Data Processing Pipeline**
   - Azure Data Factory for data orchestration
   - Azure Databricks for transformation (Medallion Architecture)
   - Azure Data Lake Storage Gen2 for data storage
   - Azure Synapse Analytics for data warehousing

3. **Visualization**
   - Power BI dashboards and reports
   - Interactive visualizations
   - Real-time data updates

## 📦 Datasets

The project utilizes three comprehensive datasets:

1. **Weather Dataset** (1.8M+ rows)
   - Daily meteorological data
   - Temperature metrics
   - Precipitation and snow data
   - Geographical coordinates

2. **Energy Dataset** (69K+ rows)
   - Energy production metrics
   - Renewable energy statistics
   - GDP and economic indicators
   - Carbon emissions data

3. **Population Dataset** (2.5K+ rows)
   - Demographic information
   - Population density
   - Urbanization metrics
   - Migration statistics

## 🔄 Data Processing

### Medallion Architecture Implementation:
- **Bronze Layer**: Raw data ingestion
- **Silver Layer**: Data cleansing and validation
- **Gold Layer**: Analytics-ready datasets

## 🔒 Security

- Azure Key Vault for secrets management
- Azure Active Directory integration
- Role-based access control
- Secure data storage and transmission

## 📊 Key Visualizations

The platform provides interactive dashboards for:
- Renewable energy adoption trends
- Economic impact analysis
- Climate correlation studies
- Regional comparison tools
- Seasonal pattern analysis

## 🛠️ Technologies Used

- Azure Data Factory
- Azure Databricks
- Azure Synapse Analytics
- Azure Data Lake Storage Gen2
- Azure Key Vault
- Power BI
- Python (PySpark)
- SQL

## 🎯 Benefits

- Data-driven decision making for renewable energy initiatives
- Economic impact assessment capabilities
- Climate pattern correlation analysis
- Interactive visualization tools
- Scalable and secure architecture
- Real-time data processing

---
Built with ❤️ by Raghul K
