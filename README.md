# getdata-011-Project

* how to run
> source("run_analysis.R")

* see comments in code for description of process

* decision on which variables to pick

Although many variable names contain mean or std, I selected only those that had the string "mean()" or "std()" in them since variable names without the parentheses denote some other type of mean calculation.

* decriptive variable names

I assumed the original researchers used good, descriptive variable names for their data and kept them as close to the original as possible. The only alterations I made were getting rid of parenthese and hyphens

can be read by
> data<-read.table("final.txt",header=TRUE)
