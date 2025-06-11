# ecse420-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [ECSE420 Assignment 2 Solved](https://mantutor.com/product/ecse420-assignment-2-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115018&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECSE420  Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

Submission instructions: Students are to work in groups of two on the assignment.

Each group should submit a pdf file that contains the following information: students’ names, students’ IDs, instructions on how to run each file and the associated question solved. Students are also expected to submit a .zip file containing their source code. This code must compile and run without error. The code must be well formatted, commented, and follow the Google Java Style Guide. For more information, see the ECSE420AssignmentSubmissionInstructions.pdf in the Assignment section on myCourses.

Questions

1.1. Implement the Filter lock described in Chapter 2 of the course text.

1.2. Does the Filter lock allow threads to overtake other threads an arbitrary number of times?

Explain.

1.3. Implement Lamport’s Bakery lock described in Chapter 2.

1.4. Does the Bakery lock allow some threads to overtake others an arbitrary number of times? Explain

1.5. Propose a test that verifies if a lock works for n-thread mutual exclusion. Provide an implementation for the proposed test and verify if the locks implemented above do provide n-thread mutual exclusion.

3.1. Does this protocol satisfy mutual exclusion? (Hint: Start the proof by assuming that two threads A and B are in the critical section at the same time.)

3.2. Is this protocol deadlock-free? Explain.

3.3. Is this protocol starvation-free? Explain.

1 class ShakyLock implements Lock {

2 private int turn;

3 private boolean busy = false;

4 public void lock() {

5 int me = ThreadID.get();

6 turn = me;

7 do {

8 busy = true;

9 } while ( turn == me || busy);

10 }

11 public void unlock() {

12 Busy = false;

13 }

14 }

Fig.1 ShakyLock lock protocol used in Question 3.

Fig. 2 History A

Fig. 3 History B

5.1. According to what you have been told about the Java memory model, will the reader method ever divide by zero? If yes, describe the order in which writer and reader should be invoked (by threads A and B) and take effect for a division by zero to happen.

5.2. Is division by zero possible if both x and v are volatile? What happens if neither x nor v are volatile? Justify your answer.

Fig. 4 Volatile example

6.1. If we change the loop at line 11 to “for (int i = x + 1; i &lt; RANGE; i++)”, then the construction is still a regular M-valued MRSW register. Justify your answer.

6.2. If we change the loop at line 11 to “for (int i = x + 1; i &lt; RANGE; i++)”, then the construction yields a safe M-valued MRSW register. Justify your answer.

Fig. 5 The regular M-valued MRSW class
