# Election-Analysis

## Project Overview
A Colorodo Board of Elections employee, Tom, needs assitance with an election audit for congressional US precinct in Colorado. We are looking for the total votes cast, a list of the candidates that recieved votes, the number of votes per candidate,  the percentage of votes for each candidate, and the winner of the election based on popular vote. The election commission would like some additional information to complete the audit. The commission wants to know the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout as well. 

## Election Audit Results
The analysis of the election show that:
* There were 369,711 total votes cast in the election. 
* The counties votes were cast in were:
    - Jefferson
    - Denver
    - Arapahoe
* The counties results were:
    - Jefferson received 10.5% of the votes and 38,855 votes.
    - Denver received 82.8% of the votes and 306,055 votes.
    - Arapahoe received 6.7% of the votes and 24,801 votes.
* The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
* The candidate results were:
    - Charles Casper Stockham received 23.0% of the votes and 85,213 votes.
    - Diana DeGette received 73.8% of the votes and 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the votes and 11,606 votes.
* The winner of the election was:
    - Diana DeGette, who received 73.8% of the votes and 272,892 votes.

## Election Audit Summary
This script can be used for any election as long as the formatting is the same in the CSV file. The formatting must be the same so the same information can be pulled from the same colmuns in the Excel sheet. Since we calculated the winning county vote, we could modify the script to put it in our output as it is useful information. It would also be helpful to use the import keyword to made this code available in one mdule so that the code can be reused more easily without messing up the structure of the code.
