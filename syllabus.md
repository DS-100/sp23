---
layout: page
title: Syllabus
nav_order: 2
description: >-
    Principles and Techniques of Data Science
markdown: kramdown
course:
    edstem: https://edstem.org/us/courses/25695/
    faq: https://ds100.org/fa22faq
    bcourses: ""
    head_ta_1: Kanu Grover 
    head_1_email: grover.kanu@berkeley.edu
    head_ta_2: Bella Crouch
    head_2_email: isabella.crouch@berkeley.edu
    comms_ta: Samantha Wray
    comms_email: samanthawray@berkeley.edu
    email: data100.instructors@berkeley.edu
---

# Syllabus - To Be Updated
{:.no_toc}

Jump to:
* TOC
{:toc}

<br>

<a name = 'about'></a>

## About Data 100

Combining data, computation, and inferential thinking, data science is redefining how people and organizations solve challenging problems and understand their world. This intermediate level class bridges between [Data 8](http://data8.org) and upper division computer science and statistics courses as well as methods courses in other fields. In this class, we explore key areas of data science including question formulation, data collection and cleaning, visualization, statistical inference, predictive modeling, and decision making.​ Through a strong emphasis on data centric computing, quantitative critical thinking, and exploratory data analysis, this class covers key principles and techniques of data science. These include languages for transforming, querying and analyzing data; algorithms for machine learning methods including regression, classification and clustering; principles behind creating informative data visualizations; statistical concepts of measurement error and prediction; and techniques for scalable data processing.

### Goals
{:.no_toc}

- Prepare students for advanced Berkeley courses in data-management, machine learning, and statistics, by providing the necessary foundation and context.
- Enable students to start careers as data scientists by providing experience working with real-world data, tools, and techniques.
- Empower students to apply computational and inferential thinking to address real-world problems.

<a name = 'prerequisites'></a>
### Prerequisites

While we are working to make this class widely accessible, we currently require the following (or equivalent) prerequisites. **Prerequisites will be enforced in this class. It is your responsibility to know the material in the prerequisites.** The instructors do not have the authority to waive these requirements. You should fill out the [Enrollment Exception Form](https://data.berkeley.edu/academics/undergraduate-programs/courses/fall-2022-classes-enrollment-info) managed by CDSS to request an exception.

- **Foundations of Data Science**: [Data 8](http://data8.org) covers much of the material in Data 100 but at an introductory level. Data8 provides basic exposure to python programming and working with tabular data as well as visualization, statistics, and machine learning.
- **Computing**: _The Structure and Interpretation of Computer Programs_ ([CS 61A](http://cs61a.org)) or _Computational Structures in Data Science_ ([CS 88](https://cs88-website.github.io)). These courses provide additional background in python programming (e.g., for loops, lambdas, debugging, and complexity) that will enable Data 100 to focus more on the concepts in Data Science and less on the details of programming in python.
- **Math**: _Linear Algebra_ (Math 54, [EE 16A](https://eecs16a.org/), or Stat 89A): We will need some basic concepts like linear operators, eigenvectors, derivatives, and integrals to enable statistical inference and derive new prediction algorithms. <b>This may be satisfied concurrently to Data 100.</b>

<br>

## Course Culture

Students taking Data C100 come from a wide range of backgrounds. We hope to foster an inclusive and safe learning environment based on curiosity rather than competition. All members of the course community—the instructor, students, and GSIs—are expected to treat each other with courtesy and respect. Some of the responsibility for that lies with the staff, but a lot of it ultimately rests with you, the students.

### Be Aware of Your Actions

Sometimes, the little things add up to creating an unwelcoming culture to some students. For example, you and a friend may think you are sharing in a private joke about other races, majors, genders, abilities, cultures, etc. but this can have adverse effects on classmates who overhear it. There is a great deal of research on something called “stereotype threat,” which finds simply reminding someone that they belong to a particular culture or share a particular identity (on whatever dimension) can interfere with their course performance.

Stereotype threat works both ways: you can assume that a student will struggle based on who they appear to be, or you can assume that a student is doing great based on who they appear to be. Both are potentially harmful.

Bear in mind that diversity has many facets, some of which are not visible. Your classmates may have medical conditions (physical or mental), personal situations (financial, family, etc.), or interests that aren’t common to most students in the course. Another aspect of professionalism is avoiding comments that (likely unintentionally) put down colleagues for situations they cannot control. Bragging in open space that an assignment is easy or “crazy,” for example, can send subtle cues that discourage classmates who are dealing with issues that you can’t see. Please take care, so we can create a class in which all students feel supported and respected.

### Be Respectful

Beyond the slips that many of us make unintentionally are a host of behaviors that the course staff, department, and university do not tolerate. These are generally classified under the term harassment; sexual harassment is a specific form that is governed by federal laws known as Title IX.

UC Berkeley’s <a href="https://ophd.berkeley.edu/">Title IX website</a> provides many resources for understanding the terms, procedures, and policies around harassment. Make sure you are aware enough of these issues to avoid crossing a line in your interactions with other students. For example, repeatedly asking another student out on a date after they have said no can cross this line.

Your reaction to this topic might be to laugh it off, or to make or think snide remarks about “political correctness” or jokes about consent or other things. You might think people just need to grow a thicker skin or learn to take a joke. This isn’t your decision to make. Research shows the consequences (emotional as well as physical) on people who experience harassment. When your behavior forces another student to focus on something other than their education, you have crossed a line. You have no right to take someone else’s education away from them.

### Communicate Issues with Course Staff

Professionalism and respect for diversity are not just matters between students; they also apply to how the course staff treat the students. The staff of this course will treat you in a way that respects our differences. However, despite our best efforts, we might slip up, hopefully inadvertently. If you are concerned about classroom environment issues created by the staff or overall class dynamic, please feel free to talk to us about it. The instructors in particular welcome any comments or concerns regarding conduct of the course and the staff.

We are committed to creating a learning environment welcoming of all students that supports a diversity of thoughts, perspectives and experiences and respects your identities and backgrounds (including race, ethnicity, nationality, gender identity, socioeconomic class, sexual orientation, language, religion, ability, and more.) To help accomplish this:

- If your name and/or pronouns differ from those that appear in your official records, please let us know.
- If you feel like your performance in the class is being affected by your experiences outside of class (e.g., family matters, current events), please don’t hesitate to come and talk with us. We want to be resources for you.
- We (like many people) are still in the process of learning about diverse perspectives and identities. If something was said in class (by anyone) that made you feel uncomfortable, please talk to us about it.
- While the course staff understands that improving diversity, equity, and inclusion (DEI) are not enough to overcome systemic issues in academia such as racism, queerphobia, and other forms of discrimination and hatred, we also recognize the importance of DEI work.
  - The Data Science Department has some resources available at [https://data.berkeley.edu/about/diversity-equity-and-inclusion](https://data.berkeley.edu/about/diversity-equity-and-inclusion).
  - There’s also a great set of resources available at [https://eecs.berkeley.edu/resources/students/grievances](https://eecs.berkeley.edu/resources/students/grievances).
- If there are other resources you think we should list here, let us know!

**We take all complaints about unprofessional or discriminatory behavior seriously.**

## Course Components

Below is a high-level “typical week in the course” for Fall 2022.

|  Mo | Tu | We | Th | Fr |
| --- | --- | --- | --- | --- | --- |
| Office Hours | Office Hours | Office Hours | Office Hours | Office Hours | 
| | <span style="color:Green">Live Lecture</span> |  | <span style="color:Green">Live Lecture</span> | |
| | <span style="color:Blue">Discussion Section</span>| <span style="color:Blue">Discussion Section</span>| | | 
| | | |<span style="color:Red">**Homework N-1 due**</span> | <span style="color:Red">Homework N released</span> | 
| |<span style="color:Red">**Lab N-1 due**</span>| | | <span style="color:Red">Lab N released</span>|

* **All deadlines are subject to change.**
* Office Hours are scheduled on the [Calendar page](../calendar). 
* Lectures, discussions, assignments, projects, and exams are scheduled on the [Home page](../).

<br>

### Lecture
There are 2 live lectures per week. Lectures will be in Wheeler 150 and broadcasted live on Zoom. All lecture recordings will also be published within 24 hours of the live recording.

### Discussion
Live discussion sections are on Tuesdays and Wednesdays, lasting for one hour. The goal of these sessions is to work through problems, hone your skills, and flesh out your understanding as part of a team. The problems that you solve and present as part of discussion are important in understanding this material. 
- You need to be assigned to a discussion section. Sign-ups will be posted on Ed.
- Discussion attendance is mandatory for students enrolled in Data 100. Discussion attendance is not mandatory for students enrolled in Data 200.
- Each discussion will be graded on a 0/1 basis. As of now, that one point will be based on attendance to only the section you signed up for at the beginning of the semester. Please attend the discussion section you signed up for on Sign Up Genius. For the first three weeks, you will be able to attend any online section and receive credit. We are working to allow for more section availability in the coming days.

### Homework and Projects

Homeworks are half-week-long assignments that are designed to help students develop an in-depth understanding of both the theoretical and practical aspects of ideas presented in lecture.

Projects: Projects are week-long assignments that synthesize multiple topics.

- Homeworks and projects have both visible and hidden autograder tests. The visible tests are mainly sanity checks. For example, a sanity check might verify that the answer you entered is a number as expected, and not a word. The hidden tests generally check for correctness, and are invisible to students while they are doing the assignment.
- The primary form of support students will have for homeworks and projects are the **office hours** we’ll host, and **Ed**.
- Homeworks and projects must be completed individually. See the [Collaboration Policy](#collaboration-policy-and-academic-dishonesty) for more details.

### Lab

Labs are shorter programming assignments designed to give students familiarity with new ideas.
- All lab autograder tests are visible.
- We will not be having Lab sections this semester. Rather, we'll provide extensive lab support on Ed and an accompanying video-walkthorugh.
- All labs are intended to take about an hour. 


### Office Hours and Communication

The office hours and locations (mainly in [Warren 101](https://dac.berkeley.edu/warren-hall-2195-hearst-ave)) are listed on the [Calendar](../calendar); office hours will mainly be held in-person, with some virtual options available. Instructor office hours are also listed on the calendar.

In general, students can come to office hours for any questions on course assignments or material. We will also have Homework/Project parties Wednesday 5-8 PM (Warren Hall 101B), where you can come work with your peers and ask questions.

Office hour queues are managed through [oh.ds100.org](https://oh.ds100.org/), where students add themselves to the “queue” and specify the assignment they need help on.

**EdStem**, or **Ed** for short, is our course forum this summer. The course is [here]({{page.course.edstem}}). Please check out EdStem or the [FAQ]({{page.course.faq}}) page first before emailing instructors. 

**Staff email**:
You can email [{{page.course.email}}](mailto:{{page.course.email}}) and one of the TAs will get back to you. Note that to ensure more timely responses, this address is monitored by a team of two instructors (Lisa and Narges), Head TA's (Kanu Grover and Bella Crouch), as well as several lead GSIs, to ensure more timely responses. 

For sensitive matters, you should directly contact the Head TA's [{{page.course.head_ta_1}}](mailto:{{page.course.head_1_email}}) and [{{page.course.head_ta_2}}](mailto:{{page.course.head_2_email}}). You should only contact Lisa and Narges directly for matters that require strict privacy and their direct attention.


### Exams

There will be two exams in this course:
* Midterm on **Thursday, March 9** 7-9PM PT.
* Final on **Thursday, May 11** 8-11AM PT.

Alternate exam policies:
- **Midterm**: We will not offer alternate exams except for students with DSP, student atheletes.
- **Final**: We will not offer alternate exams except for students with DSP, student atheletes.

<!--
Two time options will be offered to cover various timezones. No further alternates will be offered.
-->

### Graduate Final Project
All students enrolled in the graduate version of the course (CS C200 or Stat C200C, i.e. Data 200) will be graded according to the Graduate grading scheme, which includes a graduate final project. More details to follow.



## Policies

### Grading Scheme

| Category | Data 100 | Data 200 | Details |
| --- | --- | --- | --- |
| Homeworks | 25% | 25%| No drop|
| Projects | 15% | 15%| No drop|
| Labs | 10% |  - | No drop|
| Discussion | 5% | - | Drop 3 lowest scores|
| Lecture Participation | 5% | 5% | Drop 3 lowest scores|
| Midterm Exam | 15% | 15%| |
| Final Exam | 25% | 25% | |
|Graduate Final Project| - | 15% | |

**Note**: Unlike previous semesters, we will not offer assignment drops, instead, we will offer a 2-day grace period submission for Homeworks, Projects, and Labs. If submissions were made on-time students will receive a 3% bonus. See the next section for more details.
<br>


### Late Policy

All assignments are due at 11:59 PM Pacific Time on the due date specified on the syllabus. 

#### Grace Period

You have a **two-day** grace period to submit your assignment after the main deadline. To use grace day on an assignment, you can submit your assignment any time during the next two days following the main deadline. If you are in the Disabled Students' Program and are offered an extension, your grace period is added to your standard accommodation. Please note that your extension, plus the grace period combined, can be at most **7 days**.


- **Extension beyond grace period**: You must use your grace days first before you can request any extension. At that point, we will require supporting documentation and extensions will only be granted for exceptional situations (doctor-documented illness, major family emergency, etc.)


**Extensions** are provided to students with DSP accommodations, or in the case of exceptional circumstances. If you have DSP accommodations, you should expect to receive an email from us. Otherwise, email our Communications TA [{{page.course.comms_ta}}](mailto: {{page.course.comms_email}}) to request an extension. If you make a request close to the deadline, we can not guarantee that you will receive a response before the deadline. Additionally, simply submitting a request does not guarantee you will receive an extension. Even if your work is incomplete, please submit before the deadline so you can receive credit for the work you did complete.

<!--
{{page.course.comms_ta}} at [{{page.course.comms_email}}]({{page.course.comms_email}}) 
-->

Note that extension requests will *not* be granted in cases where a student’s local (DataHub) tests are not passing. It is the student’s responsibility to solve such problems in advance of the deadline.

### Regrade Requests

Students will be allowed to submit regrade requests for the autograded and written portions of assignments in cases in which the rubric was incorrectly applied or the autograder scored their submission incorrectly. Regrades for the written portions of assignments will be handled through Gradescope, and autograder regrades via a Google Form. The deadline for regrade requests (autograded and written) is one week after grades are released for the corresponding assignment.

**Always check that the autograder executes correctly!** Gradescope will show you the output of the public tests, and you should see the same results as you did on DataHub. If you see a discrepancy, ensure that you have exported the assignment correctly and, if there is still an issue, post on EdStem _as soon as possible_.

Regrade requests will **not** be considered in cases in which:

- a student uploads the incorrect file to the autograder.
- the autograder fails to execute and the student does not notify the course staff _before the assignment deadline_.
- a student fails to save their notebook before exporting and uploads an old version to the autograder.
- a situation arises in which the course staff cannot ensure that the student's work was done before the assignment deadline.
<!--- a students submits without following the steps outlined in [@13](https://piazza.com/class/kqsiwfz12g0482?cid=13)-->

### Collaboration Policy and Academic Dishonesty

We will be following the [EECS departmental policy on Academic Honesty](https://eecs.berkeley.edu/resources/students/academic-dishonesty), which states that using work or resources that are not your own or not permitted by the course may lead to disciplinary actions, up to and including a failing grade in the course.

**Assignments.**
Data science is a collaborative activity. While you may talk with others about the homework and projects, we ask that you write your solutions individually in your own words. If you do discuss the assignments with others please include their names at the top of your notebook. Keep in mind that content from assignments will likely be covered on both the midterm and final.

If we suspect that you have submitted plagiarized work, we will call you in for a meeting. If we then determine that plagiarism has occurred, we reserve the right to give you a negative full score (-100%) or lower on the assignments in question, along with reporting your offense to the Center of Student Conduct.

Rather than copying someone else's work, ask for help. You are not alone in this course! The entire staff is here to help you succeed. If you invest the time to learn the material and complete the assignments, you won't need to copy any answers. (taken from [CS61A](https://cs61a.org/articles/about/#academic-honesty))

We also ask that you **do not post your assignment solutions publicly**.

**Exams.**
Cheating on exams is a serious offense. We have methods of detecting cheating on exams – so don't do it! Students caught cheating on any exam will fail this course.

## We want you to succeed!

If you are feeling overwhelmed, visit our office hours and talk with us. We know college can be stressful – and especially so during the COVID-19 pandemic – and we want to help you succeed.

**Important Note**: We are committed to being a resource to you, but it is important to note that all members of the teaching staff for this course are [responsible employees](https://svsh.berkeley.edu/responsible-employee), meaning that **we must disclose any incidents of sexual harassment or violence to campus authorities**. If you would like to speak to a confidential advocate, please consider reaching out to the [Berkeley PATH to Care Center](https://care.berkeley.edu/).

## Acknowledgments!
{:.no_toc}

Course Culture and Additional Resources inspired and adapted with permission from Dr. Sarah Chasins' [Fall 2021 CS 164 Syllabus](https://inst.eecs.berkeley.edu/~cs164/fa21/syllabus.html) and Grace O'Connell, the Asssociate Dean for Inclusive Excellence.