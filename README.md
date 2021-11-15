# election_analysis

## Project Overview

Must perform an election audit of a recent local congressional election. The script must perform the following functions:

1. Calculate total number of votes cast
2. Get a complete list of candidates who receieved votes
3. Calculate the percentage of votes for each candidate.
4. Determine the winner of the election based on popular vote.
5. Calculate the total votes by County
6. Get a complete list of counties where voting was done
7. Determine the county with the highest voter turnout

## Resources

- Data provided in the 'Resources' folder as election_results.csv
- Programming done using Python 3.8.2 using Visual Studio Code for Mac (Version: 1.62.2) 

# Summary
The election analysis done shows that the vote count at **369,711**. 

The candidates from the ballot given included:
- **Charles Casper Stockham**
    - 23.0% (85,213)
- **Diana DeGette**
    - 73.8% (272,892)
- **Raymon Anthony Doane**
    - 3.1% (11,606)

The winning candidate for the election was **Diana DeGette**, with a vote count of 272,892 (73.8% of Total).

The counties from the ballot given includes:
- **Jefferson**
    - Received 10.5% of votes (38,855)
- **Denver**
    - Received 82.8% of votes (306,055)
- **Arapahoe**
    - Received 6.7% of votes (24,801)

The election analysis done shows that the highest turnout was at **Denver**, with a voter turnout of: **306,055 (82.8 % of Total)**


## Challenge Overview
- Write a Python script to automate the process of tabulating the Election results using the required metrics. 
- Save results to text file and output results in the Terminal

### Step 1:
- Initialize a list of counties
- Initialize a dictionary for votes in each county

### Step 2: 
- Initialize an empty string to hold the county name with the largest turnout
- Initialize an integer variable to hold the number of votes of the county with the largest turnout

### Step 3:
- Read election results for each row inside for loop and get each county name

### Step 4:
- Add distinct county name to the list of counties using a logical operator
- Initialize county vote to zero

### Step 5:
- Write loop to track the vote totals by county

### Step 6:
- Save county and total votes and percentage of total to the election_results text file

### Step 7:
- Create conditional statement to output the county with the largest turnout

### Step 8:
- Save largest turnout county results to the election_results text file