---
layout: default 
title: Syllabus
nav_order: 2
---
# Syllabus

## Course Objectives

This course is intended to cover topics on the abstraction hierarchy 
ranging from a step above silicon to a step below languages you are likely to program.
At the end of it, you will be able to

- Read and write C and (to a lesser extent) assembly
- Understand how C become assembly and how assembly is run by a computer
- Describe how both simple and complicated data is stored in memory
- Discuss legal, ethical, and security issues related to these topics
- Use basic command-line development tools

## Logistics

### Getting Connected

Instructor: Robbie Hott
- Email: jrhott_at_virginia.edu
- Office: Rice 210
- Office Hours:
    - Wednesdays 2:30-4:30pm in Rice 210
    - Thursdays 2-3pm on Discord

For most communication, Piazza is preferred to email.
If you email, include "CSO1" at the beginning of the subject line to help us prioritize your email.

Our TAs are students too, with duties and work outside of their TAing. Please do not ask them to act as your TA except at the scheduled on-the-clock times they have listed as their office hours and lab time. They are also kind people; please don't put them in the position of having to say no or (worse) being nice to you at the expense of their own schooling.

### Course Meetings

Mondays, Wednesdays, Fridays:
- 9am @ Chem 402 (Section 101)
- 1pm @ Warner 209 (Section 102)

### Practicing and Measuring Learning

Some tasks are designed to help you learn and practice what you learned enough that the concepts solidify in your mind.
Others are designed to measure what you have learned.
The primary kinds of tasks are:

#### Lab
- Labs are primarily learning exercises and most credit is for participation, but learning only occurs if sufficient progress is made so each lab has milestones that need to be reached for full credit.
- We expect everyone to be ill, need to travel, or otherwise miss one lab, which will be excused without the need to provide documentation of your situation. To be excused for more than one lab, documentation of why each was missed is needed.  You *will* still need to check off an excused lab with a TA during office hours for credit (see below).

#### Homework
- Each homework is an **individual assignment** unless otherwise announced.
- Some homework will be programming assignments; others will be puzzles, worksheets, or other kinds of activities.

#### Weekly Quizzes
- We will have weekly quizzes, administered online.
- Your lowest quiz score is dropped.

#### Exams
- Exams will be in-class and must be taken in person.
- There will be 3 exams throughout the semester (two midterms and one final exam).

### Readings

Primary readings are write-ups posted on this website and on the schedule.  You may also search the course site using the search box above.
We may also link to external articles when appropriate.  You should complete the readings *before* coming to class that day, as we will be discussing or using that material in lecture.

If you desire a different take on the same material, the textbook *Introduction to Computer Systems: From Bits and Gate to C/C++ & Beyond* by Yale Patt and Sanjay Patel contains all of the major topics we'll cover, with a different presentation than we'll cover them.

### Coding

> "If you really want to understand something, the best way is to try and explain it to someone else. That forces you to sort it out in your own mind. And the more slow and dim-witted your pupil, the more you have to break things down into more and more simple ideas. And that’s really the essence of programming. By the time you’ve sorted out a complicated idea into little steps that even a stupid machine can deal with, you’ve certainly learned something about it yourself."
> <div class="text-right">-Douglas Adams</div>

This course will teach you the basics of x86-64 assembly and quite a bit of C.
There will be multiple assignments dealing with each.

Estimating how long it will take someone to complete a coding assignment is always difficult.
The target difficulty is 5–10 hours of focused effort each week.

### Editors

In this course, we'll primarily be using the command line interface, which you will set up and begin to get familiar with in Lab 1.  Compiling and running of code will primarily be done on the CS department servers (portal).  While we may provide instructions on how to sync files, such as with git or scp, we expect everyone to become familiar with the shell as we progress through the semester.

**You may NOT use online compilers (or editors) for this course.**  One of the learning goals of the course is to be familiar with the shell, and you will likely use SSH and the shell in future courses and later in your career.  Using an online compiler will result in a **0** on the assignment in which it was used.

## Grading

