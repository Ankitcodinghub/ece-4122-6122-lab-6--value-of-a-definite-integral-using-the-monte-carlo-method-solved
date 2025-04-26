# ece-4122-6122-lab-6--value-of-a-definite-integral-using-the-monte-carlo-method-solved
**TO GET THIS SOLUTION VISIT:** [ECE 4122/6122 Lab 6- Value of a Definite Integral using the Monte Carlo method Solved](https://www.ankitcodinghub.com/product/ece-4122-6122-lab-6-using-openmpi-to-estimate-the-value-of-a-definite-integral-using-the-monte-carlo-method-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127135&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE 4122\/6122 Lab 6- Value of a Definite Integral using the Monte Carlo method Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
(100 pts)

Category: OpenMPI

Objective:

Use OpenMPI to estimate the value of a definite integral using the Monte Carlo method.

How to use Monte Carlo simulation to estimate an integral:

The Monte Carlo technique takes advantage of a theorem in probability that is whimsically called the Law of the Unconscious Statistician. The theorem is basically the chain rule for integrals. If 𝑋𝑋 is a continuous random variable and 𝑌𝑌 = 𝑔𝑔(𝑋𝑋) is a random variable that is created by a continuous transformation (g) of 𝑋𝑋, then the expected value of 𝑌𝑌 is given by the following convolution:

𝐸𝐸[𝑌𝑌] = 𝐸𝐸[𝑔𝑔(𝑋𝑋)] = 𝑔𝑔(𝑥𝑥)𝑓𝑓𝑋𝑋(𝑥𝑥)𝑑𝑑𝑥𝑥

where 𝑓𝑓𝑋𝑋 is the probability density function for 𝑋𝑋.

To apply the theorem, choose 𝑋𝑋 to be a uniform random variable on the interval (𝑎𝑎, 𝑏𝑏). The density function of 𝑋𝑋 is therefore 𝑓𝑓𝑋𝑋(𝑥𝑥) = 1/(𝑏𝑏 − 𝑎𝑎) if 𝑥𝑥 is in (𝑎𝑎, 𝑏𝑏) and 0 otherwise. Rearranging the equation gives

𝑏𝑏

𝑔𝑔(𝑥𝑥)𝑑𝑑𝑥𝑥 = (𝑏𝑏 − 𝑎𝑎) ∙ 𝐸𝐸[𝑔𝑔(𝑋𝑋)]

𝑎𝑎

Consequently, to estimate the integral of a continuous function g on the interval (𝑎𝑎, 𝑏𝑏), you need to estimate the expected value 𝐸𝐸[𝑔𝑔(𝑋𝑋)], where 𝑋𝑋 ~ 𝑈𝑈(𝑎𝑎, 𝑏𝑏). To do this, generate a uniform random sample in (𝑎𝑎, 𝑏𝑏), evaluate g on each point in the sample, and take the arithmetic mean of those values. In symbols,

𝑏𝑏𝑛𝑛

𝑔𝑔(𝑥𝑥)𝑑𝑑𝑥𝑥 ≈ (𝑏𝑏 − 𝑎𝑎) 𝑔𝑔(𝑥𝑥𝑖𝑖)

𝑎𝑎 𝑛𝑛 𝑖𝑖=1

where the 𝑥𝑥𝑖𝑖 are independent random uniform variates on (𝑎𝑎, 𝑏𝑏).

Method:

Description:

Write a C++ application that uses OpenMPI to estimate the following two definite integrals

1) 𝑑𝑑𝑥𝑥 which should be equal to 1/3 to test your results

2) 𝑑𝑑𝑥𝑥

You application should take two command line arguments (-P and -N):

-P 1 this can be 1 or 2, and indicates which integral listed above to estimate.

-N 1000000 this is the number of random samples to generate in total and needs to be distributed across the available processors.

Your program should use MPI’s broadcast communication methods to distribute random runs among processors and then gather the results for the final calculation of the integral.

Sample Run:

 srun ./a.out -P 1 -N 10000000

 The estimate for integral 1 is 0.33333321  Bye!

Turn-In Instructions

Zip up your file(s) into Lab6.zip and upload this zip file on the assignment section of Canvas.

Grading Rubric:

AUTOMATIC GRADING POINT DEDUCTIONS PER PROBLEM:

Element Percentage Deduction Details

Does Not Compile 40% Code does not compile on PACE-ICE!

Does Not Match Output Up to 90% The code compiles but does not produce correct outputs.

Clear Self-Documenting Coding Styles Up to 25% This can include incorrect indentation, using unclear variable names, unclear/missing comments, or compiling with warnings. (See Appendix A)

LATE POLICY

Element Percentage Deduction Details

Appendix A: Coding Standards

Indentation:

When using if/for/while statements, make sure you indent 4 spaces for the content inside those. Also make sure that you use spaces to make the code more readable. For example:

for (int i; i &lt; 10; i++)

{ j = j + i;

}

If you have nested statements, you should use multiple indentions. Each { should be on its own line (like the for loop) If you have else or else if statements after your if statement, they should be on their own line.

for (int i; i &lt; 10; i++)

{

if (i &lt; 5) {

counter++; k -= i; } else

{ k +=1; } j += i;

}

Camel Case:

This naming convention has the first letter of the variable be lower case, and the first letter in each new word be capitalized (e.g. firstSecondThird).

This applies for functions and member functions as well!

The main exception to this is class names, where the first letter should also be capitalized.

Variable and Function Names:

Your variable and function names should be clear about what that variable or function represents. Do not use one letter variables, but use abbreviations when it is appropriate (for example: “imag” instead of

“imaginary”). The more descriptive your variable and function names are, the more readable your code will be. This is the idea behind self-documenting code.

File Headers:

Every file should have the following header at the top

/*

Author: your name

Class: ECE4122 or ECE6122 (section)

Description:

What is the purpose of this file?

*/

Code Comments:

1. Every function must have a comment section describing the purpose of the function, the input and output parameters, the return value (if any).

2. Every class must have a comment section to describe the purpose of the class.

3. Comments need to be placed inside of functions/loops to assist in the understanding of the flow of the code.
