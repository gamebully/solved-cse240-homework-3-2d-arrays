Download Link: https://assignmentchef.com/product/solved-cse240-homework-3-2d-arrays
<br>
<h1>Introduction</h1>

The aim of this assignment is to make sure that you understand and are familiar with the concepts covered in the lectures, including basic C syntax, using the strings, arrays, and multidimensional arrays.  By the end of the assignment, you should have

<ul>

 <li>understood the concepts of data, data declaration, forward declaration, and manipulation of values stored in the memory.</li>

 <li>reviewed the array operations that you have learned in your previous programming classes;</li>

 <li>written a program using multidimensional arrays in C.</li>

</ul>

Note: <strong>Do</strong>​<strong> not</strong> use pointer in this assignment. Pointer assignment will be given in the next homework.

<strong>Reading</strong>:​ Textbook ​ Chapter 2, ​ sections 2.1, 2.2, 2.3, and 2.4, and lecture slides covered​  .​

<strong>Exercising</strong>:​ Complete the multiple choice questions in Textbook Section 2.12. The answers of the questions are available in course Web page.

You are expected to do the majority of the assignment outside the class meetings. Should you need assistance, or have questions about the assignment, please contact the instructor or the TA during their office hours.

You are encouraged to ask and answer questions on the course discussion board. However, in do not share your answers or code in the course discussion board. <strong>Do</strong>​<strong> not cooperate with your peers in doing the individual assignments. </strong>Programming Assignment

For this assignment, you can use ASU General GNU GCC environment or Visual Studio. Please specify the environment that you use at the beginning of your program:

// State the IDE that you use: Visual Studio or GCC

If you use any other environment, please test it either using GCC or visual Studio before submission. If you do not specify the environment, the grader will use either GCC or Visual Studio, but not both. If you program does not compile or execute correctly, your grade will be deducted.

GCC command to compile this program: <em>gcc hw03q1.c -std=c99 -o output</em>​

<ol>

 <li>You are given an hw03q1.c file, which contains a partially completed program. You are to follow the instructions contained in comments and complete the required functions. You will be writing functions for a program, which accepts four strings and an integer key as input from the user. The program will then use the integer key to encrypt the input strings (adding the key to each character in the string and a swapping function), decrypt the strings and then print the strings. There is also a matrix operation of determinant which uses 2D integer array. Example output given below.</li>

</ol>

Note, when you create the Visual Studio project, the default location of project is similar to the file path shown in example figure above. For your convenience, if you wish you may change the project location while creating the project at the beginning.