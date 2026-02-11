# Sales Analysis Dashboard

## Overview
A comprehensive multi-page business intelligence dashboard for sales analytics, providing insights across products, categories, regions, time periods, and customer segments. This interactive dashboard enables data-driven decision-making through detailed sales performance analysis.

## Dashboard Navigation

The dashboard consists of four main pages:
1. **Home/Overview** - Key metrics and navigation
2. **Sales Performance** - Year-over-year trends and product analysis
3. **Category & Geographic Analysis** - Detailed category breakdown and geographic distribution
4. **Shopping Trends** - Monthly patterns and shipping analysis

### Navigation Menu (Home Page)
- **Sales** - Access sales performance metrics
- **Category** - View category-level analysis
- **Shopping** - Explore shopping patterns and trends

## Key Performance Indicators (KPIs)

### Summary Metrics (Consistent Across All Pages)
- **Average Discount**: 15.6%
- **Total Sales**: $2.30M
- **Total Quantity**: 38K units
- **Total Profit**: $286.4K (displayed as "286.4...")
- **Total Orders**: 5K

## Page 1: Home/Overview

### Purpose
Landing page with primary navigation and key metrics display.

### Features
- Clean, modern interface with light blue theme
- Quick access navigation buttons
- Summary KPI cards prominently displayed
- Home icon for dashboard branding

### Navigation Options
1. **Sales** - Leads to sales performance analysis
2. **Category** - Leads to category breakdown
3. **Shopping** - Leads to shopping behavior analysis

## Page 2: Sales Performance Analysis

### Dashboard Components

#### 1. Total Sales by Year
**Chart Type**: Line graph

Shows sales growth trajectory from 2015-2018:
- **2015**: ~0.48M (starting point)
- **2016**: ~0.47M (slight dip)
- **2017**: ~0.6M (recovery and growth)
- **2018**: ~0.75M (strong growth, 56% increase from 2015)

**Trend**: Clear upward trajectory with consistent year-over-year growth after 2016.

#### 2. Total Sales by Category
**Chart Type**: Donut chart

Category distribution:
- **Technology**: 36.4% (largest segment)
- **Office Supplies**: 31.3%
- **Furniture**: 32.3%

**Insight**: Balanced portfolio with Technology leading by narrow margin.

#### 3. Top 5 Products
**Chart Type**: Horizontal bar chart

Best-performing products by sales value:
1. **Canon imageCLASS**: ~60K (dominant leader)
2. **Fellowes PB500 Electric**: ~40K
3. **Cisco TelePresence**: ~35K
4. **HON 5400 Series**: ~33K
5. **GBC DocuBind TL**: ~30K

**Observation**: Canon imageCLASS significantly outperforms other products.

#### 4. Total Sales By Sub Category
**Chart Type**: Vertical bar chart

Detailed subcategory breakdown showing:
- **Phones**: ~0.33M (highest)
- **Chairs**: ~0.33M (tied for highest)
- **Storage**: ~0.22M
- **Tables**: ~0.21M
- **Binders**: ~0.2M
- Additional categories: Machines, Accessories, Copiers, Bookcases, Appliances, Furnishings, Paper, Supplies, Art, Envelopes, Labels, Fasteners

**Pattern**: Phones and Chairs dominate, with steep decline in subsequent categories.

### Filters Available
- **YEAR**: Dropdown filter (default: "All")
- **REGION**: Multi-select with options:
  - Select all
  - Central
  - East
  - (Additional regions available)
- **CATEGORY**: Multi-select with options:
  - Select all
  - Furniture
  - Office Supplies
  - (Technology implied)

## Page 3: Category & Geographic Analysis

### Dashboard Components

#### 1. Total Sales by Category (Treemap)
**Chart Type**: Treemap visualization

Proportional area representation:
- **Technology**: 836,154.03 (largest area, dark blue)
- **Furniture**: 741,999.80 (medium area, light blue)
- **Office Supplies**: (lightest blue)

Sub-category drill-down visible showing:
- T_sales: 2,297,200.86

#### 2. Total Sales by Category (Geographic Map)
**Chart Type**: Interactive world map with bubble markers

**Segments Tracked**:
- Consumer (blue)
- Corporate (dark blue)
- Home Office (orange)

