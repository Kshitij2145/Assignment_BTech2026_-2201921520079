# Assignment_BTech2026_-2201921520079

PLATFORM USED-HACKERRANK,CODECHEF
Language Used-C++

PROBLEM 1-APPLY INHERITANCE ON THE HUMAN BEING CLASS USING OOPS->

SOLUTION-MADE A BASE CLASS HUMANBEING AND TWO CHILD CLASSES MALE AND FEMALE.THEN USED INHERITANCE FEATURE IN OOPS TWO INHERIT ALL THE PROPERTIES AND FUNCTIONS OF BASE CLASS INTO CHILD CLASS. CHILD CLASS MALE AND FEMALE ALSO HAD THEIR OWN METHODS ALONG WITH THE PROPERTIES OF BASE CLASS. WE THEN MADE THE OBJECT OF BOTH THE CLASSES , SET AND ACCESED THE METHODS AS WELL AS THEIR AGES.


PROBLEM 2-Write the following code in your editor below:

A class named Arithmetic with a method named add that takes  integers as parameters and returns an integer denoting their sum.
A class named Adder that inherits from a superclass named Arithmetic.

SOLUTION-
1-MADE A BASE CLASS NAMED ARITHMETIC.
2-THEN INCLUDED MEMBER FUNCTION TO RETURN THE SUM OF TWO INTEGERS PASSED BY USER
3-INHERITED THE BASED CLASS AND NAMED IT ADDER
4-CREATED CHILD CLASS OBJECT IN MAIN FUNCTION AND CALLED BASE CLASS METHOD USING INHERITANCE
5-OUTPUT WAS SCUCCESFULLY GENERATED


Problem 3-A Java abstract class is a class that can't be instantiated. That means you cannot create new instances of an abstract class.

ollowing is an example of abstract class:

abstract class Book{
    String title;
    abstract void setTitle(String s);
    String getTitle(){
        return title;
    }
}
If you try to create an instance of this class like the following line you will get an error:

Book new_novel=new Book(); 
You have to create another class that extends the abstract class. Then you can create an instance of the new class.

Notice that setTitle method is abstract too and has no body. That means you must implement the body of that method in the child class.

In the editor, we have provided the abstract Book class and a Main class. In the Main class, we created an instance of a class called MyBook. Your task is to write just the MyBook class.

Your class mustn't be public.

Sample Input

A tale of two cities
Sample Output

The title is: A tale of two cities

Solution-
1-FIRSTLY WE CREATE A ABSTRACT CLASS BOOK WHICH CONTAINS A ATTRIBUTE TITLE, DECLARING A PURE VIRTUAL MEMBER FUNCTION SETTITLE SETTING THE TITLE AND A MEMBER FUNCTION GETTILE RETURNING TITLE VALUE.

2-THEN WE MOVE ON TO CRETAE A CHILD CLASS EXTENDING BASE ABSTRACT CLASS  IMPLEMENTING THE BASE CLASS VIRTUAL FUNCTION SETTITLE INSIDE IT.

3-IN MAIN FUNCTION AN OBJECT OF CHILD CLASS IS CREATED.

4-IT SETS THE TITLE USING OBJ.SETTITLE(PARAMETER).

5-FINALLY IT PRINTS THE TITLE NAME USING GETTITLE MEMBER FUNCTION.



PROBLEM 4-
// 1. Create a Simple Bank Account System
// Problem:
// Create a class BankAccount with the following attributes and methods:

// balance (private)
// deposit(amount)
// withdraw(amount)
// displayBalance()
// Implement encapsulation to protect balance from direct modification.

SOLUTION-

1-CREATED A CLASS NAMED BANKACCOUNT CONSISTING OF DATA MEMBER BALANCE SET AS PRIVATE, MEMBER FUNCTIONS DESPOSIT(),WITHDRAWL() AND DISPLAYBALANCE().

2- CREATED A CONSTRUCTOR OF BANKACCOUNT CLASS INITIALIZING BALNCE WITH ZERO.

3- DEFINED DEPOSIT METHOD CONTAINING ONE PARAMETER AMOUNT WHICH IS ADDED TO CURRENT BALANCE.

