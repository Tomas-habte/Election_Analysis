# Election_Analysis
## Overview of Election Audit
The purpose of this election analysis audit is to provide the Colorado Board of Elections with key insights into how the election went. Some of the insights include the total number of votes cast and the winner of the election. We will conduct the analysis by creating and running a Python script.

## Election-Audit Results

- The total number of votes cast was 369,711.
- Denver had the largest number of votes with 306,055 making up 82.8% of the votes.
- Dianna DeGette won the election with 272,892 votes making up 73.8% of the votes. 

| County Breakdown  | Candidate Breakdown |
| ------------- | ------------- |
| ![County Breakdown](https://user-images.githubusercontent.com/111667387/190880631-22d271fb-0265-4cbb-99d1-00ea83ff4f12.png) | ![Candidate Breakdown](https://user-images.githubusercontent.com/111667387/190880632-94a17951-c310-4155-8d0a-9398ebd9f572.png) |

## Election-Audit Summary
**Below are two ways we can modify the the Python script to gather more insights:**

1. Include insights on ways that people voted. There are different methods of voting so the election comission may find it valuable to know the most and least popular ways of voting. An example of how the script would be modified is by adding the lines below: 
```
# Create a voting methods list
voting_methods = []

# Track the most popular voting method
pop_voting_method = ""
voting_method_count = 0
```
2. Include insights on the age of voters. This is an important metric that can reveal voter turnout rates by age for the election comission. An example of how the script would be modified is by adding the lines below: 
```
# Create an age groups list
age_groups = []

# Track the largest voting group
largest_voting_group = ""
largest_group_count = 0 
```
