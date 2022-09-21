# Election analysis
## Overview 
  The purpose of this election audit was to display the vote data from an election in an efficient, readable manner. Instead of having to tally the votes from each person at manually categorize them by county, we ran a script that shows votes from each county along with the overall winner. 
## Results 
  * 369,711 votes were casted in this congressional election 
  * County votes 
    * Jefferson: 10.5% (38,855)
    * Denver: 82.8% (306,055)
    * Arapahoe: 6.7% (24,801) 
  * Denver is the winning county with 306,055 votes 
  * Candidate votes 
    * Charles Casper Stockham: 23.0% (85,213)
    * Diana DeGette: 73.8% (272,892)
    * Raymon Anthony Doane: 3.1% (11,606)
  * The winning candidate was Dianna DeGette with 272,892 votes winning 73.8% of the total votes 
## Summary 
  What is great about this script is that we can use if for any election, with some modications. To find the winner instead of using an if statement we could use a max() function to look for the maximum amount of votes that one candidate has. We could also add a further breakdown of candidates votes, by displaying the number of votes each candidate received from each county. In addition, we can also add a total population metric so we can see how the total number of votes stack up to the total population of a county. In our results Denver had the most votes, but what if Jefferson, which had 38,855 votes, had a population of 39,000. This county had great voter turnout but was overshadowed by Denver.
