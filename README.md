# csf211-lab-3-abstract-data-type-linked-lists-measuring-run-time-solved
**TO GET THIS SOLUTION VISIT:** [CSF211 Lab 3-Abstract Data Type, Linked Lists, Measuring Run Time Solved](https://www.ankitcodinghub.com/product/csf211-lab-3-abstract-data-type-linked-lists-measuring-run-time-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91909&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSF211 Lab 3-Abstract Data Type, Linked Lists, Measuring Run Time Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Topic: Abstract Data Type, Linked Lists, Measuring Run Time

Definition: ADT Queue (a.k.a. FIFO List a.k.a. FIFO Queue)

<ul>
<li>Queue newQ() // returns an empty Queue</li>
<li>Boolean isEmptyQ(Queue q) // tests whether q is empty</li>
<li>Queue delQ(Queue q) // deletes the element from the front of the Queue;
returns the modified Queue
</li>
<li>Element front(Queue q) // returns the element from the front of the Queue;</li>
<li>Queue addQ(Queue q , Element e) // adds e to the rear of the Queue; returns the
modified Queue
</li>
<li>Queue lengthQ(Queue q) // returns the length of the Queue
Exercise 1. (a) Define the ADT Queue interface in file que.h.

(b) Implement ADT Queue using a linked list in file que.c. Note that efficient implementation of a Queue in a linked list requires a head (pointing to the first node of the linked list) and a tail (pointing to the last node of the linked list). ==========================================================================

Consider a task scheduling system where tasks are queued according to priority i.e. each task is added to a FIFO queue according to its priority. (e.g. an Operating System where processes arrive to be executed and each process has a priority that is not necessarily unique; e.g. a machine shop where requests for machining jobs come with a priority). All these scenarios can be modelled using the ADT MultiQ defined with the following behaviour:

<ul>
<li>MulitQ createMQ(int num) // creates a list of num Queues, each of which is empty.</li>
<li>MultiQ addMQ(MultiQ mq, Task t) // adds t to the Queue corresponding to priority p in mq. Task includes a TaskID tid and a priority p.</li>
<li>Task nextMQ(MultiQ mq) // returns the front of the non-empty Queue in mq with the highest priority.</li>
<li>Task delNextMQ(MultiQ mq) // deletes the front of the non-empty Queue in mq with the highest priority; returns the modified MultiQ</li>
<li>Task isEmptyMQ(MultiQ mq) // tests whether all the Queues in mq are empty</li>
<li>int sizeMQ(MultiQ mq) // returns the total number of items in the MultiQ</li>
<li>int sizeMQbyPriority(MultiQ mq, Priority p) returns the number of items in
mq with the priority p.
</li>
<li>Queue getQueueFromMQ(MultiQ, Priority p) returns the Queue with priority
p.
</li>
</ul>
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Exercise 2: (a) Define the MultiQ interface in file multiq.h

(b) Implement the operations on MultiQ in file muliq.c. Note that createMQ should dynamically allocate an array of size num (the value that is passed to it) and return it. The implementation of MultiQ should use ADT Queue (as implemented in Exercise 1(a)) to perform the operations.

Exercise 3: (a) Write a main function in testMultiq.c that tests the MultiQ ADT using the following functions:

<ol>
<li>MultiQ loadData(File f) – reads from f a list of pairs (task_id, priority) and adds each item to a MultiQ appropriately.</li>
<li>MultiQ testDel(int num) – performs num of delNextMQ operations.</li>
</ol>
You can use the attached files – input10.txt, input100.txt and input10000.txt each having 10, 100 &amp; 10,000 &lt;task_id,priority&gt; pairs in them respectively.

[Note- there are a total of 10 different priorities each task can take in the given input files. Both task_id and priority are positive integer values.]

(b) Measure the time taken for adding the elements to MultiQ within the loadData operation. Also measure the time taken for performing the testDel function and compute the average cost per delete operation.

Measurements are to be done in two ways: (i) using functions in the library (see header file time.h and use man to find details) (ii) using the gnu profiler (gprof) that comes with gcc.

Given below is a sample program that measures the time taken by a program using – “sys/time.h”

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>#include &lt;sys/time.h&gt;
</pre>
int main() {

<pre>    struct timeval t1, t2;
    double elapsedTime;
</pre>
<pre>    // start timer
    gettimeofday(&amp;t1, NULL);
</pre>
<pre>    // do something or call a function
    // ...
</pre>
<pre>    // stop timer
    gettimeofday(&amp;t2, NULL);
</pre>
<pre>    // compute and print the elapsed time in millisec
    elapsedTime = (t2.tv_sec - t1.tv_sec) * 1000.0;
    elapsedTime += (t2.tv_usec - t1.tv_usec) / 1000.0;
    printf("Total time is" + elapsedTime + "ms.\n";
</pre>
return 0; }

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// for gettimeofday()
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// sec to ms
// us to ms
</pre>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
To measure time using gprof, you don’t need to add any instrumentation in the file like we did before. Rather we should compile our files and link them using the flag “-pg”, execute your program and then generate the profiling output. For example you need to do the following for profiling a program writing in “file1.c” :

<pre>gcc –pg file1.c –o test        // compiles file1.c and generates an executable with
                                  name test
</pre>
<pre>./test                         // execute the program
</pre>
<pre>gprof test gmon.out &gt; prof_output      // creates a file prof_output which contains
                                          the time taken for execution of each
</pre>
<pre>                                          function in file1.c
</pre>
(c) Repeat steps (a) and (b) for different sizes of the list in the input file and for different num values for deletion.

Assignment Task for this week (deadline: Saturday, Feb 06, 2021, 23:59):

Upload the solution of Exercise 1 (a, b), Exercise 2(a, b). Note that Functions of Exercise-2 uses the functions implemented in Exercise-1.

</div>
</div>
</div>
