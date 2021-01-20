# Py-Stories-
# This repository contains solutions to real life problems being worked out with Python. The aim is to train basic Python operator, work flow functions and have some fun=) 
#Funny Tasks for the operators and Work Flow 
# The Silvester is a nice guy of 18 who fall in love with his classmate Samantha. One year latter 
# Samantha got pragnant and gave birth to their first 2 kids . With an exeptional 
#health that they both had our couple got 10 kids at the age of 30. 
# Needless to say our guy Silvester should work like a hourse ann be really financial savy. I mean  seriously.  
 
# At the age of 30 Silvester has 10.000 euros in his bank account 
# His income is 3000 euro after taxes and general expenses before expneses on Kids. 
#  The monthly cost per one Kid is 500 Euro. 
#Please calculate how many income is left after costs on Kids. 
i=3000# for income before Kinds   
c=500# for cost per Kid 
n=10# Number of Kinds 
#Solution 
monthDeficit= i-c*n
monthDeficit


#Okay, nicely done, So our guy is 2000 deficite per month. Lets levelp up the game. How fast will the Silvesters's bank account
# run out of money  
MonthDeficit=2000# in absolute term 
b=10000 # for the bank account 
#Solution
financialRuin=b/MonthDeficit 
financialRuin

# Meaning in 5 monthes he will run out of money 


#Good, so our guy is in trouble and in 5 monthes he had no money in the bank. 
# Lets suppose Silvester is a man of the character and capble to get his staff together. 
#After looking for possible solutions he decided to go for selfemployment. Being a talanted Machine Learning Engineer 
# the only thing he need is a little bit of luck. 
#Because of the blood sweat and tears he is abble to increase his income with one percent every day. 
#Sounds like really small percentage? 
# Here is the question: 
# Would Silvester be able to provide for his Kinds without facing finacai ruin in 5 monthes. 
#Lets suppose than one month has 30 Days.
# Solution 
incSalary= 1.01**(30*5)
#incSalary
newSalary=s*incSalary
newSalary


#That what is called the power of compouninng. In five monthes he would be able to earn 13.345 euros
#before Kids related expense. 
# Well that is a good news. 
# The other interesting question would be 
#How many full days would it take for Silvester to breaken even his expenses  under the prerequisite of 1 percent salary increase daily. 

#Solution 

#Lets first calculate what is the Silvester's average income before Kids per day 
#CostDay= c*n/30
#CostDay=500*10/30
#CostDay
# lets find out the break even: 
# everage income per day 
#3000/30= 100

#Our average total Kids cost per day 
#(500*10/30)=166.67 
# So for our guy to get out of troble his daily salary should be higher than his daily expenses,
#Okay, that means: 

#Solution: 
# if the breakeven is the number of days than: 

#100*1.01**breakeven>(500*10/30)
# which means the moment 

#100*1.01**breakeven/(500*10/30)<1
# is not True we break even, so lets use while loop to find a solution to this problem: 

breakeven=0
while 100*1.01**int(breakeven)(500*10/30)<1:
    breakeven=breakeven+1
print(breakeven)



