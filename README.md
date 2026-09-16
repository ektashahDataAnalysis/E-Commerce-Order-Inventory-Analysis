# E-Commerce-Order-Inventory-Analysis
Excel E-Commerce Order &amp; Inventory Analysis Project
E-Commerce Order & Inventory Analysis
Excel-only analytics workbook — order trends, channel mix, and live low-stock alerts.

Business question: Which channels and categories drive the most revenue, and which SKUs are at risk of stocking out before the next supplier delivery?

Sheets:
  Orders_Raw            300 synthetic order lines (Jan-Sep 2025) across 4 sales channels and 10 SKUs.
  Inventory_Reference   Current stock, trailing 90-day sales, reorder point, supplier, and lead time per SKU — with a live VLOOKUP price lookup and a Days-of-Supply / Restock Alert formula.
  Dashboard             KPI cards, a channel selector (data validation dropdown), and 2 charts.

All calculated cells use formulas (SUMIFS, VLOOKUP, IF) referencing Orders_Raw and Inventory_Reference — nothing is hardcoded.


