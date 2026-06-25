# Chart Selection Justification

## 1. Sales Trend View

### What question does this chart answer?
How are sales changing over time?

### Why is this chart type appropriate?
A line chart is the most effective way to display trends over time. It helps identify growth patterns, seasonal fluctuations, and changes in sales performance.

### Fields Used
- Order Date (Month) on X-axis
- Sales on Y-axis
- Region used as a filter

### Design Principle Applied
- Clear visualization of trends
- Minimal clutter
- Easy interpretation

### Mistake Avoided
Avoided using pie charts or bar charts for time-series data because they do not clearly show trends over time.

---

## 2. Regional Performance View

### What question does this chart answer?
Which region generates the highest sales?

### Why is this chart type appropriate?
A horizontal bar chart allows easy comparison of sales performance across regions and quickly highlights top-performing and underperforming areas.

### Fields Used
- Region
- Sales
- Color based on sales value
- Region filter

### Design Principle Applied
- Easy comparison across categories
- Clear labeling
- Consistent color usage

### Mistake Avoided
Avoided using pie charts because comparing multiple regional values is difficult in pie charts.

---

## 3. Category Profitability View

### What question does this chart answer?
Which product categories and sub-categories contribute most to profit?

### Why is this chart type appropriate?
Bar charts provide accurate comparison of profitability across categories and help identify the strongest and weakest product groups.

### Fields Used
- Category
- Sub Category
- Profit
- Profit Margin used for color

### Design Principle Applied
- Hierarchical analysis
- Meaningful use of color
- Clear profit comparison

### Mistake Avoided
Avoided overly complex visualizations that make profit comparisons difficult.

---

## 4. Customer Segment Analysis View

### What question does this chart answer?
Which customer segment contributes the highest sales?

### Why is this chart type appropriate?
Bar charts clearly compare sales performance across customer segments and support quick business decision-making.

### Fields Used
- Customer Segment
- Sales
- Color based on sales values

### Design Principle Applied
- Readable labels
- Easy comparison
- Consistent formatting

### Mistake Avoided
Avoided 3D charts and decorative visuals that could distort interpretation.

---

## 5. Shipping Performance View

### What question does this chart answer?
Which shipping modes experience longer delivery times?

### Why is this chart type appropriate?
A stacked bar chart allows comparison of average delivery days while also displaying delay categories.

### Fields Used
- Ship Mode
- Average Delivery Days
- Shipping Delay Bucket used for color

### Design Principle Applied
- Visual comparison of delays
- Consistent color coding
- Operational performance focus

### Mistake Avoided
Avoided using tables because visual comparisons are easier with charts.

---

## 6. KPI Cards

### What question does this chart answer?
What are the key business performance metrics at a glance?

### Why is this chart type appropriate?
KPI cards provide executives with an immediate summary of overall business performance.

### KPIs Displayed
- Total Sales
- Total Profit
- Return Rate

### Design Principle Applied
- Strong visual hierarchy
- Large readable numbers
- Positioned at the top of the dashboard

### Mistake Avoided
Avoided placing important summary metrics inside charts where they may be overlooked.

---

# Dashboard Design Principles Applied

## Correct Chart Selection
Each chart type was selected based on the business question it answers.

## Clear Hierarchy
KPI cards are placed at the top, followed by trend analysis and supporting performance views.

## Minimal Clutter
Only essential charts, labels, legends, and filters are included.

## Consistent Color Usage
A consistent blue color palette is used throughout the dashboard to improve readability and maintain a professional appearance.

## Proper Labels
All charts include descriptive titles and axis labels.

## Appropriate Sorting
Regional and category views are organized to improve comparison and readability.

## Useful Filters
The dashboard includes interactive filters that allow users to analyze specific regions and business segments.

## Avoidance of Misleading Scales
Charts use appropriate scales and accurate representations of data.

## Focus on Business Interpretation
The dashboard focuses on actionable business insights rather than decorative visual elements.
