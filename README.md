# EECS 589 Fall 2024: Advanced Computer Networks
EECS589: Advanced Computer Networks (Fall 2024)

## Administrivia
* Lectures: 3150 DOW, MW 9-10:30AM
* Discussion: 1008FXB, F 1030-1130AM

### Team

| Member (uniqname) | Role | Office Hours |
| :---------------- | :--- | :----------- |
| [Z. Morley Mao](http://eecs.umich.edu/~zmao) (zmao) | Faculty | 4629 BBB. By appointment and after each lecture |
| [Xueshen Liu](https://luke20000429.github.io/) (liuxs) | GSI | BBB Learning Center or [Zoom (passcode:20240111)](https://umich.zoom.us/j/4770432209). Thur. 13:00-14:00pm |

### Piazza

ALL communication regarding this course must be via [Piazza](https://piazza.com/umich/fall2024/cse589001fa2024/home). 
This includes questions, discussions, announcements, as well as private messages.
Sign up for the course Piazza [here](https://piazza.com/umich/fall2024/cse589001fa2024).

Presentation slides and paper summaries should be emailed to uploaded to [Canvas](https://umich.instructure.com/courses/707608).

**Paper summaries are due before the lecture (i.e., before 9am Mondays and Wednesdays) to be done individually.**  

## Course Description
This is a graduate level course on computer networking focusing on advanced
topics and is a must for anyone interested in doing research in computer
networks. This class examines current and emerging research topics in
computer networking. Topics covered include network protocols, network
measurement, Internet routing, peer to peer networks, network security,
wireless, and sensor networks. 

The course consists of both a reading/lecture/discussion component and a project
component. Emphasis of the course is on topics in wide-area networks, wireless
networks, and measurement methodologies for Internet and wireless experiments.
Significant emphasis will be put on security and network management issues
related to computer networks, as these are becoming increasingly important given
the growing number attacks and complexity of networks.  We focus both on 
existing technologies and on why some of them are not sufficient because of
technology trends or changes in fundamental assumptions. As an example, early
designers of Internet assumed cooperative behavior of end nodes. The state of
the art of millions of compromised hosts completely changes this assumption and
today's landscape on the Internet. We will read about ~50 research papers on the
most recent topics of computer networking.

Students are expected to carry out a research project including analysis,
design, and implementation components when appropriate on a novel subject.  The
class projects can be any of the following types: 
(1) algorithm design applied to
networked system, implementation of a novel networking system, 
(2) measurement of
existing network protocols, and 
(3) simulation of a proposed network algorithm. We
emphasize problems that are real and solutions that will make a difference,
ideally can be deployed.

The lecture will be conducted in an interactive
fashion. The instructors will lead the discussion for the first few meetings of the class, but
everyone must participate. For the remainder of the class, each
student will present a paper. Students will read and review
papers before class.  You will be graded on reviews; class discussions; and
project scope, effort, and results.  It is critical that you participate in the class discussions to get more out of the class.

### Prerequisites
Students are expected to have good programming skills and must have taken at
least one undergraduate-level systems-related course (from operating systems,
databases, distributed systems, and networking).  However, for graduate students, we expect that 
the students will be able to pick up the required background.  Please come to talk to the instructor if you are concerned.

### Textbook
This course has NO textbook. The class will select and discuss recent papers from the networking literature
in order to understand trends in networking research. 
Instructors will select papers based on the interests of the class
focusing primarily on the top networking and systems conferences, e.g., SIGCOMM, Mobicom, MobiSys, NSDI, Usenix Security, IMC, and lead discussions.

I also recommend supplemental reading of well recognized papers from [SIGCOMM Test-of-Time papers](https://www.sigcomm.org/awards/test-of-time-paper-award).

## Proposed Schedule and Reading List
Papers to be selected from but not limited to:
* [SIGCOMM'24](https://conferences.sigcomm.org/sigcomm/2024/program/)
* [MobiSys'24](https://www.sigmobile.org/mobisys/2024/program.html)
* [NSDI'24](https://www.usenix.org/conference/nsdi24/technical-sessions)
* [Usenix Security'24](https://www.usenix.org/conference/usenixsecurity24/technical-sessions)

The latest reading list is [linked here](ReadingList.md).

|#| Date      | Topic and Readings                       | Presenter|
|--|-----------|----------------------------------------|---------| 
|1 | Aug 26      | **Background:Internet philosophy**                 | Prof. Mao | 
|2| Aug 28 |  Review of the networking basics      |Prof. Mao | 
|| Sep 2 |  Labor Day (holiday)       | | 
|3| Sep 4 | Software defined Networks ([paper](https://storage.googleapis.com/gweb-research2023-media/pubtools/1002525.pdf))  |Xueshen | 
|4| Sep 9 |  AI/ML for networks ([paper](https://arxiv.org/pdf/2402.02338))           |Prof. Mao | 
|5| Sep 11 | LLM for security ([paper](https://www.usenix.org/system/files/usenixsecurity24-liu-peiyu.pdf))              | Prof. Mao | 
|6| Sep 16 |  ML at scale ([QuickUpdate](https://www.usenix.org/conference/nsdi24/presentation/matam))    | Jiarui Li | 
|7| Sep 18 |  Networking for AI/ML ([CacheGen](https://dl.acm.org/doi/pdf/10.1145/3651890.3672274))                         | Prof. Mao | 
|8| Sep 23 |  Network virtualization ([NetEdit](https://dl.acm.org/doi/pdf/10.1145/3651890.3672227))                        | Tao Wei | 
|9| Sep 25 | Mobile / Wireless networks  ([5G study](https://cs.stanford.edu/~keithw/sigcomm2024/sigcomm24-final1021-acmpaginated.pdf))    | Yoon Sung Ji  | 
|10| Sep 30 | Mobile / Wireless networks ([5G Carrier Aggregation](https://cs.stanford.edu/~keithw/sigcomm2024/sigcomm24-final610-acmpaginated.pdf))                             | Robert Stanley   | 
|11| Oct 2 |  Network security / privacy (Weiyuan:[VPNChecker](https://dl.acm.org/doi/10.1145/3589334.3645552))/ blockchains / Censorship(Erik:[GFW paper](https://www.usenix.org/conference/usenixsecurity23/presentation/wu-mingshi))                          | Erik Chi, Weiyuan Lyu   | 
|12| Oct 7 |   Network security / privacy  / blockchains ([ConfMask](https://charlie-xiao.github.io/assets/pdf/projects/confmask.pdf))                           | Pratik Nadipelli   | 
|13| Oct 9 |    Network security / (Christine:[BEAM](https://www.usenix.org/conference/usenixsecurity24/presentation/chen-yihao))  (Wayne:[TSPU](https://dl.acm.org/doi/abs/10.1145/3517745.3561461))                            | Christine Zeng, Wayne Wang | 
|| Oct 14 |  Fall study break        |    | 
|14| Oct 16 |  Network measurement, Scheduling data transfers (Daniel:[vPIFO](https://cs.stanford.edu/~keithw/sigcomm2024/sigcomm24-final1052-acmpaginated.pdf))                              | Yijia Gao, Daniel Tian   | 
|15| Oct 21 |  Network measurement                              |  Calvin Chan  | 
|16| Oct 28 |  Data center networking, Networking for Video games (Ravi:[ZGaming](https://dl.acm.org/doi/10.1145/3603269.3604819))      | Jiyu Chen, Ravi Bhatt| 
|17| Oct 30 |  Data center networking, Neural WAN TE (Rushil:[HARP](https://cs.stanford.edu/~keithw/sigcomm2024/sigcomm24-final310-acmpaginated.pdf))   | Efe Akinci, Rushil Talla   | 
|18| Nov 4 |   Network QoS                  | Dhanya Narayanan   | 
|19| Nov 6 |   Programming networks         |  Charles Cal  | 
|20| Nov 11 |  Wireless sensing ([Radarize](https://arxiv.org/abs/2311.11260))           | Joey Brewington   | 
|21| Nov 13 |  Modeling networks, streaming applications (Jimmy:[NeRFHub](https://dl.acm.org/doi/pdf/10.1145/3643832.3661879))               | Feiyu Wu, Zheng Jimmy Li  | 
|22| Nov 18 |  Cloud systems              |  Chunhao Liao  | 
|23| Nov 20 |  Network applications, e.g., vehicular networks                              | Ankith Palakodati, Nikhil Sridhar  | 
|24| Nov 25 |  Traffic engineering  ([Effingo](https://dl.acm.org/doi/pdf/10.1145/3651890.3672262))       | Mitchell Chang   | 
|25| Nov 25 |     Thanksgiving break         | |
|26| Dec 2 |   Verification / validation      | Zhengwei Wang | 
|27| Dec 4 |  Final project presentations   |Students | 
|28| Dec 9 |  Final project presentations   |Students | 


## Grading
Students who satisfactorily complete all assigned work will receive a B+ or better.

## Policies

### Honor Code
[The Engineering Honor Code](http://honorcode.engin.umich.edu/) applies to all activities related to this course.

### Groups
All activities of this course will be performed in **groups of 2-3 students**.
Please use Piazza to form groups.

### Paper Presentation
The course will be conducted as a seminar. 
One or two students will present in each class depending on the paper assigned.
Each student will be assigned to present a pair of papers once or twice
throughout the semester. 

Presentations should last **about 45 minutes** without interruption.
However, presenters should expect questions and interruptions throughout. 

In the presentation, you should:

* Motivate the paper and provide background.
* Present the high-level idea, approach, and/or insight (using examples, whenever appropriate). 
* Discuss technical details so that one can understand the key details without carefully reading it.
* Explain the difference between this paper and related work.
* Raise questions throughout the presentation to generate discussion.
* Discuss the positive and negatives/limitations of the work.  Highlight opportunities for potential follow-up work.

### Paper Summaries
Every student is required to review one to two papers assigned for each class (except for the paper they present in class).
One of these reviews can be brief, summarizing the main contributions of the paper and one critical assessment (e.g., how the paper could be improved, or compares to related work, or advances the state of the art).
This brief review should be about a paragraph in length. 

The second review should be up to one page long, explaining in detail the contributions and context of the paper.  This review
should address the following four questions in about a paragraph each.
**(If there is only one paper assigned for review, use the detailed format for the review.)**

* What is the problem addressed by the paper, and why is this problem important?
* What is the hypothesis of the work?
* What is the proposed solution, and what key insight guides their solution?
* What is one (or more) drawback or limitation of the proposal, and how will you improve it?

Reviews must be submitted on [Canvuas](https://umich.instructure.com/courses/707608).

**Late reviews will not be counted.** 
You should use [this template](SummaryTemplate.md) for writing your summary.
Allocate enough time for your reading, discuss as a group, write the summary carefully, and finally, include key observations from the class discussion.

You must read and review every assigned paper and bring questions to the lectures for discussions.

### Participation
You are expected to attend all lectures (you may skip up to 2 lectures for legitimate reasons), and more importantly, participate in class discussions.

### Project
You will complete substantive work an instructor-approved problem and have original contribution. 
[This doc](https://docs.google.com/document/d/1fjmfxW84lJFY-CQal0EGETEDBRXGnoPDr8xm5pSWOQo/edit) has some project ideas with support from grad students in Prof. Mao's lab who can provide additional information.
Surveys are not sufficient as projects; instead, each project must contain a survey of background and related work. 
You must meet the following milestones (unless otherwise specified in future announcements) to ensure a high-quality project at the end of the semester:
(These dates are tentative and will be confirmed via Canvas assignments.)

* Turn in a 2-page draft proposal (including references) by **September 23**. Remember to include the names and Michigan email addresses of the group members. 
* Keep revising your initial idea and incorporate instructor feedback. However, your team and project proposal must be finalized and approved on or before September 30.
* Each group must submit a 4-page mid-semester progress report and present mid-semester progress during class hours on the week of Nov 4.
* **Each group must prepare for 5 to 15 minutes presentation for mid-semester progress during class hours on November 4**.
* Each group must present their final results during a presentation starting on December 4.
* **Each group must turn in an 8-page final report and your code via email on or before 11:59PM EST on December 13.** The report must be submitted as a PDF file, with formatting similar to that of the papers you've read in the class. The self-contained (i.e., include ALL dependencies) code must be submitted as a zip file. Each zip file containing the code must include a README file with a step-by-step guide on how to compile and run the provided code.


#### Acknowledgement
This course syllabus is influenced by [prior offerings](https://github.com/forkjoseph/EECS589) of EECS589.
