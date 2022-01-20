# Clinical Informatics Education - Statistics Basics

01/20/2022

* Slido participation link: https://wall.sli.do/event/7gqUV9n9GN9GGY8SoGHbQQ?section=ea1df556-6a63-4aa7-a0ac-4fc810f44061
* Slido admin link: https://admin.sli.do/event/7gqUV9n9GN9GGY8SoGHbQQ/polls

## Conflicts

<details>
  <summary>Expand</summary>
  
* I don't have any financial conflicts to declare.
  
</details>

## Introduction

<details>
  <summary>Expand</summary>
  
* Christopher I. Macintosh, PhD, RN
* I am currently a Clinical Informatics Analyst on the CTIS Health Information Technology (HIT) Safety Team.
* I am an Adjunct Assistant Professor at the University of Utah College of Nursing.
* I have worked for the last 5 years on the Terminology and Modeling Team at Intermountain.
* I received my PhD from the University of Utah College of Nursing.
* Before going to graduate school I worked in the OR at LDS Hospital, IMC, and the U of U. I also worked for a short time in home health and hospice.
  
</details>

## Case study preview

<details>
  <summary>Expand</summary>
  
* Problem: During a transition period with staff changes an Outlook inbox with error messages from an interface was unmonitored for a period of time. Approximately 390,000 messages had built up over about 3 months.
  
</details>

## Relationship between informatics and statistics

<details>
  <summary>Expand</summary>
  
* Slido polls 1 - 3
* Slides https://github.com/cmcntsh/clinical_informatics_education_statistics_basics/blob/main/InformaticsAndStatistics.pdf
  
</details>

## Some basic data skills

<details>
  <summary>Expand</summary>
  
* Slido polls 4


  ### Creating tables in Excel
  
  <details>
    <summary>Expand</summary>
    
    * Video https://www.youtube.com/watch?v=M07df44RXOM 
    * Don't have anything above the first row of your table
    * Start in cell A1
    * Each column should have a header (variable name)
    * Column names should be unique
    * Avoid spaces in column names
      * It's OK for Excel, but it's better not to have spaces if you may export your data for use in other analysis software.
    * Remove any summary rows. Only have data rows.
    * Don't merge cells. (Unmerge them if any exist.)
    * Don't use formatting to code for meaning. (i.e. text color, highlighting) If you need to add some meaning to a row, create a new column to code that meaning with text/numbers.
    
  </details>
  
  ### Tidy data
  
    <details>
    <summary>Expand</summary>
    
    * Video: https://www.youtube.com/watch?v=jpCz8dAYf0o
    * Variables (columns)
    * Observations (rows)
    * Values (the content of each cell)
    * Hadley Wickham - "Tidy datasets are all alike but every messy dataset is messy in its own way."
    * Example of how not to structure for analysis. https://www.healthypeople.gov/2020/data-search/Search-the-Data?objid=4828
    * No blank rows
    * No heading rows other than the one at the top. (Make a new column with that information.)
    * Don't store multiple variables in a single column. 
    * Don't put values in columns.
    * Wide vs Long format
      * Wide format has repeated measures in columns.
      * Long format has repeated measures in rows.
      
  </details>
  
  ### Import table data from web resources in Excel
  
    <details>
    <summary>Expand</summary>
    
    * Example site: https://datatables.net/examples/data_sources/dom.html
    * Excel - Data - Get Data - From Web - URL (paste address of web page) - OK (You might have to click through a couple pages. Usually default settings work.)
    * When the Navigator window pops up, you can click through the available tables to see what you want. When you have the one you want click `Load`.
    * The data should import into a table in a new sheet.
      
    </details>
  
  ### Create a pivot table from a table in Excel.
  
    <details>
    <summary>Expand</summary>
    
    * Great for quick analysis/reporting.
    * Go to the sheet which has your data table.
    * Insert - Pivot Table - The default settings usually work (New Worksheet) - Click `OK`
    * Drag the fields desired to Rows, Columns, Values
      
  </details>
  
</details>

## Some basic statistical concepts

<details>
  <summary>Expand</summary>
  
