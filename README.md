# MS_Fabric_LAB_13
# 🚴‍♂️ Real-Time Dashboard with Microsoft Fabric: Bike Data Visualization

This project demonstrates how to build a **real-time dashboard in Microsoft Fabric** using **Eventstream**, **Eventhouse**, and **Kusto Query Language (KQL)**. The data source simulates real-time bicycle availability across neighborhoods.

---

## 🧪 Lab Summary

| Feature             | Used Tool                        |
|---------------------|----------------------------------|
| Data Ingestion      | Eventstream (sample data)        |
| Real-time Database  | Eventhouse (KQL Database)        |
| Query Language      | Kusto Query Language (KQL)       |
| Dashboard Type      | Microsoft Fabric Real-Time       |

---

## 🔧 Steps Followed

### 1. Workspace & Eventhouse
- Created a **Fabric-enabled workspace**
- Created an **Eventhouse** (includes a KQL database)

### 2. Eventstream Setup
- Created **Bicycle-data** eventstream
- Used **sample Bicycles data**
- Configured output:
  - **Destination**: Eventhouse
  - **Table Name**: `bikes`
  - **Input Format**: JSON

### 3. Real-Time Dashboard
- Created **Real-Time Dashboard** named `bikes-dashboard`
- Added two visuals:
  - **Bar Chart**: Number of bikes and empty docks by neighborhood
  - **Map**: Location of bikes with counts

### 4. Optimization
- Created a **base query** `base_bike_data` to reuse logic
- Added a **parameter** `Neighbourhood` for filtering visuals dynamically

### 5. Final Touches
- Added a second page with recent observation times
- Configured **Auto Refresh** (every 30 minutes)
- Shared and tested the dashboard

---

## 📸 Screenshots

> ![18](https://github.com/user-attachments/assets/d2aa6f80-d993-48b1-83d1-5155fa7838d8)

---

## 🧹 Clean-up

- Removed the workspace after testing to avoid capacity charges.

---

## 💡 Technologies Used

- Microsoft Fabric
- Eventstream
- Eventhouse (KQL DB)
- Real-Time Dashboard
- Kusto Query Language (KQL)

---

## 🔗 Connect with me

This project was completed as part of hands-on practice to explore real-time analytics in Fabric.

> 👤 (https://www.linkedin.com/in/nejdet-yalcin/)  
> 📫 Contact: nejdetyalcin2@gmail.com

