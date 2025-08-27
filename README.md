#Aim: To study and implement Classes and Objects
## SOFTWARE USED: VS CODE
### THEORY:In Object-Oriented Programming (OOP), classes and objects form the foundation for representing real-world entities and concepts in a program.

A class acts as a blueprint or template used to create objects with similar features and behavior. In simple terms, a class defines the structure, while an object is a concrete instance of that structure. A class in C++ is a user-defined data type that bundles together variables (known as data members) and functions (called member functions or methods). Data members store the attributes of the class, while member functions describe the actions or behavior associated with it.

When a class is declared, only the design is specified (its attributes and methods), but no memory is assigned until an object of that class is created. Objects are the actual entities that occupy memory and allow interaction with the class’s data and functions. A class can have multiple objects. Apart from the commonly used global classes, C++ also supports local classes, which are defined inside a function and can only be accessed within that function.

Access specifiers are an important part of classes, as they control the visibility and accessibility of data members and functions. They ensure data protection and structured programming. C++ provides three access levels:

public – members are accessible from anywhere in the program.

private – members cannot be accessed directly outside the class.

protected – members remain hidden from outside access but are available to derived (inherited) classes.

Implementation of these concepts can be seen through examples such as:

1)Displaying student details using a class.

2)Storing and showing car information using classes and methods.

3)Creating a calculator with arithmetic operations using class functions.

4)Finding the area of a rectangle with the help of classes and methods.

5)Computing the volume of a cuboid while applying private and public members.

Algorithms for Implementation:

1)Algorithm: Student Information using Class and Object

Start.

Define a class Student with public members: name, branch, subject, year, result.

In main(), create an object s1 of Student.

Assign values to s1 (e.g., name = "Yash Rastogi", result = 9.5) and display them.

Reassign new values (e.g., name = "Yashpratapsingh", result = 6.9) and display again.

End.

2)Algorithm: Calculator using Classes

Start.

Create class Calculator with members a, b, and functions for input, addition, subtraction, multiplication, and division.

Define input() to take two numbers from the user.

Define respective operations in member functions.

In main(), create object c1, call input, perform all operations, and print results.

End.

3)Algorithm: Car Information using Classes

Start.

Define class Car with members: brand, year, and model.

Create function info() to input and display details.

In main(), create object c1, call info(), and show stored details.

End.

4)Algorithm: Rectangle Area using Classes

Start.

Define class rec_area with members length, breadth, and area.

Create function area1() to input values and calculate area = length × breadth.

In main(), create object r1, call area1(), and display result.

End.

5)Algorithm: Cuboid Volume using Classes

Start.

Define class cuboid with private members: height = 10, width = 20, length = 45.

Add public function volume() to calculate volume = height × width × length.

In main(), create object c1, call volume(), and display result.

End.

Conclusion:
These examples clearly illustrate how classes and objects work in C++ by combining attributes and methods into a single unit. They also demonstrate the importance of access specifiers (public, private, protected) in controlling accessibility. Together, these features form the basis of OOP in C++.
