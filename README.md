# KickStart Analysis

### Background <br/>
- Over two billion dollars have been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the over 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome. 
- Since getting funded on Kickstarter requires meeting or exceeding the project's initial goal, many organizations spend months looking through past projects in an attempt to discover some trick to finding success. The main objective of this homework is to organize and to analyze a database of four thousand past Kickstarter projects in order to uncover any hidden trends.

### Process <br/>
1.  Conditional formating state column: "successful"-> Red; "failed"-> Yellow; "cancelled" -> Green and "live" -> Blue <br />
2. A new column called percent funded is create. The colum values is calculated as pledged/goal. three-color scale. The cell values are colored  using a three-color scale. dark shade of red for 0 - transitioning to green at 100 - blue at 200.<br />
3. New column "Average donation" is created to track how much on average each investor funds the project <br />
4. Column category and and sub-category  are used to split the colum category and Sub-category into 2 parts. For exmaple: film & video/television will be split into film & video as category and television as sub-category <br />
5.  New sheet with pivot table is used to analyze how many projects were "successful," "failed," "cancelled," or are currently "live" per category.
	- A pivot chart filter by country is also created<br />
6. New sheet with pivot table is used to analyze how many projects were "successful," "failed," "cancelled," or are currently "live" per sub-category <br />
	- Create a Pivot chart of sub-category vs outcome. 
 7. New column named Date Created Conversion, Date Ended Conversion uses [This formula](http://spreadsheetpage.com/index.php/tip/converting_unix_timestamps/) to convert data contained within launched_at and deadline respectively into Excel's Date format<br />
8. New sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.<br />
### Report <br/>
- See report.docx file

<img width="756" alt="screen shot 2018-11-13 at 2 20 01 pm" src="https://user-images.githubusercontent.com/42792976/48440761-5cca6200-e74f-11e8-97a2-470f2b8be689.png">