4-DEFINED WITHDRWAL METHOD WITHDRAWING THE MONEY IF CURRENT BALANCE IS GREATER THAN OR EQUAL TO THE AMOUNT DEPOSITED.

5-CREATED AN INSTANCE OF THE CLASS BANKACCOUNT AND CALLED OUT ALL MEMBER FUNCTIONS.



PROBLEM 5-// Implement a Student Management System
// Problem:
// Create a class Student that has:

// name (string)
// rollNumber (int)
// marks (array of 3 subjects)
// Method to calculate average marks.
// Method to display student details.
// Create an array of Student objects and print the details of each student.

SOLUTION-
1-CREATED A STUDENT CLASS CONTAINING ATTRIBUTES NAME,ROLL NO. AND  AN ARRAY OF SIZE 3 CONTAINING MARKS IN EACH SUBJECT.

2- NEXT UP,WE DEFINED 2 METHODS NAMED CALCULATEAVERAGEMARKS() FOR CALCULATING THE AVERAGE MARKS AND DISPLAY() FOR DISPLAYING ALL DETAILS OF THE STUDENT.

3-CREATED A OBJECT USING VECTOR OF TYPE STUDENTS CONTAINING DIFFERENT STUDENTS AND THEIR DETAILS PASSED USING THE CONSTRUCTOR.

4-FINALLY WE DISPLAY ALL THE DETAILS OF THE STUDENT OBJECT USING DISPALY METHOD.


PROBLEM 6-Write a C++ program to create a class called Triangle that has private member variables for the lengths of its three sides. Implement member functions to determine if the triangle is equilateral, isosceles, or scalene.


SOLUTION-
1-The program defines a Triangle class to determine the type of a triangle based on its three side lengths.

2- It uses a constructor to initialize the side lengths of the triangle.

3- The triangletype() method returns one of the three types of triangles:
     Equilateral Triangle (all three sides are equal)
     Isosceles Triangle (two sides are equal)
     Scalene Triangle (all sides are different)


4- The main() function creates a Triangle object with predefined values and prints the triangle type.

PROBLEM 7-
Write a C++ program to implement a class called Date that has private member variables for day, month, and year. Include member functions to set and get these variables, as well as to validate if the date is valid.

Solution 7-

This C++ program defines a Date class to handle date-related operations.

It includes member functions to set, retrieve, and validate a date.

The isValidDate() function checks if a given date is valid, considering leap years and month-day constraints.

The main() function takes user input for day, month, and year, then validates and displays the date.

If the date is valid, a confirmation message is displayed; otherwise, an invalid date message is shown.


// Problem 8.
//  Write a C++ program to implement a class called Shape with virtual member functions for calculating area and perimeter. Derive classes such as Circle, Rectangle, and Triangle from the Shape class and override virtual functions accordingly.


Solution-

1-Implements an abstract base class Shape with pure virtual functions (area() and perimeter()).

2-Uses constructors to accept shape dimensions dynamically.

3-Circle, Rectangle, and Triangle classes override area() and perimeter() functions.

4-Heron's formula is used for triangle area calculation.

5-Demonstrates polymorphism by enforcing method implementation in derived classes.

PROBLEM 9-
Eligibility Checker for Students
You are tasked with designing a simple program that determines the eligibility of students based on their scores and ages.

Class Definitions:

Student class:
Attributes:
name (String): The name of the student.
score (int): The student's academic score.
age (int): The age of the student.
Methods:
eligible(): A method that checks the student's eligibility and prints "YES" if the score is greater than 10 and the age is greater than 20. Otherwise, it prints "NO."

SOLUTION-

1-Student Class Implementation - Defines a Student class with attributes: name, score, and age.

2-Eligibility Check - The eligible() method checks if a student qualifies based on a score greater than 10 and age above 20.

3-Object Creation & Initialization - Creates a Student object in main(), assigning values to name, score, and age.

4-Output Behavior - Prints "YES" if the student meets the criteria, otherwise prints "NO".

5-Simple OOP Concept - Demonstrates basic class, object, and method usage in C++.


Problem 10-

