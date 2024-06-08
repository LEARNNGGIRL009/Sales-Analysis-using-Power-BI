# Sales-Analysis-using-Power-BI

## Problem Statement
Key features of our sales dashboard include:
🔹 Total sales revenue by month and quarter
🔹 Sales performance by region and product category
🔹 Top-selling products and their contribution to overall revenue

Interactive Insights: Our dashboard features synced filters across pages, making it easy to carry your analysis seamlessly across different sections. Explore data with confidence and unlock actionable insights to drive business success. 



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Gate Location" & "Type of travel".
- Step 9 : Two card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes.
Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
- Step 10 : A bar chart was also added to the report design area representing the number of satisfied & neutral/unsatisfied customers. While creating this visual, field named "Gender" was also added to the Legends bucket, thus number of customers are also seggregated according the gender. 
- Step 11 : Ratings Visual was used to represent different ratings mentioned below,
- Step 12 : In the report view, under the insert tab, two text boxes were added to the canvas, in one of them name of the airlines was mentioned & in the other one company's tagline was written.
- Step 13 : In the report view, under the insert tab, using shapes option from elements group a rectangle was inserted & similarly using image option company's logo was added to the report design area. 
- Step 14 : Calculated column was created in which, customers were grouped into various age groups.
     
- Step 15 : New measure was created to find total count of customers.
        
 - Step 16 : New measure was created to find  % of customers,
 
 - Step 17 : New measure was created to calculate total distance travelled by flights & a card visual was used to represent total distance.
 
 - Step 18 : The report was then published to Power BI Service.
 
# Snapshot of Dashboard (Power BI Service)
  -File Attached
 # Report Snapshot (Power BI DESKTOP)
  -File Attached
# Insights
  -File Attached
A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

It allows tracking sales in real-time, analyzing market trends, identifying most profitable products, monitoring profit margins, and making strategic decisions based on concrete data. 
