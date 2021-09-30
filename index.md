
## Overview
This course introduces the foundational theory and algorithms of machine learning. The goal of this course is to endow the student with a) a solid understanding of the foundational concepts of machine learning, and b) the ability to derive and analyze machine learning algorithms. Topics to be covered include empirical risk minimization, PAC learning, Agnostic PAC learning, perceptron, linear regression, nearest neighbors, decision trees, boosting, structural risk minimization, surrogate loss functions, stochastic gradient descent, support vector machines, kernel methods, multi-class classification, and clustering etc. Slides and homework assignments will be released on CCLE and this website. Homework solutions will only be released on CCLE.

## Prerequisites
Two years of college mathematics, including calculus, linear algebra, probability and statistics, and the ability to write computer programs.

## Textbook
Shalev-Shwartz, Shai, and Shai Ben-David. Understanding machine learning: From theory to algorithms. Cambridge University Press, 2014.

## Programming Language
Python

## Logistics
<!--University of California, Los Angeles  -->
- Time: **Monday and Wednesday 12:00PM - 1:50PM**
- Location: **[Zoom](https://ucla.zoom.us/j/93701646138)**  
- Instructor: [Quanquan Gu](http://web.cs.ucla.edu/~qgu/) (Email: qgu at cs dot ucla dot edu)   
- Teaching Assistant: 
  - Zixiang Chen, Section 1A (Email: chenzx19 at cs dot ucla dot edu)
  - Jiafan He, Section 1B (Email: jiafanhe19 at g dot ucla dot edu)
  - Lucas Tecot, Section 1C (Email: lucastecot at gmail dot com)
   
- Office hours: 
    - The instructor's office hour is Thursday 9:00am-10:00am, **[Zoom](https://ucla.zoom.us/j/93475216622)**. 
    - The TA's office hour is 
      - Zixiang Chen, Tuesday 12:00pm-2:00pm, **[Zoom](https://ucla.zoom.us/j/97892492653)**.
      - Jiafan He, Thursday 2:00pm-4:00pm, **[Zoom](https://ucla.zoom.us/j/93911326319)**.
      - Lucas Tecot, Monday and Wednesday 10:00am-11:00am, **[Zoom]()**.
  
- Course Website: [https://uclaml.github.io/CS260-Fall2021/](https://uclaml.github.io/CS260-Fall2021/)
- Course Forum: [https://piazza.com/ucla/fall2021/cs260/home](piazza.com/ucla/fall2021/cs260/home)
(If you haven’t already, [sign up here](https://piazza.com/ucla/fall2021/cs260).)

## Grading Policy
 
Grades will be computed based on the following factors:

- Homework 35%
- Quiz 5%
- Midterm 30%
- Final Project 30%

## Schedule

| # | Date   |      Topics      |  Reading | Homework |
|---- | ----------|-------------|------|---|
| 1 | 9/27 | Introduction ([slides](https://www.dropbox.com/s/umb5cj22wktqxwq/Lecture1.pdf?dl=0)) | Chapter 1, 2.1 |  |
| 2 | 9/29 | Empirical Risk Minimization, PAC Learning ([slides](https://www.dropbox.com/s/oz92oe6w24x7q1a/Lecture2.pdf?dl=0))([slides_annotated](https://www.dropbox.com/s/5luo12khex046pg/Lecture2_annotated.pdf?dl=0)) | Chapter 2 | [HW1 Out](https://www.dropbox.com/s/g31899cgztwdfov/HW1.pdf?dl=0)|
||10/1| TA Session Week 1 ([slides](https://www.dropbox.com/s/q3yrzly1a6b7o5r/Week1.pdf?dl=0))|||
| 3 | 10/4 | Agnostic PAC Learning ([slides](https://www.dropbox.com/s/2hp40z7fpu9e79t/Lecture3.pdf?dl=0))([slides_annotated](https://www.dropbox.com/s/h61d32bdtkz5wem/Lecture3_annotated.pdf?dl=0))| Chapter 3 | |
| 4 | 10/6 | Uniform Convergence ([slides](https://www.dropbox.com/s/tl3xxu117lmke5g/Lecture4.pdf?dl=0))([slides_annotated](https://www.dropbox.com/s/ryz8busg0iulnxa/Lecture4_annotated.pdf?dl=0)) | Chapter 4 | |
|| 10/8 | TA Session Week 2 ([slides](https://www.dropbox.com/s/ah0c0gi9t3avtqa/Week2.pdf?dl=0))|||
| 5 | 10/11 | Bias-Complexity Tradeoff ([slides](https://www.dropbox.com/s/ptngys3fue0ic2k/Lecture5.pdf?dl=0))([slides_annotated](https://www.dropbox.com/s/hraoue74uqwsbme/Lecture5_annotated.pdf?dl=0)) | Chapter 5, 11 | HW1 Due, [HW2 Out](https://www.dropbox.com/s/w72l7xz131ke9t1/HW2.pdf?dl=0) |
| 6 | 10/13 | VC dimension ([slides](https://www.dropbox.com/s/qho2fjrvivkkniv/Lecture6.pdf?dl=0)) ([slides_annotated](https://www.dropbox.com/s/ptmevztdjuzyezm/Lecture6a_annotated.pdf?dl=0))  | Chapter 6 |  |
||10/15| TA Session Week 3 ([slides](https://www.dropbox.com/s/gmns3kg1dmii3j3/Week3.pdf?dl=0))|||
| 7 | 10/18 | VC dimension Cont. ([slides](https://www.dropbox.com/s/qho2fjrvivkkniv/Lecture6.pdf?dl=0)) ([slides annotated](https://www.dropbox.com/s/xc5unsqes2wk4lz/Lecture6b_annotated.pdf?dl=0))| Chapter 6, 28 | |
| 8 | 10/20 | Nonuniform Learnability ([slides](https://www.dropbox.com/s/r16kjfli9i9lguu/Lecture7.pdf?dl=0)) ([slides annotated](https://www.dropbox.com/s/6eay3q56xx7mqw5/Lecture7_annotated.pdf?dl=0)) | Chapter 7 | |
||10/22| TA Session Week 4 ([slides](https://www.dropbox.com/s/3mk1b1p3h38ishh/Week4.pdf?dl=0))|||
| 9 | 10/25 | Perceptron/Linear regression ([slides](https://www.dropbox.com/s/na1gea5xtz83k70/Lecture8.pdf?dl=0))([slides_annotated](https://www.dropbox.com/s/lyt1z9htjda38uy/Lecture8_annotated.pdf?dl=0)) | Chapter 9 | HW2 Due, [HW3 Out](https://www.dropbox.com/s/rs1rtw7tf7lxwlk/homework3.zip?dl=0) |
| 10 | 10/27 | Nearest Neighbors ([slides](https://www.dropbox.com/s/a3sz9r267h99xx7/Lecture9.pdf?dl=0)) ([slides annotated](https://www.dropbox.com/s/amps5b3cual390n/Lecture9_annotated.pdf?dl=0)) | Chapter 19 |  |
|| 10/29 | TA Session Week 5 ([slides](https://www.dropbox.com/s/5c45v8m1ceqx9gh/Week5.pdf?dl=0))|||
| 11 | 11/1 | Decision Trees ([slides](https://www.dropbox.com/s/rlfcyuxsdj1qx74/Lecture10.pdf?dl=0)) ([slides annotated](https://www.dropbox.com/s/se1g3lo18se1392/Lecture10_annotated.pdf?dl=0))| Chapter 18 | Project Proposal Due |
| 12 | 11/3 | Boosting ([slides](https://www.dropbox.com/s/04waxzju22snvm9/Lecture11.pdf?dl=0))([slides annotated](https://www.dropbox.com/s/apnzqczrkjpuskt/Lecture11_annotated.pdf?dl=0)) | Chapter 10 | |
||11/5| TA Session Week 6 (slides on CCLE-Week6)|||
| | 11/8 | Midterm Exam | | |
| 13 | 11/10 | Convex Learning and SGD ([slides](https://www.dropbox.com/s/rbvq691ds5xvv4t/Lecture12.pdf?dl=0))([slides annotated](https://www.dropbox.com/s/hn5bih2mynzfwki/Lecture12_annotated.pdf?dl=0)) | Chapter 12, 14 | HW3 Due, [HW4 Out](https://www.dropbox.com/s/fr7r20jfx2x3g2k/homework4.zip?dl=0) |
||11/12| TA Session Week7 (slides on CCLE-Week7)|||
| 14 | 11/15 | Regularization Stability ([slides](https://www.dropbox.com/s/jiandf0d1fts4du/Lecture13.pdf?dl=0)) ([slides annotated](https://www.dropbox.com/s/czsqyq2dgwy3oo4/Lecture13_annotated.pdf?dl=0)) | Chapter 13 |  |
| 15 | 11/17 | Support Vector Machines ([slides](https://www.dropbox.com/s/syoeilzvdghw7jx/Lecture14.pdf?dl=0)) ([slides annotated](https://www.dropbox.com/s/5n2xnvhagkq1fdw/Lecture14_annotated.pdf?dl=0))| Chapter 15 | |
||11/19 | TA Session Week 8 ([slides](https://www.dropbox.com/s/hp2x3ahron9c4ls/Week8.pdf?dl=0))|||
| 16 | 11/22 | Kernel Methods ([slides](https://www.dropbox.com/s/wk08zpn7ya187gx/Lecture15.pdf?dl=0)) ([slides annotated](https://www.dropbox.com/s/f1n3qu3k9wm03ty/Lecture15_annotated.pdf?dl=0))| Chapter 16 | HW4 Due, [HW5 Out](https://www.dropbox.com/s/8kv12pz2eejy78h/homework5.zip?dl=0) |
|17|11/24| Multi-class Classification ([slides](https://www.dropbox.com/s/iwwiefnwggptgo3/Lecture16.pdf?dl=0)) ([slides annotated](https://www.dropbox.com/s/o2lcmvasw64wcbu/Lecture16_annotated.pdf?dl=0))|Chapter 17 ||
||11/26| Thanksgiving holidays|||
| 18 | 11/29 | Clustering ([slides](https://www.dropbox.com/s/pbtywmm9uge1h9e/Lecture17.pdf?dl=0)) ([slides annotated](https://www.dropbox.com/s/rc133xdmyu89j3s/Lecture17_annotated.pdf?dl=0)) | Chapter 22| |
| 19 | 12/1 | TBD |  |  |
||12/3| TA Session Week10 ([slides1](https://www.dropbox.com/s/t2nbniblsm0dz5i/Week9.pdf?dl=0)) ([slides2](https://www.dropbox.com/s/5dpysyftmc15hob/Week10.pdf?dl=0)) | | HW5 Due |
| | 12/8 | Final Project Presentation | |  |
| | 12/12 | | | Project Report Due |

## Academic Integrity Policy
Students are encouraged to read the [UCLA Student Conduct Code](https://www.deanofstudents.ucla.edu/Individual-Student-Code) for Academic Integrity. 

## Homework
There will be about 5 homework assignments during the semester as we cover the corresponding material. Homework consists of both mathematical derivation, algorithm analysis and programming. Homework is required to be written in Latex. Latex homework template can be found [here](https://www.dropbox.com/s/cbfagod4yq5zsdg/CS260-hw-template.zip?dl=0). The lowest homework score will be dropped for you.

Unless otherwise indicated, you may talk to other students about the homework problems but each student must hand in their own answers and write their own code in the programming part. You also must indicate on each homework with whom you collaborated and cite any other sources you use including Internet sites. Students cannot use old solution sets for this class or solution manual to the textbook under any circumstances.

Homework assignments will be submitted through Gradescope. You should have received an invite to Gradescope after you get enrolled in this class. Login via the invite, and submit the homework assignments on time. 

Please submit your homework on time. Homework is worth full credit before the due date. It is worth zero credit after the due date.

## Exam
There will be one midterm. The exam is a take-home, 24-hours, open-book exam. If you need a makeup exam, please email us by Nov 1st.

## Quiz
There will be 6 in-class pop-up quiz for the purpose of reviewing the newly learned concepts. The quizzes are closed book and closed notes. No electronic aids or cheat sheets are allowed. We will drop the lowest quiz score for you.

## Project
Students are required to do a project in this class. The goal of the course project is to provide the students an opportunity to explore research directions in optimization or machine learning. Therefore, the project should be related to the course content. An expected project consists of
• A novel and sound solution to an interesting problem
• Comprehensive literature review and discussion
• Thorough theoretical/experimental evaluation and comparisons with existing approaches

The best outcome of the project is a manuscript that is publishable in major machine learning conferences (COLT, ICML, NeurIPS, ICLR, AISTATS, UAI etc.) or journals (Journal of Machine Learning Research, Machine Learning).

Instruction can be found [here](https://www.dropbox.com/s/iq6ctshs91ea3ok/Instruction.pdf?dl=0), and template for proposal and final report can be found [here](https://www.dropbox.com/s/9i5kjaibbw58ghl/template.zip?dl=0).

Please refer to [syllabus](https://www.dropbox.com/s/89u56o3rzr54asv/syllabus_CS260.pdf?dl=0) for more details.
