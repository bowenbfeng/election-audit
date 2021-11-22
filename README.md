# Election Audit

## Overview of the Election Audit
Given by the Colorado Board of Elections, this audit task is to conduct an analysis on the election results. This script is inteded to deliver a comprehensive list of information, including the total number of votes cast, a complete list of candidates who received notes, total number of votes each candidated received, percentage of the votes each candidate won, and the winner of the election based on popular vote. This will be based on the dataset provided by the Colorado Board of Elections. 

## Election-Audit Results
The results shows a comprehensive list of things. 

* There were a total of 369,711 votes which were casted during the vote. 
* There were votes from 3 counties,
  * 10.5% (38.855) votes from Jefferson,
  * 82.8% (306,055) votes from Denver, and
  * 6.7% (24,801) votes from Arapahoe.
* As can be seen, Denver has the largest county turnout. 
* There were 3 candidates,
  * Charles Casper Stockham, who got 23.0% (85,213) votes,
  * Diana DeGette, who got 73.8% (306,055) votes, and
  * Raymon Anthony Doane, who got 3.1% (11,606) votes. 
* As can be concluded, the winning candidate is Diana DeGette, who got 306,055 votes, accounting for 73.8% of the total votes. 

The picture below shows the result from the command line.

![result](/Resources/command_line.png)

The picture below shows the result from the output txt file.

![result](/Resources/txt.png)

## Election-Audit Summary
This script has limited functions at this point. However, with further development, it is able to discover more details and provide more insights on the election audit.

On the one hand, more functions can be developed. For example, a check-duplicate function can be applied towards to ballot ID to check if there's any ballot frauds. 

On the other hand, if provided with more data, such as the time of the vote, more analysis can be conducted to further examine the election. 
