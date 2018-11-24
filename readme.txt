This is my solution for problem 2, data cleansing. I was able to modify the TokenizerMapper
class to cleanse the data being sent to the reducer in such a way that each word is now
set to lowercase, any trailing whitespace is removed, and any non alpha-numeric characters
are also removed. This was accomplished with string methods that became available by casting
the Hadoop text object into a String.