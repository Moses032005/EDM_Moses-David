## Midterm Lab Task 2 -  Data Cleaning and Transformation Using Power Query Editor

### Step 1 - Cleaning the data using PowerQuery Editor
- Download and open the raw data given by your instructor.
- Add the required columns (Min Sal, Max Sal, Role Type).
- Split the columns (Salary Estimate, Location, Size).
- Change the columns to appropriate data types (Currency, Text).
- Filter columns (Competitors, Revenue, Industry to remove negative values).
- Remove unnecessary columns to avoid redundancy (Company Name ratings, extra descriptions).
- Save the M Language to a notepad.
  
  ## Before Cleaning  
![screenshot](/Midterm%20Task%201/Images/before.PNG)

  ## After Cleaning
  ![screenshot](/Midterm%20Task%201/Images/after.png)
  
## Step 2 - Reshaping and Grouping the Tables
- Duplicate and reference Unclean DS Jobs to create new queries (Sal By Role Type dup, Sal By Role Size ref, Sal By State ref).
- Select appropriate columns (Role Type, Size, Min Sal, Max Sal).
- Change the columns to required data types (Currency).
- Multiply Min Sal and Max Sal by 1000.
- Group data by Role Type, Size, State Full Name to get averages.
- Merge State Mapping with Unclean DS Jobs using State Abbreviation.
- Rename merged column to State Full Name and remove nulls.
- Check and review Query Dependencies.

  ## Grouped Tables

    **Salary by Role Type Table**

    ![screenshot](/Midterm%20Task%201/Images/salbyroletypedup.png)


    **Salary by Size Table**

   ![screenshot](/Midterm%20Task%201/Images/salbysizeref.png)


    **Salary by Size Role Type Table**

   ![screenshot](/Midterm%20Task%201/Images/salbysizeroletypedup.png)


    **States (Mapping) Table**
  
   ![screenshot](/Midterm%20Task%201/Images/state.PNG)

    
    **Query Dependecies**
![screenshot](/Midterm%20Task%201/Images/Screenshot(Q).png)
