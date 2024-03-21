# R-programming

 # Access the data from excel file in any data in the help of sql command.
getwd()
library("sqldf")
stu<-read.csv(file.choose())
stu<-read.csv("student.csv")
stu
View(sqldf("select * from stu"))
sqldf("select count (*) from stu")
sqldf("select * from stu where marks>80")
sqldf("select * from stu where marks<80")
sqldf("select * from stu where name=='anshul'")
sqldf("select * from stu where marks==45")
sqldf("select name from stu where marks==45")
sqldf("select roll.no from stu where marks==45")
sqldf("select distinct name from stu")
sqldf("select * from stu limit 4")
sqldf("select * from stu order by name desc")
sqldf("select * from stu where name like '%s'")
sqldf("select * from stu where name like 'v%'")
sqldf("select * from stu where name like '%k%'")
sqldf("select name as N, marks as M from stu ")
sqldf("select sum(marks) from stu")
sqldf("select avg(marks) from stu")
sqldf("select min(marks) from stu")
sqldf("select max(marks) from stu")


