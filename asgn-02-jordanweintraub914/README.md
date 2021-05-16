# Assignment 2 (Spring 2020)


### Cheat Sheet 
For defining a log variable with a 0 or negative value...
- .mask() function replaces the values df.mask(df condition...) 
- replace function also useful 
- .unique() vs .nunique() prints out the unique terms and the # of of nonduplicates 
- for pandas, & and | should be used instead of "and" and "or"
- when using the datetime, it goes datetime(year, month, day)
- df.loc[(df.column == 'value') & or | then a new condition] is helpful for labeling/indexing 
- df.groupby(['col', 'col2'])['output col3'] group by col1 and col2 and find col3
- **Using Yahoo's stock price api takes forever to load 



### Repo Purpose
The purpose of the asgn-02-'username' repository is to store our files that are related to this homework. We are analyzing the changes we make within our repo. We take the already made master repo from online, fetch the changes to our local computer, modify it by completing the assignment, and pushing the changes to the cloud so that the master repo shows the latest version.

The key inputs are going to be: 
- Instructions folder
    - Instructions.md
    - rubric.md
- asgn02exercises.ipynb
- stock_prices.ipynb
- README.md


### Necessary Steps to Follow 
- Make sure the latest version of pip install which looks for the latest version of the library package and installs it
    - Good way to check if a package installed properly is to try to import it. If it imports, you're good. Otherwise, you probably didn't install it correctly (easy fix with google)

Packages used incude: 
- pandas
- numpy 
- matplotlib
- statsmodels
- datetime 







