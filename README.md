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

## 🗂️ Data Source
- İzmir Metropolitan Municipality Open Data Portal: [Access the Data](https://acikveri.bizizmir.com/en/dataset/kuzey-guney-alani-park-sayilari)

## 🛠️ Tools & Libraries Used
- Python (Pandas, Matplotlib, Seaborn, OpenPyXL)
- Jupyter Notebook

## 📊 Outputs
- Green Spaces CSV formats with coordinates,
- Green Spaces Shapefile, GeoJSON, and GPKG formats.
- PDF Report (available in the `outputs/` folder).

📄 Project Report
[View PDF Report](https://github.com/yalgettekin/izmir-green-space-analysis/blob/main/outputs/geocoding_green_areas.pdf)

Naile Yalgettekin

[GitHub](https://github.com/yalgettekin)
[LinkedIn](https://www.linkedin.com/in/naile-yalgettekin-2b8a43100/)
