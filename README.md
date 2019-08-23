# Data-Analytics-in-R
Learn Basics of R
Follow the commands below
#Basics on R
#Data Types
#Logical
a=TRUE
#TRUE,FALSE
print(class(a))
#Numeric
b=19.28
print(class(b))
#Integer
c=19L
print(class(c))
#Complex
d=19+28i
print(class(d))
#Character
#Examples: 'a',"bc","23.5".'TRUE'
e='TRUE'
print(class(e))
#Raw
#Raw are used to store fixed-length sequences of bytes
f=charToRaw("Sai Pranay")
#Let's check printing f
f
print(class(f))
#Data Structures
#Vector(Must have elements of same Data-Type)
ab=c(19,28)
ab
ac=c('true','sai')
ac
#typeof() command used to find the type of elements in given vector
typeof(ab)
typeof(ac)
#Lists
#Lists are R data types that stores a collection of objects of differing lengths and types using list() function.
ba=list(19,"28",'Sai')
ba
#Adding elements in lists
ba[1]="Sai1928"
ba
#Matrices
#Matrices are data frames which contain lists of homogeneous data in a tabular format.
rownames = c("r1", "r2", "r3")
colnames = c("c1", "c2", "c3")
ca <- matrix(c(1:9), nrow = 3, byrow = TRUE, dimnames = list(rownames, colnames))
ca
#Accessing Specific Element
ca[1,1]
ca[2,3]
#Arrays
# Create two vectors of different lengths.
da <- c(5,9,3)
db <- c(10,11,12,13,14,15)
# Creating an array from above vectors.
dc <- array(c(da,db),dim = c(3,3,2))
print(dc)
#Factors
ea <- c("West","East","North","East","West","West","West","East")
eb<- factor(ea)
print(is.factor(eb))
#Data Frames
fa <- c(19,28)
fb <- c("Sai","Pranay")
fc <- data.frame(fa,fb)
print(fc)
