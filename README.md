# Perfume
Business Understanding:
Recently I was interested in how the Cosmetics Market especially the perfumes Market performance , so i use some research to get the data from one of the biggest perfume dealer and try to find some insight.


Data Understanding:
this data is the 2018 some perfume dealer's sales data:

data-base: CSVFile_2019-01-23T18_06_44.csv

columns:

TXD_Date:  the date of the saled goods, format is YYYYmmdd 

CounterName: the counter of the saled goods

MemberID: the member'id, 0 means he/she is not a member

Age: the age of the member

Sex: the gender of the member

ClassName_1:	the first class of the product

ClassName_2:	the second class of the product

ProductName:	the name of the product

Quantity: the quantity of the saled product 

AmountPortion:  the money of the saled product 

Prepare Data:
force on the member data,fill na with the 'Unknown' because the memberdata is only 20% of the all data and i don't want to lose any of them.

Data Modeling
import matplotlib,pandas and numpy
use the matplotlib to visualization the data

Evaluate the Results:

1，member orders/sales proportion

only 30% of the sales have the member information

2，member’s Purchase frequency

Turn's out the mean of the times a member will buy is 2.3,it is means 5 or 6 months later, a member will buy the perfume again. And the average money a member pay for the perfume is 688.18 CNY. 

3，age and sexual distribution of the members.

most of the members are 20~35 years old.80% of the member are female.

4， member's favorite brand

Bvlgari is the most popular brand in china's perfume market own's 23.8% of the market.

5， member's favorite product

Men's perfume from Bvlgari(so surprised)

6，summary
the age and sexual distribution of the perfumes market is the same(most of the members are 20~35 years old.80% of the member are female),but alone with self use,i really think now days the perfumes are more like a gift for male and female.
