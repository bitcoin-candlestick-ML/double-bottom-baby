## Double Bottom Baby!

# Steps to creating our PNL prediction model "Double Bottom Baby!"
We have several different price events we were considering and ultimately
decided that we could accomplish identifying a double bottom baby within our 
bootcamp's project deadline of two weeks.

1. Load a csv file containing a range of dates of bitcoin prices where we expect double bottom events to occur; at minimum one event, maximum is max
2. Create ETL pipeline that identifies event points a to f, then leadup and extracts these rows to a new dataframe we will use to create a predictive model to measure the vector between e and f
3. Engineer features that measure stock vectors between event points
4. Create a predictive model for target Y (the metric that measures price movement between e and f)
5. Enter position at event point e and exit at event position f to capture profit or opportunity cost

