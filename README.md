# PyPoll with Python
## Overview
For this challenge, I was tasked with creating a Python script to determine the results of an election audit. The elections data file contained over 300,000 rows of information and reviewing all of it would have been very time-consuming and tedious. The script I created was able to loop through all this data with the click of a buttong and show me the total votes, votes submitted per county, the votes each candidate received, and most importantly the winning candidate.

## Audit Results
Once the script was completed, all the major results were printed in a new data file to cleanly display the data. The details for the election are:
- 369,711 votes were cast in this congressional election.
- The total votes cast for each county were:
  - Jefferson: 10.5% with 38,855 votes 
  - Denver: 82.8% with 306,055 votes
  - Arapahoe: 6.7% with 24,801 votes
- Denver had the largest quantity of votes with 306,055 votes.
- The total votes cast for each candidate were:
  - Charles Casper Stockham received 23.0% with 85,213 votes
  - Diana DeGette received 73.8% with 272,892 votes
  - Raymon Anthony Doane received 3.1% with 11,606 votes
- Diana DeGette is the election winner! Receiving 73.8% of all votes with 272,892 votes.
![Election_results](https://user-images.githubusercontent.com/88118759/133906429-f7fd58d7-5798-458c-a4b0-103680b5d567.PNG)
## Election Audit Summary
To conclude, this module was challenging mainly due to not knowing how to use Python but as I learned it has hundreds of applications where large amounts of data are involved. In this election there were only 3 candidates to vote for and 3 counties voting, with hundreds of thousands of rows of data to evaluate. Now in a larger election with more counties this data could be increased significantly and having a script such as mine would be beneficial to quickly and accurately determine the results. 

The code I wrote for this program could be updated to include more information if it were needed. In this case, the script could be expanded in order to determine which candidate received the most votes per county, breaking down even further the data and calculating a percentage of popularity in the different counties. Another example of modification that could provide significant information would be to add demographics such as age or gender into data set, then show which candidate was most popular among these categories.