### Grading Scale

We will use the standard grading scheme for this course.

|  Grade    |  Lower Bound    |
| :-------: | :-------------: |
| A+        | 98.0            |
| A         | 93.0            |
| A-        | 90.0            |
| B+        | 87.0            |
| B         | 83.0            |
| B-        | 80.0            |
| C+        | 77.0            |
| C         | 73.0            |
| C-        | 70.0            |
| D+        | 67.0            |
| D         | 63.0            |
| D-        | 60.0            |
| F         | 0               |

### Points per Activity Type

Points are awarded per task.
Different tasks and different task types are given different weight, as outlined below.

| Task        | Weight    |
|:------------|:---------:|
| Quizzes     |   10%     |
| Assignments |   40%     |
| Lab         |   10%     |
| Midterms    | 12% each  |
| Final Exam  |   16%     |

### Late Assignments

#### Weekly Quizzes

Quiz solutions are released shortly after the quiz closes, and thus quizzes cannot be taken late.  However, since we know that life happens, your lowest quiz score is dropped.

#### Homework Assignments

> **Updated Policy:**
> It was our goal to be lenient with extensions this semester, so we
> provided a guaranteed 48-hour extension without penalty for *all*
> homework assignments.  However, there have been a large volume of
> extension requests *after* the homework deadline, leading us to need
> to change this policy.
>
> - Extension requests must be made **24 hours before** the deadline.
>   - Requests must include a valid justification for the extension request.
>       - Some examples include SDAC accommodations, severe illness, religious observations, personal or family tragedy, legal obligations, varsity athletic competitions.
>       - This is *not* an exhaustive list; please request an extension if needed.
>   - Congestion of assignments with other courses, confusion on course material, non-working code, issues submitting to the autograder, and most forseeable or planned events scheduled on or after the due date are **not** sufficient justification for an extension.
> - Extension requests made **less than 24 hours before** the deadline (or within 24 hours after the deadline) must also include a valid reason why the extension request **could not** be requested more than 24 hours before the deadline.
> - Requests must be [submitted online](https://forms.gle/XEKpnxV3tTJHodyFA).

Homework assignments may be submitted up to 48 hours late.
<!--They are given 90% credit between 0 and 24 hours late;
at 80% credit between 24 and 48 hours late.-->  No office hours assistance will be provided for an assignment *after* the due date.
If extensions beyond that time are needed, please see the professor to discuss why and if other accommodations are also needed.

#### Exams 

Exams may not be taken late (or early) without special-case permission.

#### Labs

We expect everyone to participate fully in lab and lab activities.

No early checkoff
:   We hope you will begin labs during lab time, with the guidance of TAs and help of fellow students during the initial stages of the lab. We also want to have the freedom to alter the labs before they begin and want to limit how many labs TAs have to be ready to check off at any one time. For these reasons we do not permit early lab check-off.

In-lab check-off
:   Checking off a lab (meeting the milestones) during lab time gets 100%.  We anticipate that labs can be completed within the 75-minute lab time.

In-lab unfinished work
:   If you participated in lab but didn't quite finish, you get 50% at the end of lab.
    This can be changed to 100% by checking off the completed lab (meeting the milestones) with a TA during office hours before the start of the next week's lab.

Check-off without attending
:   If you missed lab, you can get 90% by checking off with a TA during office hours after the lab ends and before the start of the next week's lab.  **You may only check-off 3 labs without attending.**

Check-off with excused absence
:   If you have an excused absence (such as quarantine or university-sponsored travel), you can get 100% by checking off with a TA during office hours after the lab ends and before the start of next week's lab (or within a week of feeling better, ending quarantine, or returning from travel).

In all cases, TAs may award lesser credit if your work is incorrect. 

TAs will prioritize helping students during the first part of lab. If for some reason you come to lab with it already completed, you'll be checked off after the TAs have helped everyone else begin to make progress.


## Professionalism

In this course, there will be a focus on working well together and learning. Students and staff are all expected to treat each other with respect. This includes, but certainly is not limited to:

- Misuse of class platforms (Discord, Piazza, YouTube comments, etc.)
- Disrespectful language or actions to course staff or other students
- Promptness for all deadlines and class meetings
- Quality work
- Not following University COVID-19 regulations or being mindful of others

Behave professionally.

Never abuse anyone, including the emotional abuse of blaming others for your mistakes.
Kindness is more important than correctness.

Let our TAs be students when they are not on the clock as TAs.

<!--Students can and will be penalized for unprofessional behavior.-->
**Consequences of Unprofessional Behavior**: Unprofessional behavior, such as misbehavior towards instructors, classmates, or TAs, or causing disctractions for other students, can be held against a student when final grades are calculated.  The penalty is up to 20% of the final course grade.

## Honesty

We always hope everyone will behave honestly.
We know we all are tempted to do what we ought not;
if you do something you regret, the sooner you tell us the sooner (and more leniently) we can correct it.

### No plagiarism (nor anything like it)

You **must** cite any and every source you consult, other than those explicitly provided by the course itself.
Talked to a friend, saw an interesting video, consulted a website, had a tutor?
Tell us!
Put it in a comment in your code or quiz.

### Write your own code

You must write your own code.
Not just type it (though you need to do that too): **compose it yourself**, as your own original work.

We ask you to program to help you learn the content covered in the programming assignment and to help you demonstrate to us your knowledge.
This is *unlike* industry, where you program to create a product.
Because it is your mind we are looking to help develop and measure, it is your mind that must do all the work.
Working with others is *not* OK.

Our TAs have been trained to provide help that does not undermine the primary purpose of helping you learn. Other people (tutors, fellow students, etc) have not. As such, you should not give help to your peers nor accept help from others besides course staff.

### Understand what you submit

Your understanding is the primary deliverable of our assignments, not the code itself.
As such, we may ask you to explain aspects of a solution you turn in,
and may dock points if it appears you simply copied someone else's ideas (or just guessed a lot of things until one worked) without understanding them.

### Do NOT share your code

You should not share any code from an individual assignment.  That means you should not push it to GitHub (or any other site), send a copy to a friend who "just needs help with the last part," turning your screen to your neighbor, coding up solutions together, etc.  We know that sometimes you have good intentions--and we've seen it before--but it may not always go the way you think, so please do NOT share your code with anyone.

### No help on quizzes or exams

It would probably go without saying if we didn't say it, but no assistance may be given or received on any supervised evaluation or online quiz unless specifically announced otherwise by the professor (or another proctor of the evaluation).

### Consequences of Dishonesty

If we believe you have acted dishonestly, including sharing or receiving code, we will communicate this fact to you and propose a penalty.
If you have information we lack, please share that with us; we may thereafter change our belief and/or proposed penalty.
Penalties may be up to and including a failing grade (F) in the course, *independent of and in addition to the operations of the Honor Code*.
- A typical first offense penalty: A zero (0) on the assignment in which the dishonesty or plagiarism occurred
- A typical second or later offense penalty: an automatic F in the course.

If the case is particularly egregious and beyond our comfort level handling in-course, we will refer the case to the University Honor System.


## COVID-19 and Illness Policies

In this course, we will diligently follow all University regulations in effect at that time.  I also respectfully ask that we follow some additional safety precautions with regard to COVID-19, since my son is very young.  (He is 2 years old!)  So to protect him and keep us a little extra safe, I will continue to wear a mask when lecturing and ask that you wear a mask as well in the classroom, too, as needed.  We will interpret wearing a mask as being considerate and caring of others, not that you're sick.

If you're not feeling well, for all our safety and health, please watch the virtual or recorded lecture--whether you might think it's actually a cold or just seasonal allergies.  We will ensure that staying home **does not** impact your grade compared to being in person, so that you can take the time you need to get better, quarantine, and/or isolate.

### COVID-19/Illness Q&A

**Q: How will you accommodate a student who needs to isolate/quarantine?**

If a student informs us that they cannot attend class in-person because they have been requested to isolate or quarantine due to possible exposure to COVID-19, we will treat you as we would any other student absent due to illness. You will have access to the recordings of the lecture as well as lecture slides. You are also encouraged to post questions on Piazza. 

**Q: What if the Professor has to isolate/quarantine (either for themselves or because of a family member)?**

If Prof. Hott has to isolate or quarantine, we may have a virtual class session, recording, or guest lecture.

**Q: Are office hours going to be in-person or online?**

We anticipate offering a mix of in-person and online office hours. Some staff may only offer online office hours. We will make this clear on the calendar found on the course webpage.

**Q: Do I have to wear a mask?**

Our class will diligently follow all University regulations in effect at that time. If masks are required during a certain period, then they are absolutely required for class. If policy has changed, then we will adjust accordingly. Failure to mask if a regulation is in effect will result in reporting to UJC and a professionalism penalty for the class.

Note that some members of the staff and class will continue to mask for the entire semester for various reasons. They also may request that you remain distant (or wear a mask as a courtesy) as well. Please be kind to each other!

## Life

Bad things happen.
People forget things and make mistakes.
Bad days coincide with due dates.
etc.

If you believe that circumstances warrant an change in deadline, a second chance, or some other accommodation in order to more accurately synchronize grade with knowledge, come talk to your professor and we'll resolve the situation as best we can.

### Special Circumstances 
It is my goal to create a learning experience that is as accessible as possible. If you anticipate any issues related to the format, materials, or requirements of this course, please meet with me outside of class so we can explore potential options. Students with disabilities may also wish to work with the Student Disability Access Center (SDAC) to discuss a range of options to removing barriers in this course, including official accommodations. We are fortunate to have an SDAC advisor, Courtney MacMasters, physically located in Engineering. You may email her at [cmacmasters@virginia.edu](mailto:cmacmasters@virginia.edu) to schedule an appointment. For general questions please visit the SDAC website: [sdac.studenthealth.virginia.edu](http://sdac.studenthealth.virginia.edu/). If you have already been approved for accommodations through SDAC, please send me your accommodation letter and meet with me so we can develop an implementation plan together.

Since we are a large course, we ask that students with special circumstances let us know as soon as possible, preferably during the **first week of class**.

### Religious Accommodations 
It is the University's long-standing policy and practice to reasonably accommodate students so that they do not experience an adverse academic consequence when sincerely held religious beliefs or observances conflict with academic requirements.

Students who wish to request academic accommodation for a religious observance should submit their request in writing to me as far in advance as possible. If you have questions or concerns about academic accommodations for religious observance or religious beliefs may contact the [University's Office for Equal Opportunity and Civil Rights](https://eocr.virginia.edu/accommodations-religious-observance)  (EOCR) at [UVAEOCR@virginia.edu](mailto:UVAEOCR@virginia.edu) or 434-924-3200.  Accommodations do not relieve you of the responsibility for completion of any part of the coursework missed as the result of a religious observance.

### Safe Environment
The University of Virginia is dedicated to providing a safe and equitable learning environment for all students. 
If you or someone you know has been affected by power-based personal violence, more information can be found on the UVA Sexual Violence website that describes reporting options and resources available -- [www.virginia.edu/sexualviolence](www.virginia.edu/sexualviolence). 

The same resources and options for individuals who experience sexual misconduct are available for discrimination, harassment, and retaliation.  [UVA prohibits discrimination and harassment](https://uvapolicy.virginia.edu/policy/HRM-009) based on age, color, disability, family medical or genetic information, gender identity or expression, marital status, military status, national or ethnic origin, political affiliation, pregnancy (including childbirth and related conditions), race, religion, sex, sexual orientation, veteran status. [UVA policy](https://uvapolicy.virginia.edu/policy/HRM-010) also prohibits retaliation for reporting such behavior. 

If you witness or are aware of someone who has experienced prohibited conduct, you are encouraged to submit a report to [Just Report It](https://justreportit.virginia.edu) (justreportit.virginia.edu) or contact [EOCR](mailto:UVAEOCR@virginia.edu), the office of Equal Opportunity and Civil Rights.

If you would prefer to disclose such conduct to a confidential resource where what you share is not reported to the University, you can turn to [Counseling & Psychological Services](https://www.studenthealth.virginia.edu/caps) (CAPS) and [Women's Center Counseling Staff and Confidential Advocates](https://womenscenter.virginia.edu/confidential-advocates) (for students of all genders). 

As your professor and as a person, know that I care about you and your well-being and stand ready to provide support and resources as we can. As a faculty member, I am a responsible employee, which means that I am required by University policy and federal law to report certain kinds of conduct that you report to me to the University's Title IX Coordinator. The Title IX Coordinator's job is to ensure that the reporting student receives the resources and support that they need, while also determining whether further action is necessary to ensure survivor safety and the safety of the University community. 

### Well-being 
If you are feeling overwhelmed, stressed, or isolated, there are many individuals here who are ready and wanting to help. The Student Health Center offers Counseling and Psychological Services (CAPS) for all UVA students. Call 434-243-5150 (or 434-972-7004 for after hours and weekend crisis assistance) to get started and schedule an appointment. If you prefer to speak anonymously and confidentially over the phone, Madison House provides a HELP Line at any hour of any day: 434-295-8255.

### Support for Your Career Development 

Engaging in your career development is an important part of your student experience. For example, presenting at a research conference, attending an interview for a job or internship, or participating in an extern/shadowing experience are not only necessary steps on your path but are also invaluable lessons in and of themselves. I wish to encourage and support you in activities related to your career development. To that end, please notify me at least one-week in advance of such an event to arrange for appropriate accommodations.


## Student Support Team 

You have many resources available to you when you experience academic or personal stresses. In addition to your professor, the School of Engineering and Applied Science offers free tutoring, and has three staff members located in Thornton Hall who you can contact to help manage academic or personal challenges. Please do not wait until the end of the semester to ask for help!

#### Learning
- Lisa Lampe, Director of Undergraduate Education (academic), ll4uu@virginia.edu
- Blake Calhoun, Director of Undergraduate Success (academic), bic4sc@virginia.edu
- Courtney MacMasters, Accessibility Specialist, cmacmasters@virginia.edu

#### Health and Wellbeing
[Assistant Dean of Students](https://engineering.virginia.edu/about/offices/office-graduate-programs/student-support-services#accordion716460), Student Safety and Support  
Elizabeth Ramirez-Weaver, CAPS counselor
Katie Fowler, CAPS counselor


You may schedule time with the CAPS counselors through Student Health ([www.studenthealth.virginia.edu/getting-started-caps](https://www.studenthealth.virginia.edu/getting-started-caps)).  When scheduling, be sure to specify that you are an Engineering student. You are also urged to use [TimelyCare](https://www.studenthealth.virginia.edu/timelycare) for either scheduled or on-demand 24/7 mental health care.   

#### Community and Identity

The [Center for Diversity in Engineering](https://engineering.virginia.edu/about/diversity-and-engagement/center-diversity-engineering) (CDE) is a student space dedicated to advocating for underrepresented groups in STEM. It exists to connect students with the academic, financial, health, and community resources they need to thrive both at UVA and in the world.  The CDE includes an open study area, event space, and staff members on site. Through this space, we affirm and empower equitable participation toward intercultural fluency and provide the resources necessary for students to be successful during their academic journey and future careers.

## Additional Notes

**Syllabus Note**: This syllabus is to be considered a reference document that may be adjusted throughout the course of the semester to address necessary changes. This syllabus can be changed at any time without notification; it is up to the student to monitor the website for news of any changes. Final authority on any decision in this course rests with the professor, not with this document.

**Research**: Your class work and related data might be used for research purposes. For example, we may use anonymized scores from student assignments to compare to other student performance data. Any student who wishes to opt out can contact the instructor or TA to do so *after* final grades have been issued. This has no impact on your grade in any manner.
