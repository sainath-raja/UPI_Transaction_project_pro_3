# UPI_Transaction_project_pro_3

# UPI_Transactions-Dashboard

## Recommended Structure and Order

### 1. Project Title - 💸 **UPI Insights: Transaction Behavior & Channel Analysis Dashboard**  
An intuitive Power BI dashboard built to explore UPI transaction patterns, device usage, city-wise trends, and customer behavior across banking channels—leveraging slicer sync, bookmarks, and matrix visuals for multi-dimensional insights.

---

### 2. Short Description  
UPI Insights is an interactive analytics dashboard designed to analyze digital transaction data using Power BI. It explores UPI usage trends, switching options between different charts, and provides a breakdown of transaction behaviors across multiple dimensions like bank, gender, city, and device type.

---

### 3. Tech Stack  
The dashboard was built using the following tools and technologies:<br>
• 🗃️ **CSV Dataset** – `UPI_Transaction.csv` used as the raw data source.<br>
• 🧱 **Data Modeling in Power BI** – Relationship building and calculated fields.<br>
• 📊 **Power BI Desktop** – Used for building visuals, bookmarks, and slicer sync.<br>
• 🔁 **Slicer Sync** – Enabled for seamless filtering across multiple report pages.<br>
• 🔖 **Bookmarks** – Implemented to toggle between different visual perspectives (Line vs Cluster Chart).<br>
• 📤 **Power BI Service** – Used for publishing and enabling scheduled access.<br>
• 📁 **File Format** – `.pbix` for development and `.png` for visual snapshots.

---

### 4. Data Source  
**Source:** `UPI_Transaction.csv`

The dataset includes the following columns:<br>
• Transaction ID<br>
• Transaction Date<br>
• Amount<br>
• Bank Name Sent<br>
• Bank Name Received<br>
• Remaining Balance<br>
• City<br>
• Gender<br>
• Transaction Type<br>
• Status<br>
• Device Type<br>
• Payment Method<br>
• Merchant Name<br>
• Purpose<br>
• Customer Age<br>
• Payment Mode<br>
• Currency<br>
• Customer Account Number<br>
• Merchant Account Number<br>

---

### 5. Features / Highlights  

• **Business Problem**  
Digital transaction systems process massive amounts of data, yet users and analysts struggle to gain real-time insights into patterns by city, bank, payment method, or device. Without centralized visual tools, it’s difficult to identify fraud trends, customer behavior, or peak transactional loads.

---

• **Goal of the Dashboard**  
To deliver an interactive Power BI tool that:  
- Analyzes UPI transactions across various dimensions.  
- Empowers stakeholders with multi-chart toggle options.  
- Enables filtering across pages with synchronized slicers.  
- Provides city-currency-month summaries through matrix visualizations.

---

• **Walkthrough of Key Visuals**  

- **📄 Page 1: Transaction Overview**  
  • 10 interactive slicers: Bank Sent, Bank Received, City, Device Type, Gender, Age Group, Merchant Name, Payment Method, Purpose, Transaction Type.  
  • Line Chart: Sum of Amount by Month.  
  • Toggle Feature: Bookmarks allow switching between Line Chart and Cluster Column Chart.  
  • Bookmark variations:  
    - Line Chart (Amount)  
    - Cluster Column Chart (Amount)  
    - Line Chart (Remaining Balance)  
    - Cluster Column Chart (Remaining Balance)  

- **📄 Page 2: Matrix Summary**  
  • Matrix visual showing City, Currency, and Month.  
  • All slicers are synced from Page 1 for consistent interactivity.  
  • Drill-down capabilities for analyzing trends by transaction currency and geography.

---

• **Business Impact & Insights**  
- **User Behavior**: Understand how transaction activity varies by city, gender, or device type.  
- **Banking Trends**: Analyze sending vs. receiving bank patterns.  
- **Interface Usability**: Slicer sync and bookmarks offer a tailored user experience.  
- **Fraud Detection**: Enables institutions to monitor unusual patterns across payment types and devices.

---

### 6. Screenshots / Demos  
Show what the dashboard looks like.  
- ![Transaction Overview](https://github.com/sainath-raja/UPI_Transaction_project_pro_3/blob/main/Line_chart.png)  
- ![Matrix Visual](https://github.com/sainath-raja/UPI_Transaction_project_pro_3/blob/main/Matrix_chart.png)  
