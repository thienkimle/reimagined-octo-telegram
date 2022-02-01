# Assignment 7: C++ Variables
Due Date: March 7, 2021

## Problem 1
This program is made to demonstrate storing data, calculations, declaring variables, assigning expressions

```C++ 
#include <iostream>
using namespace std;
int main()
{
cout << "Thien Kim Le - March 5th, 2021 \n";
cout << "Assignment 7 Problem 1";
// Problem 1 part 2
// Declare variables
double num1, num2, num3;
double average1;
// Assign hard coded values to variables
num1 = 7; // hard coded
num2 = 45;
num3 = 3;
// Calculate the average
average1 = (num1 + num2 + num3) / 3;
// Print result
cout << "Average of 7, 45, and 3 = " << average1 << endl;
// Problem 1 part 3
// Generalized using abstraction
double average2;
cout << "Enter three numbers separated by a space: \n"; // prompt
cin >> num1 >> num2 >> num3;
// Calculate the average and print result
average2 = (num1 + num2 + num3) / 3;
cout << "Average = " << average2 << endl;
return 0;
}
```

## Problem 2
This program is made to demonstrate storing data, calculations, declaring variables, assigning expressions

```C++
#include <iostream>
using namespace std;
int main()
{
cout << "Thien Kim Le = March 5th, 2021 \n";
cout << "Assignment 7 Problem 2: Calculating distance \n";
// Declare variables
double speed, time, distance;
// Assign values for variables
speed = 70; // hardcoded since the assignment doesn't ask for user input for speed. 
// User input for time
cout << "Enter hours driven: \n";
cin >> time;
// Formula for distance
distance = speed * time;
// Caculations for distance
cout << "The car travelled " << distance << " miles after " << time << " hours." << endl;
return 0;
}
```

## Problem 3
This program is made to demonstrate storing data, calculations, declaring variables, assigning expressions

```C++
#include <iostream>
using namespace std;
int main()
{
cout << "Thien Kim Le - March 5th, 2021 \n";
cout << "Assignment 7 Problem 3: Finding the cube of x. \n";
// Declare variable
double x, cubex;
// user input for x
cout << "Enter a numerical value for x: \n";
cin >> x;
// cube of x value
cubex = x * x * x;
cout << "The cube of " << x << " is " << cubex << endl;
return 0;
}
```

## Problem 4
This program is made to demonstrate storing data, calculations, declaring variables, assigning expressions

```C++
#include <iostream>
#include <string>
using namespace std;
int main()
{
cout << "Thien Kim Le - March 5th, 2021 \n";
cout << "Assignment 7 Prolem 4: Calculate gross pay \n";
// declare name as a string variable
string name;
// declare variables for hrs, rate, pay
double hrs, rate, pay;
// User input for name
cout << "Enter your first name: ";
cin >> name;
// Greet the user with name
cout << "Hello " << name << ". \n";
// User input for hours
cout << "Enter Hours Worked: ";
cin >> hrs;
// User input for rate
cout << "Enter Rate: "; 
cin >> rate;
// Calculate gross pay
pay = rate * hrs;
// Output for gross pay
cout << "Pay: " << pay << endl;
return 0;
}
```

## Problem 5
This program is made to demonstrate storing data, calculations, declaring variables, assigning expressions

```C++
#include <iostream>
using namespace std;
int main()
{
cout << "Thien Kim Le - March 5th, 2021 \n";
cout << "Assignment 7 Problem 5: Calculating subtotal, sale tax, and total price for 5 items.\n";
// declare variables
double price1, price2, price3, price4, price5;
double subtotal, taxpercent, tax, total;
// user input for prices
cout << "Enter price for item 1: ";
cin >> price1;
cout << "Enter price for item 2: ";
cin >> price2;
cout << "Enter price for item 3: ";
cin >> price3;
cout << "Enter price for item 4: ";
cin >> price4;
cout << "Enter price for item 5: ";
cin >> price5;
// calculations 
subtotal = price1 + price2 + price3 + price4 + price5; // subtotal
taxpercent = 0.07; // hardcoded percentage
tax = subtotal * taxpercent; // amount of sales tax
total = subtotal + tax; // total amount for 5 items
// Output
cout << "Subtotal: " << subtotal << endl;
cout << "Sales Tax: " << tax << endl;
cout << "Total: " << total << endl;
return 0;
}
```
