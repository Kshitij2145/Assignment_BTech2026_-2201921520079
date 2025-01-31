# Assignment_BTech2026_-2201921520079

PLATFORM USED-HACKERRANK
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

