# arm-program-that-takes-takes-an-input-n-solvved
**TO GET THIS SOLUTION VISIT:** [ARM program that takes takes an input n Solvved](https://www.ankitcodinghub.com/product/arm-program-that-takes-takes-an-input-n-solvved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;102217&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ARM program that takes takes an input n   Solvved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<strong>Instructions</strong>

<strong>Objective</strong>

Write an ARM program that takes takes an input n and uses recursion to print n down to zero and back to n.

Here is sample output

Here is the c++ code for the procedure.&nbsp; (This is simply meant to help you understand the assignment!!)

void printFun(int n)

{

if (n == 0) {

cout &lt;&lt; 0 &lt;&lt; endl;

return;

}

else if (n &lt; 0) {

cout &lt;&lt; “Please input a positive number” &lt;&lt; endl;

}

else {

cout &lt;&lt; n &lt;&lt; endl;

printFun(n – 1);

cout &lt;&lt; n &lt;&lt; endl;

return;

}

}

<strong>Requirements and Specifications</strong>

Your inputs n&nbsp;<strong>cannot be stored as a global variable at any point</strong>. This means you cannot store them at a data section address, even when accepting them from scanf; they must be returned from scanf on the stack.

X19-X27 are global variables. You may not use X19-X27 in your recursive function. If you want, you may<strong>&nbsp;</strong>use X19-X27 in your main function.&nbsp; You can use any registers you want to in your main function.

A recursion procedure requires:

<ul>
<li>Allocate stack space</li>
<li>Save the return address and argument on the stack</li>
<li>Recursively call procedure with BL</li>
<li>Unwind the stack by restoring the return address and arguments and deallocating stack memory</li>
</ul>
&nbsp;

<strong>Hints and Warnings</strong>

You must put the argument and return address on the stack before any bl call, and restore the argument and the return address after the bl call.&nbsp;&nbsp; This includes every printf call and every recursive call.

<strong>Submission</strong>

Submit your ARM assembly language program source code. Name the file “pa2.txt”. Submitting with a different filename or different extension will result in point deductions.

<strong>Skeleton Code</strong><a href="https://ufl.instructure.com/courses/471300/files/74700165?verifier=0s80RPrMLRXslaCq12XiiRPQaa6i1e7TGeevU2Nb&amp;wrap=1">&nbsp; pa2.txt</a>

<strong>You must give us a file with a .txt extension so we can run it through Turnitin.</strong>

We will be applying a filter to compare your file to other student submissions to detect plagiarism. &nbsp;You must do your own work.

&nbsp;
