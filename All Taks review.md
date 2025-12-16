 ***Task 1***



According to me I use line chart in which I put discount Y axis and in X axis I put price range this gives the data that is discount in percentage, I have a used line chart because it gives us a trend that at what price range the discount is and how it varies with the different price ranges although in histogram it is basically for one continuous variable, showing distribution not for relationship. Scatter plot is also used to show a relationship definitely but I do not used it and instead heat map uses a distribution visualization that is how it discount distributed among different prices which will be more difficult to understand i.e. it will be much trickier.



***Task 2***



To apply the conditional formatting in Power BI, I will use the Conditional formatting rules



**1. Formatting the Discount Column**



* Click on table visual in Power BI.
* Apply the desired data.
* Then, go to the Format pane (the paintbrush icon).
* Then, we expand the Cell elements section.
* Now, we select the Discount column from the "Apply to" dropdown.
* Then, we turn on the Background color.
* Now, Click on the fx button that appears next to the color option; This opens the Background color dialog box.
* In the dialog box:

 		Set Format style to Rules >> Ensure field is set to Discount >> Enter rule values as decimals i.e. If value is "greater than or 	equal to" and "and is less than" fields to ensure accurate formatting.



* Now, add the first rule (Green for > 50%):

 		If value is greater than 0.5 and is less than or equal to 1000 >> Set the color to Green.



* Now, add the second rule (Red for < 10%):

 		Click + New rule >> If value is greater than or equal to 0 and is less than 0.1 >> Set the color to Red.



* Click OK to apply the rules to the Discount column.



**2. Formatting the Rating Column**



* Stay in the Cell elements section of the Format pane.
* Select the Rating column from the "Apply to" dropdown.
* Turn on Background color and click the fx button.
* In the dialog box:

 		Set Format style to Rules >> Ensure the field is Rating.



* Now, add the rule (Orange for < 3):

 		If value is greater than or equal to 0 and is less than 3 >> Set the color to Orange.



* Click OK to apply the rule to the Rating column.





***Task 3***





The best chart type according to me for comparing Average Price and Average Rating across Subcategory is a Column and Line Combo Chart.



**AS I prefer it because:-**



1. *Dual Axes:* A combo chart allows you to use two different Y-axes i.e. Price and rating data are measured on entirely different scales.
2. *Clear Comparison by Category:* The column axis naturally organizes data by Subcategory, making it easy to visually correlate the height of a price column with the position of a rating data point for the exact same category.



**I would interpret following facts when expensive Categories Have Lower Ratings:-**



* *Potential Quality/Value Mismatch:* The data suggests that customers perceive these expensive products are not providing value as compared with their price. Customers are paying a premium but are dissatisfied with the experience or product quality.



* *Customer Feedback Analysis:* Reading specific reviews for those subcategories to identify common complaints (e.g. durability issues, poor customer service, missing features, etc.).



* *Competitive Analysis:* Checking if competitors offer better-rated products at a similar price.



* *Product Development Review:* Determining if the product is failing to meet market expectations set by its high price tag.



In short, expensive categories with low ratings indicate dissatisfaction and a potential threat to market position if not addressed.





***Task 4***





For showing that higher discounts don't necessarily lead to higher ratings I used clustered column chart in which I kept ratings in y axis and discount bin in x axis which let us know that higher discount have comparatively lower rating.





***Task 5***





For this task I should use Line Chart because



1. *Best for Trends:* Line charts are specifically designed to visualize changes, patterns, and fluctuations in continuous data over a timeline.
2. *Clarity and Precision:* Unlike area charts, which can feel "heavy" due to color fills, line charts provide a clear view of specific data points and are best for identifying exact peaks or dips in your discount strategy.
3. *Comparison:* If you later want to compare discount trends by Category, a line chart can handle multiple series (lines) simultaneously without the "occlusion" (overlap) issues that make area charts difficult to read.



**Steps to create the visualization:-**



* *Add the Visual:* Select the Line Chart icon from the Visualizations pane.



* *Assign the X-Axis:* Drag your Scraping Date column into the X-axis field. Power BI will likely create an automatic Date Hierarchy (Year, Quarter, Month, Day), which you can keep or toggle to just "Scraping Date" for a continuous timeline.



* *Assign the Y-Axis:* Drag the Discount column into the Y-axis field.



* *Change Aggregation to Average:* By default, Power BI may sum the discounts. Click the down arrow next to the Discount field in the Y-axis bucket and select Average to see the true trend.



* Now, go to the Analytics pane (magnifying glass icon) and add a Trend line to see the overall direction (increasing or decreasing) of your discounts.



* Now, add a Forecasting line (available in the Analytics pane for line charts) to predict future discount levels based on historical scraping data.





***Task 6***



An e-commerce manager would interpret these KPIs as signs of a high-volume, low-margin "Discount-Driven" strategy with potential quality or value-perception risks.



**Business Interpretation of the KPI Card are as follows:-**



* *Average Price (₹950):* This places your typical product in the "mid-tier" or "affordable premium" segment in the Indian market. It is high enough to cover some shipping and fulfillment costs but requires healthy volume to maintain profitability.



* *Average Discount (40%):* This is significantly higher than the standard 10–30% e-commerce benchmark. It suggests the business is aggressively using price to drive sales volume or clear inventory. While this boosts short-term conversion, it risks eroding brand value and can cut net profits by 30% or more.



* Average Rating (3.8 ⭐): This is a "mediocre" score. In e-commerce, ratings below 4.0 often indicate consistent customer dissatisfaction with product quality, shipping speed, or unmet expectations. A 3.8 rating may specifically suggest that despite the heavy 40% discount, customers still feel the product doesn't fully deliver on its value promise.



**Actionable Insights for an E-commerce Manager are:-**

1. Analyze "Price-Quality Gap":



* *Insight:* A 40% discount should ideally drive very high satisfaction because of the perceived "bargain." A 3.8 rating suggests that even at a lower price, the product is underperforming.



* *Action:* Audit customer reviews for products with 40%+ discounts. Look for recurring complaints about "low quality" or "not as described" to see if deep discounts are attracting the wrong audience or masking product flaws.



2\. Evaluate Profitability vs. Growth:



* *Insight:* High discounts (40%) combined with a mid-range price (₹950) can lead to a "Net Loss" if logistics and marketing costs (CAC) are high.



* *Action:* Compare Customer Acquisition Cost (CAC) against Average Order Value (AOV). If you are spending ₹300 to acquire a customer for a ₹950 item that is already 40% off, your margins may be unsustainable.



3\. Optimize Discount Strategy:



* *Insight:* Frequent heavy discounting trains customers to never pay full price, which lowers your Customer Lifetime Value (CLTV).



* *Action:* Transition from "site-wide" 40% discounts to tiered loyalty rewards or lifecycle-based offers (e.g., 15% for repeat buyers) to protect margins while keeping engagement high.



4\. Boost Ratings to Drive Organic Sales:



* *Insight:* Increasing ratings can boost sales by up to 40% without increasing ad spend.



* *Action:* Target a rating of 4.2+ to improve search visibility and trust. Address the "3.8 gap" by improving post-purchase communication or packaging quality to exceed customer expectations.
