# Formula 1 Analytics Dashboard

## **Introduction**
This project aims to develop a **Formula 1 Analytics Dashboard**, providing insights into past races to assist with strategy development before a Grand Prix weekend. Since no real-time data is available, the focus is on **historical data analysis** from the [Fast-F1 API](https://docs.fastf1.dev/).

## **Project Overview**
### **Objective**
- Analyze **historical Formula 1 race data** to extract insights on driver performance, lap times, tire strategies, and track conditions.
- Build an **interactive dashboard** for pre-race decision-making using **Dash/Streamlit**.
- Start with **local development** using PostgreSQL for structured data storage, and later **migrate to Azure** for cloud-based analytics.

### **Tech Stack**
- **Data Source**: Fast-F1 API
- **Database**: PostgreSQL (locally), later Azure SQL
- **Front-End**: Dash / Streamlit
- **Cloud Services (Future Phase)**: Azure Data Factory, Azure Synapse Analytics, Azure ML

## **Database & Storage Decisions**
### **Why PostgreSQL?**
- Handles **structured** race data efficiently.
- Supports **complex queries** (lap times, tire wear trends, sector analysis).
- Scales well if later migrated to **Azure SQL Database**.
- Allows indexing for **fast retrieval of race data**.

### **Storage Plan**
- **PostgreSQL** → Stores structured data (race details, lap times, telemetry).

## **Project Development Phases**
### **Phase 1: Local Development**
- ✅ Set up **PostgreSQL** and define schema for structured race data.
- ✅ Develop scripts to pull and store **Fast-F1 API** data in PostgreSQL.
- ✅ Build an **initial Dash/Streamlit prototype** for data visualization.

### **Phase 2: Cloud Migration (Azure Integration)**
- 🔜 Move **data pipeline** to **Azure Data Factory** (automate data fetching).
- 🔜 Store race data in **Azure SQL** for scalability.
- 🔜 Process large datasets with **Azure Synapse Analytics**.

### **Phase 3: Machine Learning & Strategy Insights**
- 🔜 Train models on **Azure ML** to predict pit stops and race outcomes.
- 🔜 Deploy an **ML-powered strategy simulator** in the dashboard.

---
