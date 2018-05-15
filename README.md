# MITRE-ATT&CK Matrix for Enterprise
## Goals
- Quantify the relationship between **Platforms & Tactics & Techniques & Data Sources**
- Summarize data and information about **ATT&CK Matrix for Enterprise**
- Develop a dashboard with **Tableau** to present the results of this analysis
## Understanding the Tableau Dashboard
The minimum unit of analysis for this matrix is the combinations of Platform & Tactic & Technique & Data Source. Considering this, the matrix has 1715 registers.

**1. Pie Chart (Platform):** This graphic shows us the distribution of the registers by Platform. If we consider all the registers: 46% belongs to Windows, 29% belongs to macOS, and 25% belongs to Linux.

**2. Blue Bar Charts (Tactics):** This graphic shows us the following information: Number of Tactics (On Top of the vertical bar chart), Relative Percentage with respect to the Total of Tactics of the selected Platform (Vertical bar chart), and the number of Techniques for each Tactic (Horizontal bar chart).

**3. Red Bar Charts (Techniques):** This graphic shows us the following information: Number of Techniques (On Top of the vertical bar chart), Relative Percentage with respect to the Total of Techniques of the selected Platform (Vertical bar chart), and the number of Data Sources for each Technique (Horizontal bar chart).

**4. Orange Bar Charts (Data Sources):** This graphic shows us the following information: Number of Data Sources (On Top of the vertical bar chart), Relative Percentage with respect to the Total of Data Sources of the selected Platform (Vertical bar chart), and the number of Techniques for each Data Source (Horizontal bar chart).

**5. Text table (Summary of Data):** This table shows us a summary of data about the ATT&amp;CK Matrix for Enterprise. This table allows us to export data into a CSV file.

**6. Filters (Green Box):** You can perform filters using the fields related to the minimum unit of analysis: Platform, Tactics, Techniques, and Data Sources. The most general filter is Platform and the most specific is Data Source. The values of the 4 fields are filtered among themselves.

This is a general view of the dashboard: Without any filter selected, there are 11 Tactics, 219 Techniques, and 48 Data Sources for all the Platforms.
<img src= "Images/AllPlatforms.PNG" width="1000" height="500" >

## Using The Tableau Dashboard
**1. Filtering the data:** Select a variable or variables for analysis (Green box): You have four options to filter data and perform an analysis (Platforms, Tactics, Techniques, and Data Sources).

  a) Example of view: Platform & Tactic
    - Platform filter = Windows
    <img src= "Images/WindowsPlatform.PNG" width="1000" height="500" >
    - Tactic filter = Command and Control
    <img src= "Images/WindowsPlatformTacticFilter.PNG" width="1000" height="500" >
  
  
**2. Exporting the Text Table to a .CSV file:**
Select a Tactic or Technique or Data Source
  - 

## Resources
- [Tableau Dashboard - ATT&CK Matrix for Enterprise](https://public.tableau.com/profile/cyb3rpanda#!/vizhome/MITREATTCKMatrixforEnterpriseV2/ATTCK?publish=yes)
- [Spread Sheet - ATTCK Matrix for Enterprise](https://docs.google.com/spreadsheets/d/1voZ_CdlYQHw2jgp-Ses-hW7cH5vZhSoVevBL7PvIXPQ/edit#gid=0)
- [MITRE-ATT&CK](https://attack.mitre.org/wiki/Main_Page)
## Author
- Jose Luis Rodriguez [Cyb3rPanda](https://twitter.com/Cyb3rPandaH)
- Roberto Rodriguez [Cyb3rWarD0g](https://twitter.com/Cyb3rWard0g)
## Contributors
## Contributing
## TO-DO
- [ ] 
