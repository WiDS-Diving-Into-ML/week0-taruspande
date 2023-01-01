# Feedback for Problem 2

## Loading Data 

* The standard csv way to read a file is to use the reader class in the csv module, but if you observe the data, it's almost like a text file, just that it's structured column-wise as well.
* So a nice way to read this (especially since it has no header, which csv files usually have) is to treat it like a text file and read it line by line into a list, and then split the string with the ',' character, and you get what you want.
* That's what I was posting to everyone, since they either used the `csv` module or some other fancy library, you're the only person to call my bluff of making it a csv file and reading it like a normal text file, kudos :)

## Grouping the Data

* For this part, your idea is correct, but after you got the list of indices, you can directly put the list of indices into the array to get the values for those indices, so you didn't need to go through the entire thing again (You've essentially gone through all the indices using native Python, so in reality that's a 60000 loop) to get the values.
* Check these two links out as well, they talk about group by using pure NumPy : https://stackoverflow.com/questions/49372918/group-numpy-into-multiple-sub-arrays-using-an-array-of-values and https://stackoverflow.com/questions/49141969/vectorized-groupby-with-numpy?noredirect=1&lq=1

Overall, great job, and hope to see this level in the future assignments as well!
