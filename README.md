Download Link: https://assignmentchef.com/product/solved-comp1400-lab6-working-with-basic-types-and-more-with-loops
<br>
<strong>Pin code security check:</strong> The Hogwarts School was so happy with your math helper program that they referred you to a security firm! This security firm creates pin code door lockers like you see in the movies. They now need help to design an algorithm that will power the authentication system. The algorithm they want to validate codes is pretty weak, but it should work in the following way:

<ul>

 <li>It first checks if the pin code entered is five digits. If not, the code is invalid.</li>

 <li>It then checks if each digit within the five-digit pin is divisible by 3. If not, the code is invalid.</li>

 <li>If six consecutive invalid pins are entered, the system locks out and reports an intruder.</li>

</ul>

Therefore, codes 357 and 16343 are invalid because the former is less than five digits and the latter has numbers which are not divisible by 3 (i.e. 1 and 4). A valid pin code could be 63339 because it has exactly five digits. . In addition, all of its five digits (i.e., 1, 3, 5, and 7) are divisible by 3. A sample interaction is shown below




<table width="0">

 <tbody>

  <tr>

   <td width="274"> Enter pin code (attempt 1):</td>

   <td width="66"><u>1234</u></td>

  </tr>

  <tr>

   <td width="274">  Code 1234 is invalid!Enter pin code (attempt 2):</td>

   <td width="66"> <u>12534</u></td>

  </tr>

  <tr>

   <td width="274">  Code 12534 is invalid!Enter pin code (attempt 3):Code 63963 is success!</td>

   <td width="66"> <u>63963</u> </td>

  </tr>

 </tbody>

</table>




If the user entered more than 6 invalid pins:










<strong>Part A: RAPTOR Exercise </strong>

<ol>

 <li>Understand more about RAPTOR by watching the video about <em><u>how to work with</u></em><em> <u>subcharts</u></em></li>

 <li>Start RAPTOR and create the flowchart of pin code security check.</li>

 <li>Save the flowchart to a file named “pinCode.rap” in the working directory on the PC you are using.</li>

 <li>Demonstrate the pinCode.rap file to GA/TAs and run with different input values.</li>

</ol>




<strong>Suggestion</strong>: Add a subchart CheckCode to help improving the readability of the flowchart <strong> </strong>

<strong> </strong>

<strong>Part B: C Programming Exercise </strong>

<ol>

 <li>Implement the algorithm as represented by “picCode.rap”, and write an equivalent C program that accomplishes what the flowchart does.</li>

 <li>Save your program to a file named “picCode.c” in the working directory on the PC you are using.</li>

 <li>Demonstrate the picCode.c file to GA/TAs and run with different input values.</li>

</ol>




<strong>EVALUATION: </strong>

You need to show your GA/TA the complete programs at the end of this lab, or at the beginning of your next lab. The marks you will receive for this lab are made of two parts: Lab work marks 10 and attendance marks 5. <strong>Total 15 marks</strong>.




<strong> </strong>

<strong>Lab Work Mark</strong>: Your C code will be evaluated based on your solutions for the problems based on the following scheme:




<ol>

 <li>Does the code run and meet specifications?

  <ul>

   <li>Is input adequate and input data type properly validated?</li>

   <li>Is processing adequate?</li>

   <li>Is output correct and adequate?</li>

   <li>Is the code compliable? Is the code run properly?</li>

  </ul></li>

</ol>




<ol start="2">

 <li>Is the code properly commented?

  <ul>

   <li>Is the program title, programmer’s first and last name, and the date posted at the top in a multi-line comment?</li>

   <li>Is each significant step of the program properly commented?</li>

   <li>Are comments added to clarify details?</li>

   <li>Are comments clear, accurate, neatly formatted, and have no misspellings?</li>

  </ul></li>

</ol>




<ol start="3">

 <li>Is the code properly formatted?

  <ul>

   <li>Are blocks of code indented according to their parent-child relationship?</li>

   <li>Do curly braces line up vertically?</li>

   <li>Is there an empty line between significant steps (blocks) of the program?</li>

   <li>Is the width of the code contained within a reasonable limit so that minimal horizontal scrolling is required (with 800 x 600 monitor resolution), and there is minimal linewrapping when printed?</li>

   <li>Is camel-case notation used for variable, e.g. employeeLastName?</li>

  </ul></li>

</ol>

<strong>IMPORTANT: </strong>DO YOUR OWN CODE. ANY CODE SUSPECTED TO BE SIMILAR TO ANOTHER SUBMISSION WILL CAUSE BOTH SUBMISSIONS TO RECEIVE A ZERO MARK ON ALL LABS AND BE REPORTED FOR PLAGIARISM.


