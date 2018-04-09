## Galvanize Data Analytics
# Load data from text files
#### Block 2 Lesson 1
75 min
<br>
<br>
In our work with SQL we have learned how to extract the data we need from databases and save it into text data files.  We saved the files in the same text file format since there was value in consistency.  But there are several formats and we will want to be able to import those as well/   In this lesson we will learn how to import data from a variety of file types into Excel.
<br>

> **Think as a BI analyst tip**:  Even though Excel is limited in the amount of data it can hold in a spreadsheet, it can be a very useful tool for analysing smaller data sets or providing aggregate information to users.  For example, Pivot tables provide a rapid way to share findings and provide interaction for users.  A good BI analyst will use Excel where it is appropriate even when more sophisticated tools are available.    
<br>

### Lesson objectives

*By the end of this lesson, you will be able to:*
* Describe the difference between CSV, delimited, JSON and XML data transfer files
* Load data text files including CSV, TSV and files with other delimiters
* Set data types on intake

### Pre-work
* If you do not have a version of Excel 2013 or newer on your laptop, install a recent version of Excel onto your laptop.  This typically requires purchasing and installing Microsoft Office or at least the Excel portion
  * Make sure you are installing an laptop version and not an Office 356 version (cloud only)
  * Home and Student version of Microsoft Office is sufficent

## Import data from text files
* Discuss three types of text file formats for storing data - **15 min**
  * Rows and column text files such as CSV and delimited files
  * JSON
  * XML

* Code along - Import a delimited file - **20 min**
  * In a file manager clicking on a .csv file to open it in Excel
    * Successful import
  * Import a less well behaved CSV file by clicking on it 
    * Note defects
    * Moral is you cannot depend on the click import
  * Import using Data > From Text

* Exercise **15 min**
  * Students import a new file using Data > From Text
    * In pairs
    * Import file with:
      * Both enclosing characters and non-comma delimiter
      * Integers that may want to import as text
     * Duplicate (copy) the "raw data tab" to a new tab

* Difference between CSV and delimited files - demo - **15 min**

* Exercise **15 min**
  * Students import a new file using Data > From Text
    * On own for first 7 minutes then in teams of 3
    * Import file with:
      * Both enclosing characters and non-comma delimiter
      * Integers that may want to import as text
    * Duplicate (copy) the "raw data tab" to a new tab
    * Bonus: set a range name for the raw data
      
* Quick look at submitting SQL queries directly from Excel **15 min**
  * Demo functionality
  * Discuss pitfalls (Excel's propensity to format fields)
  * Tour additional resources

* Exercise - **40 min**
Format: work alone for 7 minutes and then in groups of three for 8 minutes for each of the three tasks below
  * Create and submit a query that returns an aggregate table
  * Export the file as a CSV file using delimiters and enclosing characters appropriate to the contents of the fields
     * Note: Aggregate table will contain fields with commas and other issues that will require a delimiter different from comma
  * Import the data into Excel, creating a raw_data tab and and a data tab

 
 
