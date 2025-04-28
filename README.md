# comp598-homework-2---unix-server-and-command-line-exercises-solved
**TO GET THIS SOLUTION VISIT:** [COMP598 Homework 2 – Unix server and command-line exercises Solved](https://www.ankitcodinghub.com/product/comp-598-homework-2-unix-server-and-command-line-exercises-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118606&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP598 Homework 2 – Unix server and command-line exercises Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
The goal of this assignment is to for you to get more familiar with your Unix EC2 – both as a data science machine and as a server (as a data scientist, you’ll need it as both).

Task 1: Setting up a webserver (15 pts)

The objective of this task is to setup your EC2 instance to run an apache webserver on port 8008. Your goal is to have it serving up the file comp598_hw2.txt at the www root. In other words, my web browser can access it at http://X.Y.Z.W:8008/comp598_hw2.txt, where X.Y.Z.W is the public IP address of your EC2. The file itself should be empty.

Task 2: Data filtering (15 pts)

Write a bash shell script stats.sh that accepts as a command line argument a tweet file (similar to the one in homework 1) and prints out, on subsequent lines:

– The number of lines in the file

– The first line of the file (i.e., the header row)

– The number of lines in the last 10,000 rows of the file that contain the string “potus” (case-insensitive).

– Of rows 100 – 200 (inclusive), how many of them that contain the word “fake”

All this should be done only using standard Unix commands and pipes.

To be clear, your script should work on any file which has at least 10,000 lines in it. It will be tested by TAs by calling it using:

stats.sh &lt;test_file&gt;

The TAs will get to choose the test file.

Submission Instructions

Your MyCourses submission should contain – at minimum – the following:

– ip_address.txt o contains exactly one line containing the public IP address of your EC2 instance. – stats.sh – the bash file that performs the tasks described above

In addition to the submission file:
