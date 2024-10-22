Amazon Agency test task
========================

This task was completed by Vitalii Halaiko.

## Task description
1) Clone the repository: https://github.com/developeragencyamazon/test-task-agencyamazon.git
2) Complete task (unit tests should be successful)
3) Publish your solution on GitHub (personal account)

## Solution
1) Clone the repository: https://github.com/developeragencyamazon/test-task-agencyamazon.git
2) Initialize my repository 
3) Update remote
4) Update file CampaignStatService.java (There was a bug in this file in the creation of the map for storing stats. The problem was that when filling the map for statistics, even if there was no file before, the add() method was called, because of which the data was doubled. I fixed this by adding a check to see if there are already statistics for the required company. If yes, I increased the data, if not, I just created a new object with the required data.)