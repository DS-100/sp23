---
layout: page
title: Syllabus
nav_order: 2
description: >-
    Principles and Techniques of Data Science
markdown: kramdown
course:
    semester: Spring 2023
    edstem: https://edstem.org/us/courses/33744/
    faq: https://ds100.org/sp23faq
    bcourses: ""
    instructors: Lisa and Narges
    head_ta_1: Kanu Grover 
    head_1_email: grover.kanu@berkeley.edu
    head_ta_2: Bella Crouch
    head_2_email: isabella.crouch@berkeley.edu
    comms_ta: support email
    comms_email: data100.support@berkeley.edu
    email: data100.instructors@berkeley.edu
---

# Syllabus
{:.no_toc}

<p>
<a href="https://www.youtube.com/watch?v=wiP7Tvc2jZs" class="btn btn-blue" target="_blank">Syllabus Walkthrough</a>
</p>

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

While we are working to make this class widely accessible, we currently require the following (or equivalent) prerequisites. **Prerequisites will be enforced in Data 100. It is your responsibility to know the material in the prerequisites.** The instructors do not have the authority to waive these requirements. Undergraduates should fill out the [Enrollment Exception Form](https://data.berkeley.edu/academics/undergraduate-programs/courses/fall-2022-classes-enrollment-info) managed by CDSS to request an exception.

- **Foundations of Data Science**: [Data 8](http://data8.org) covers much of the material in Data 100 but at an introductory level. Data8 provides basic exposure to python programming and working with tabular data as well as visualization, statistics, and machine learning.
- **Computing**: _The Structure and Interpretation of Computer Programs_ ([CS 61A](http://cs61a.org)) or _Computational Structures in Data Science_ ([CS 88](https://cs88-website.github.io)). These courses provide additional background in python programming (e.g., for loops, lambdas, debugging, and complexity) that will enable Data 100 to focus more on the concepts in Data Science and less on the details of programming in python.
- **Math**: _Linear Algebra_ (Math 54, [EE 16A](https://eecs16a.org/), or Stat 89A): We will need some basic concepts like linear operators, eigenvectors, derivatives, and integrals to enable statistical inference and derive new prediction algorithms. <b>This may be satisfied concurrently to Data 100.</b>

Please consult the [Resources](../resources) page for additional resources for reviewing prerequisite material.

**Textbook**: There is no official textbook for Data 100 this semester; in its stead, we will provide course notes that will be released with the respective lectures.

<br>

## Course Culture

Students taking Data C100 come from a wide range of backgrounds. We hope to foster an inclusive and safe learning environment based on curiosity rather than competition. All members of the course community—the instructor, students, and GSIs—are expected to treat each other with courtesy and respect. Some of the responsibility for that lies with the staff, but a lot of it ultimately rests with you, the students.

### Be Aware of Your Actions

Sometimes, the little things add up to creating an unwelcoming culture to some students. For example, you and a friend may think you are sharing in a private joke about other races, majors, genders, abilities, cultures, etc. but this can have adverse effects on classmates who overhear it. There is a great deal of research on something called “stereotype threat": research finds that simply reminding someone that they belong to a particular culture or share a particular identity (on whatever dimension) can interfere with their course performance.

Stereotype threat works both ways: you can assume that a student will struggle based on who they appear to be, or you can assume that a student is doing great based on who they appear to be. Both are potentially harmful.

Bear in mind that diversity has many facets, some of which are not visible. Your classmates may have medical conditions (physical or mental), personal situations (financial, family, etc.), or interests that aren’t common to most students in the course. Another aspect of professionalism is avoiding comments that (likely unintentionally) put down colleagues for situations they cannot control. Bragging in open space that an assignment is easy or “crazy,” for example, can send subtle cues that discourage classmates who are dealing with issues that you can’t see. Please take care, so we can create a class in which all students feel supported and respected.

### Be Respectful

Beyond the slips that many of us make unintentionally are a host of behaviors that the course staff, department, and university do not tolerate. These are generally classified under the term harassment; sexual harassment is a specific form that is governed by federal laws known as Title IX.

UC Berkeley’s <a href="https://ophd.berkeley.edu/">Title IX website</a> provides many resources for understanding the terms, procedures, and policies around harassment. Make sure you are aware enough of these issues to avoid crossing a line in your interactions with other students. For example, repeatedly asking another student out on a date after they have said no can cross this line.

Your reaction to this topic might be to laugh it off, or to make or think snide remarks about “political correctness” or jokes about consent or other things. You might think people just need to grow a thicker skin or learn to take a joke. This isn’t your decision to make. Research shows the consequences (emotional as well as physical) on people who experience harassment. When your behavior forces another student to focus on something other than their education, you have crossed a line. You have no right to take someone else’s education away from them.

### Communicate Issues with Course Staff and/or the Department

**We take all complaints about unprofessional or discriminatory behavior seriously.**
Professionalism and respect for diversity are not just matters between students; they also apply to how the course staff treat the students. The staff of this course will treat you in a way that respects our differences. However, despite our best efforts, we might slip up, hopefully inadvertently. If you are concerned about classroom environment issues created by the staff or overall class dynamic, please feel free to talk to us about it. The instructors in particular welcome any comments or concerns regarding conduct of the course and the staff. See [below](#office-hours-and-communication) for how to best reach us.

*From the Data Science Department*: [Data Science Undergraduate Studies](https://data.berkeley.edu/academics/undergraduate-programs) faculty and staff are committed to creating a community where every person feels [respected, included, and supported](https://data.berkeley.edu/equity-inclusion). We recognize that incidents may happen, sometimes unintentionally, that run counter to this goal. There are many things we can do to try to improve the climate for students, but we need to understand where the challenges lie. If you experience a remark, or disrespectful treatment, or if you feel you are being ignored, excluded or marginalized in a course or program-related activity, please speak up. Consider talking to your instructor, but you are also welcome to contact Executive Director Christina Teller at [cpteller@berkeley.edu](mailto: cpteller@berkeley.edu) or report an incident anonymously through this [online form](https://docs.google.com/forms/d/e/1FAIpQLSfBwaUe7VMQz6VzkYFvf4KYwNSTve9iJlBSQyAmsXoSE0LnWw/viewform).

As course staff, we are committed to creating a learning environment welcoming of all students that supports a diversity of thoughts, perspectives and experiences and respects your identities and backgrounds (including race, ethnicity, nationality, gender identity, socioeconomic class, sexual orientation, language, religion, ability, and more.) To help accomplish this:

- If your name and/or pronouns differ from those that appear in your official records, please let us know.
- If you feel like your performance in the class is being affected by your experiences outside of class (e.g., family matters, current events), please don’t hesitate to come and talk with us. We want to be resources for you.
- We (like many people) are still in the process of learning about diverse perspectives and identities. If something was said in class (by anyone) that made you feel uncomfortable, please talk to us about it.
- While the course staff understands that improving diversity, equity, and inclusion (DEI) are not enough to overcome systemic issues in academia such as racism, queerphobia, and other forms of discrimination and hatred, we also recognize the importance of DEI work.
  - The Data Science Department has some resources available at [https://data.berkeley.edu/about/diversity-equity-and-inclusion](https://data.berkeley.edu/about/diversity-equity-and-inclusion).
  - There’s also a great set of resources available at [https://eecs.berkeley.edu/resources/students/grievances](https://eecs.berkeley.edu/resources/students/grievances).
- If there are other resources you think we should list here, let us know!

## Course Components

Below is a high-level “typical week in the course” for {{page.course.semester}}.

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
There are 2 live **lectures** held on Tuesdays and Thursdays, 11:00am-12:30pm, hybrid: in-person in Wheeler 150 and broadcasted live on Zoom. All session recordings, slides, activities, and examples will be provided to the course website within 24 hours of the lecture. 

**Lecture participation**: While synchronous lecture attendance (in-person or through Zoom) is not mandatory, we expect you to "participate" in lecture by answering lecture poll questions in one of two ways: (1) synchronously during the lecture as poll questions are launched; or (2) asynchronously using a link provided after lecture.
- Lecture participation is graded using poll responses on a 0/1 basis.
  - Synchronous Participation: complete at least one participation poll question during the live lecture timeslot (11-12:30, Tuesdays and Thursdays). As long as you submit a response to at least one poll question in this timeframe, you will receive synchronous attendance credit.
  - Asynchronous Participation: complete all participation poll questions from the link provided on the course website within one week of the corresponding lecture.
  - In both cases, participation is graded on completion, not correctness.
- If you submit all participation polls over the course of the semester (i.e., do not use any of the three automatic drops), you will receive +0.5% bonus points applied to your final overall grade in the class.
- See the [Policies](#policies) section for lecture participation drops.

### Discussion
Live **discussion sections** are one hour long, held on Tuesdays or Wednesdays. The goal of these GSI-led sessions is to work through problems, hone your skills, and flesh out your understanding as part of a team. The problems that you solve and present as part of discussion are important in understanding course material. 
- Discussion attendance is mandatory for students enrolled in Data 100. Discussion attendance is not mandatory for students enrolled in Data 200.
- Each weekly discussion will be graded on a 0/1 basis. You will only get credit for attending the discussion section that you are signed up for.
- Discussion sections start in the second week of class.
- You will need to be assigned to a discussion section. Discussion times and your sign-up preferences will be collected in a Welcome Form distributed in the first week of class, and section assignments will occur over the weekend. Discussion switches will then be available on a first-come, first-serve basis.
- Online sections are reserved for students with specific needs, e.g., DSP, Data 200S, etc.; these can be requested through the Welcome Form.
- See the [Policies](#policies) section for discussion drops. There are no discussion make-ups.

### Homework and Projects

**Homeworks** are week-long assignments that are designed to help students develop an in-depth understanding of both the theoretical and practical aspects of ideas presented in lecture. **Projects** are 2-week assignments (with a weekly checkpoint) that synthesize multiple topics.

- All homeworks and projects must be submitted to Gradescope by their posted deadlines. There may be separate coding and written Gradescope portals for the same assignment; please check that you are submitting the right part.
- Homeworks and projects have both visible and hidden autograder tests. The visible tests are mainly sanity checks. For example, a sanity check might verify that the answer you entered is a number as expected, and not a word. The hidden tests generally check for correctness, and are invisible to students while they are doing the assignment.
- The primary form of support students will have for homeworks and projects are **office hours** and **Ed**.
- Homeworks and projects must be completed individually. See the [Collaboration Policy](#collaboration-policy-and-academic-dishonesty) for more details.
- See the [Policies](#policies) section for the submission grace period.

### Lab

**Labs** are shorter, weekly programming assignments designed to give students familiarity with new ideas. They are meant to be completed prior to homework.
- All lab assignments must be submitted to Gradescope by their posted deadlines.
- All lab autograder tests are visible.
- We will not be having Lab sections this semester. Rather, we'll provide extensive lab support on Ed and an accompanying video walkthroughs. For Data 200S students, please contact us.
- All labs are intended to take about an hour.
- Lab submissions are mandatory for students enrolled in Data 100. Lab submissions are not mandatory for students enrolled in Data 200. See the [Policies](#policies) section for the submission grace period.

### Exams

There will be two exams in this course:
* **Midterm** on **Thursday, March 9** 7-9PM PT.
* **Final** on **Thursday, May 11** 8-11AM PT.

All exams are in-person (not online) for Data 100 and Data 200 and are subject to standard proctoring procedures. Data 200S students will receive separate instructions for exam scheduling.
- **Midterm alternate exam**: In addition to offering alternate exams for students with DSP or student athletics accommodations, we will offer one alternate exam slot for the midterm exam, time TBD (but likely same day). All alternate exam requests must be pre-approved.
- **No Final alternate exam**: We will not offer alternate exams for the final exam except for students with DSP or student athletics accommodations.
<!-- - We will not offer alternate midterm nor final exams except for students with appropriate accommodations, such as DSP and student athletics.
-->

### Graduate Final Project
All students enrolled in the graduate version of the course (CS C200A or Stat C200C, i.e. Data 200; Data 200S) will be graded according to the Graduate grading scheme, which includes a team-based **Graduate Final Project** distributed in the second half of the semester. More details to be released soon.

## Office Hours and Communication

We want to enable everyone to succeed in this course. We encourage you to discuss course content with your friends, classmates, and course staff throughout the semester, particularly during **office hours**. 
- All office hours are listed on the [Calendar](../calendar).
- Almost all office hours will be held in [Warren Hall 101B](https://dac.berkeley.edu/warren-hall-2195-hearst-ave)). A small, limited portion of office hours are listed as online, primarily to accommodate online/remote students (e.g., Data 200S). 
- In general, students can come to office hours for any questions on course assignments or material.
- We manage office hours through an **Office Hour Queue** on [oh.ds100.org](https://oh.ds100.org/). Students attending non-instructor OH should add themselves to the “queue” and specify the assignment they need help on.
- We will also hold **Homework/Project parties** on Wednesday evenings (Warren Hall 101B), where you can come work with your peers and ask questions.
- Instructor office hours are generally reserved for conceptual questions, course review, or course logistics.

Course Communication:

- **EdStem**, or **Ed** for short, is our course forum this semester. The course is [here]({{page.course.edstem}}). <i>**All course announcements will be through Ed.**</i> We are not using bCourses this semester. Please check out EdStem or the [FAQ]({{page.course.faq}}) page first before emailing course staff directly.
  - Ed is a formal, academic space. We must demonstrate appropriate respect, consideration, and compassion for others. Please be friendly and thoughtful; our community draws from a wide spectrum of valuable experiences. For further reading, please reference [Berkeley’s Principles of Community](https://diversity.berkeley.edu/principles-community) and the [Berkeley Campus Code of Student Conduct](https://sa.berkeley.edu/sites/default/files/Code%20of%20Conduct_January%202016.pdf).

- **Staff email**:
Our course staff email is [{{page.course.email}}](mailto:{{page.course.email}}). Note that to ensure more timely responses, this address is monitored by a team of instructors ({{page.course.instructors}}), Head TAs (Kanu Grover and Bella Crouch), as well as several lead GSIs, to ensure more timely responses. 

- **Extenuating Circumstances Form, Head TA emails, and Instructor emails**: For sensitive matters, you should fill out the [Extenuating Circumstances Form](#extenuating-circumstances) or directly contact the Head TAs [{{page.course.head_ta_1}}](mailto:{{page.course.head_1_email}}) and [{{page.course.head_ta_2}}](mailto:{{page.course.head_2_email}}). You should only contact {{page.course.instructors}} directly for matters that require strict privacy and their direct attention.

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
| Graduate Final Project| - | 15% | |

Data 200S students will receive separate communication about course grading in the first week of class.

**Note**: Unlike previous semesters, in Spring 2023 we are only offering drops for lecture participation and discussion. We will not offer drops for any other assignments. Instead, for homeworks, projects, and labs we will offer a grace period for some types of assignments, as well as an Extenuating Circumstances Form. See the next sections for more details.
<br>


### On-Time Submission

All assignments are due at <i>**11:59 PM Pacific Time**</i> on the due date specified on the [Home / Schedule](../) page. The date and time of this deadline are firm. Submitting even a minute past is considered late.

<i>**Submitting by this "on-time" deadline earns an extra-credit on-time bonus, typically a ~3% perk.**</i> This is available for homeworks, projects, and labs. Graduate Final Project on-time grading policies are [here](../gradproject/#late-policy).

### Grace Period

If you miss the deadline for homeworks, projects, and labs, we will offer a 2-day (48-hour) **grace period** for late submissions. You can make a late submission after the on-time deadline and up to the end of the grace period. <i>**These late submissions are not penalized, but do not earn the on-time bonus.**</i> You do not need to explicitly contact staff about late submissions; just submit directly to Gradescope within the listed grace period.

<u><i>**Submissions are not accepted beyond the grace period. The grace period is strictly enforced.**</i></u> We recommend thinking of the grace period as a backup, in case something unexpected comes up when aiming for the on-time deadline. As a result, getting an extension beyond the grace period will generally not be granted, except in emergencies (see the [Extenuating Circumstances](#extenuating-circumstances) section). 

All official communication will refer to the on-time deadline as the expected dates that you will submit assignments. Graduate Final Project grace period policies are forthcoming and will be announced soon.

### Extenuating Circumstances

We recognize that our students come from varied backgrounds and have widely-varying experiences. If you encounter extenuating circumstances at anytime in the semester, please do not hesitate to let us know. The sooner we are made aware, the more options we have available to us to help you. 

The [**Extenuating Circumstances Form**](https://docs.google.com/forms/d/e/1FAIpQLSf39rTqkAmLRDg9n0uf-1DD7UfhkBDrWR2wNzgYo9avIyCK8w/viewform?usp=sf_link){:target="_blank"} is for any circumstances that cannot be resolved via the grace period policy above. Within two business days of filling out the form, a course staff will reach out to you and provide a space for conversation, as well as to arrange course/grading accommodations as necessary. For more information, please email our [{{page.course.comms_ta}}](mailto: {{page.course.comms_email}}).

We recognize that at times, it can be difficult to manage your course performance---particularly in such a huge course, and particularly at Berkeley's high standards.
Sometimes emergencies just come up (personal health emergency, family emergency, etc.).
For those of you in Data 100, this could be your first upper-division course. For those of you in Data 200, this could be your first time simultaneously exploring computing, statistics, and data.
<i>**Our Grace Period Policy combined with the Extenuating Circumstances Form is meant to lower the barrier to reaching out to us, as well as build your independence in managing your academic career long-term.**</i> So please do not hesitate to reach out.

\[Update Monday 02/13\] Note that extenuating circumstances do not extend to logistical oversight, such as Datahub/Gradescope tests not passing, submitting only one portion of the homework, forgetting to save your notebook before exporting, submitting to the wrong assignment portal, or not properly tagging pages on Gradescope.
**It is the student’s responsibility to identify and resolve these issues in advance of the on-time deadline.**
We will not grant accommodations for these cases; instead, please use the grace period to cushion these submission errors. 

### DSP Accommodations

If you are registered with the Disabled Students' Program (DSP) and have accommodations, you should expect to receive an email from us. Otherwise, email our [{{page.course.comms_ta}}](mailto: {{page.course.comms_email}}). DSP students who receive approved assignment accommodations will have the 2-day grace period added to the approved extension to the on-time deadline. Please note that any extension, plus the grace period combined, cannot exceed **7 days**.

You are responsible for reasonable communication with course staff. If you make a request close to the deadline, we can not guarantee that you will receive a response before the deadline. Additionally, simply submitting a request does not guarantee you will receive an extension. Even if your work is incomplete, please submit before the deadline so you can receive credit for the work you did complete.

### Regrade Requests

Students will be allowed to submit regrade requests for the autograded and written portions of assignments in cases in which the rubric was incorrectly applied or the autograder scored their submission incorrectly. Regrades for the written portions of assignments will be handled through Gradescope, and autograder regrades via a Google Form. The deadline for regrade requests (autograded and written) is one week after grades are released for the corresponding assignment.

**Always check that the autograder executes correctly!** Gradescope will show you the output of the public tests, and you should see the same results as you did on DataHub. If you see a discrepancy, ensure that you have exported the assignment correctly and, if there is still an issue, post on EdStem _as soon as possible_.

Regrade requests will **not** be considered in cases in which:

- a student uploads the incorrect file to the autograder.
- the autograder fails to execute and the student does not notify the course staff _before the assignment deadline_.
- a student fails to save their notebook before exporting and uploads an old version to the autograder.
- a situation arises in which the course staff cannot ensure that the student's work was done before the assignment deadline.
<!--- a students submits without following the steps outlined in [@13](https://piazza.com/class/kqsiwfz12g0482?cid=13)-->

### Collaboration Policy and Academic Honesty

We will be following the [EECS departmental policy on Academic Honesty](https://eecs.berkeley.edu/resources/students/academic-dishonesty), which states that using work or resources that are not your own or not permitted by the course may lead to disciplinary actions, including a failing grade in the course.

**Assignments.**
Data science is a collaborative activity. While you may talk with others about the homework and projects, we ask that you write your solutions individually in your own words. **If you do discuss the assignments with others please include their names at the top of your notebook.** Restated, you and your friends are encouraged to discuss course content and approaches to problem-solving, but you are not allowed to share your code nor answers with other students, nor are you allowed to post your assignment solutions publicly. Doing so is considered academic misconduct. We will be running advanced plagiarism detection programs on all assignments.

**Exams.**
Cheating on exams is a serious offense. We have methods of detecting cheating on exams – so don't do it! Students caught cheating on any exam will fail this course.

<br/>
Plagiarism on any assignment, as well as other violations to Berkeley's [Code of Conduct](https://sa.berkeley.edu/code-of-conduct), will be reported to the Center for Student Conduct. The CSC treats most first-time offenses as a [Non-Reportable Warning](https://sa.berkeley.edu/student-code-of-conduct-section6). Additionally we reserve the right to give you a negative full score (-100%) or lower on the assignments in question, an F in the course, or even dismissal from the university. It's just not worth it!

Rather than copying someone else's work, ask for help. You are not alone in Data 100! The entire staff is here to help you succeed. We expect that you will work with integrity and with respect for other members of the class, just as the course staff will work with integrity and with respect for you.

Finally, know that it’s normal to struggle. Berkeley has high standards, which is one of the reasons its degrees are valued. Everyone struggles, even though many try not to show it. Even if you don’t learn everything that’s being covered, you’ll be able to build on what you do learn, whereas if you cheat you’ll have nothing to build on. You aren’t expected to be perfect; it’s ok not to get an A.

## Academic and Wellness Resources

Our [Resources](../resources) page lists not only course-specific academic resources such as course notes, past exams, study guides, and prerequisite review links, but also campus wellness resources on COVID-19, academic support, technology support, mental well-being, DSP accommodations, dispute resolution, social services, campus community, nad basic needs. Our staff will also refer to this page when supporting you through this course.

## We want you to succeed!

If you are feeling overwhelmed, visit our office hours and talk with us, or fill out the Extenuating Circumstances Form. We know college and graduate school can be stressful – especially so during the COVID-19 pandemic – and we want to help you succeed.

**Important Note**: We are committed to being a resource to you, but it is important to note that all members of the teaching staff for this course are [responsible employees](https://svsh.berkeley.edu/responsible-employee), meaning that **we must disclose any incidents of sexual harassment or violence to campus authorities**. If you would like to speak to a confidential advocate, please consider reaching out to the [Berkeley PATH to Care Center](https://care.berkeley.edu/).

Finally, the main goal of this course is that you should learn, and have a fantastic experience doing so. Please keep that goal in mind throughout the semester. Welcome to Data 100!

## Acknowledgments
{:.no_toc}

Academic Honesty policy and closing words adapted from [Data 8](https://data8.org). Course Culture inspired and adapted with permission from Dr. Sarah Chasins' [Fall 2021 CS 164 Syllabus](https://inst.eecs.berkeley.edu/~cs164/fa21/syllabus.html) and Grace O'Connell, the Asssociate Dean for Inclusive Excellence.
