# League of Legends matches analysis
Repository to contain all the R scripts that we develop for the KE5107 course CA assessment on the League of Legends matches data.


## Description of files

1. LeagueofLegends Discovery.Rmd - contains all scripts to perform discovery on the raw dataset
2. Process.Rmd - contains all scripts to perform data processing and create more columns from the existing ones. This generates a processed file as output.
3. Processed Data Discovery.Rmd - Contains all scripts to do additional discovery on the processed data. Note that this should use the processed file as input.


## R programming style guide

1. This one (https://google.github.io/styleguide/Rguide.xml) from Google looks nice and we can try to follow this to have a standardized code base.

## Steps to get going

1. Git clone the repository
   `git clone https://github.com/nakamura41/LeagueofLegends_Matches_Analysis.git`

2. Checkout your branch - The branch name is the name by which we call each other: anurag, ryan, vaibhav, charles, pier, david
    `git checkout <<name>>`
    E.g. `git checkout david`

3. Write your code in this branch and then add, commit the changes like you would have done normally. Then use the below code to push your changes to the remote repository:
    `git push origin <<name>>`
    E.g. `git push origin david`

    Validate that your changes have made way to remote by checking in the GitHub web portal!

4. You can have a look at 'david' branch to get an idea of what should be present in your branch

### Kindly note
5. Please do not commit anything to the master branch. This is the sacred branch where we consolidate our code after the discussion!
