[README.md](https://github.com/user-attachments/files/26326180/README.md)
# Pricing Optimization for Burger Gram

A data analytics capstone project submitted as part of the Business Data Management (BDM) course at IIT Madras. The project analyzes one month of real sales data from Burger Gram, a small fast-food shop in Gurugram, Haryana, and provides data-driven recommendations to improve pricing, revenue, and inventory management.

---

## Business Context

Burger Gram is a B2C fast-food shop operating in Sarhaul Village, Sector-18, Gurugram. Despite a commitment to quality and affordable pricing, the business faced two core challenges:

- Raw material wastage due to underperforming and zero-demand menu items
- Suboptimal pricing — high-demand items were priced too low, limiting profit potential

---

## Objective

Analyze 30 days of sales data (June 2023) to:

1. Identify best and worst performing products and categories
2. Recommend price increases for high-demand items
3. Identify zero-sales items for menu removal
4. Propose inventory and pricing strategies to improve net profitability

---

## Dataset

| Property | Details |
|---|---|
| Source | Primary data collected from the business owner |
| Period | June 1, 2023 to June 30, 2023 |
| Total Orders | 2,173 units sold |
| Total Revenue | Rs. 1,69,717 |
| Avg Daily Sales | 72.43 units |
| Avg Daily Revenue | Rs. 5,657 |
| Menu Items | 70+ food products across 11 categories |

---

## Tools Used

- Microsoft Excel — data cleaning, pivot tables, VLOOKUP, charts (line, bar, pie, Pareto)

---

## Project Structure

```
bdm-capstone-burger-gram/
│
├── BG_Main_Data.xlsx                  # Raw and processed sales and menu data
├── Burger_Gram_Presentation.pptx      # 10-slide presentation of analysis and recommendations
├── Final_Submission.pdf               # Full written report with methodology and findings
└── README.md
```

---

## Analysis Performed

**Sales Analysis**
- Day-wise sales trend — peak: 104 units on 4 June, low: 46 units on 28 June
- Product-wise sales ranking using pivot tables
- Category-wise sales distribution

**Revenue Analysis**
- Day-wise revenue — peak: Rs. 8,309, low: Rs. 3,410
- Product-wise revenue share
- Pareto chart identifying top 7 revenue-driving items

**Inventory Optimization**
- Identified 8 zero-sales items using VLOOKUP across menu and sales sheets
- Identified least-selling items (below 0.05% contribution) for menu streamlining
- Identified poor-performing categories (below 5% share)

---

## Key Findings

| Finding | Detail |
|---|---|
| Top selling product | Aloo Tikki Burger (15.65% of sales) |
| Top revenue product | Mix Veg Pizza Small (12.43% of revenue) |
| Top revenue category | Pizza (44% of total revenue) |
| Zero-sales items identified | 8 items including Veg King Burger with Cheese, Chicken Pizza Large |
| Worst performing items | 7 items each at 0.05% contribution |
| Burger vs Pizza insight | Burgers: 27% sales but only 20% revenue — Pizza: 30% sales but 44% revenue |

---

## Recommendations

1. **Price increase on high-demand items** — Aloo Tikki Burger (Rs. 50), Mix Veg Pizza Small (Rs. 79), and Cold Drink Small are underpriced relative to their demand; a nominal increase directly improves net profit
2. **Remove zero-sales items** — 8 items have zero contribution; removing them reduces raw material costs with no revenue impact
3. **Trim low-performing menu** — Items below 0.05% share account for only 0.35% of sales combined; streamlining improves operational focus
4. **Introduce combo pricing** — Pizza + Fries + Cold Drink combos can increase average order value
5. **B2B partnerships** — Bulk pizza sales to event organizers as a new revenue channel
6. **Structured data tracking** — Recommended the owner maintain a spreadsheet covering costs, inventory, and expenses beyond just sales records

---

## Limitations

- Analysis is based on a single month of data; broader dataset would yield more robust insights
- External factors such as seasonality, competition, and local events are not accounted for
- Competitive pricing analysis was outside the scope of this project

---

## Author

**Jeet Kumar** | IIT Madras BS Degree Program (Roll: 21f3002041)  
[GitHub](https://github.com/JayZCrash2000) | [LinkedIn](https://www.linkedin.com/in/jeet-kumar-a912aa219/)
