# Retail Sales Analysis — 2025

A guided Excel portfolio project using 1,200 fictional orders.

## Purpose

Compare monthly, regional and product sales performance,
and present the results in an interactive dashboard.

## Tools and skills

- Power Query: importing data and preparing calculated columns.
- Excel formulas: summary measures and data-quality checks.
- PivotTables: monthly, regional and product comparisons.
- Charts and a region slicer: interactive reporting.

## Main findings

- Revenue: £109,800.
- Direct product cost: £65,880.
- Gross profit: £43,920.
- Gross profit margin: 40%.
- Orders: 1,200; units sold: 5,446.
- West generated the highest regional revenue: £28,460.
- Coffee generated £83,010 revenue; Tea generated £26,790.
- October had the highest revenue (£10,620);
  September had the lowest (£7,200).

## Files

- [Source data](data/orders_synthetic_1200.csv)
- [Excel workbook](workbook/retail_project.xlsx)
- [Dashboard PDF](reports/Retail_Dashboard_2025.pdf)

## Quality checks

Checked order ID uniqueness, missing quantities, prices and costs,
and zero or negative quantities. Confirmed that total revenue
minus direct cost equals gross profit.

## Using the workbook

The region slicer filters the three charts.
The summary figures always show totals for all regions.

To refresh on another computer, update the Power Query Source
step to point to the supplied CSV's local location.
Refresh the query first, then refresh the PivotTables.

## Limitations and learning context

This project was completed with step-by-step AI guidance.
The data is synthetic and supplied by the accompanying learning pack.

Results demonstrate analytical techniques, not real customer demand.
Gross profit excludes rent, wages and other operating expenses.
Both products have a fixed 40% margin in this dataset.
