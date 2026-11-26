# RetailInsight: Sales & Customer Analytics

RetailInsight is a browser-based analytics dashboard for small retailers. It turns sales data into clear views of business performance, top products, customer behaviour and future sales.

## Pages

| Page | What it shows |
|---|---|
| `index.html` | Login screen |
| `dashboard.html` | Business performance overview: revenue, profit and order volume |
| `products.html` | Top-selling products |
| `customers.html` | Customer insights and buying patterns |
| `forecasting.html` | Sales forecasting chart |

## Data

The app works with order-level sales data. `sample_sales_data.csv` shows the expected format:

```csv
order_id,order_date,product_name,customer_id,quantity,price,cost
1001,1/5/2025,iPhone 14,1,2,800,600
```

Revenue (`quantity × price`) and profit (`quantity × (price − cost)`) are calculated from these columns.

## Running

There's no build step. Clone the repo and open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Tech

HTML5 · CSS3 · JavaScript · Chart.js. The interface was prototyped in Figma.

---
Author: [Mujahed Alabed](https://github.com/Muj-04)
