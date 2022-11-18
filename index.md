
## Overview
This course introduces the foundational concepts and algorithms of machine learning and deep learning. The goal of this course is to endow the student with a) a solid understanding of the foundational concepts of machine learning, and b) morden machine learning techniques such as deep learning. Topics to be covered include empirical risk minimization, PAC learning, Agnostic PAC learning, perceptron, linear regression, boosting, stochastic gradient descent, support vector machines, multi-layer perceptron, convolutional neural networks, recurrent neural networks, attention mechanism. Slides and homework assignments will be released on this website. Homework solutions will only be released on Bruinlearn.

## Prerequisites
Calculus, linear algebra, probability and statistics, and Python programming.

## Textbook
- [SSBD] Shai Shalev-Shwartz and Shai Ben-David. Understanding machine learning: From theory to algorithms. Cambridge University Press, 2014.
- [ZLLS] Aston Zhang, Zachary C. Lipton, Mu Li, Alexander J. Smola, Dive into Deep Learning. 

## Programming Language
Python, Pytorch

## Logistics
<!--University of California, Los Angeles  -->
- Time: **Monday and Wednesday 2:00PM - 3:50PM**
- Location: **DODD 147**  
- Instructor: [Quanquan Gu](http://web.cs.ucla.edu/~qgu/) (Email: qgu at cs dot ucla dot edu)   
- Teaching Assistant: 
  - Zixiang Chen, Section 1A (Email: chenzx19 at cs dot ucla dot edu)
  - Jiafan He, Section 1B (Email: jiafanhe19 at g dot ucla dot edu)
  - Lucas Tecot, Section 1C (Email: lucastecot at gmail dot com)
   
- Office hours: 
    - The instructor's office hour is Thursday 9:00am-10:00am, EVI 382. 
    - The TA's office hour is 
      - Zixiang Chen, Monday 10am-12pm, Boelter 3256S-A
      - Jiafan He, Thursday 1-3pm, Boelter 3256S-F
      - Lucas Tecot, Wednesday 10am-12pm, Boelter 3256S-F
  
- Course Website: [https://uclaml.github.io/CS260-Fall2022/](https://uclaml.github.io/CS260-Fall2022/)
- Course Forum: [https://piazza.com/ucla/fall2022/cs260/home](piazza.com/ucla/fall2021/cs260/home)
(If you haven’t already, [sign up here](https://piazza.com/ucla/fall2022/cs260).)

## Grading Policy
 
Grades will be computed based on the following factors:

- Homework 35%
- Quiz 5%
- Midterm 30%
- Final Project 30%

## Schedule

| # | Date   |      Topics      |  Reading | Homework |
|---- | ----------|-------------|------|---|
| 1 | 9/26 | Introduction ([slides](https://www.dropbox.com/s/t7yujn59t5o5j4q/Lecture1.pdf?dl=0)) | Chapter 1, 2.1 of [SSBD] |  |
| 2 | 9/28 | Empirical Risk Minimization, PAC Learning ([slides](https://www.dropbox.com/s/6kc21cvmdm3o8tv/Lecture2.pdf?dl=0)) | Chapter 2 of [SSBD]| [HW1 Out](https://www.dropbox.com/s/p8alcn4l58bxoaw/hw1.pdf?dl=0) [Latex Template](https://www.overleaf.com/read/gspjpbqhbntv)|
||9/30| TA Session Week 1 ([1A slides](https://www.dropbox.com/s/1aplmmjnxtpfw30/discussion_1ar.pdf?dl=0))([1B slides](https://www.dropbox.com/s/2lgv0rbyq86ca0c/disc_1_1b.pdf?dl=0))([1C slides](https://www.dropbox.com/s/nc89ykwavsq3fe6/disc_1_1c.pdf?dl=0))|||
| 3 | 10/3 | Agnostic PAC Learning ([slides](https://www.dropbox.com/s/yhg3b9v5itnvqhw/Lecture3.pdf?dl=0))| Chapter 3, 4 of [SSBD] | |
| 4 | 10/5 | Bias-Complexity Tradeoff ([slides](https://www.dropbox.com/s/im0uev900nnb2li/Lecture4.pdf?dl=0)) | Chapter 5, 11 of [SSBD] |  |
|| 10/7 | TA Session Week 2 ([1A slides](https://www.dropbox.com/s/gm7a8wusu32ipct/CS_260_TA_Session%20%284%29.pdf?dl=0))([1B slides](https://www.dropbox.com/s/gnbfcdyhl9swr8r/week2_b.pdf?dl=0))([1C slides](https://www.dropbox.com/s/15ein6fkurprv7w/disc2_1c.pdf?dl=0))|||
| 5 | 10/10 | Perceptron/Linear regression ([slides](https://www.dropbox.com/s/fk608vjtzx58feg/Lecture5.pdf?dl=0))  | Chapter 9, 19 of [SSBD] | HW1 Due,  |
| 6 | 10/12 | Boosting ([slides](https://www.dropbox.com/s/elim4msoknhd386/Lecture6.pdf?dl=0)) | Chapter 10 of [SSBD] | [HW2 Out](https://www.dropbox.com/s/3mlp3yfdqj8m9uo/hw2.pdf?dl=0)|
||10/14| TA Session Week 3([1A slides](https://www.dropbox.com/s/sff2n90pqod5sy4/Discussion1Aweek3.pdf?dl=0))([1B slides](https://www.dropbox.com/s/znln3x9mhet0yra/CS_260_TA_Session_2021_fall%20%287%29.pdf?dl=0))([1C slides](https://www.dropbox.com/s/hhyrvqi46jb9m3k/disc3_1c.pdf?dl=0))|||
| 7 | 10/17 | Boosting, Convex Learning and SGD ([slides](https://www.dropbox.com/s/8idtj5ksrj06rtc/Lecture7.pdf?dl=0)) | Chapter 12, 14 of [SSBD] |  |
| 8 | 10/19 | AI4Database | Guest lecture |  |
||10/21| TA Session Week 4 ([1A slides](https://www.dropbox.com/s/qffpy5jr4jqlvg0/week4_1A.pdf?dl=0))([1B slides](https://www.dropbox.com/s/oopia2cp186pgb9/week4_1b.pdf?dl=0))([1C slides](https://www.dropbox.com/s/0c2bfadpht4j70n/disc4_1c.pdf?dl=0))||HW2 Due, | 
| 9 | 10/24 | Convex Learning and SGD ([slides](https://www.dropbox.com/s/8idtj5ksrj06rtc/Lecture7.pdf?dl=0))  | Chapter 12, 14 of [SSBD] | [HW3 Out](https://www.dropbox.com/s/xghwr3jw0h2sqmj/HW3.pdf?dl=0) |
| 10 | 10/26 | Regularization and Stability, Support Vector Machines ([slides](https://www.dropbox.com/s/rnnucuyzpk3wlz9/Lecture8.pdf?dl=0))|  Chapter 13 and 15 of [SSBD] |  |
|| 10/28 | TA Session Week 5 ([1A slides](https://www.dropbox.com/s/wlglz1i9ellml54/Week51A.pdf?dl=0))([1B slides](https://www.dropbox.com/s/xotkk5h6q905am7/week5_1b.pdf?dl=0)) ([1C slides](https://www.dropbox.com/s/f4v2s599fet1enn/disc5_1c.pdf?dl=0))|||
| 11 | 10/31 | Kernel Methods ([slides](https://www.dropbox.com/s/17zuj93n4pzjk7c/Lecture9.pdf?dl=0)) | Chapter 16 of [SSBD] |  |
| 12 | 11/2 | Multi-layer Perceptron I ([slides](https://www.dropbox.com/s/ufn9eis2q3n8njc/Lecture10.pdf?dl=0)) | Chapter 4 and 5 of [ZLLS] | HW3 Due |
||11/4| TA Session Week 6([1B slides](https://www.dropbox.com/s/4izv766wv14w3ga/week61b%20%282%29.pdf?dl=0))|||
|  | 11/7 | Midterm Exam |  | [HW4 Out](https://github.com/uclaml/CS260-Fall2022/blob/main/Homeworks/homework4.md) |
| 13 | 11/9 | Multi-layer Perceptron  II ([slides](https://www.dropbox.com/s/e6kko3xhxpvedz5/Lecture11.pdf?dl=0)) | Chapter 4 and 5 of [ZLLS] | |
||11/11| TA Session Week7 |||
| 14 | 11/14 | Covolutional Neural Networks I ([slides](https://www.dropbox.com/s/6knvi8o4jomvs3q/Lecture12.pdf?dl=0)) | Chapter 7 of [ZLLS] | |
| 15 | 11/16 | Covolutional Neural Networks II | Chapter 8 of [ZLLS] | HW4 Due [HW5 Out] |
||11/18 | TA Session Week 8 ([1B slides](https://www.dropbox.com/s/nwpdc64jbbkwf6u/week8_1b.pdf?dl=0))|||
| 16 | 11/21 | Recurrent Neural Networks I | Chapter 9 of [ZLLS] | |
| 17 |11/23| Recurrent Neural Networks II|Chapter 10 of [ZLLS]|HW5 Due, [HW6 Out]|
| | 11/28 | Canceled Due to NeurIPS |  | |
| 18| 11/30 | Attention Mechanisms | Chapter 11 of [ZLLS] | |
||12/2| TA Session Week10  | | HW6 Due |
| | 12/8 | Final Project Presentation | |  |
| | 12/12 | | | Project Report/Slides Due |

## Academic Integrity Policy
Students are encouraged to read the [UCLA Student Conduct Code](https://www.deanofstudents.ucla.edu/Individual-Student-Code) for Academic Integrity. 

## Homework
There will be about 5 homework assignments during the semester as we cover the corresponding material. Homework consists of both mathematical derivation, algorithm analysis and programming. Homework is required to be written in Latex. Latex homework template can be found [here](https://www.overleaf.com/read/gspjpbqhbntv). The lowest homework score will be dropped for you.

Unless otherwise indicated, you may talk to other students about the homework problems but each student must hand in their own answers and write their own code in the programming part. You also must indicate on each homework with whom you collaborated and cite any other sources you use including Internet sites. Students cannot use old solution sets for this class or solution manual to the textbook under any circumstances.

Homework assignments will be submitted through Gradescope.

Please submit your homework on time. Homework is worth full credit before the due date. It is worth zero credit after the due date.

## Exam
There will be one in-class midterm on Oct 31.

## Quiz
There will be 6 in-class pop-up quiz for the purpose of reviewing the newly learned concepts. The quizzes are closed book and closed notes. No electronic aids or cheat sheets are allowed. We will drop the lowest quiz score for you.

## Project
Students are required to do a project in this class. The goal of the course project is to provide you an opportunity to either do machine learning research or solve a real-world problem using machine learning. 

The best outcome of the project is a manuscript that is publishable in major machine learning conferences (COLT, ICML, NeurIPS, ICLR, AISTATS, UAI etc.) or journals (Journal of Machine Learning Research, Machine Learning).

<!---Instruction can be found [here](https://www.dropbox.com/s/iq6ctshs91ea3ok/Instruction.pdf?dl=0), and template for proposal and final report can be found [here](https://www.dropbox.com/s/9i5kjaibbw58ghl/template.zip?dl=0).

Please refer to [syllabus](https://www.dropbox.com/s/89u56o3rzr54asv/syllabus_CS260.pdf?dl=0) for more details.--->

