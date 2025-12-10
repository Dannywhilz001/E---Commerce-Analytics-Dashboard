# E-Commerce Analytics Dashboard

A comprehensive business intelligence dashboard for e-commerce analytics, providing executive insights, customer segmentation, product performance tracking, and temporal intelligence across your entire business operations.

[Executive Summary](https://ibb.co/0R7bP43p)
[Customer Analytics](https://ibb.co/4wDC00rv)
[Product Performance](https://ibb.co/VWQfhv5j)
[Time Intelligence](https://ibb.co/mFXb6kTr) 

## 📊 Overview

This advanced analytics dashboard transforms raw e-commerce data into actionable insights across four key dimensions: Executive Summary, Customer Analytics, Product Performance, and Time Intelligence. Built for data driven decision making, it provides real time visibility into business performance with intuitive visualizations and KPI tracking.

**Key Metrics:**
- £8.62M total revenue with 1404% growth
- 19K orders from 4K unique customers
- £465 average order value
- 65.57% repeat purchase rate
- 100% retention rate

## ✨ Features

### 🎯 Executive Summary
- **Real-time KPIs**: Total revenue, orders, unique customers, and average order value with period-over-period comparison
- **Revenue Trend Analysis**: Monthly revenue progression with trend identification
- **Growth Rate Monitoring**: Month-over-month growth rates with automatic peak detection
- **Geographic Performance**: Top countries by revenue contribution
- **Product Rankings**: Top 10 products by revenue with visual comparison
- **Yearly Distribution**: Order volume breakdown by year
- **AI-Powered Insights**: Automated business intelligence highlighting growth acceleration, peak performance, and opportunities

### 👥 Customer Analytics
- **RFM Segmentation**: Recency, Frequency, Monetary analysis with visual bubble chart
- **Customer Lifetime Value**: £1.99K CLV with 207% growth tracking
- **Retention Analytics**: Cohort-based retention heatmap showing customer behavior over time
- **Segment Distribution**: Pie chart visualization of Champions, Loyal, At Risk, Lost, and Other segments
- **Revenue Run Rate**: Projected annual revenue based on current performance (£10.1M)
- **Acquisition Cohort Analysis**: LTV tracking by customer acquisition month

### 📦 Product Performance
- **Inventory Overview**: 5M total products with new product tracking
- **Pricing Analytics**: £2.99 average unit price analysis
- **Category Performance**: Treemap visualization showing Bags, Lighting, Home Décor, Kitchen, Vintage, and Christmas categories
- **Revenue & Unit Analysis**: Dual-axis visualization of top products by revenue and quantity sold
- **Price-Quantity Matrix**: Scatter plot analysis across product categories
- **Contribution Waterfall**: Visual breakdown of revenue increases and decreases by product

### ⏰ Time Intelligence
- **Year-over-Year Comparison**: Monthly revenue comparison between 2010 and 2011
- **Day of Week Analysis**: Performance patterns showing Thursday peak at £1.81M
- **Hourly Patterns**: Heatmap revealing 9AM-5PM weekday peak (3PM optimal on Friday at £47.3K)
- **Quarterly Progression**: Q1 to Q4 growth trajectory (£1.53M to £2.53M)
- **Seasonal Insights**: Automated detection of holiday season performance spikes

## 📥 Installation

```bash
# Clone the repository
git clone https://github.com/Dannywhilz001/e-commerce-analytics-dashboard.git

# Navigate to project directory
cd ecommerce-analytics-dashboard

# Install dependencies
npm install
# or
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env

# Configure database connection
# Edit .env with your database credentials

# Run database migrations
npm run migrate
# or
python manage.py migrate

# Start the development server
npm run dev
# or
python app.py
```

## ⚙️ Configuration

Create a `.env` file in the root directory:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/ecommerce_db
REDIS_URL=redis://localhost:6379
API_PORT=3000
NODE_ENV=development
ANALYTICS_REFRESH_INTERVAL=300000
```

## 📊 Data Requirements

### Input Data Structure

```json
{
  "orders": {
    "order_id": "string",
    "customer_id": "string",
    "order_date": "datetime",
    "total_amount": "decimal",
    "country": "string",
    "items": "array"
  },
  "products": {
    "product_id": "string",
    "name": "string",
    "category": "string",
    "price": "decimal",
    "quantity": "integer"
  },
  "customers": {
    "customer_id": "string",
    "acquisition_date": "datetime",
    "segment": "string"
  }
}
```

## 🚀 Usage

### Dashboard Navigation

1. **Executive Summary Tab**: Get a high-level overview of business performance
2. **Customer Analytics Tab**: Deep dive into customer behavior and segmentation
3. **Product Performance Tab**: Analyze product categories and individual SKU performance
4. **Time Intelligence Tab**: Identify temporal patterns and optimize operations

### Key Workflows

**Monthly Business Review:**
```
1. Check Executive Summary KPIs
2. Review monthly growth rate trends
3. Analyze top performing products
4. Assess customer retention metrics
5. Export insights for stakeholder presentation
```

**Customer Retention Strategy:**
```
1. Navigate to Customer Analytics
2. Review RFM segmentation bubble chart
3. Identify "At Risk" segment (27.1%, £890K opportunity)
4. Analyze cohort retention heatmap
5. Design targeted re-engagement campaigns
```

**Inventory Optimization:**
```
1. Go to Product Performance
2. Check category performance treemap
3. Review top 10 products revenue & units
4. Analyze price vs quantity scatter plot
5. Adjust inventory based on contribution waterfall
```

## 📈 Key Insights & Recommendations

### Growth Opportunities
- **September Acceleration**: 47.91% MoM growth indicates successful marketing campaigns
- **Champion Customers**: Top 31% generating 58% of revenue
- **Product Focus**: Regency Cake Stand (£143K) and White Hanging Heart (£100K) are star performers
- **Seasonal Strategy**: November peak (£1.16M) shows strong holiday performance

### Risk Mitigation
- **At Risk Segment**: 27.1% of customers (£890K recovery opportunity)
- **Weekend Underperformance**: Sundays at £757K (58% below Thursday peak)
- **Average Unit Price**: £2.99 suggests potential for premium product introduction
- **Units Per Order**: 270.72 indicates bulk ordering opportunity

### Operational Optimization
- **Staff Scheduling**: Prioritize 9AM-5PM weekday coverage
- **Marketing Timing**: Focus campaigns on mid-week afternoons (3PM Friday peak)
- **Inventory Planning**: Prepare for Q4 seasonal surge (65% growth from Q3)
- **Geographic Expansion**: Netherlands (£285K) and Eire (£262K) show potential

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow existing code style and conventions
- Add unit tests for new features
- Update documentation for API changes
- Ensure all tests pass before submitting PR

## 👨‍💻 Authors

- **Oladotun Olawale** - *Initial work* - [GitHub](https://github.com/Dannywhilz001)

## 🙏 Acknowledgments

- Inspired by modern BI platforms like Tableau and Power BI
- Built with best practices from data analytics community
- Special thanks to contributors and beta testers

**Built with ❤️ for data driven e-commerce businesses**

*Last Updated: December 2025*