* Slido polls 4


  ### Levels of Measurement
  
  <details>
    <summary>Expand</summary>
    
    * Video https://www.youtube.com/watch?v=M07df44RXOM 
    * Don't have anything above the first row of your table
    * Start in cell A1
    * Each column should have a header (variable name)
    * Column names should be unique
    * Avoid spaces in column names
      * It's OK for Excel, but it's better not to have spaces if you may export your data for use in other analysis software.
    * Remove any summary rows. Only have data rows.
    * Don't merge cells. (Unmerge them if any exist.)
    * Don't use formatting to code for meaning. (i.e. text color, highlighting) If you need to add some meaning to a row, create a new column to code that meaning with text/numbers.
    
  </details>
  
  ### Descriptive Statistics
  
    <details>
    <summary>Expand</summary>
    
    * Video: https://www.youtube.com/watch?v=jpCz8dAYf0o
    * Variables (columns)
    * Observations (rows)
    * Values (the content of each cell)
    * Hadley Wickham - "Tidy datasets are all alike but every messy dataset is messy in its own way."
    * Example of how not to structure for analysis. https://www.healthypeople.gov/2020/data-search/Search-the-Data?objid=4828
    * No blank rows
    * No heading rows other than the one at the top. (Make a new column with that information.)
    * Don't store multiple variables in a single column. 
    * Don't put values in columns.
    * Wide vs Long format
      * Wide format has repeated measures in columns.
      * Long format has repeated measures in rows.
      
  </details>
  
  ### Plots
  
    <details>
    <summary>Expand</summary>
    
    * Example site: https://datatables.net/examples/data_sources/dom.html
    * Excel - Data - Get Data - From Web - URL (paste address of web page) - OK (You might have to click through a couple pages. Usually default settings work.)
    * When the Navigator window pops up, you can click through the available tables to see what you want. When you have the one you want click `Load`.
    * The data should import into a table in a new sheet.
      
    </details>
  
  ### Comparisons
  
    <details>
    <summary>Expand</summary>
    
    * z-scores (standardization)
    * Video: https://www.youtube.com/watch?v=uAxyI_XfqXk&list=PL8dPuuaLjXtNM_Y-bUAhblSAdWRnmBUcr&index=20
      
  </details>
  
  ### Data Screening
  
    <details>
    <summary>Expand</summary>
    
    * What is the general purpose of what you're trying to accomplish?
    * How does your purpose and your data source(s) affect the generalizability of your results?
    * What question(s) are you trying to answer?
    * When were the data collected?
    * How were the data collected?
    * How were the data handled?
    * What variables are in your data set?
    * What is the level of measurement for each variable? (This impacts how you will visualize it and report it.)
    * Are there any problems with data accuracy?
      * Typographical errors
      * Values which don't make sense
      * Categories which don't seem to match
    * Are there any data transformations which should take place?
    * Do any variables have missing data? How will you handle that?
    * Do any variables have outliers? How will you handle that?
      
  </details>
  
  ### Reporting
  
    <details>
    <summary>Expand</summary>
    
    * Tips
      * Always provide context for the numbers you're reporting
        * What are the lowest and highest possible values?
        * Imagine how hard a graph without any scale numbers or scale markers/indicators is to read.
      * When reporting summary scales that were derived from multiple individual questions, provide the list of which questions were used to calculate the scale.
    * Categorical variables
      * See descriptive statistics and plots sections above
    * Continuous variables
      * See descriptive statistics and plots sections above
      
  </details>
  
</details>

## Case study: Grouping and prioritizing error messages

<details>
  <summary>Expand</summary>
  
* Problem: During a transition period with staff changes an Outlook inbox with error messages from an interface was unmonitored for a period of time. Approximately 390,000 messages had built up over about 3 months.
* Solution: 
  * Read the messages. (Python was used to interface with Outlook, loop through the messages)
  * Tabulate data. (Python was used to count duplicate messages and produce an Excel report with message information and counts.)
  * Prioritize work. (Message counts were used to decide which errors to fix first. Higher counts took higher priority.)
* Result:
  * Over time error counts dropped with some days having 0 errors.
* Lesson to be learned: 
  * Simple statistical techniques like counts can lead to significant improvements and reduce workload.
  
</details>

## Statistics resources

<details>
  <summary>Expand</summary>
  
  * Slido polls 5
  * GitHub repository: https://github.com/cmcntsh/stats2021_topics
  
</details>

## Questions?

## Thanks for participating! :)

<details>
  <summary>Expand</summary>
  
  * claim ID:16427
  
  </details>
