# 🚖 Uber Insights Dashboard

**Uber Insights: Ride Analytics Dashboard**  
A dynamic, interactive Power BI dashboard built to explore Uber booking data worldwide—focusing on booking trends, cancellations, revenue, and customer ratings.

## Purpose  
The Uber Insights Dashboard is a visually engaging and analytical Power BI report designed to help users explore and compare Uber’s operational performance. It highlights booking status breakdowns, vehicle type performance, revenue trends, cancellation reasons, and customer ratings.  

This tool is intended for use by operations managers, data analysts, and business strategists who seek to optimize ride-sharing services and improve customer experience.

## 3. Tech Stack  
The dashboard was built using the following tools and technologies:  
- 📊 **Power BI Desktop** – Main data visualization platform used for report creation  
- 📂 **Power Query** – Data transformation and cleaning layer for reshaping and preparing the data  
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, dynamic visuals, and conditional logic  
- 📝 **Data Modeling** – Relationships established among tables (bookings, vehicles, customers, payments) to enable cross-filtering and aggregation  
- 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews  


## 4. Data Source  
**Source:** csv dataset -> `.ncr_ride_bookings.csv` 

Data includes:  
- Booking status (success, cancelled, ongoing)  
- Vehicle type details (total bookings, average distance traveled)  
- Revenue and payment method breakdowns  
- Customer and driver cancellation reasons  
- Customer ratings across vehicles  


## 5. Features / Highlights  

### • Business Problem  
Ride-sharing platforms like Uber generate millions of bookings daily, yet managers and analysts often lack an intuitive way to track performance across bookings, cancellations, revenue, and customer satisfaction.  

Key questions such as:  
- Which vehicle types generate the most successful bookings?  
- What are the most common cancellation reasons by customers and drivers?  
- Which payment methods dominate revenue?  
- Who are the top customers by booking value?  
… are difficult to answer quickly with raw data.  

### • Goal of the Dashboard  
To deliver an interactive visual tool that:  
- Enables users to explore Uber booking and revenue trends  
- Supports decisions such as driver allocation, payment optimization, and customer engagement strategies  
- Uncovers patterns in cancellations, ratings, and vehicle performance  

### • Walkthrough of Key Visuals  
- **Booking Overview (Top Left)**: Breakdown by booking status, monthly trends, and interactive date slicers  
- **Vehicle Type Preview**: Table showing total bookings, success rate, and average distance traveled  
- **Revenue Overview**: Daily ride distance, most used payment methods, and top 5 customers by booking value  
- **Cancellation Overview**: Reasons for cancellations by customers and drivers, cancel rate %, and interactive filters  
- **Rating Overview**: Average customer ratings across all vehicle types  

### • Business Impact & Insights  
- ⚡ **Operational Efficiency**: Identify peak booking times and optimize driver allocation  
- 💳 **Revenue Strategy**: Understand payment preferences and top customers to tailor promotions  
- ❌ **Service Improvement**: Analyze cancellation reasons to reduce drop-offs and improve reliability  
- ⭐ **Customer Experience**: Track ratings to enhance service quality across vehicle types  

---



## 📂 File Information  
- Development File: `Uber_Insights.pbix`  
- Preview Images: `.png` snapshots of dashboard visuals  

---

## 🚀 How to Use  
1. Open the `.pbix` file in Power BI Desktop  
2. Connect to the Uber dataset  
3. Use interactive slicers to filter by date, vehicle type, and booking status  
4. Explore insights across bookings, revenue, cancellations, and ratings  

---

## 👩‍💻 Author  
Created by **Tanvi** – Data Analyst passionate about building polished, insightful dashboards that drive business impact.


