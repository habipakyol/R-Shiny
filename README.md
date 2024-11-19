# R Shiny Sales Dashboard

![R](https://img.shields.io/badge/R-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![Shiny](https://img.shields.io/badge/Shiny-blue?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Dashboard-orange?style=for-the-badge)


A comprehensive sales analytics dashboard built with R Shiny, providing real-time insights into sales performance, customer behavior, and product management.

![GenelBakis](https://github.com/user-attachments/assets/2bfaae1a-5a84-424b-a783-e0b65efa1c14)
![MusteriAnaliz](https://github.com/user-attachments/assets/94c05e99-1d0a-45a4-95be-ffa142916898)
![UrunYonetim](https://github.com/user-attachments/assets/aa29bbe7-e8a8-405a-b66a-f200d401db3d)

## Features

- **General Overview (Genel Bakış)**
  - Total revenue and profit metrics
  - Monthly revenue trend analysis
  - Interactive sales summary table
  - Key performance indicators in value boxes

- **Customer Analysis (Müşteri Analizi)**
  - Age distribution visualization
  - Gender distribution analysis
  - Detailed customer information table
  - Purchase behavior insights

- **Product Management (Ürün Yönetimi)**
  - Real-time stock level monitoring
  - Price distribution analysis
  - Comprehensive product listing
  - Interactive stock visualization

## Dependencies

```R
library(shiny)
library(shinydashboard)
library(DT)
library(ggplot2)
library(dplyr)
library(plotly)
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/r-shiny-sales-dashboard.git
```

2. Install required R packages:
```R
install.packages(c("shiny", "shinydashboard", "DT", "ggplot2", "dplyr", "plotly"))
```

3. Run the application:
```R
shiny::runApp()
```

## Data Structure

The dashboard uses three main data frames:

1. **Sales Data**
   - Date
   - Revenue
   - Profit
   - Category

2. **Customer Data**
   - Customer ID
   - Age
   - Gender
   - Purchase Amount

3. **Product Data**
   - Product ID
   - Name
   - Stock
   - Price

## Usage

1. **General Overview Tab**
   - Monitor total revenue and average profit
   - Track monthly sales trends
   - View detailed sales records

2. **Customer Analysis Tab**
   - Analyze customer demographics
   - Review purchase patterns
   - Export customer data

3. **Product Management Tab**
   - Monitor stock levels
   - Analyze price distributions
   - Manage product inventory

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
