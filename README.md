# EECS 589 Fall 2024: Advanced Computer Networks
EECS589: Advanced Computer Networks (Fall 2024)

## Administrivia
* Lectures: 3150 DOW, MW 9-10:30AM
* Discussion: 1008FXB, F 1030-1130AM

### Team

| Member (uniqname) | Role | Office Hours |
| :---------------- | :--- | :----------- |
| [Z. Morley Mao](http://eecs.umich.edu/~zmao) (zmao) | Faculty | 4629 BBB. By appointment and after each lecture |
| [Xueshen Liu](https://luke20000429.github.io/) (liuxs) | GSI | BBB Learning Center. By appointment |

### Piazza

ALL communication regarding this course must be via [Piazza](https://piazza.com/umich/fall2024/cse589001fa2024/home). 
This includes questions, discussions, announcements, as well as private messages.
Sign up for the course Piazza [here](https://piazza.com/umich/fall2024/cse589001fa2024).

Presentation slides and paper summaries should be emailed to uploaded to [Canvas](https://umich.instructure.com/courses/707608).

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
student (can be in groups) will present a paper. Students will read and review
papers before class.  You will be graded on reviews; class discussions; and
project scope, effort, and results.

### Prerequisites
Students are expected to have good programming skills and must have taken at
least one undergraduate-level systems-related course (from operating systems,
databases, distributed systems, and networking).

### Textbook
This course has NO textbook. The class will select and discuss recent papers from the networking literature
in order to understand trends in networking research. 
Instructors will select papers based on the interests of the class
focusing primarily on the top networking and systems conferences, e.g., SIGCOMM, Mobicom, MobiSys, NSDI, Usenix Security, IMC, and lead discussions.

I also recommend supplemental reading of well recognized papers from [SIGCOMM Test-of-Time papers](https://www.sigcomm.org/awards/test-of-time-paper-award).

## Proposed Schedule and Reading List
Papers to be selected from but not limited to:
* [SIGCOMM'24](https://conferences.sigcomm.org/sigcomm/2024/program/)
* [MobiCom'23](https://sigmobile.org/mobicom/2023/accepted.html)
* [NSDI'24](https://www.usenix.org/conference/nsdi24/technical-sessions)
* [Usenix Security'24](https://www.usenix.org/conference/usenixsecurity24/technical-sessions)

The latest reading list is [linked here](ReadingList.md).

|#| Date  | Topic and Readings                       | Presenter|
|--|------|----------------------------------------|---------| 
|1 | Aug 26      | **Background:Internet philosophy**                 | Prof. Mao | 
|2| Aug 28 |  Review of the networking basics      |Prof. Mao | 
|| Sep 2 |  Labor Day (holiday)       | | 
|3| Sep 4 | Software defined Networks  |Xueshen | 
|4| Sep 9 |  AI/ML for networks           |Prof. Mao | 
|5| Sep 11 | AI/ML for networks                            |  | 
|6| Sep 16 |  Networking for AI/ML                          |  | 
|7| Sep 18 |  Networking for AI/ML                               |  | 
|8| Sep 23 |  Network virtualization                               |  | 
|9| Sep 25 | Mobile / Wireless networks                              |    | 
|10| Sep 30 | Mobile / Wireless networks                              |    | 
|11| Oct 2 |  Network security / privacy                              |    | 
|12| Oct 7 |   Network security / privacy                               |    | 
|13| Oct 9 |    Network security / privacy                              |    | 
|| Oct 14 |  Fall study break        |    | 
|14| Oct 16 |  Network measurement                              |    | 
|15| Oct 21 |  Network measurement                              |    | 
|16| Oct 28 |  Data center networking                              |    | 
|17| Oct 30 |  Data center networking                              |    | 
|18| Nov 4 |   Network QoS                  |    | 
|19| Nov 6 |   Programming networks         |    | 
|20| Nov 11 |  Wireless sensing            |    | 
|21| Nov 13 |  Modeling networks               |    | 
|22| Nov 18 |  Cloud systems              |    | 
|23| Nov 20 |  Network applications, e.g., vehicular networks                              |    | 
|24| Nov 25 |  Traffic engineering                              |    | 
|25| Nov 25 |     Thanksgiving break         | |
|26| Dec 2 |   Verification / validation      |    | 
|27| Dec 4 |  Final project presentations   |Students | 
|28| Dec 9 |  Final project presentations   |Students | 


## Grading
Students who satisfactorily complete all assigned work will receive a B+ or better.

## Policies

### Honor Code
[The Engineering Honor Code](http://honorcode.engin.umich.edu/) applies to all activities related to this course.

### Groups
All activities of this course will be performed in **groups of 2-3 students**.

[comment] [Declare your group's membership and paper preferences](https://goo.gl/forms/VuAkrqQqkSKgZEUn2) by September 9, 2024.
[comment] After this date, we will form groups from the remaining students.

### Paper Presentation
The course will be conducted as a seminar. 
Two students will present in each class.
Each student will be assigned to present a pair of papers at least twice
throughout the semester. 
Presentations should last **at most 45 minutes** without interruption.
However, presenters should expect questions and interruptions throughout. 
[comment[ [You should sign-up for the desired presentation date here](https://goo.gl/forms/sk0VOeKYxtfscjVy2).

In the presentation, you should:

* Motivate the paper and provide background.
* Present the high-level idea, approach, and/or insight (using examples, whenever appropriate). 
* Discuss technical details so that one can understand the key details without carefully reading it.
* Explain the difference between this paper and related work.
* Raise questions throughout the presentation to generate discussion.

### Paper Summaries
Every student is required to review the two papers assigned for each class.
One of these reviews can be brief, summarizing the main contributions of the paper and one critical assessment (e.g., how the paper could be improved, or compares to related work, or advances the state of the art).
This brief review should be about a paragraph in length. 

The second review should be up to one page long, explaining in detail the contributions and context of the paper.  This review
should address the following four questions in about a paragraph each.

* What is the problem addressed by the paper, and why is this problem important?
* What is the hypothesis of the work?
* What is the proposed solution, and what key insight guides their solution?
* What is one (or more) drawback or limitation of the proposal, and how will you improve it?

Reviews must be submitted on [Canvuas](https://umich.instructure.com/courses/707608).
[comment] The list of papers can be found at [here](https://eecs589.eecs.umich.edu/search?q=) (note that you must sign up with umich.edu email). 

**Late reviews will not be counted.** 
You should use [this template](SummaryTemplate.md) for writing your summary.
Allocate enough time for your reading, discuss as a group, write the summary carefully, and finally, include key observations from the class discussion.

You must read and review every assigned paper.

### Participation
You are expected to attend all lectures (you may skip up to 2 lectures for legitimate reasons), and more importantly, participate in class discussions.

### Project
You will complete substantive work an instructor-approved problem and have original contribution. 
Surveys are not permitted as projects; instead, each project must contain a survey of background and related work. 
You must meet the following milestones (unless otherwise specified in future announcements) to ensure a high-quality project at the end of the semester:

* Turn in a 2-page draft proposal (including references) by September 16. Remember to include the names and Michigan email addresses of the group members. 
* Keep revising your initial idea and incorporate instructor feedback. However, your team and project proposal must be finalized and approved on or before September 30.
* Each group must submit a 4-page mid-semester progress report and present mid-semester progress during class hours on the week of Nov 4.
* **Each group must prepare for 5 to 15 minutes presentation for mid-semester progress during class hours on November 4**.
* Each group must present their final results during a presentation starting on December 2.
* **Each group must turn in an 8-page final report and your code via email on or before 11:59PM EST on December 13.** The report must be submitted as a PDF file, with formatting similar to that of the papers you've read in the class. The self-contained (i.e., include ALL dependencies) code must be submitted as a zip file. Each zip file containing the code must include a README file with a step-by-step guide on how to compile and run the provided code.


#### Acknowledgement
This course syllabus is heavily influenced by prior offerings of EECS589 [EECS 589](https://github.com/forkjoseph/EECS589).
