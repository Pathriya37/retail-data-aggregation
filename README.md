# Data Aggregation - Practice Sheet (Retail Dataset)

Retail sales dataset par Pandas aggregation ke 30 questions, Google Colab par banaya hai.

## Dataset
- 120 sales records, 10 din, 3 branches (Mathura, Agra, Aligarh), 4 products (Notebook, Bottle, Backpack, Headphones)
- Columns: `record_id`, `day`, `branch`, `product`, `units_sold`, `target_units`, `unit_price`, `unit_cost`, `discount_pct`, `delivery_minutes`, `customer_rating`
- `delivery_minutes` (9) aur `customer_rating` (10) me kuch values missing hain

## Sections
- **Section A:** Q1 se Q15 (`groupby` with `sum`, `mean`, `max`, `min`, `count`)
- **Section B:** Q16 se Q25 (`agg()`, `size()` vs `count()`, user-defined function, `as_index=False`, group iteration, quantile, hierarchical index, `pivot_table`)
- **Section C:** Q26 se Q30 (`transform()`, `apply()`, weighted average, top-N per group, `pd.qcut()`)

## Files
| File | Description |
|------|-------------|
| `retail_data_aggregation.ipynb` | Colab notebook (har question ka alag cell, output ke saath) |
| `retail_data_aggregation.py` | Same code, normal Python file |
| `retail_data.csv` | Dataset |

## Kaise run karein
1. `retail_data_aggregation.ipynb` ko [Google Colab](https://colab.research.google.com) me kholo
2. `Runtime -> Run all` dabao

Dataset notebook ke pehle cell me hi diya hua hai, alag se file upload karne ki zarurat nahi.

Local me chalane ke liye:

```bash
pip install pandas numpy
python retail_data_aggregation.py
```
