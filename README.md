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
