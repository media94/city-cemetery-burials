The city of Nashville provides a dataset of known burials in city cemeteries from 1846 through 1979. This dataset holds factual information, but it also offers a fascinating glimpse into historical trends in medicine, literacy, racial equality, and more.

Created  marketing materials for The Nashville City Cemetery Association.  The following materials are  visualizations about the data to help with storytelling to attract more tourist.

![Top 10 Causes](/assets/Top_10_Cause_Death.png) 

1.	Used a pivot table to find the 10 most common (known) recorded causes of death, and evaluate the counts of each type. Used a **bar chart** to display results. In the analysis of the top 10 causes of death, you may see spelling mistakes that are affecting your counts. Due to the spelling errors in the data, I created a new column in the original dataset to update spelling errors to make the count of the top 10 causes more accurate. To see changes, you will need to **refresh your pivot table** .

2.	Created a line chart showing number of burials per year to show  what years were there the most burials. 

3. Examined deaths for each decade beginning with the 1850s. Looked at the total number of deaths and the proportion of male deaths to female deaths. Used a **pivot table** with a **slicer** to do this, and created a clustered bar chart to show how male and female deaths have changed over time.

4. Next, looked at how age at time of death has changed over time by add a column to the original dataset.  This will classify each row to one of the following categories (0-18, 19-25, 26-40, 41-64, and 65+). Created a series of pie charts to show the breakdown of each age group for these four periods: before 1880, 1881-1900, 1900-1920, after 1920.

5. Examined burials by month to see if there are months with higher burials. Displayed the top five causes of death for each month Then used cluster column chat to show a visualisation that conveys the differences well.

6. Created a new column titled Last Name. Extracted the last name from the Name column by subsetting to all characters to the left of the comma by using "LEN, SEARCH” funictions. Used the filter function to help find the most common last names of people buired in this cemetery. 
    
7. Displayed a **pivot table** to show which (`Section/Lot`) people were buried in.
