# cs3305a-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS3305A Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs-3305a-operating-systems-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119597&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3305A Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
&nbsp;

Purpose

The goals of this assignment are the following:

• Get experience with the fork(), wait() and execl() system functions

• Learn more about how operating systems are structured

• Gain more experience with the C programming language from an OS perspective

Parent and Child Processes (100 points)

Write a program in C that will perform the following tasks (must follow the task sequence below):

1. Your parent process will create a child process (i.e., child_1)

2. Parent process will wait for child_1 to complete before creating child_2

3. child_1 will call an external program “external_program.out” (hint: excel()) and pass its PID concatenated with string “ for child_1”. As a result of this external program call, child_1 will be replaced by external_program.out.

4. Parent process will create child_2 and then child_2 will create child_2.1

5. Inside child_2.1, a call to an external program “external_program.out” will be made (hint: excel()). child_2.1 must pass its PID to “external_program.out” concatenated with string “ for child_2.1”. As a result of this external program call, child_2.1 will be replaced by external_program.out.

6. Parent process will wait for child_1 and child_2 to be completed before it terminates.

The expected output from your program should look like the following:

parent (PID 333275) created child_1 (PID 333276)

parent (PID 333275) is waiting for child_1 (PID 333276) to complete before creating child_2

child_1 (PID 333276) is calling an external program external_program.out and leaving parent

From the external program: The PID was 333276 for child_1 parent (PID 333275) created child_2 (PID 333277) child_2 (PID 333277) created child_2.1 (PID 333278)

child_2.1 (PID 333278) is calling an external program external_program.out and leaving child_2

From the external program: The PID was 333278 for child_2.1 child_1 and child_2 are completed and parent process is terminating…

Hints: fork(), wait(), getpid(), getppid(), execl(), strcat()

1

Mark Distribution

a) A parent process will create two child processes: 20 points

b) parent will wait for child_1 to complete before creating child_2: 20 points

c) child_1 will make a system call to an external program: 15 points

d) child_2 will create its own child child_2.1: 10 points

e) child_2.1 will make a system call to an external program: 15 points

f) parent process must not terminate until all child processes have completed: 20 points

Computing Platform for Assignments

• Students have virtual access to the MC 244 lab, which contains 30 Fedora 28 systems. Linux machines available to you are: linux01.gaul.csd.uwo.ca through linux30.gaul.csd.uwo.ca.

• It is your responsibility to ensure that your code compiles and runs on the above systems. You can SSH into MC 244 machines (please see the Assignment 1 file transfer tutorial).

• If you are off campus, you have to SSH to compute.gaul.csd.uwo.ca first (this server is also known as sylvia.gaul.csd.uwo.ca, in honour of Dr. Sylvia Osborn), and then to one of the MC 244 systems (linux01.gaul.csd.uwo.ca through linux30.gaul.csd.uwo.ca) (please see the Assignment 1 file transfer tutorial).

• https://wiki.sci.uwo.ca/sts/computer-science/gaul

Provided Files

• The source code for the external program “external_program.c” is provided.

• Do not make any changes to “external_program.c”

• When running the program, you must provide the path to “external_program.out” as an argument (see Assignment 1 tutorial Powerpoint)

Assignment Submission

2
