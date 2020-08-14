# **Election_Analysis**
---
## **U.S. congressional results analysis project**
---
### **Overview of Election Audit**

The purpose of this audit analysis was to assist a Colorado Board of Elections employee, Tom, with collecting and analysing the totals for the U.S. congressional precinct in Colorado. Data was previously collected from multiple sources including mail-in ballots, punch cards, and direct recording electronics. Using the Python programming language, outcomes were determined for voter count and the winner of the precinct's election.
---
## **Election-Audit Results**

* There were 369,711 total votes

* Jefferson County had a turnout of 10.5% with 38,855 of the votes. Denver County had a turnout of 82.8% with 306,055 of the votes. Arapahoe County had a turnout of 6.7% with 24,801 of the votes.

* The county with the largest number of votes was Denver.

* Charles Casper Stockham had a total vote percentage of 23% with 85,213 of the votes. Diana DeGette had a total vote percentage of 73.8% with 272,892 of the votes. Raymon Anthony Doane had a total percentage of 3.1% with 11,606 of the votes.

* The winner of the Colorado election was Diana DeGette with 73.8% and 272,892 of the total election votes.
---
## **Election-Audit Summary**

The code used to run this analysis is versatile in that it can be re-purposed for any other election. As you can see below, the dictionaries created to pull the information needed from the raw data was a simple format:

![Code%20for%20dictionaries%20](https://github.com/CypherGreen/Election_Analysis/blob/master/Images/Code%20for%20dictionaries.png)

The candidate, votes, and county data sections can be modified to pull other types of voting elections, for example, propositions on ballots instead of candidates. Depending on if more data columns were collected, the dictionaries could be expanded to collect from these other columns. In that case, the word 'candidate' would need to be replaced throughout the length of code.

![Code_for_rows](https://github.com/CypherGreen/Election_Analysis/blob/master/Images/Code_for_rows.png)

The 'for' loop going through the csv file would also need to be adjusted if there were more or less rows to loop through. As long as the new code matched up with the new data collected and certain words were exchanged then it can be re-purposed to accomodate larger or smaller datasets. If the new dataset was the same as the one used here, except with just the names of the candidates being different, then this same exact code could be re-used as is since the code calls for the locations of the specific data or data types, not individual names.
