# ie507-lab-4-solved
**TO GET THIS SOLUTION VISIT:** [IE507 Lab 4 Solved](https://www.ankitcodinghub.com/product/ie507-lab-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97667&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IE507 Lab 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Instructions:

We will practice modeling optimization problems by loading information from files in this lab. We will also continue modeling problems with integer variables.

To load directly from a .txt file containing numbers, we will use the numpy.loadtxt() construct. To know more on the numpy methods to load from files, please check https://numpy.org/doc/ stable/reference/routines.io.html.

To load directly from a file with comma separated values (.csv file), we will use pandas library. The construct pandas.read csv helps to read contents from a .csv file. Please check https: //pandas.pydata.org/pandas-docs/stable/getting_started/index.html to know more about pandas library.

Please follow the instructions given below:

<ul>
<li>Please use different notebooks for solving different problems.</li>
<li>The notebook name for Exercise 1 should be YOURROLLNUMBER IE507 Lab4 Ex1.ipynb.</li>
<li>Similarly, the notebook name for Exercise 2 should be YOURROLLNUMBER IE507 Lab4 Ex2.ipynb,
etc.
</li>
<li>Please post your doubts in MS Teams or Moodle so that TAs can clarify.
For more details on pyomo, please consult https://pyomo.readthedocs.io/en/stable/index. html.

There are only 3 exercises in this lab. Try to solve all problems on your own. If you have difficulties, ask the Instructors or TAs.

Only the questions marked [R] need to be answered in the notebook. You can either print the answers using print command in your code or you can write the text in a separate text tab. To add text in your notebook, click +Text. Some questions require you to provide proper explanations; for such questions, write proper explanations in a text tab.

After completing this lab’s exercises, click File → Download .ipynb and save your files to your local laptop/desktop. Create a folder with name YOURROLLNUMBER IE507 Lab4 and copy your .ipynb files to the folder. Then zip the folder to create YOURROLLNUMBER IE507 Lab4.zip. Then upload only the .zip file to Moodle.

The deadline for today’s lab submission is tomorrow, 10th September 2020, 11 59 PM Indian Standard Time (IST).
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab Lab 04

Exercise 1: Loading values from a file [6 marks] Consider the following optimization problem:

max −0.5×1 − 1.25×2 − 5×3 + 3×4 + 10×5 + 25×6 s.t. 0.8×1 − 1.3×2 − x4 x2 −x3 −x5 x3 − x6 0.5×1 + 0.8×2 + 4×3 0.9×1 + 1.5×2 xi ≥ 0 ∀i ∈ {1,2,…,5}.

1. Create a .txt file such that:

</div>
<div class="column">
09-September-2020

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>The coefficients of the objective function are present in the first line, separated by com- mas, and the last value represents the scalar (note that the scalar in the objective function is zero in problem (OP)).</li>
<li>The remaining lines contain the coefficients of the constraints (separated by commas) and the last value in each of the remaining lines represent the right-hand-sides of the constraints.
See the lab4 practice coef.txt file used in practice.
</li>
</ul>
<ol start="2">
<li>Name the file lab4 ex1 coef.txt</li>
<li>Copy the file to colab environment.</li>
<li>Use numpy.loadtxt to load lab4 ex1 coef.txt into an appropriate numpy array.</li>
<li>Write code using pyomo to create the model for the optimization problem (OP) using the coefficients loaded from lab4 ex1 coef.txt file.</li>
<li>Use cbc solver to solve the optimization problem (OP).</li>
<li>[R] Print and explain the solver termination condition and solver status message and provide
possible reasons for the messages obtained.
</li>
<li>If the solver does not give an optimal solution, try to devise a remedy and use it to get an optimal solution.</li>
<li>[R] If you have devised a remedy, explain about it and then report the optimal objective function value, the values of variables and the constraint activities.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
≤ 12 ≤0.6 ≤ 1.2 ≤ 45 ≤ 27,

</div>
</div>
<div class="layoutArea">
<div class="column">
(OP)

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 04 09-September-2020

Exercise 2: Time taken in MILP. [10 marks] In this exercise we will compare the time taken to solve LP and MILP. Consider the integer optimization problem

</div>
</div>
<div class="layoutArea">
<div class="column">
and its LP relaxation

</div>
<div class="column">
n

max 􏰀cjxj j=1

n

s.t. 􏰀aijxj ≤ bi,

j=1

xj ∈ {0,1},

n

max 􏰀cjxj j=1

n

s.t. 􏰀aijxj ≤ bi,

j=1

0≤xj ≤1,

</div>
<div class="column">
i = 1,…,m (MILP) j = 1…,n.

i = 1,…,m (LP) j=1…,n.

</div>
</div>
<div class="layoutArea">
<div class="column">
Specific data is available for this problem in Moodle in lab4 ex2 lp ip coef.txt file. It has n = 500 variables and m = 5 constraints. Note that the file is modeled similar to the lab4 practice coef.txt file used in practice session.

<ol>
<li>Copy the lab4 ex2 lp ip coef.txt file to colab environment.</li>
<li>Use numpy.loadtxt to load lab4 ex2 lp ip coef.txt into an appropriate numpy array.</li>
<li>[R] Create a pyomo model using the coefficients loaded from the file and solve the MILP using cbc solver. Report the optimal objective function value (Do not report the values of variables).</li>
<li>[R] How much time does it take to solve the MILP? Suppose you have saved the results of opt cbc.solve to results, you can use results.solver.time to report time.</li>
<li>[R] Solve the LP relaxation (LP obtained by removing integer restrictions on all variables) of the same problem using cbc solver. Report only the objective function values of the optimal solution. (You need not report the values of the variables.)</li>
<li>[R] How much time does it take to solve the problem? Compare with the results obtained by solving the MILP.</li>
<li>[R] Also report the statistics printed in Branch and Bound section of results for both MILP and LP.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 04 09-September-2020

Exercise 3: Another Exercise on LP Vs MILP [20 marks]

The simplest application of MILP is when the variables model discrete objects that can only take whole-number values (e.g. number of drones to manufacture). The Indian Air Force (IAF) has planned to purchase drones from the Hindustan Aeronautics Limited (HAL) for using them in surveillance activities and during crisis situations like floods, fires and earthquakes. The drones are expected to carry cameras and freight. Five different types of drones are available with HAL. Their carrying capacities, costs and parking space requirements are listed below:

</div>
</div>
<div class="layoutArea">
<div class="column">
Drone Model

<pre>  SANKALP
  KARTAV
  SAAHAS
   VIJAY
  LAKSHYA
</pre>
</div>
<div class="column">
Carrying Capacity (kgs) 15

</div>
<div class="column">
Cost (in Crores of rupees) Parking space (sq. m.) 43

</div>
</div>
<div class="layoutArea">
<div class="column">
10 3.5 3.25

</div>
</div>
<div class="layoutArea">
<div class="column">
20 10 15

</div>
<div class="column">
54

4 2.75 4.5 2.5

</div>
</div>
<div class="layoutArea">
<div class="column">
The IAF wants to have maximum possible carrying capacity. The budget of IAF is limited to 29 crores of rupees. In addition, parking space for drones is limited to 37 sq. m.

<ol>
<li>Create a .csv file containing the data given in the table. Name the file as lab4 ex3.csv. Use simple and appropriate names for the headers.</li>
<li>Copy the file to colab environment.</li>
<li>Use pandas to load the .csv file contents.</li>
<li>[R] Write a mathematical optimization problem to find the number of drones of each type that can be bought in order to maximize the goal. Mention which variables must be integers.</li>
<li>Create a model using pyomo to solve your optimization problem. Use the loaded contents of .csv file to create your model. Use cbc solver to solve your optimization problem. In your code, remember to specify which variables are integers.</li>
<li>[R] Report the optimal objective function value and the solution.</li>
<li>[R] Let us now compare it to a linear program. Suppose we remove the restrictions that the variables in the above problem are integers. Solve this modified problem and report the solution and the objective value.</li>
<li>[R] Can the solution of the MILP be obtained by merely rounding the solution of the LP? Why or why not?</li>
<li>[R] Suppose now we are interested in finding how the solution changes when the right-hand- sides in our constraints change. Suppose the limit on budget is increased to 41 units and the parking space is increased to 47 units, how will the new LP objective value change? How does the new MILP objective value change?</li>
<li>[R] Now try decreasing limit on budget from 41 units to 39, 37, 35 and 33 units. Correspond- ingly, increase the parking space to 49, 51, 53 and 55 units. Solve the LP and MILP for each of these four possiblities and comment on the pattern seen in objective values of the LP and MILP.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
