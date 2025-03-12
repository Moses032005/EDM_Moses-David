## Midterm Lab Task 2 -  Data Cleaning and Transformation Using Power Query Editor

### Step 1 - Cleaning the data using Power Query Editor
- Start by obtaining your instructor's raw data and opening it in Power Query Editor.
- Add Necessary Columns: To improve the dataset, provide columns such as Min Sal, Max Sal, and Role Type.
- Split Columns: Divide complex columns like Salary Estimate, Location, and Size into small sections.
- Change Data Types: Convert columns to their correct data types, such as salary columns to Currency and other pertinent columns to Text.
- Filter Out Negative numbers: Remove any negative or irrelevant numbers from columns such as Competitors, Revenue, and Industries.
- To simplify the dataset, remove unnecessary columns such as Company Name ratings and redundant descriptions.
- Lastly, Save the M Language to a notepad.
  
  ## Before Cleaning  
![screenshot](/Midterm%20Lab%20Task%202/Images/before.PNG)

  ## After Cleaning
  ![screenshot](/Midterm%20Lab%20Task%202/Images/after1.png)
  ![screenshot](/Midterm%20Lab%20Task%202/Images/after2.png)
   
## Step 2 - Reshaping and Grouping the Tables
- Create new queries by duplicating and referencing Unclean DS Jobs (Sal By Role Type, Sal By Role Size, and Sal By State).
- Select the necessary columns (Role Type, Size, Minimum Salary, Maximum Salary).
- Convert the columns to the desired data type (Currency).
- Multiply the minimum and maximum salaries by 1000.
- To calculate averages, group data by role type, size, and state full name.
- Combine State Mapping with Unclean DS Jobs utilizing State Abbreviation.
- Rename the merged column to State Full Name and delete the nulls.
- Check and review query dependencies.

  ## Here's our Sample Tables

  **Salary by Role Type Table**

  ![screenshot](/Midterm%20Lab%20Task%202/Images/salbyroletypedup.png)

  **Salary by Size Table**

  ![screenshot](/Midterm%20Lab%20Task%202/Images/salbysizeref.png)

  **Salary by Size Role Type Table**

  ![screenshot](/Midterm%20Lab%20Task%202/Images/salbysizeroletypedup.png)

  **States (Mapping) Table**

  ![screenshot](/Midterm%20Lab%20Task%202/Images/state.PNG)

    
  **Query Dependecies**

  ![screenshot](/Midterm%20Lab%20Task%202/Images/Screenshot%20(Q).png)
