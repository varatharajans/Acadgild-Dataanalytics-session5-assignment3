# Acadgild-Dataanalytics-session5-assignment3
DATA ANALYTICS WITH R, EXCEL AND TABLEAU SESSION 5ASSIGNMENT 3

1. Test whether two vectors are exactly equal (element by element).
vec1 = c(rownames(mtcars[1:15,]))
vec2 = c(rownames(mtcars[11:25,]))
identical(vec1, vec2)

2. Sort the character vector in ascending order and descending order.
vec1 = c(rownames(mtcars[1:15,]))
vec2 = c(rownames(mtcars[11:25,]))
sort(vec1)-ascending
sort(vec2, decreasing=TRUE)


3. What is the major difference between str() and paste() show an example.
Str() will you the data type in the data frame.
Paste() will print the elements of data frame.


4. Introduce a separator when concatenating the strings.
Paste(“This is first class”, sep = “-“)
Cat(“This is first class”, sep=”-“)
