# ee425-lab-6-discrete-time-series-averaging-filters--part-ii-solved
**TO GET THIS SOLUTION VISIT:** [EE425 Lab 6-Discrete-time Series Averaging Filters -Part II Solved](https://www.ankitcodinghub.com/product/ee425-lab-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95139&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE425 Lab 6-Discrete-time Series Averaging Filters -Part II Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Exp. 6: Discrete-time Series Averaging Filters -Part II Objective: Implementation of moving average filters with application to discrete-time series.

Consider the moving average filter given by:

y[n] = 𝑥[𝑛] + 𝑥[𝑛−1] + 𝑥[𝑛−2] + 𝑥[𝑛−3]

4

In Figure 1 we show the output time series yi[n], for i=1,…,4, produced by this filter when it is convolved with each of the five different periodic times series inputs xi[n], for i=1,…,4. In this figure, the inputs xi[n] are shown in blue, while the outputs yi[n] are shown in red, and it should be evident to you, by inspection, why we call such a filter a moving average filter: note how in Figure 1 all the outputs appear “smoother” than the inputs, in some sense. Indeed, averaging can be interpreted as a smoothing process.

Figure 1. Inputs xi[n] and outputs yi[n], for i=1,…,4.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
IMPORTANT NOTE 1: Please note that the outputs yi[n] , for i=1,…,4, in Figure 1 are showing both the transient phase and the steady-state phase.

Task 1

<ol>
<li>The first thing for you to do is to compile and simulate the given .asm template titled “ template_for_moving_average_Part_II.” While you do that, please note the following:
<ol>
<li>The variable of interest in this template is, again, the register called value.</li>
<li>Simulate the template as is (i.e., without making any changes) and note that the contentsof value are exactly the values for time series x1[n] shown in Figure 1.</li>
</ol>
</li>
<li>Go back to the template and locate the sections of code shown in Figures 2 and 3.Figure 2. counter variable, where the literal 2 is the period of time series x1[n].
Figure 3. Periodic time series of different periods.
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>Consider Figures 2 and 3, and perform the following changes in the template:
<ol>
<li>Corresponding to Figure 2, replace the literal 2 with the new literal 4. This new literal 4 is simply the period of the second time series x2[n], of period 4, shown in the code inFigure 3.</li>
<li>Corresponding to Figure 3, comment out the following lines of code, which correspondto time series x1[n]:
<ol>
<li>SimpleTable; —&gt; period 2,</li>
<li>db 80,240</li>
</ol>
</li>
<li>Corresponding to Figure 3, uncomment the following lines of code, which correspond to time series x2[n]:
<ol>
<li>;SimpleTable ; —&gt; period 4</li>
<li>;db 80,240,160,60</li>
</ol>
</li>
</ol>
</li>
<li>Simulate the code again, with the changes made in step 3, and note how the contents of registervalue change according to the time series x2[n], also shown in Figure 1.</li>
<li>Repeat step 3 above for each of the remaining time series in Figure 3 and note that the contents of value will vary according to the time series that you choose. All the available time series in the template are shown in the time domain in Figure 1 as xi[n], for i=1,…,4, and shown in code in Figure 3. Each time series has a different period, please verify this through simulations before moving on to the next task.</li>
</ol>
Task 2

1. Having completed Task 1, please write the .asm code to implement the moving average filter y[n] specified above.

a. Convolve your implemented filter with each of the time series xi[n], for i=1,…,4, in the template, one at a time, of course.

<ol>
<li>Note that this Task is an extension of your work for Lab 5.</li>
<li>You must implement a linear memory buffer exactly like the one that you wrote forLab 5.</li>
<li>Just like for the filter in Lab 5, you should also add all the values first, and then“divide” the entire sum after (in this case it will be “division” by 4). Note that now you will be adding four (4) variables and not just two (2) like in Lab 5. Consequently, your adder/divider from Lab 5 will have to be extended to account for this. Recall
There are many ways to perform this addition. I suggest that you draw out the process on a piece of paper, before writing any code, to

help you get your ideas straight and so that you can get a clear idea of what you are trying to do here. Note that this adder/divider is not a difficult thing to do, but you really have to be clear on what is going on when you are trying to add four variables (two at a time), considering that each of these variables is 8 bits long.
</li>
</ol>
b. Verify that your filter was properly implemented by comparing your results with each output yi[n], for i=1,…,4, in Figure 1. In order to help you keep track of all the values, you should create a table for each pair xi[n] and yi[n] as shown in Table 1 for x1[n].

</div>
</div>
<div class="layoutArea">
<div class="column">
that addition can only be performed with two registers at a time. This means that you

</div>
</div>
<div class="layoutArea">
<div class="column">
may want to create additional variables to help you keep track of the full sum, which

</div>
</div>
<div class="layoutArea">
<div class="column">
will necessarily span two registers.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
c. For this task, you should fill up the tables for each pair on your own, by hand, before implementing the filter. This is so that you know what outputs to expect (Hint: see Figure 1). Include all tables in your report.

n … k k+1 k+2 k+3 k+4 k+5 k+6 k+7 k+8 k+9 k+10 k+11 … x1[n] … 180 240 180 240 180 240 180 240 180 240 180 240 … y1[n] … 210 210 210 210 210 210 210 210 210 210 210 210 …

Table 1. Periodic discrete-time series input x1[n] and corresponding output y1[n]. IMPORTANT NOTE 2: Please note that the output y1[n], in Table 1, is only showing the

steady-state phase, and not the transient phase.

IMPORTANT NOTE 3: The remaining tasks in this assignment are simple extensions of your work in Task 2. Thus, it is important that you simulate your code for Task 2 extensively to make sure that it is correct. If you do that, then the following tasks will only require trivial changes to the code that you wrote for Task 2. Furthermore, you should take advantage of the simulator and use it to generate the values for the tables (similar to Table 1) for all the cases below. In short, for the following tasks, you should not be calculating the values for the desired tables by hand anymore. Instead, use the simulator and just fill up the tables with the values it generates!

Task 3

2. Repeat Task 2 for the following moving average filter A[n]:

A[n] = 𝑥[𝑛] + 𝑥[𝑛−2] + 𝑥[𝑛−4] + 𝑥[𝑛−6] 4

Task 4

3. Repeat Task 2 for the following moving average filter B[n]:

B[n] = 𝑥[𝑛] + 𝑥[𝑛−3] + 𝑥[𝑛−6] + 𝑥[𝑛−9] 4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Task 5

4. Choose three arbitrary and distinct positive integers j, k, and l, each no greater than 15, and then

repeat Task 2 for the following moving average filter C[n]:

C[n] = 𝑥[𝑛] + 𝑥[𝑛−𝑗] + 𝑥[𝑛−𝑘] + 𝑥[𝑛−𝑙] 4

</div>
</div>
</div>
