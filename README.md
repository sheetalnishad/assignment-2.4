1. x <- c(‘data.science.in.R’, ‘machine.learning.in.R’)
Perform the below string Operation:
• Replace the period character "." within each string with another character i.e. "-" minus sign.
Ans.
 
x<-c("data.science.in.r","machine.learning.in.r")
x
#Replace "." with "-"
x<-chartr(".","-",x)
x

2. x <- c('data.science.in.R','machine.learning.in.R')
Perform the below String Operation:
• Append again with “-“ minus sign character at the start of the each string and finally concatenate all the
string within the vector to form a final single string and assigning it the project.
Ans. 
x<-c("data.science.in.r","machine.learning.in.r")

#"-" at the start of each string
x<-paste("-",x)
x

#Single string
x<-paste(x[1],x[2])
x
