# **FizzBuzz Solution**

### **The question reads:**

* > Write a program that takes a user’s input and prints the numbers from one to the number the user entered. However, for multiples of three print Fizz instead of the number and for the multiples of five print Buzz. For numbers which are multiples of both three and five print FizzBuzz.


## **The Plan**

Does my program have an interface? What will it look like? My FizzBuzz solution will be a browser console program, so we don’t need an interface. The only user interaction will be allowing users to enter a number.


What inputs will my program have? Will the user enter data or will you get input from somewhere else? The user will enter a number from a prompt (popup box).


What’s the desired output? The desired output is a list of numbers from 1 to the number the user entered. But each number that is divisible by 3 will output Fizz, each number that is divisible by 5 will output Buzz and each number that is divisible by both 3 and 5 will output FizzBuzz.

## **My Pseudo-Code**

```
*When a user inputs a number
*Loop from 1 to the entered number
*If the number is divisible by 3 then print "Fizz"
*If the number is divisible by 5 then print "Buzz"
*If the number is divisible by both 3 and 5 print "FizzBuzz"
*Otherwise print the number
```