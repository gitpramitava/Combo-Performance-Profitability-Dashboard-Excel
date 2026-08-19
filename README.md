# Combo-Performance-Profitability-Dashboard-Excel
Excel dashboard analyzing 360+ food-service orders — combo profitability, branch/shift adoption, and a live pricing simulator. Built during Advanced Excel Internship, Ivy Professional School
# Combo Performance & Profitability Dashboard

An interactive Excel dashboard built to help a food-service business understand combo-order performance, profitability, and ordering patterns across branches and shifts — and to test pricing decisions in real time.

**Context:** Built as the capstone project for the Advanced Excel Internship at Ivy Professional School (18 June – 17 July 2026).

## Dataset

- 360 orders across 3 branches (Head Office Café, Plant 1 Canteen, Plant 2 Canteen) and 3 shifts (Breakfast, Lunch, Dinner)
- 924 order-line records
- 19 menu items across Hot Meals, Beverages, Snacks, and Desserts

## What the dashboard does

1. **Combo performance summary** — total combo orders, combo share of all orders, average ticket size, average gross profit per combo
2. **Combo vs. Single comparison** — ticket size, cost, gross profit, and margin, side by side
3. **Branch-level adoption analysis** — surfaced a 2x gap in combo adoption between branches (13.8% at Plant 1 Canteen vs. 28.9% at Head Office Café)
4. **Shift-level adoption analysis** — combo adoption compared across Breakfast, Lunch, and Dinner
5. **Item-category ranking** — most frequently ordered item-category pairings, ranked by order count
6. **Interactive Branch/Shift filters** — the full dashboard updates live via slicers, without rebuilding any report
7. **Live profitability simulator** — select any Hot Meal + Beverage, enter a discount %, and instantly see net selling price, food cost, gross profit, margin, and live inventory stock — fully formula-driven (INDEX/MATCH), no manual entry

## Key findings

- Combo orders made up **23.9%** of all orders but drove a **74% higher average ticket size** (₹544 vs. ₹313) than single orders
- Combo orders produced **75% higher gross profit per order** (₹279 vs. ₹159) while holding nearly identical margin (50.8% vs. 50.9%) — the business case for combo-first promotion
- Combo adoption varies sharply by branch, pointing to where promotional focus would have the highest ROI

## Tools & techniques

Advanced Excel — PivotTables, INDEX/MATCH, COUNTIFS, Data Validation (dropdowns), Slicers, dashboard design

## File

`PramitavaDas_Answers_Day7.xlsx` — open the **"Combo Performance Dashboard"** sheet to view the full interactive dashboard.
