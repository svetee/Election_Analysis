# Election_Analysis 


## Overview of Election Audit

A Colorado Board of Elections employee requested help in completing an election audit of a recent local congressional election. The following tasks are included in the completed election audit:

	1. Total number of votes cast. 
	2. Complete list of candidates who received votes. 
	3. Total number of votes each candidate received. 
	4. Percentage of votes each candidate won. 
	5. Winner of the election based on popular vote. 

## Election-Audit Results:

The election audit shows: 

* A total of 369,711 votes cast in the election.
* The candidates were:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane
* The candidate results were:
	- Charles Casper Stockham received **_23.0%_** of the vote and _85,213_ number of votes.
	- Diana DeGette received **_73.8%_** of the vote and _272,892_ number of votes.
	- Raymon Anthony Doane received **_3.1%_** of the vote and _11,606_ number of votes.
  
  
  
  ## The Winner
  
  
         The **winner** of the election was:

    **Diana DeGette**, who received **272,892** number of votes, **73.8%** of the total votes cast in the election.
	
  

## Challenge Overview



Seth, a Colorado Board of Elections employee, requested your help in completing an election audit of a recent local congressional election.

You provided Seth and his team with the findings of the following tasks in your *first draft* of the election audit:

	1. Calculate the total number of votes cast. 
	2. Get a complete list of candidates who received votes. 
	3. Calculate the total number of votes each candidate received. 
	4. Calculate the percentage of votes each candidate won. 
	5. Determine the winner of the election based on popular vote.
	
Although these outcomes are important, there are a few more key insights his team would like to review. The election commission of Seth's team asked if he could confirm the voter turnout for each county that voted in *this* congressional district.

The findings of the following tasks were added to the final election audit:
	
	1. Calculate the voter turnout for each county.
	2. Calculate the percentage of votes each county contributed to the election.
	3. Determine which county had the largest turnout.


#### Election Results

Total Votes: 369,711
	
County Results:
	
	Jefferson: 10.5% (38,855)
	
	Denver: 82.8% (306,055)
	
	Arapahoe: 6.7% (24,801)
	
Largest County Turnout: Denver

Candidate Results:

	Charles Casper Stockham: 23.0% (85,213)

	Diana DeGette: 73.8% (272,892)

	Raymon Anthony Doane: 3.1% (11,606)

Election Winner: 

	Diana DeGette

	Vote Count: 272,892

	Percentage: 73.8%
	
## Election-Audit Summary:
	
This script can be used for any election if the script is modified. Two examples to modify the scrip are below: 

* Load different data into the script by changing this command line to the new data source
	Assign a variable to load a file from a path.
	file_to_load = os.path.join("Resources", "election_results.csv")
* Include an option for election results not to account for counties since many countries don't have this system
  	Challenge: Track the largest county voter turnout and its percentage
	largest_county_turnout = ""
	largest_county_vote = 0

