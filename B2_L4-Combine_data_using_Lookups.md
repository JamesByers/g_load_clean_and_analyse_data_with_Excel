## Galvanize Data Analytics
# Combine data from different sources using Lookups
#### Block 2 Lesson 4

1.25 hrs
<br><br>
We are going to continue to prepare data by fetching and combining data from several spreadsheets into a worksheet

### Learning Objectives
*By the end of this lesson you will be able to:*
* Use VLOOKUP and HLOOKUP to fetch data from another table
* Apply parameters to alter the lookup
<br>
 
### Combine data from different sources using VLOOKUP - 40 min
#### Overview of VLOOKUP function - 10 min
* Use on-line documentation 
* Emphasize the need to typically set the "Range Lookup" parameter to FALSE
  * A good example of the benefit of looking through what is set by default and what options are available
  * Note limitations such as Lookups returning only the first match of the external table  
<br>

#### Code-along - 15 min
Students complete the actions concurrently with the instructor
* Apply VLOOKUP
  * Load file
  * Create new worksheet
  * Add function to some columns to link to columns in another worksheet
  * Create a new column Use VLOOKUP to fetch the data that matches the 
  * Danger! You have to use absolute references else the table_range moves when you copy the VLOOKUP formula to another cell
    * There is definitely an advantage to using range names.  We will change our VLOOKUP reference table_array value to a range name.
<br>

#### Exercise: Use VLOOKUPs to fetch data from other tables - 15 min
* Work in pairs
* Fetch data from other worksheets using VLOOKUPs
  * Match strings
  * Match numerical values
<br>

### Combine data from different sources using HLOOKUP - 10 min  
#### Code-along
Students complete the actions concurrently with the instructor
* 
* Apply HLOOKUP
  * Load file
  * Create new worksheet
  * Add function to some columns to link to columns in another worksheet
  * Create a new column Use VLOOKUP to fetch the data that matches matches values in a column
  * Danger! You have to use absolute references else the table_range moves when you copy the VLOOKUP formula tp another cell
    * There is definitely an advantage to using range names.  We will change our VLOOKUP reference table_array value to a range name.
    
#### Exercise: Use Lookups to fetch data from other tables - 25 min
* Students work independently and then in teams of three
* Fetch data from other worksheets using lookups
  * Match numerical values
  * Match string values
  * Handle case where external column is string but fetching column is number
  
### Additional Resources
*
