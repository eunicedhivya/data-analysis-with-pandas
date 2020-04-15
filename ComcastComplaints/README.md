Data analysis with Pandas
# Comcast Telecom Consumer Complaints

### Data Cleanup
  - Change the type of columns (to_numeric, to_datetime, astype)

### Data Exploration
  - Provide the trend chart for the number of complaints at monthly and daily granularity levels.
  - Provide a table with the frequency of complaint types.
    - Which complaint types are maximum i.e., around internet, network issues, or across any other domains.
  - Create a new categorical variable with value as Open and Closed. Open & Pending is to be categorized as Open and Closed & Solved is to be categorized as Closed.
    - Provide state wise status of complaints in a stacked bar chart. Use the categorized variable from Q3. Provide insights on:
    - Which state has the maximum complaints
    - Which state has the highest percentage of unresolved complaints
    - Provide the percentage of complaints resolved till date, which were received through the Internet and customer care calls.
 
### Techniques Practiced
    - Time Conversion
    - Adding columns
    - Parsing cells as strings to make new columns (.str)
    - Using Stack or Unstack
    - Using groupby to perform aggregate analysis
    - Plotting Stackbar Charts and Trend Charts

### Data Output
    -JSON format for D3.js presentation