# Age_Calc
datetime is a Python module used to perform operations on date and time objects.
datetime module is imported for the purpose of calculation of number of days, months and year by finding the difference from today's date to the birthdate.
Issue arises when the value of either year or month or days go negative(one cannot measure the age with negative values), if the birthdate mentioned is greater than today's date(the day mentioned is from future), the code asks the user to Enter the Valid Date. If the number of days is negative , then it is subtracted from total number of days from previous month and the value of calculated month is decreased by 1 and if month value goes negative , it is added with 12 and calculated year value is decreased by 1.
A function is designed with this Parameters and birthdate is taken as arguement for calculating the Age.