Player BMI Calculation
Write a Player class containing height and weight as attributes. Also this class contains a BMI method which returns an integer BMI of this person.

Solution-

1-Player Class: Defines a class Player with private attributes height and weight.

2-Constructor: Initializes height and weight using the constructor.

3-BMI Calculation: Method calculateBMI() computes BMI using weight / (height * height).

4-Object Creation: An instance of Player is created with height 5 and weight 54.


Problem 11-
The Car class has two constructors: one to set the car's name and another called the copy constructor.

The copy constructor is called when we create a new car object (copiedCar) and initialize it using an existing car object (originalCar).

The copy constructor copies the car's name from the existing car to the new car, creating a new car that's a copy of the original one.

In the main() function, we create an originalCar, display its name, and then create a copiedCar using the copy constructor and display its name.

Solution-

1️- Car class has a parameterized constructor and a copy constructor to initialize and copy name and color.

2️- Newcar inherits from Car but must explicitly call Car's constructor for proper initialization.

3️- Newcar's parameterized constructor calls Car(name, color), ensuring base class attributes are set correctly.

4️- Newcar's copy constructor calls Car(obj), ensuring proper copying of inherited attributes.

5️- Demonstrates correct object copying in inheritance, preventing shallow copy issues.


Problem 12-
Static Balance Tracker

Create a BankAccount class that simulates a simple bank account. The class should have the following features:

A static data member totalBalance to keep track of the total balance across all accounts.

A constructor that takes an initial balance as a parameter and updates totalBalance accordingly.

There are 2 BankAccounts in the Bank. Given the balance of both the accounts as input, create the object using constructor to update totalBalance and print totalBalance of Bank.

SOLUTION-

1- Overview: This program simulates a simple bank account system with a shared total balance across all accounts.

2- Static Data Member: Uses a static variable totalBalance to keep track of the total balance of all accounts.

3- Constructor: Automatically updates totalBalance when a new account is created.

4- Static Method: showTotalBalance() displays the total balance and is accessible without creating an object.

5- Usage: Simply create BankAccount objects with initial balances, and call BankAccount::showTotalBalance() to check the total balance.


Problem 13- Circle Area Calculation

You are given a class Circle having radius as attributes, constructors and a getArea function which return the area of the circle. Task Create two circles c1 and c2. c1 is created using the default constructor, which initializes its radius to 1.0. c2 is created using the constructor with one parameter, which initializes its radius to 5.0. The getArea() function is used to calculate the area of each circle.

Output Format Print the area of c1 at first line. Print the area of c2 at second line.

Solution-

Class Definition: The Circle class is defined with a private member radius and public constructors and methods.

Constructors: The class has a default constructor that initializes radius to 1.0 and a parameterized constructor that sets radius to a given value.

getArea Method: This method calculates and returns the area of the circle using the formula π × radius² (approximating π as 3.14).

Object Creation: Two objects, c1 (default radius 1.0) and c2 (radius 5.0), are created.

Output Calculation: The areas of both circles are computed and printed, resulting in 3.14 for c1 and 78.5 for c2.


Problem 14-
Question:
You are developing a payment processing system that supports multiple payment methods like Credit Card and UPI. The system should ensure that all payment methods follow a common interface but have different processing implementations.

Requirements:
Create an abstract class Payment with the following:

A pure virtual function processPayment(double amount)
A function displayTransaction(double amount, string method) that prints the payment details
Create two derived classes, CreditCardPayment and UPIPayment, that inherit from Payment:

CreditCardPayment deducts 2% transaction fees
UPIPayment has no transaction fees
Demonstrate functionality:

Create objects of both classes
Process payments and display transactions


Solution-

1-The program defines an abstract class Payment with a pure virtual function processPayment() for enforcing a common payment structure.

2-Two derived classes, CreditCardPayment (which deducts a 2% fee) and UPIPayment (which processes payments without fees), implement this function.

3-The displayTransaction() method in Payment provides a standard way to display transaction details.

4-The main() function creates objects of both derived classes and processes payments dynamically.

5-The program demonstrates abstraction and polymorphism, ensuring different payment methods follow a unified structure. 

