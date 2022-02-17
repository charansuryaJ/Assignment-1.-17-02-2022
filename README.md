# Assignment-1.-17-02-2022
Assignment 1 : Write a program to print sum of even numbers and odd 
maximum=int (input ("please enter the maximum value:"))
even_total = 0
odd_total = 0
for number in range (1, maximum + 1):
if (number % 2 == 0):
even _total = even_total + number
else:
odd_total = odd_total + number
print ("the sum of even numbers from 1 to (0) = (1)". format (number,even_total))
print ("the sum of odd numbers from 1 to (0} = (1)" .format (number, odd_total))
OUTPUT:
please enter the maximum value: 10
the sum of even numbers from 1 to 10 =30
the sum of odd numbers from 1 to 10 = 25
