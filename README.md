# Election-Analysis
Analyze Election results for congressional district

## Election-Audit Results:

-There were 369,711 votes cast in this election.

### Results by county:
-Denver County (largest vote total and percentage):
  -306,055 votes
  -82.8%
  
-Jefferson County
  -38,855 votes
  -10.5%
  
-Arapahoe County
  -24,801 votes
  6.7%
  
### Results by Candidate:
-Diana DeGette (winning candidate)
  -272,892 votes
  -73.8%
  
 -Charles Casper Stockham
  -85,213 votes
  -23%
  
 -Raymon Anthony Doane
  -11,606 votes
  -3.1%
  
## Election-Audit Summary: 
This script could be easily adapted to any election. As long as the original data file is in a similar format (.csv file), the code will read whatever county names and candidate names are in the file, and then output the appropriate data. It would also read any number of counties or candidates; it is not limited to the number for this election. For example, this code:

![image](https://user-images.githubusercontent.com/84299125/124387680-b8e5aa00-dc9c-11eb-9062-fe3ca2e17195.png)

            
will continue to cycle through the file until it finds all iterations of each candidate and tallies their votes, regardless of the number of candidates.

It would also be possible to write a block of code that would give us the election data for each candidate in each county. In this particular election, that would not seem helpful, because the results were so lopsided. In addition, the large turnout for Denver County makes it possible for a candidate to receive no votes in the other two counties and still win the election if they carry Denver County. However, other congressional districts may have a far more balanced electorate, and it would be good to see a more detailed breakdown to strategize for upcoming elections.
