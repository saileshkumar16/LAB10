# LAB10
## DATE: 12-13 October
## Aim: Operator Overloading
## Algorithm :

Initialize Date Class:

Create a class called Date with private variables for day, month, and year.
Implement a constructor to set the initial date, and a display function to print the date.

Leap Year Check:
Create a function (isLeapYear) to check if a given year is a leap year.
A leap year is divisible by 4, but century years must also be divisible by 400.

Days in Month:
Create a function (daysInMonth) to determine the number of days in the current month.
February has 29 days in a leap year and 28 days otherwise.
April, June, September, and November have 30 days, while other months have 31 days.

Overloaded ++ Operator:
Overload the ++ operator as a member function in the Date class.
Increment the day by 1.
Check if the new day exceeds the number of days in the month.
If yes, reset the day to 1 and increment the month.
If the month exceeds 12, reset the month to 1 and increment the year.

Main Function:
In the main function, create an instance of the Date class with an initial date.
Display the current date.
Use the overloaded ++ operator to increment the date by one day.
Display the updated date.

This algorithm provides a simple way to manage dates, ensuring that the day, month, and year are correctly updated when the date is incremented by one day. The logic considers variations in the number of days in different months and leap years.

## Explanation 

Initialize Date Class:
Imagine we have a special box called "Date" that holds three pieces of information: day, month, and year.
When we create a new date, we put in the starting values for day, month, and year.

Leap Year Check:
We want to figure out if a certain year is a special type called a "leap year." It's like asking, "Is this a special year that has an extra day?"
If the year is divisible by 4 (like 2004, 2008), it's a leap year. But if it's a century year (like 1900, 2000), it should be divisible by 400 to be a leap year.

Days in Month:
Now, let's think about how many days are in each month. February is a bit tricky because it can have 28 days or 29 days in a leap year.
Other months have different numbers of days: some have 30, and some have 31.

Overloaded ++ Operator:
We want a special way to add one day to our date. So, we create a rule: when we add a day, we increase the day value by 1.
But, we need to be smart. If the day becomes too big for the month, we reset it to 1 and add 1 to the month.
If the month becomes too big (more than 12), we reset it to 1 and add 1 to the year.

Main Function:
In the main part of our program, we create a date (our special box) and set it to a specific day, month, and year.
We show what the date looks like (display it).
We then add one day to our date using our special rule.
Finally, we show the updated date.

In simple terms, it's like managing a calendar. We set a date, check for special years, know how many days each month has, and when we want to move to the next day, we follow some rules to keep things in order.

## OUTPUT
![Screenshot (80)](https://github.com/saileshkumar16/LAB10/assets/144588637/c6f71204-a1d0-499b-8738-47394fefc424)
