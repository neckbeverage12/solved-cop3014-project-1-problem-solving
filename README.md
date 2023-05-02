Download Link: https://assignmentchef.com/product/solved-cop3014-project-1-problem-solving
<br>
An important goal of this course is to develop students’ ability to solve problems using C++ programming. In this project, you are asked to solve a number of problems to develop this skill as well as review basic C++ constructs such as loops, decision statements, arrays, and expressions.

<h1>Learning Objectives</h1>

The focus of this assignment is the following learning objectives:

<ul>

 <li>Be able to solve problems using C++ programming</li>

 <li>Be able to identify appropriate C++ constructs for a specific problem.</li>

</ul>

<h1>Prerequisites</h1>

<ul>

 <li>To complete this project, you need to make sure that you have the following:</li>

 <li>C++ and the g++ compiler</li>

 <li>A C++ IDE or text editor (multiple editors exist for developers)</li>

 <li>An understanding of the basic C++ constructs.</li>

</ul>

<h1>Problem Description</h1>

Given the following problems, write C++ programs to solve <strong>any</strong> <strong>seven </strong>of these problems.




<ol>

 <li>Write a C++ program called <strong><em>cpp</em></strong> that reads an integer number into your program and prints out all factors of the number.</li>

</ol>




<ol start="2">

 <li>Write a C++ program called <strong><em>cpp</em></strong> that reads an integer number into your program and counts the number of digits in the number. Example 1: 435 à3, Example 2: 1992 à 4</li>

</ol>




<ol start="3">

 <li>Write a C++ program called <strong><em>cpp</em></strong> that continuously accepts integers from the user and fills them into an integer array of 5 elements. The program stops accepting integers when the user enters a zero. At that point, the program prints the current content of the array. Filling of the array happens in a circular way. That means when the program reaches the end of the array, it wraps around and begins to override the numbers entered earlier. Initialize the array to zeros before beginning to accept input from the user.</li>

</ol>




<strong>Example 1:</strong> Assume that the array size is 5. If user input is 1,2,3,0 à then the contents of the array = {1,2,3,0,0}

<strong>Example 2:</strong> Assume that the array size is 5. If user input is 1,2,3,4,5,6,7 à then the contents of the array = {6,7,3,4,5}  (after 5, the program wraps around and begin to fill the array from the beginning).

<ol start="4">

 <li>Write a C++ program called <strong><em>cpp</em></strong> that accepts integers from the user and fills them into an integer array of 5 elements. Given this array of integers, check if the elements of the array are monotonically increasing. Example 1: a [] = {2 ,4, 6, 7, 10} à True. Example 2: a [] = {2,3,4,1,5} à False.</li>

 <li>Write a C++ program called <strong><em>cpp</em></strong> that prompts the user to enter the cartesian coordinates of the three vertex points ( x1, y1), ( x2, y2), ( x3, y3) of a triangle. Based on the locations of the vertex points of the triangle, your program must calculate and display its area. The different formula that can be used for calculating the area of a triangle are as follows: Semi Perimeter  s = (side1 + side2 + side3)/ 2;</li>

</ol>




area = √s( s – side1)( s – side2)( s – side3)

The distance between two points that have their cartesian coordinates ( x1, y1) and ( x2, y2) can be found out by the formula




<ol start="6">

 <li>Write a C++ program called <strong><em>cpp</em></strong> that reads an integer between 0 and 1000 and adds the cubes of all the digits in the integer. For example, if an integer is 432, the sum of the cubes all its digits is 4<sup>3</sup> + 3<sup>3</sup> + 2<sup>3</sup> = 64 + 27 + 8 = 95. If the user enters an input that is invalid, the program must show an error and ask the user to enter a valid number again.</li>

 <li>To find out the extent of coldness of the weather or the wind chill, certain other factors other than temperature need to be considered. Factors involving relative humidity, wind speed, and sunshine perform vital roles in defining the coldness outside.  In 2001, the National Weather Service (NWS) implemented the new wind-chill temperature to measure the coldness using temperature and wind speed.  The formula is given as follows:</li>

</ol>




<h1><em>              </em><em>t<sub>wc</sub></em> = 35.74 + 0.6215<em>t<sub>a</sub></em> – 35.75<em>v</em><sup>0.16</sup> + 0.4275<em>t<sub>a</sub>v</em><sup>0.16 </sup></h1>




where <em>t<sub>a</sub></em> is the outside temperature measure in degrees Fahrenheit and v is the wind speed in miles per hour.  <em>T<sub>wc</sub></em> is the wind-chill temperature.  This formula cannot be used for wind speeds below 2 mph or temperatures below -58ºF or above 41ºF.




Write a C++ program called <strong><em>windchill.cpp</em></strong> that prompts the user to enter a temperature. If the temperature is between -55ºF and 45ºF and a wind speed greater than or equal to 2, the program calculates and displays the wind-chill temperature – and then ends.

If the value entered by the user is outside the range, the program displays an error saying “Value outside range) and keeps looping till the user enters a valid value.




<ol start="8">

 <li>Write a C++ program called <strong><em>cpp</em></strong> that accepts an arbitrary floating-point value from standard input and returns the value truncated to the second position after the decimal (the hundredths place). The value needs to be printed to the screen according to the following format:</li>

</ol>




The truncated value is v.




The variable v needs to be substituted for the corresponding value. <u>You may not use any</u> <u>library function or conditionals to compute the value.</u> Instead, <u>you must use</u> simple multiplications, divisions, additions, and/or subtractions as well as type casts to calculate the truncated value and then print it to the screen. In the output, ensure that only two digits after the decimal point are shown in the output of v. For example, if you enter 3.768, the output should show the value 3.76.

<ol start="9">

 <li>According to the Gregorian calendar, it was Monday on the date 01/01/1900. If any year is input through the keyboard, write a C++ program called <strong><em>cpp</em></strong> that to find out what is the day on 1st January of this year.</li>

</ol>




<ol start="10">

 <li>Write a C++ program called <strong><em>cpp</em></strong> to accept unspecified number of integers from the user (every time the user enters a number, the program asks if the user wants to enter another number). When the user finishes entering numbers, the program displays the count of positive, negative and zeros entered.</li>

</ol>




<ol start="11">

 <li>Write a C++ program called <strong><em>cpp</em></strong> to find the octal equivalent of the entered number.</li>

</ol>