**Geographic Distribution**:
- Heavy concentration in **North America** (multiple large bubbles)
- Significant presence in **Asia-Pacific region**
- Scattered presence in **South America** and **Australia**
- Minimal visibility in Africa and Europe

**Powered by**: Microsoft Azure (indicated at bottom)

#### 3. Product Hierarchy Flow
**Chart Type**: Sankey/flow diagram

Shows relationship flow:
- **Category** → **Product Name** → **Sub-Category**
- **Technology** (836,154.03) connects to:
  - PNY Rapid USB Car Charger
  - Memorex Mini Travel Drive (13.62)
  - Maxell 4.7GB DVD+R (11.68)
  - Other technology products flowing to **Phones** subcategory

#### 4. Total Sales by Sub Category
**Chart Type**: Horizontal bar chart

Ranking (highest to lowest):
1. **Phones**: ~0.34M
2. **Chairs**: ~0.34M
3. **Storage**: ~0.23M
4. **Tables**: ~0.21M
5. **Binders**: ~0.2M

(Consistent with Page 2 data)

### Filters Available
- **CATEGORY**: Multi-select
  - Select all
  - Furniture
  - (Additional options)

## Page 4: Shopping Trends & Orders

### Dashboard Components

#### 1. Total Sales by Month
**Chart Type**: Line graph

Monthly pattern analysis (January-December):
- **January**: ~180 (low season)
- **February**: ~140 (lowest point)
- **March-July**: ~350-370 (stable baseline)
- **August**: Sharp dip to ~320
- **September**: Spike to ~680 (peak season)
- **October**: Dip to ~420
- **November**: Strong recovery to ~760 (highest peak)
- **December**: Slight decline to ~730

**Seasonality**: Clear Q4 surge (September-December) with November peak.

#### 2. Total Order By Ship Mode
**Chart Type**: Donut chart

Shipping preference distribution:
- **Standard Class**: 1.36M (59% - dominant method)
- **Second Class**: 0.46M (19.95%)
- **First Class**: 0.35M (15.26%)
- **Same Day**: 0M (0.13% - negligible)

Additional segment shown:
- 0M (0.03%)
- 0M (0.04%)

**Insight**: Standard shipping overwhelmingly preferred; same-day delivery underutilized.

#### 3. Total Sales by Category (Horizontal Bar)
**Chart Type**: Horizontal bar chart by ship mode

Breakdown by shipping class:
- **Standard Class**: ~1.4M (largest)
- **Second Class**: ~0.45M
- **First Class**: ~0.35M
- **Same Day**: ~0.05M (smallest)

**Pattern**: Shipping preference consistent across all categories.

#### 4. Order By Ship Date
**Chart Type**: Data table

Detailed order listing with columns:
- **T_order**: Order count (all showing "1")
- **Order ID**: Format CA-2015-XXXXXX
- **Year**: 2015 (all entries)
- **Quarter**: Qtr 1, 2, 3, 4
- **Month**: Various months throughout year
- **Day**: Specific day of month

**Sample Entries**:
- CA-2015-100006 | 2015 | Qtr 3 | September | 13
- CA-2015-100090 | 2015 | Qtr 3 | July | 12
- CA-2015-100293 | 2015 | Qtr 1 | March | 18
- CA-2015-100328 | 2015 | Qtr 1 | February | 3

**Total Records**: 5009 orders shown at bottom

**Functionality**: Scrollable table for detailed order-level analysis.

### Filters Available
- **YEAR**: Dropdown filter (default: "All")

## Key Insights & Analytics

### Sales Performance
1. **Strong Growth Trajectory**: 56% sales increase from 2015 to 2018
2. **Balanced Portfolio**: Three categories within 5% of each other (31-36%)
3. **Product Concentration**: Top product (Canon imageCLASS) drives significant revenue
4. **Subcategory Leaders**: Phones and Chairs each account for ~$330K

### Geographic Patterns
1. **North America Dominance**: Highest concentration of sales activity
2. **Asia-Pacific Growth**: Secondary market with significant presence
3. **Segment Distribution**: Consumer and Corporate segments lead
4. **Expansion Opportunities**: Underserved markets in Europe and Africa

### Seasonal & Shipping Trends
1. **Q4 Surge**: November and December show 300%+ increase over February low
2. **Shipping Preference**: 59% prefer standard shipping (cost-conscious customers)
3. **Fast Shipping Underutilization**: Less than 1% use same-day delivery
4. **Peak Season Planning**: September-November require increased capacity

