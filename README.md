# Hotel Revenue Analytics Dashboard 🏨

A comprehensive Power BI analytics dashboard for hotel booking and revenue analysis, developed as a Final Year Project at GHRCE (G H Raisoni College of Engineering).

## 📊 Project Overview

This Power BI project provides in-depth analytics and visualization of hotel booking data, enabling data-driven decision-making for hotel revenue management. The dashboard analyzes booking patterns, revenue trends, occupancy rates, and customer behavior across different hotels and room types.

## 🎯 Key Features

- **Revenue Analysis**: Track total revenue, revenue per available room (RevPAR), and revenue trends over time
- **Booking Analytics**: Monitor booking patterns, cancellation rates, and successful bookings
- **Occupancy Insights**: Analyze room occupancy rates and capacity utilization
- **Performance Metrics**: Compare performance across different hotels and room types
- **Time-based Analysis**: Identify seasonal trends, weekday vs weekend patterns, and peak booking periods
- **Interactive Dashboards**: Drill-down capabilities and dynamic filtering for detailed analysis

## 🗂️ Data Model Structure

The project follows a star schema design with the following tables:

### Dimension Tables
- **dim_date**: Date dimension with calendar attributes for time-based analysis
- **dim_hotels**: Hotel information including properties and locations
- **dim_rooms**: Room types and categories information
- **Week_day**: Weekday classification for pattern analysis

### Fact Tables
- **fact_bookings**: Detailed booking records with guest information and booking status
- **fact_aggregated_bookings**: Pre-aggregated booking metrics for performance optimization

### Measure Tables
- **resource_measures**: Custom DAX measures for KPIs and calculations

## 📈 Key Metrics & KPIs

The dashboard calculates and visualizes various metrics including:

- Total Revenue
- Revenue Per Available Room (RevPAR)
- Occupancy Percentage
- Average Daily Rate (ADR)
- Total Bookings
- Successful Bookings
- Cancellation Rate
- Capacity Utilization
- Daily Sellable Room Nights (DSRN)
- Realization Percentage

## 🛠️ Technical Details

- **Tool**: Microsoft Power BI Desktop
- **Data Model**: Star Schema
- **File Format**: .pbix (Power BI Desktop file)
- **Version**: Power BI Desktop (Compatible with latest versions)

## 📁 Project Structure

```
GHRCE-Final_Year_Project.pbix
├── Data Model (Star Schema)
│   ├── Dimension Tables
│   │   ├── dim_date
│   │   ├── dim_hotels
│   │   ├── dim_rooms
│   │   └── Week_day
│   ├── Fact Tables
│   │   ├── fact_bookings
│   │   └── fact_aggregated_bookings
│   └── Measure Tables
│       └── resource_measures
├── Relationships
├── DAX Measures
└── Report Pages/Dashboards
```

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop (Download from [Microsoft Power BI](https://powerbi.microsoft.com/desktop/))
- Windows 10/11 or compatible OS

### Installation & Usage

1. **Download Power BI Desktop**
   ```
   Visit: https://powerbi.microsoft.com/desktop/
   ```

2. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/GHRCE-Final_Year_Project.git
   ```

3. **Open the Project**
   - Launch Power BI Desktop
   - Open the `GHRCE-Final_Year_Project.pbix` file
   - Wait for data to load and relationships to initialize

4. **Explore the Dashboard**
   - Navigate through different report pages
   - Use slicers and filters to drill down into specific data
   - Hover over visuals for detailed tooltips
   - Click on visual elements to cross-filter data

## 📊 Dashboard Pages

The project includes multiple report pages covering:

1. **Overview Dashboard**: High-level KPIs and trends
2. **Revenue Analysis**: Detailed revenue breakdown and trends
3. **Booking Analysis**: Booking patterns and behavior
4. **Property Performance**: Hotel-wise performance comparison
5. **Trends & Patterns**: Time-based analysis and seasonality

## 🔄 Data Refresh

To update the data:
1. Click on "Refresh" in the Home tab
2. Ensure data source connections are properly configured
3. Update credentials if prompted

## 💡 Use Cases

- **Hotel Management**: Monitor overall performance and identify improvement areas
- **Revenue Management**: Optimize pricing strategies based on demand patterns
- **Operations Planning**: Staff and resource allocation based on occupancy trends
- **Marketing Analysis**: Identify high-performing periods for promotional campaigns
- **Strategic Planning**: Make data-driven decisions for business growth

## 🎓 Academic Context

This project was developed as a Final Year Project at **G H Raisoni College of Engineering (GHRCE)** to demonstrate practical application of:
- Business Intelligence concepts
- Data modeling and database design
- Data visualization best practices
- Analytics and reporting
- Decision support systems

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

## 📝 License

This project is developed for educational purposes as part of academic curriculum.

## 👥 Authors

- **Chinmay Randive** - *Final Year Student, GHRCE*

## 🙏 Acknowledgments

- G H Raisoni College of Engineering for providing the opportunity
- Project guide and faculty mentors
- Microsoft for Power BI Desktop
- Hospitality industry for domain insights

## 📸 Screenshots

<img width="1259" height="739" alt="image" src="https://github.com/user-attachments/assets/8b8aa7e3-849e-4b1c-a5f0-5a4307053cd3" />
<img width="1254" height="742" alt="image" src="https://github.com/user-attachments/assets/c0d048f5-991b-4977-81d9-019525059ca1" />
<img width="1253" height="745" alt="image" src="https://github.com/user-attachments/assets/b7e295a7-7e7e-46cd-9313-e5f8711b5c53" />


---

**Note**: This is an academic project created for learning purposes. The data used may be sample/mock data for demonstration.

