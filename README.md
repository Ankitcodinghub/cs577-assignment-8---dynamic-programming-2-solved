# cs577-assignment-8---dynamic-programming-2-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs577-solved-7/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120295&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS577 Assignment 8 – Dynamic Programming 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
Answer the questions in the boxes provided on the question sheets. If you run out of room for an answer, add a page to the end of the document.

Dynamic Programming

Do NOT write pseudocode when describing your dynamic programs. Rather give the Bellman Equation, describe the matrix, its axis and how to derive the desired solution from it.

1. Kleinberg, Jon. Algorithm Design (p. 329, q. 19).

We say that a string s is an interleaving of x and y if its symbols can be partitioned into two (not necessarily contiguous) subsequences s0 and s00, so that s0 is a repetition of x and s00 is a repetition of y. Give an efficient algorithm that takes strings s, x, and y and decides if s is an interleaving of x and y. Note: We write xk to denote k copies of x concatenated together. We say that a string x0 is a repetition of x if it is a prefix of xk for some number k. So x0 = 10110110110 is a repetition of x = 101.

Kleinberg, Jon. Algorithm Design (p. 328, q. 18).

Consider the problem of editing strings over a four-letter alphabet {z1,z2,z3,z4}. The edits one can make are (1) you can insert a character, (2) delete a character, and (3) replace a character with another. You are given a fixed cost G per insertion, and the same cost G for deletion. You are also given a fixed cost R for replacing a mismatched character. Assume that each of these parameters is a positive integer. The edit distance between the two strings is G times the number of insertions plus G times the number of deletions plus R times the number of replacements.

Suppose you are given two strings A = a1a2…am and B = b1b2…bn and a proposed edit to transform A into B. Give an O(mn) algorithm to decide whether this edit is the unique minimum-cost edit between A and B.

Kleinberg, Jon. Algorithm Design (p. 327, q. 16).

In a hierarchical organization, each person (except the ranking officer) reports to a unique superior officer. The reporting hierarchy can be described by a tree T, rooted at the ranking officer, in which each other node v has a parent node u equal to his or her superior officer. Conversely, we will call v a direct subordinate of u.

Consider the following method of spreading news through the organization.

• The ranking officer first calls each of her direct subordinates, one at a time.

• As soon as each subordinate gets the phone call, he or she must notify each of his or her direct subordinates, one at a time.

• The process continues this way until everyone has been notified.

Note that each person in this process can only call direct subordinates on the phone.

We can picture this process as being divided into rounds. In one round, each person who has already heard the news can call one of his or her direct subordinates on the phone. The number of rounds it takes for everyone to be notified depends on the sequence in which each person calls their direct subordinates. Give an efficient algorithm that determines the minimum number of rounds needed for everyone to be notified, and outputs a sequence of phone calls that achieves this minimum number of rounds.

Kleinberg, Jon. Algorithm Design (p. 330, q. 22).

To assess how “well-connected” two nodes in a directed graph are, one can not only look at the length of the shortest path between them, but can also count the number of shortest paths.

Give an efficient algorithm that computes the number of shortest v w paths in G. (The algorithm should not list all the paths; just the number suffices.)

The following is an instance of the Knapsack Problem. Before implementing the algorithm, run through the algorithm by hand on this instance. To answer this question, generate the table, indicate the and implement it in O(nW) time, where n is the number of items and W is the capacity.

The input will start with an positive integer, giving the number of instances that follow. For each instance, there will two positive integers, representing the number of items and the capacity, followed by a list describing the items. For each item, there will be two nonnegative integers, representing the weight and value, respectively.

A sample input is the following: Ioo 0i or 3o 4o

2 o

nen 1 34 1003 4o Ww i 00 2Z 2Z 3Z 5Z z 1 2

3 3 3 o Z 2 6 4th

2 4

The sample input has two instances. The first instance has one item and a capacity of 3. The item has weight 4 and value 100. The second instance has three items and a capacity of 4.

For each instance, your program should output the maximum possible value. The correct output to the sample input would be:

0

6
