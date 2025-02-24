# İzmir Green Space Accessibility Analysis  

## 📌 Project Overview  
This project focuses on analyzing the **distribution and accessibility of green spaces** in İzmir. Green spaces play a crucial role in urban sustainability, public health, and environmental balance. However, their **accessibility and spatial distribution** vary across different neighborhoods, potentially leading to **inequality in access**.  

### **🔍 Objective**  
This repository contains the **first phase** of the İzmir Green Space Accessibility Analysis. The main goal is to **prepare spatial data** by converting green space addresses into geographic coordinates and integrating them into a GIS-compatible format.  

## 🏗 **Phase 1: Data Preparation**
### **✅ Steps Completed in This Phase**  
1️⃣ **Geocoding**: Address-based green space locations were converted into **latitude and longitude** using OpenStreetMap’s Nominatim API.  
2️⃣ **Spatial Conversion**: The dataset was transformed into a **GeoDataFrame**, enabling GIS operations.  
3️⃣ **Shapefile Export**: The processed dataset was saved in **Shapefile, GeoJSON, and GPKG formats** for compatibility with GIS tools like QGIS and Python’s GeoPandas.  
4️⃣ **Dataset Cleaning**: Column names were adjusted to ensure **compliance with GIS file format limitations** (Shapefile’s 10-character column name limit).  

## 🎯 **Next Steps (Future Phases)**
🚀 **Phase 2: Spatial Analysis**  
- Analyzing green space availability per **neighborhood**.  
- Identifying **underserved areas** with limited access to green spaces.  
📊 **Phase 3: Accessibility Evaluation**  
- Measuring **proximity to green spaces** using spatial analysis.  
- Identifying **gaps in urban green coverage** for future urban planning improvements.  

## 📂 **Project Structure**
📁 data/            # Contains raw and processed data
📁 notebooks/       # Jupyter notebooks for analysis
📁 src/            # Python scripts for processing
📁 outputs/        # Results and final outputs
📄 README.md       # Project documentation

## 🛠 **Technologies Used**
- **Python** (GeoPandas, Pandas, Geopy, Shapely)  
- **QGIS** (for spatial visualization and analysis)  
- **OpenStreetMap** (for geocoding and mapping)  
## 📢 **Acknowledgment**  
This dataset was obtained from the **[İzmir Open Data Portal](https://acikveri.bizizmir.com/en/dataset/kuzey-guney-alani-park-sayilari)**. The study aims to contribute to **data-driven urban planning** by evaluating green space accessibility in İzmir.  


✅ Status: 🟢 Phase 1 Completed – Preparing for Spatial Analysis
📅 Last Updated: February 2025
🚀 Let’s make İzmir greener and more accessible!
