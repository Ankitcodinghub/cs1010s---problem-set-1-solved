# cs1010s---problem-set-1-solved
**TO GET THIS SOLUTION VISIT:** [CS1010S – Problem Set 1 Solved](https://www.ankitcodinghub.com/product/cs1010s-problem-set-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115081&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1010S - Problem Set 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Basic C/C++ Expressions

Information

In this problem set, you will wet your hands writing C/C++ expressions with some useful functions.

The temperature of an object placed in a freezer will change according to this function:

T = T0−(T0− Tf)×(1− e−c×t)

where

• T0 is the initial temperature of the object

• Tf is the temperature of the freezer

• c is some coefficient of heat transfer

• t is the time in hours

Complete the function double freezer(int hrs, int mins, int t0, double c) , that takes in four inputs: hours, minutes, initial temperature and the coefficient. It should return the temperature of the object after it has been placed in a -10 degrees freezer for that given duration.

Tip: You can use the math function pow(x, y) which returns the result of xy, by adding #include &lt;math.h&gt; to the top of your file.

The formula to convert between Fahrenheit to Celsius is:

Implement the functions f_to_c and c_to_f which takes in a temperature in degrees Fahrenheit and converts it to degrees Celsius, and vice versa.

1

Given any two times of the day, we can represent the number of hours, minutes and seconds that elapsed between the two times as hh:mm:ss. Following standard convention, mm and ss should be less than 60.

The functions hrs_elapsed , mins_elapsed and secs_elapsed returns the value of hh, mm and ss, respectively.

The inputs for all three functions are six integers, representing the starting hour, minute and second, and the ending hour, minute and second, in 24-hour clock format.

For example, between 12:20:30pm and 1:30:50pm, there is a elapsed time of 1hr, 10mins and 20secs.

Hence after running these statements:

int h = hrs_elapsed(12, 20, 30, 13, 30, 50); int m = mins_elapsed(12, 20, 30, 13, 30, 50); int s = secs_elapsed(12, 20, 30, 13, 30, 50);

The value of the variables h , m and s would be 1, 10, and 20, respectively.

Implement the three functions hrs_elapsed , mins_elapsed and secs_elapsed .

192.168.0.1.

Each number is actually a representation of an 8-bit binary number. A binary number only contains the digit 0 and 1, and each digit place is referred to as a bit. Thus, the range for an 8-bit binary number is from 00000000 to 11111111.

To convert a binary number to decimal, note that both system a positional numerical systems.

In a binary system, the first 8 positions of the digits represents:

27,26,25,24,23,22,21,20

For example, the binary number 11001001 is calculated to be:

27 26 25 24 23 22 21 20

1 1 0 0 1 0 0 1

128 64 0 0 8 0 0 1 = 201

Implement the function ip_octet which takes an 8-digit binary number as input and returns the respective decimal number.

Note: In C, any number that begins with a 0 will be treated as a base-8 number. So remove all leading zeros from your integer when testing, e.g. for 00110011 , just type 110011 .
