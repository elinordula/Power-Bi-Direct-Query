# Power BI Dashboard with DirectQuery (PostgreSQL)

> **This project demonstrates a dynamic Power BI dashboard that provides real-time insights by leveraging a **DirectQuery** connection to a **PostgreSQL** database. Unlike import mode, this approach avoids storing data within the Power BI file, ensuring your reports are always up-to-date with the latest information from your data source.**

---

## 🚀 **Features**

* **Live Data Visualization**: Get up-to-the-minute data straight from your PostgreSQL database.
* **Real-Time Reporting**: The dashboard reflects the latest changes and transactions as they occur.
* **Custom Visuals & Filters**: Utilize a variety of visuals and interactive slicers to explore the data.
* **Multi-Page Analysis**: The report includes different pages for **trends**, **KPIs**, and **detailed data analysis**.

---

## 🛠️ **Tech Stack**

* **Power BI**: The primary tool for creating the dashboard and visualizations.
* **PostgreSQL**: The relational database management system serving as the data source.
* **DirectQuery Mode**: The connection method that queries the database in real-time.

---

## 📊 **Data Source**

The dashboard is configured to connect to a PostgreSQL database (either locally or remotely hosted). All data is retrieved directly from this source via **DirectQuery**, which ensures the dashboard's reports are always a true reflection of the current data without any data latency.

---

## 🖼️ **Screenshots**

* 
* 

---

## 🖥️ **How to Use**

1.  **Open the Report**: Open the **`.pbix`** file in **Power BI Desktop**.
2.  **Connect to Data Source**: Ensure your PostgreSQL database is running and accessible from your machine. Power BI will automatically attempt to refresh the data using the DirectQuery connection.
3.  **Explore**: Interact with the visuals, apply filters, and navigate through the different pages to gain insights.

---

## ⚠️ **Notes**

* Make sure you have the **PostgreSQL connector** installed in your Power BI environment.
* The performance of the dashboard in **DirectQuery** mode is heavily dependent on the optimization of your database and the efficiency of your queries.
