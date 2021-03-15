# Analysis of Election Audit

## Overview
In this exercise, we are assisting *Tom* automize elections results in **Python** for a US Congressional precicnt in Colorado to audit. The plan is to use this vote count report in auditing Senatorial district and Local elections in additon to this Congressional precicnt.

We will be totaling the following voting methods to identify the total votes cast, total votes for each candidate, percentage of votes for each candidates and winner based on popular vote:

- Mail In Ballots
- Punch Cards
- Computer Counts

### Processing of Votes

We were supplied with ***CSV*** file that list election data by *Ballot I.D.*, *County* and *Candidate*

![image](https://user-images.githubusercontent.com/79024998/111093653-da652f00-850f-11eb-9140-c6f6a0745156.png)

The using **Python** we neede to create a code that loops through the data and publish in a clean formatted text file for easy comprehension.

The below code gives us the total votes cast in this congressional election.
![image](https://user-images.githubusercontent.com/79024998/111094254-45633580-8511-11eb-8acd-c3dff6c96815.png)

Which gave us the result of **369,711** total votes.

Next we needed a code the gave us the breakdown of the number of votes and the percentage of total votes for each county in the precinct.

![image](https://user-images.githubusercontent.com/79024998/111094545-e3570000-8511-11eb-9641-9d03e21f86f6.png)

With the following breakdown:

![image](https://user-images.githubusercontent.com/79024998/111094711-3af56b80-8512-11eb-950b-70f65913ec14.png)

The above code also identified the county had the largest number of votes, which was **Denver**!

Lastly we needed to identify the number of votes and the percentage of the total votes each candidate received with declaring the of the election.

The below code allowed us to answer each of the above questions.

![image](https://user-images.githubusercontent.com/79024998/111095235-69c01180-8513-11eb-894a-e1b35d74eaec.png)

With the ***WINNER*** being....

![image](https://user-images.githubusercontent.com/79024998/111095381-b0157080-8513-11eb-9b2f-12d30efe6012.png)

### Election-Audit Summary

By taking the PyPoll Challenge script and re-factoring the code, this report can be used in any district in Colorado using a similiar ***CSV*** file to read the data from.

The script could be altered to provide the average of voters that voted in a county and also the margin of vitory between each of the candidates.

