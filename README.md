# D'Hondt Calculator
A Python Script that distributes electoral seats using the D'Hondt Method

According to Wikipedia: "The D'Hondt method... is a highest averages method for allocating seats in an electoral system and thus a type of party-list proportional representation." Many places use this method to allocate seats after an election.

You can use this calculator to get allocated seats of a hypothetical election using the D'Hondt method. 


**FORMATTING**

Make sure you use the following format or else the calculator will not work.

1) The file must be a CSV
2) The first column is the names of each district (called states here)
3) The second column is the number of seats for each district
4) The last column should be the total number of votes cast
5) The intermediate columns (3 - (length-1)) are the votes for each party, with the party name as the column header

Please contact me on Twitter (@MaronAoriak) if you have any issues. I might try to make the script more intelligent with regards to formatting and other issues, but don't hold me to it.
