# Flight_onTime_Spark
Notebook using Apache Spark to analyse publicly available Flight_onTime sample data set

In this notebook, I am experimenting with analyzing flight departure and arrival delays and taxiing times using Apache Spark.  The flight details are obtained from [On-Time Flight performance database](https://www.transtats.bts.gov/DL_SelectFields.asp?DB_Short_Name=On-Time&Table_ID=236)

All data presented here only correspond to airports within the US for the month of January 2018. Data for other time periods (month, year) are availabe at the sites mentioned above. In addition, the user selected airport is hard-coded to be Denver International Airport, but this could be easily be modifiered under the 'User Input' section of the notebook.  

Similar analysis could be applied to those other time periods by downloading the appropriate data sets. But, that is beyond the scope of this analysis.

You can view this notebook at [nbviewer](https://nbviewer.jupyter.org/github/anandvl/Flight_onTime_Spark/blob/master/Flight_onTime.ipynb).  The notebook was also published on the [community edition (CE) of DataBricks](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2452076698817046/1664537810195860/8096433167883886/latest.html).  On Databricks, the plot section at the end is commented out since categorical x-axis is not supported by the old matplotlib version that is present in the Databricks CE image.  Categorical x-axis is only supported in matplotlib version 2.1.0 or later.  
