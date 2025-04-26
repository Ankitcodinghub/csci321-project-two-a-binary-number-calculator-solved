# csci321-project-two-a-binary-number-calculator-solved
**TO GET THIS SOLUTION VISIT:** [CSCI321 Project Two: A Binary Number Calculator Solved](https://www.ankitcodinghub.com/product/csci321-project-two-a-binary-number-calculator-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;59851&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI321 Project Two: A Binary Number Calculator Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<strong>Objectives:</strong>

<ol>
<li>Demonstrate basic programming logic</li>
<li>Demonstrate how to convert between integers and their binary representation in two’s complement format</li>
<li>Demonstrate how to add two binary numbers that are in two’s complement format</li>
</ol>
&nbsp;

<strong>Problem Description:</strong>

Write a C/C++ program that simulate a menu based binary number calculator. This calculate shall have the following five functionalities:

<ol>
<li>Covert a binary string in two’s complement format to corresponding integers</li>
<li>Convert an integer to its binary representation in two’s complement format</li>
<li>Add two binary numbers, both numbers are represented as a string of 0s and 1s</li>
<li>Provide sign extension for a binary number</li>
<li>Provide two’s complement for a binary nunber</li>
</ol>
&nbsp;

This is an update of Project One. To reduce student work load, a start file CSCIProjTwoHandout.cpp is given. In this file, the structure of the program has been established. The students only need to implement the following five functions:

<ol>
<li>int binary_to_decimal_signed(string b);</li>
</ol>
// precondition: b is a string that consists of only 0s and 1s

// postcondition: the decimal integer that is represented by b

<ol start="2">
<li>string decimal_to_binary_signed(int n);</li>
</ol>
// precondition: n is an integer

// postcondition: n’s binary representation is returned as a string of 0s and 1s

<ol start="3">
<li>string add_binaries_signed(string b1, string b2);</li>
</ol>
// precondition: b1 and b2 are strings that consists of 0s and 1s, i.e. b1 and b2 are binary

//&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; two’s complement representations of two integers

// postcondition: the sum of b1 and b2 is returned. For instance, if b1 = “11”, b2 = “01”, //&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; then the return value is “100”

<ol start="4">
<li>string signed_extension(string b);</li>
</ol>
// precondition: s is a string that consists of only 0s and 1s that is at most 16 bits

// postcondition: a 16 bit string has been returned as signed extension of s. For instane,

// if s = “0101” then return value will be “00000000000000000101” total 12

//&nbsp; 0s are added in front of s

<ol start="5">
<li>string twos_complement(string s);</li>
</ol>
// precondition: s is a string that consists of only 0s and 1s

// postcondition: two’s complement of s is returned as an 16 bits binary integer. For

//&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; instance, if s = “1101”, then return value will be “1111111111111101”

&nbsp;

The following functionality has been provided. Please notice that three functions from Project One are provided. The idea is your new function will somehow call corresponding one in these three functions to do the work:

<ol>
<li>main function which presents the execution logic of the whole program</li>
<li>void menu(); which display the menu of this binary calculator</li>
<li>int binary_to_decimal(string b);</li>
</ol>
// precondition: b is a string that consists of only 0s and 1s

// postcondition: the positive decimal integer that is represented by b

<ol start="4">
<li>string decimal_to_binary(int n);</li>
</ol>
// precondition: n is a positive integer

// postcondition: n’s binary representation is returned as a string of 0s and 1s

<ol start="5">
<li>string add_binaries(string b1, string b2);</li>
</ol>
// precondition: b1 and b2 are strings that consists of 0s and 1s, i.e. b1 and b2 are binary

//&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; representations of two positive integers

// postcondition: the sum of b1 and b2 is returned. For instance, if b1 = “11”, b2 = “01”, //&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; then the return value is “100”

<ol start="6">
<li>bool isBinary(string s); which returns true if the given string s consists of only 0s and 1s; false otherwise</li>
<li>int grade(); which returns an integer that represents the student’s grade of this projects.</li>
<li>bool test_binary_to_decimal() which returns true if the student’s implementation of binary_to_decimal function is correct; false otherwise</li>
<li>bool test_decimal_to_binary() which returns true if the student’s implementation of decimal_to_binary function is correct; false otherwise</li>
<li>bool test_add_binaries which returns true if the student’s implementation of add_binaries function is correct; false otherwise</li>
</ol>
&nbsp;

<strong>Work Process:</strong>

Student shall download the CSCI365ProjTwoHandout.cpp file, saved as YourNameCSCI365ProjTwo.cpp, and add it to his/her C++ project. Please notice, at this point, your project shall be able to run. However, your project will not pass any test. i.e. if you choose option 6 from menu, it will shows that you get 0 out of 10.

&nbsp;

Student shall NOT change any name of the declared functions or the given implemented functions. Student shall only implement the bodies of three functions that need to be implemented.

&nbsp;

Please see sample run at the end of this file.

&nbsp;

<strong>Due Date:</strong>

It is specified in syllabus and is announced on Blackboard

&nbsp;

<strong>Sample Run:&nbsp;</strong>The highlighted ones are user’s input. The red part is explanation of result, which doesn’t show up in sample run output

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

******************************

*&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Menu&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 1. Binary to Decimal&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 2. Decinal to Binary&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 3. Add two Binaries&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 4. Signed extension&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 5. Two’s complement&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 6. Grade&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 7. Quit&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

******************************

&nbsp;

Enter your choice: 1

Enter a binary string: 1001101

Its decimal value is: -51 (the two’s complement of 1001101 is 0110011 which is positive 51. So 1001101 is -51)

&nbsp;

&nbsp;

******************************

*&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Menu&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 1. Binary to Decimal&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 2. Decinal to Binary&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 3. Add two Binaries&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 4. Signed extension&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 5. Two’s complement&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 6. Grade&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 7. Quit&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

******************************

&nbsp;

Enter your choice: 2

Enter an integer: -51

Its binary representation is: 1111111111001101 (51 is 0110011. So -51 is 1001101. Use sign extension to sixteen bits, it is 1111111111001101)

&nbsp;

&nbsp;

******************************

*&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Menu&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 1. Binary to Decimal&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 2. Decinal to Binary&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 3. Add two Binaries&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 4. Signed extension&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 5. Two’s complement&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 6. Grade&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 7. Quit&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

******************************

&nbsp;

Enter your choice: 3

Enter two binary numbers, separated by white space: 1001101

01101

The sum is: 1111111111011010 (both numbers get sign extension as 1111111111001101 and 0000000000001101. Then add them bits by bits with carry to get 1111111111011010)

&nbsp;

&nbsp;

******************************

*&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Menu&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 1. Binary to Decimal&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 2. Decinal to Binary&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 3. Add two Binaries&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 4. Signed extension&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 5. Two’s complement&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 6. Grade&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 7. Quit&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

******************************

&nbsp;

Enter your choice: 4

Enter a binary number: 1001101

Its signed extension to 16 bits is: 1111111111001101 (In fact, this one must be right before the first three options can be right)

&nbsp;

******************************

*&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Menu&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 1. Binary to Decimal&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 2. Decinal to Binary&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 3. Add two Binaries&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 4. Signed extension&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 5. Two’s complement&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 6. Grade&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 7. Quit&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

******************************

&nbsp;

Enter your choice: 5

Enter a binary number: 1001101

Its two’s complement is: 0000000000110011 (In fact, this one must be right before the first three options can be right)

&nbsp;

******************************

*&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Menu&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 1. Binary to Decimal&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 2. Decinal to Binary&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 3. Add two Binaries&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 4. Signed extension&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 5. Two’s complement&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 6. Grade&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 7. Quit&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

******************************

&nbsp;

Enter your choice: 6

binary_to_decimal_signed function pass the test

decimal_to_binary_signed function passed the test

add_binaries_signed function passed the test

sign_extension function passed the test

twos_complement function passed the test

If you turn in your project on blackboard now, you will get 8 out of 10

Your instructor will decide if one-two more points will be added or not based on your program style, such as good commnets (1 points) and good efficiency (1 point)

&nbsp;

******************************

*&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Menu&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*

* 1. Binary to Decimal&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 2. Decinal to Binary&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 3. Add two Binaries&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 4. Signed extension&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 5. Two’s complement&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 6. Grade&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

* 7. Quit&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *

******************************

&nbsp;

Enter your choice: 7

Thanks for using binary calculator program. Good-bye

Program ended with exit code: 0
