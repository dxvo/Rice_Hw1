<h1>KickStart Analysis </h1>
<h3>Background</h3>

Over two billion dollars have been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the over 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome. 

Since getting funded on Kickstarter requires meeting or exceeding the project's initial goal, many organizations spend months looking through past projects in an attempt to discover some trick to finding success. The main objective of this homework is to organize and to analyze a database of four thousand past Kickstarter projects in order to uncover any hidden trends.

<h3>Process</h3>
- Conditional formating state column: _"successful"-> Red; "failed"-> Yellow; "cancelled" -> Green and "live" -> Blue <br />
- A new column called percent funded is create. The colum values is calculated as pledged/goal. three-color scale. The cell values are colored  using a three-color scale. dark shade of red for 0 - transitioning to green at 100 - blue at 200.<br />
- New column "Average donation" is created to track how much on average each investor funds the project <br />
- Column category and and sub-category  are used to split the colum category and Sub-category into 2 parts. For exmaple: film & video/television will be split into film & video as category and television as sub-category <br />
- New sheet with pivot table is used to analyze how many projects were "successful," "failed," "cancelled," or are currently "live" per category. A pivot chart filter by country is also created<br />
- New sheet with pivot table is used to analyze how many projects were "successful," "failed," "cancelled," or are currently "live" per sub-category <br />
 - New column named Date Created Conversion, Date Ended Conversion uses [This formula](http://spreadsheetpage.com/index.php/tip/converting_unix_timestamps/) to convert data contained within launched_at and deadline respectively into Excel's Date format<br />
- New sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.<br />

<h3>Report </h3>
- See report.doc file
