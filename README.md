E-commerce Analytics (Python)

About the Project
Wanted to try end-to-end analysis like an e-commerce analyst: basic EDA, RFM customer segmentation, and a “quick & dirty” churn prediction. All data is randomly generated—but I tried to keep it plausible (locations are real Indian cities!).

Project Highlights
- Explores demographics, order frequency, most popular products
- Segments users by Recency-Frequency-Monetary (RFM) analysis
- Builds and evaluates a basic churn model using logistic regression.

 Workflow
- Jupyter Notebook for code and commentary.
- Step-by-step with lots of comments and plots.
- Notebook references the three CSVs above (customers, orders, products).

 Lessons Learned
Actually getting RFM logic right took a couple passes—sorting by last order date, grouping by customer, and computing quantiles for segments. For churn, it’s just a simple model—I focused more on show-and-tell than accuracy.

TODO: Try more advanced ML, visualize timelines, and scale the dataset.

 Running the Project
1. Install dependencies:
2. Place the CSVs in the same folder as the notebook.
3. Run: `jupyter notebook ecommerce_analysis.ipynb`
