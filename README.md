# cs4240-bonus-project-solved
**TO GET THIS SOLUTION VISIT:** [CS4240 BONUS Project Solved](https://www.ankitcodinghub.com/product/cs4240-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123833&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4240 BONUS Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
CS 4240: Compilers and Interpreters, BONUS Project,

1 Project Description

Minimize the file a.smt2 such that it preserves the property defined in Definition 1.

Definition 1 (Property). Let cvc4 be the provided solver program. We say that the file a.smt2 holds the property iff:

• The command “cvc4 –lang=smt2.6 a.smt2” returns “sat”; and

• If we replace “set-logic ALL” with “set-logic QF NIA” in a.smt2, the command “cvc4 –lang=smt2.6 a.smt2” returns “unknown”.

We have also provided a bash script b.sh to help you check the property. If the file a.smt2 holds the property, the return code of b.sh will be 0. Otherwise, it will return 1.

Therefore, an alternative way to define the project goal is that: Minimize the file a.smt2 such that the script b.sh will return 0.

1.1 Evaluation

We will determine the file size by running the provided b.sh script. It will count the number of characters in a.smt2 using “wc -c a.smt2”. The original size of a.smt2 is 6547.

For your property-preserving file a.smt2,

• You will receive 50% of the credit if the file size is smaller than 560; or

• You will receive 100% of the credit if the file size is smaller than 260.

2 Provided Code and Expected Output

We have provided the solver (cvc4), the input file (a.smt2) and the property testing file (b.sh) at https://faculty.cc.gatech.edu/~qrzhang/course/cs4240/bonus22.tar.bz2.

1

We will use the command “bash b.sh”to decide if a.smt2 is property-preserving.

The expected property-preserving output is given as follows:

$ bash b.sh sat unknown

Correct! The size of a.smt2 is 6547.

$ echo $?

0

3 Submission

• The minimized a.smt2 file; and

• A document that describes the key steps to obtain the final a.smt2 file.

4 Collaboration

For this BONUS project, you can form a team of at most two people.

We will award identical grades to each member of a given project team, unless members of the team directly register a formal complaint. We assume that the work submitted by each team is their work solely. Any clarification question about the project handout should be posted on the course’s public Piazza message board. Under no condition is it acceptable to use code or source written by another team.

2