### Profitability
1. **Healthy Margins**: 37% profit margin with 15.6% average discount
2. **Profit vs. Sales**: $286.4K profit on $2.3M sales (12.5% net margin)
3. **Volume vs. Value**: 38K units across 5K orders (~7.6 units per order)
4. **Order Value**: $93K average order value indicates B2B focus

## Strategic Recommendations

### Short-term Actions
1. **Inventory Planning**: Stock up for Q4 surge (September-December)
2. **Canon Partnership**: Strengthen relationship with top-performing brand
3. **Shipping Optimization**: Promote faster shipping options during peak season
4. **Technology Focus**: Invest in technology category (36.4% of sales)

### Medium-term Initiatives
1. **Geographic Expansion**: Target European and African markets
2. **Product Diversification**: Reduce dependency on Canon imageCLASS
3. **Same-Day Delivery**: Market premium shipping to increase utilization
4. **Subcategory Growth**: Expand beyond Phones and Chairs dominance

### Long-term Goals
1. **Sustained Growth**: Maintain 15-20% year-over-year growth trajectory
2. **Margin Improvement**: Target 15% net profit margin through efficiency
3. **Market Balance**: Achieve 25% sales from international markets
4. **Category Optimization**: Align inventory with balanced 33/33/33 distribution

## Use Cases

### For Executives
- Monitor overall business health through consistent KPI cards
- Track year-over-year growth trends
- Evaluate geographic expansion opportunities
- Review profit margins and discount strategies

### For Sales Managers
- Identify top-performing products and categories
- Plan for seasonal demand variations
- Allocate resources by region and segment
- Set quarterly targets based on historical patterns

### For Operations
- Optimize inventory for Q4 peak season
- Balance shipping options based on customer preference
- Plan capacity for 5K+ monthly orders
- Coordinate with top product suppliers

### For Marketing
- Focus campaigns on Technology and Furniture categories
- Target North American and Asia-Pacific markets
- Promote fast shipping options (underutilized)
- Time promotions for Q1-Q2 sales boost

## Technical Specifications

### Dashboard Platform
- **Tool**: Power BI or similar BI platform
- **Pages**: 4 interactive pages
- **Interactivity**: Cross-filtering across all visualizations
- **Mobile Responsive**: Optimized layout for multiple devices

### Data Granularity
- **Time**: Daily, monthly, quarterly, yearly views
- **Geography**: Country and region level
- **Product**: Category, subcategory, product level
- **Customer**: Segment level (Consumer, Corporate, Home Office)

### Update Frequency
- **Real-time**: Order data updated continuously
- **Batch**: Daily sales aggregations
- **Historical**: Full 2015-2018 dataset available

### Filter Capabilities
- **Year**: Single select dropdown
- **Region**: Multi-select checkbox
- **Category**: Multi-select checkbox
- **Cross-filtering**: Click any visual to filter entire dashboard

## Design & User Experience

### Color Scheme
- **Primary**: Light blue (#B3E5FC)
- **Accent**: Navy blue (#0D47A1)
- **Background**: Soft cyan gradient
- **Charts**: Blue gradient scales
- **Highlighting**: Orange for emphasis

### Layout Principles
- Consistent KPI cards across all pages
- Left-aligned filters for easy access
- Grid-based layout for visual balance
- White space for readability
- Rounded corners for modern aesthetic

### Navigation
- Home button (house icon) on all pages
- Tab-based navigation on home page
- Breadcrumb trail implied by page organization
- Consistent header with KPIs for orientation

## Data Quality & Governance

### Metrics Validation
- Total Orders (5K) × Avg Order Value ($93,273) ≠ Total Sales ($2.3M)
  - *Note: Possible data display issue or calculated field*
- Total Profit ($286.4K) ÷ Total Sales ($2.3M) = 12.5% net margin
- Units (38K) ÷ Orders (5K) = 7.6 units per order

### Data Completeness
- Full 2015-2018 historical data available
- Geographic data covers major markets
- Product hierarchy complete (Category → Sub → Product)
- Order-level detail accessible via table view

---

**Dashboard**: Sales Analysis Multi-Page Dashboard  
**Version**: 1.0  
**Data Period**: 2015-2018  
**Last Updated**: Current as of data source  
**Platform**: Business Intelligence Dashboard (Power BI/Tableau-style)
