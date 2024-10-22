# Cpp-Polymorphism
**PROBLEM SHEET FOR INHERITANCE AND POLYMORPHISM
**
1.	Write a C++ program that overloads the + operator and relational operators (suitable)
to perform the following operations:
a)	Concatenation of two strings.
b)	Comparison of two strings.

2.	Implement the complex number ADT in C++ using a class. The complex ADT is
used to represent complex numbers of the form c=a+ib, where a and b are real numbers. The operations supported by this ADT are:

a) Reading a complex number.
b) Subtraction of complex numbers.
c) Writing a complex number.
d) Multiplication of complex numbers.
e) Addition of Complex numbers.
f) Division of complex numbers.

Note: 
1.	overload << and >> operators in part a and part b.
2.	overload +, - , * , / operators in parts c, d, e and f.

3.	Write a class Time which represents time. the class should have three fields for hours, minutes and seconds. It should have constructor to initialize the hours, minutes and seconds. A method printTime() to print the current time. 
Overload the following operators: 
plus operator (+) (add two time objects based on 24 hour clock) 
and < (compare two time objects).

4.	Develop class Polynomial. The internal representation of a Polynomial is an array of terms. Each term contains a coefficient and an exponent. The term2x4 has the coefficient 2 and the exponent 4. Develop a complete class containing proper constructor and destructor functions as well as  set and  get functions. The class should also provide the following overloaded operator capabilities: 
Overload the addition operator (+) to add two Polynomials. 
Overload the subtraction operator(-) to subtract two Polynomials.
Overload the assignment operator to assign one Polynomial to another.
Overload the multiplication operator (*) to multiply two Polynomialse)

5.	Consider a class hierarchy involving motor vehicles. At the top of the hierarchy, class Motor_vehicle represents the most basic and general type of vehicles. Automobiles, Trucks, and Motorcycles are three types of vehicles that are extensions and specializations of the base class. Sport_automobiles are included in the class hierarchy as a subclass of Automobile. Design and implement this as a program with all these classes. Include attributes such as horse power, maximum speed, passenger capacity, load capacity, and weight. Include the relevant functions.

6.	 Design a hierarchy for animals. Find some behavior in all animals that is carried out in different manners (eat, move, reproduce, or others). Define the top-level animal category with an abstract base class and one or more interfaces. Define and implement the subclasses. Write the complete program.

7.	Create two classes, Apple and Orange. In Apple, create a constructor that takes an Orange as an argument. Create a function that takes an Apple and call that function with an Orange to show that it works. Now make the Apple constructor explicit to demonstrate that the automatic type conversion is thus prevented. Modify the call to your function so that the conversion is made explicitly and thus succeeds.

8.	Write base class that ask the user to enter a complex number and derived class adds the complex number of its own with the base. Finally make third class that is friend of derived and calculate the difference of base complex number and its own complex number.

9.	A company has several groups of employees, executives, managers, regular staff, hourly paid staff, and others. The company needs to maintain the data for all employees in a list. Design a solution to this problem that uses a heterogeneous array of employee objects. Use an abstract base class and apply polymorphism to process the list (array). Write the complete program. Repeat the previous problem defining an interface instead of an abstract base class. Compare the two solutions to the problem.

10.	Create a class STUDENT with data members student name, rollnumber, semester, class , branch. Create a derived class INTERNAL which stores the marks for one subject for 3 internal tests,tutorial marks,assignment marks.All these marks will be summed up to find the internal marks of an student(maximum internal mark is 50 for each subject).Create  a derived class EXTERNAL which stores the semester exam marks obtained by an student(maximum semester mark is 100 for each subject).Class RESULT should have the features of both classes INTERNAL and EXTERNAL.In RESULT class obtain both internal and external mark of an student.

11.	Check if the student has secured minimum 50 marks in both internal and external. If so declare the student has passed in the particular subject. Write a C++ program for the above scenario. Use appropriate functions to calculate and display the student result.
12. Write a program to declare classes x, y and z. Each class contains one character array as data members. Concatenate the strings of classes x and y and store it in the class z using multiple inheritance. Use Constructors and destructors.
13.  For the below scenario implement hybrid inheritance. Include your own member functions and display lecturer and student details.
 
![image](https://github.com/user-attachments/assets/85b617df-52a2-493a-a46b-5e90fb773a28)
