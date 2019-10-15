![TDL logo](/banner2.gif)

This is a GitHub page of Theoretical Deep Learning course held by Neural Networks and Deep Learning Lab., MIPT. The working language of this course is Russian.

**The second part:** there is [a second part of this course](https://github.com/deepmipt/tdl2) devoted to generalization ability. The first part of this course is **NOT** a prerequisite for the second part.

**Location:** Moscow Institute of Physics and Technology, ~~Phystech.Bio building, room 512~~ ФИЗТЕХ.ЦИФРА building, ~~room 5-6~~ ~~room 5-19~~ room 5-22.

**Time:** Friday, 10:45, starting from 15th of February, 2019.

**Videos** are available [here](https://www.youtube.com/playlist?list=PLt1IfGj6-_-dMa3Ff8mwjq1yOGijJ89Wa).

Lecture slides, homework assignments and videos will appear in this repo and will be available for everyone. However, we can guarantee that we will check your homework only if you are a MIPT student.

**For MIPT students:** in the case you want to take this course into your personal syllabus, the real name of the course is: "Теоретический анализ подходов глубокого обучения".

Further announcements will be in our Telegram chat: https://t.me/joinchat/D_ljjxJHIrD8IuFvfqVLPw

## Syllabus:

This syllabus is not final and may change. The order of topics will change with high probability.

1. [**15.02.2019**](/lecture_1) Introduction. Loss landscape of linear networks.

2. [**22.02.2019**](/lecture_2) Loss landscape of linear networks.

3. [**1.03.2019**](/lecture_3) Loss landscape of linear res-nets. Loss landscape of wide, but shallow sigmoid nets.

4. **8.03.2019** No class.

5. [**15.03.2019**](/lecture_4) Loss landscape of deep and wide sigmoid nets.

6. [**22.03.2019**](/lecture_5) Spin-glass model. Elimination of local minima.

7. **29.03.2019** ~~GD almost surely converges to local minima. Noisy GD converges to local minima for any initialization.~~ Cancelled.

8. [**5.04.2019**](/lecture_6) General convergence guarantees for GD and its variants.

9. [**12.04.2019**](/lecture_7) GD dynamics on wide shallow ReLU nets.

10. [**19.04.2019**](/lecture_8) (Ivan Skorokodov) The information bottleneck method. Part 1.

11. [**26.04.2019**](/lecture_9) (Ivan Skorokodov) The information bottleneck method. Part 2.

12. **3.05.2019** No class.

13. **10.05.2019** No class.

14. **17.05.2019** ~~Neural nets in the limit of infinite width.~~ Homework solution demonstration.

## Prerequisites:

* Basic calculus / probability / linear algebra (matrix differentiation, SVD, eigenvalues, eigenvectors, Hessian, Markov's inequality)
* Labs are given as jupyter notebooks 
* We use python3; need familiriaty with numpy, pytorch, matplotlib
* Some experience in DL (not the first time of learning MNIST, familiarity with such words as BatchNorm, ResNet, Dropout)
* Labs are possible to do on CPU, but it can take quite a long time to train (~1-2 days).
    
## Grading:

This course will contain one lab and four theoretical assignments. 
There also will be an oral exam (in the form of interview) at the end of the course.

Let p_{hw} = "your points for homeworks" / "total possible points for homeworks (excluding extra points)". Define p_{exam} analogously.

Your final grade will be computed as follows:
grade = min(10, p_{hw} * k_{hw} + p_{exam} * k_{exam}), where the coefficents are:
* k_{hw} = 8
* k_{exam} = 4

This numbers are not final and can change slightly.

The deadlines for all assignments are computed as follows: "the day, when the assignments appear at this page, 23:59 Moscow time" + 3 weeks. **All deadlines are strict.**

All homework assignments will appear not more often than once a week.

Send your homeworks to tdl_course_mipt@protonmail.com

E-mails should be named as "Lab or theory" + "number" + "-" + "Your Name and Surname"

**Current grades** live [here](https://docs.google.com/spreadsheets/d/1IbpVdEjN9CduhjGVvVB4OZBGxMXdq9bw2MFk5VW0HPQ/edit?usp=sharing). 

**Exam** (actually, zachet with grade) will take place at zachet week. **Exam syllabus** live [here](exam_syllabus.pdf).

## Homeworks:

~~The first theoretical assignment is out! Deadline: 16.03.2019 23:59 Moscow time.~~

~~The first lab assignment is out! Deadline: 30.03.2019 23:59 Moscow time.~~

~~The second theoretical assignment is out! Deadline: 16.04.2019 23:59 Moscow time.~~

~~The third theoretical assignment is out! Deadline: 13.05.2019 23:59 Moscow time.~~

The fourth theoretical assignment is out! Deadline: 21.05.2019 23:59 Moscow time.

Theoretical assignments live [here](/hw_theory).
Labs live [here](/hw_lab).

## Course staff:

- [Eugene Golikov](https://github.com/varenick) - course admin, lectures, homeworks
- [Ivan Skorokhodov](https://github.com/universome) - homework review and beta-test, lecture about information bottleneck, off-screen comments

We also thank [Mikhail Arkhipov](https://github.com/mu-arkhipov) for gingerbread operating.

This course is dedicated to the memory of [Maksim Kretov](https://github.com/kretovmk) | 30.12.1986 - 13.02.2019, without whom this course would have never been created.
