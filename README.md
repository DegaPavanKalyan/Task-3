⚙️ 1. Open Power BI Desktop and load your file Sales.pbix

⸻

📊 2. Create KPI Cards

Go to a blank report page and add Card visuals for each of these:
	•	Total Sales
→ Use: SUM(Sales)
	•	Total Profit
→ Use: SUM(Profit)
	•	Profit Margin
→ Create a DAX Measure:
Total Quantity Sold
→ Use: SUM(Quantity)

Apply formatting (e.g., ₹, %, etc.) and rename the card titles.

⸻

📅 3. Add Time Series Visuals
	•	Use a Line Chart:
	•	Axis: Order Date (Month or Year)
	•	Values: Sales, Profit, or Quantity
	•	Format x-axis as continuous to show trend

⸻

🗃 4. Create Category-Wise Visuals
	•	Bar Chart (Sales by Category/Sub-Category)
	•	Tree Map (Profit by Sub-Category)
	•	Pie Chart (Sales % by Region)

⸻

🌍 5. Map Visualization (optional)

If your dataset has a State or Region field:
	•	Add Map or Filled Map
	•	Location: State
	•	Values: Sales

⸻

🎛 6. Add Slicers for Interactivity

Use Slicer visual for:
	•	Region
	•	Category
	•	Order Date
	•	Customer Name (optional)

Use drop-down format and enable “Single Select” if needed.

⸻

🧭 7. Navigation Buttons (Optional)

If you use multiple pages (e.g., Overview, Product Insights, Region Insights):
	•	Insert buttons (from the Insert menu)
	•	Use “Page Navigation” action
	•	Style the buttons consistently

🎨 8. Design and Theme
	•	Apply a consistent color palette (e.g., blue and grey for professional tone)
	•	Use clean fonts and align visuals
	•	Remove clutter and gridlines if not helpful

⸻

📥 9. Save & Export

Once done:
	•	Save Sales.pbix
	•	Export key visuals as images or export the report as PDF
	•	Create a summary PowerPoint by taking screenshots and adding brief insights per slide
