---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: COMP221 - Algorithm Design & Analysis (Spring 2024) 
author: Suhas Arehalli
category: Syllabus
layout: post
---

Welcome to the COMP221 (Algorithm Design & Analysis) Course Page. For course policies, please check the [syllabus](https://docs.google.com/document/d/1JmHjZyhxpJ14jmWKvz0pmMYYLHjADHfDV1QcbTnYOQY/edit?usp=sharing). 


### Resources

#### Office Hours
Me and the preceptors will hold OH from the 2nd week of the semester onward. Times can be found [in this google calendar](https://calendar.google.com/calendar/u/0?cid=Y183Y2IzMjliOTYxY2ZlM2YyNDZmZDBkNzQzNmM4OTE4YWI2OWEyZTY4MTBiNGU1MjAwNWU1MjUxM2ExNzdkYTIyQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20). If posted times don't work for you, please email me and we can schedule a separate meeting!

#### MSCS Slack Channel
In addition to office hours, this course has a dedicated slack channel in the MSCS Slack: #comp221-sp24. Note that while me and the preceptors will be in the chat, occasionally posting announcements, this channel is to faciliate communication amongst students (ask questions to eachother, form study groups, etc.). If you need to contact course staff, please send me or the preceptors an email! 

### Schedule
The schedule below will be updated to keep track of all released course materials. Keep in mind that I may shift planned topics to adjust pace as necessary. 

<div class="table-wrapper" markdown="block">

| Week | Date | Topic | Reading | Materials |
| :-: | :- | :- | -: | :- |
| 0 | FRI 1/19 | Course Overview | NA |[Syllabus](https://docs.google.com/document/d/1JmHjZyhxpJ14jmWKvz0pmMYYLHjADHfDV1QcbTnYOQY/edit?usp=sharing), [Beginning-of-Semester Survey](https://docs.google.com/forms/d/e/1FAIpQLSfex1kUIEJ44Pk1jZ8UwHIWSo-bhEgpNAOZdeKqfVCjUUpKAg/viewform?usp=sf_link) |
| 1 | MON 1/22 | RAM Model, Mathematics Foundations | Skiena 2.1, 2.6--2.8  | [Activity 1](pages/Activity1/) |
| - | WED 1/24 | Big-O(h) Analysis  | Skiena 2.2--2.4 | Skiena [2--5](pages/2-5Incident), 2--11 |
| - | FRI 1/26 | Big-O(h) Analysis  | -  | [Activity 2](pages/Activity2), [Time Complexity Notes]({{ site.url }}/notes/TimeComplexity.pdf)  |
| 2 | MON 1/29 | Proofs of Correctness vs Runtime Analysis | Skiena 1.3--1.4, 1.6. Skim 2.5  |[Tao on rigor](https://terrytao.wordpress.com/career-advice/theres-more-to-mathematics-than-rigour-and-proofs/)  |
| - | WED 1/31 | *Proofs of Correctness 2* ~~Brute Force Analysis + Arrays/Linked List Review~~ |  | [Activity 3](pages/Activity3), [Correctness Notes]({{ site.url }}/notes/Correctness.pdf) |
| - | FRI 2/02 | **CLASS CANCELLED** (Review: *Arrays, Linked Lists,* Stacks, Queues)  | Skiena 3.1--3.2 | [Activity 4](pages/Activity4) |
| 3 | MON 2/05 | *Brute Force Algorithms* ~~Maps/Hashing~~  |  | [Activity 5](pages/Activity5), [Brute Force Notes]({{ site.url }}/notes/BruteForce.pdf) |
| - | WED 2/07 | *HashMaps,* Trees, PQueues & Graphs | Skiena 3.3--3.7, 7.1--7.2  | [Activity 6](pages/Activity6)  |
| - | FRI 2/09 | Sorting: Tree/HeapSort | Skiena 4.1--4.3 | [Activity 7](pages/Activity7), [HeapSort Notes]({{ site.url }}/notes/HeapSort.pdf) |
| 4 | MON 2/12 | Sorting: MergeSort | Skiena 4.5  | [Activity 8](pages/Activity8), [MergeSort Notes]({{ site.url }}/notes/MergeSort.pdf)  |
| - | WED 2/14 | Sorting: QuickSort | Skiena 4.6 | [Activity 9](pages/Activity9), [QuickSort Notes]({{ site.url }}/notes/QuickSort.pdf) |
| - | FRI 2/16 | **Exam 1** |  | [Exam 1 LGs](https://docs.google.com/document/d/1VPGXnrsCvWL3PJLWo2WqsZSgxRDYw6lbzurS5phtKhM/edit), [Exam Revision Policy](https://docs.google.com/document/d/1Gzm94mUpq-XRqZm460AsI2qo7M6ttpGVwZLLlrtWJFY/edit?usp=sharing) |
| 5 | MON 2/19 | Binary Search Variants  | Skiena 5.1--5.3  | [Activity 10](pages/Activity10)  |
| - | WED 2/21 | Recurrence Relations and the Master Theorem | Skiena 5.4 | [Activity 11](pages/Activity11), [Master Theorem Notes]({{ site.url }}/notes/MasterThm.pdf)  |
| - | FRI 2/23 | Divide & Conquer (Largest Subrange/Closest Pair) | Skiena 5.5--5.6 | [Activity 12](pages/Activity12)  |
| 6 | MON 2/26 | Graphs, BFS/DFS | Skiena 7.5--7.10  | [BFS Notes]({{ site.url }}/notes/BFS.pdf)  |
| - | WED 2/28 | Graph Traversal Problems |  | [Activity 13](pages/Activity13)  |
| - | FRI 3/01 | **Class Cancelled**: Capstone Day! | |  |
| 7 | MON 3/04 | Greedy Algorithms (Prim's/Kruskal's) | Skiena 8.1 | [Activity 14](pages/Activity14) |
| - | WED 3/06 | Union-Find + Kruskal's 2.0 |  | [Activity 14](pages/Activity14), [MST Notes]({{ site.url }}/notes/MST.pdf) |
| - | FRI 3/08 | Shortest-Path (Dijkstra's) | Skiena 8.3  | [Activity 15](pages/Activity15), [Dijkstra Notes]({{ site.url }}/notes/Dijkstra.pdf) |
| 8 | 3/11 -- 3/15 | **Spring Break** |  |  |
| 9 | MON 3/18 | Max-Flow/Min-Cut (Ford-Fulkerson, Edmonds-Karp) | Skiena 8.5  | [Activity 16](pages/Activity16)  |
| - | WED 3/20 | Max-Flow Applications/Bipartite Matching |  | [Activity 16](pages/Activity16), [Network-Flow Notes]({{ site.url }}/notes/NetworkFlow.pdf), [Quanta on Advances in Max-Flow](https://www.quantamagazine.org/researchers-achieve-absurdly-fast-algorithm-for-network-flow-20220608/) |
| - | FRI 3/22 | All-Pair Shortest-Path (Floyd-Warshall) |  | [Activity 17](pages/Activity17) |
| 10 | MON 3/25 | **Exam 2**  |  | [Exam 2 LGs](https://docs.google.com/document/d/1vmRf7zIShmZq30AMCj-T2db6x19VSpL7rqiyzWZkAVI/edit?usp=sharing) [Exam Revision Policy](https://docs.google.com/document/d/1Gzm94mUpq-XRqZm460AsI2qo7M6ttpGVwZLLlrtWJFY/edit?usp=sharing) |
| -  | WED 3/27 | **Class Cancelled** |  |  | 
| -  | FRI 3/29 | Intro to Dynamic Programming | Skiena 10.1 | [Activity 18](pages/Activity18)  |
| 11 | MON 4/1 | Approximate String Matching | Skiena 10.2 | [Activity 19](pages/Activity19)  |
| -  | WED 4/3 | CKY Parsing | Skiena 10.8  | [Activity 19](pages/Activity19) |
| -  | FRI 4/5 | Brute Force 2 | Skiena 9.1--9.3, 9.6--9.7  | [Activity 19](pages/Activity19)  |
| 12 | MON 4/8 | Intro to Complexity Theory | Skiena 11.1 | [Activity 20](pages/Activity20), [Complexity Theory Notes]({{ site.url }}/notes/Complexity.pdf) |
| -  | WED 4/10 | Reductions and SAT  | 11.2--11.6  | [Activity 20](pages/Activity20) |
| -  | FRI 4/12 | P vs. NP/Approximation | 11.9, 12.1--12.2 | [Activity 20](pages/Activity20) |
| 13 | MON 4/15 | **Exam 3** |  | [Exam 3 LGs](https://docs.google.com/document/d/17ENl5vGj3CDvw9HrW9E5CNOoROD_C0dKvNHQQbq6qew/edit?usp=sharing), [Exam 3 Revisions](https://docs.google.com/document/d/1GYhMTvtP9qTPw4GE3qNfqMsrOUa1u7LuJc1BkgJKPd8/edit?usp=sharing) |
| 13+ |  | **Project Workday** |  | [Project Guidelines](https://docs.google.com/document/d/1gTcFpb5ST8ZLcLCTL3q17xFaN8Hxy34GH9YFeRjIVDk/edit?usp=sharingr) [Register your group](https://forms.gle/Ba8i97M22jtYWXFt7) |

</div> 

Selected activity solutions can be found [here]({{ site.url }}/notes/ActivitySolutions.pdf) (Updated for: Activities 8, 10--13).

### Homeworks

#### Homework 1
**DUE: 2/20/2024**

<div class="table-wrapper" markdown="block">

[Instructions]({{ site.url }}/hws/COMP221_HW1.pdf) | [Sample CSV]({{ site.url }}/hws/sample_times.csv)

</div> 

#### Homework 2
**DUE: 3/8/2024**

<div class="table-wrapper" markdown="block">

[Instructions]({{ site.url }}/hws/COMP221_HW2.pdf) | [LaTeX Source]({{ site.url }}/hws/COMP221_HW2.tex)

</div> 

**ERRATA:** 

- Problem 4b: a valid orderings -> a valid ordering. Please provide an algorithm that finds any valid ordering of letters given the data. 
- Problem 3e: When I say faster here, it's a rare case of me referring to speed in a non-asymptotic way! Think in terms of number of vertices visited/edges traversed, etc.

#### Homework 3
**DUE: 4/8/2024**

<div class="table-wrapper" markdown="block">

[Instructions]({{ site.url }}/hws/COMP221_HW3.pdf) | [LaTeX Source]({{ site.url }}/hws/COMP221_HW3.tex) | [Sample Code](https://github.com/mac-comp221-sp24/hw3-template)

</div> 

**Errata:**:
- For implementation questions, return "inf" as the cost if the requested structure (SP/MST) doesn't exist.
- The small puzzle was added 3/29 (previously the assignment only totalled 99 points!). 
- Note that github classroom decided not to use the template as starter code, so i've linked the sample file-processing and input-handling code above. Regardless, as long as you implement the correct command-line behavior, you should be fine!
- Problem 1a: The problem says that if a shortest path exists, *that* path is simple. This neglects to cover cases where multiple shortest paths exist! This should be: if a shortest path exists, there exists a simple shortest path.  
- Problem 1d/e: Assume the $t$ iterated over in the first for loop is different than the $t$ that is the target vertex (mentally replace it with a $t'$!)
- Problem 2c: You only need to describe the modification you would make --- No need to write pseudocode! Just convey the idea of the modification.
- Problem 2: It should be that in the example we start with $1c_1$ and end with $1.05c_1$. The problem mistakenly labels the result as $1.05c_2$. Apologies for the typo! 

#### Homework 4
**Due: 4/17/2024**

<div class="table-wrapper" markdown="block">

[Instructions]({{ site.url }}/hws/COMP221_HW4_corrected.pdf) | [LaTeX Source]({{ site.url }}/hws/COMP221_HW4.tex) 

</div> 

**Errata**:
- Additional Hints + a reduction in book-keeping for HW4 (on 4/11)! Please download the new, corrected version above!
