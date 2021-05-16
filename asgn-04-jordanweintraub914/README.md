# Assignment 4 (Spring 2021)
### *Jordan Weintraub*



## Topics Covered 
- Merging datasets 
    - getting comfortable with the arguments 
- Finding variance
- Importing/downloading files  


### Function used for 90% of the Homework
.merge(left_dataset, right_dataset)

### Useful tips to know
- name_of_dataset.drop_duplicates() will drop duplicates
- Always an inner join unless specified 

### Arguments
- on= '__' specify which key (column) you're merging on 
- how='inner' will merge on column with same key
- how='outer' returns all records with either a match in left or right dataframe (known as full join) 
- how='left' or how='right' returns dataframe containing all rows of respective dataframe 
- indicator='True' will let you know where it came from 
- validate='many_to_many', 'one_to_many', 'many_to_one', 'one_to_one 

### Types of merge validation 
1. 1:1: The keys in each dataset are all unique
2. 1:M: The keys in right dataset have some duplicates
3. M:1: The keys in left dataset have some duplicates
4. M:M: The keys in both datasets have some duplicates

### What if you want to merge on the same column data but two different names?
- left_on =, right_on=

### These three packages are used to download the CCM dataset 
- from io import BytesIO
- from zipfile import ZipFile
- from urllib.request import urlopen

