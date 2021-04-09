---
title: Human-Computer Interaction
permalink: /syllabus/
---
# Human-Computer Interaction

<dl class="dl-horizontal">
  <dt>Instructor</dt>
  <dd>
    <p><a href="{{ site.instructor_homepage }}">{{ site.instructor }}</a></p>
  </dd>

  <dt>Meeting Times</dt>
  <dd>
    <ul class="list-unstyled">
      {% for item in site.meeting_times %}
        <li>{{ item | markdownify | remove: "<p>" | remove: "</p>" }}</li>
      {% endfor %}
    </ul>
  </dd>

  <dt>Office Hours</dt>
  <dd>
    <ul class="list-unstyled">
      {% for item in site.office_hours %}
        <li>{{ item | markdownify | remove: "<p>" | remove: "</p>" }}</li>
      {% endfor %}
    </ul>
  </dd>

  {% if site.review_sessions %}
    <dt>Review Sessions</dt>
    <dd>
      <ul class="list-unstyled">
        {% for session in site.review_sessions %}
          <li>{{ session }}</li>
        {% endfor %}
      </ul>
    </dd>
  {% endif %}

  {% if site.textbook %}
    <dt>Textbook</dt>
    <dd>
      {{ site.textbook | markdownify | remove: "<p>" | remove: "</p>" }}
    </dd>
  {% endif %}

  {% if site.mentors %}
    <dt>Class Mentors</dt>
    <dd>
      <ul class="list-unstyled">
        {% for mentor in site.mentors %}
          <li>{{ mentor }}</li>
        {% endfor %}
      </ul>
    </dd>
  {% endif %}

  {% if site.mentor_sessions %}
    <dt>Mentor Sessions</dt>
    <dd>
      <ul class="list-unstyled">
        {% for session in site.mentor_sessions %}
          <li>{{ session | markdownify | remove: "<p>" | remove: "</p>" }}</li>
        {% endfor %}
      </ul>
    </dd>
  {% endif %}

  {% if site.tutors %}
    <dt>CS Tutors</dt>
    <dd>
      <ul class="list-unstyled">
        {% for tutor in site.tutors %}
          <li>{{ tutor }}</li>
        {% endfor %}
      </ul>
    </dd>
  {% endif %}
</dl>

## About this course

Welcome to CSC/PSY/TEC-262-01, a two-credit course in human-computer interaction.  Grinnell's College Catalog describes this course as follows.

> Introduction to fundamental principles and methods of human-centered
interaction design: Human capabilities and limitations, usability and
accessibility guidelines, iterative design, contextual inquiry, task
analysis, prototyping, evaluation. Includes hands-on laboratory work.

In this course, we will consider a few fundamental questions:

* How do people interact with computers and computer-based systems?
* How should people interact with computers and computer-based systems?
* How can we design computer systems that help people accomplish tasks?

By the end of the course, you should be able to

* Discuss principles of interaction design (and, perhaps, some of their
  basis in cognitive psychology);
* Recognize when principles of good design have been violated and propose
  alternate designs;
* Describe the iterative practice of interaction design, including cycles
  of observation, ideation, prototyping, and evaluation;
* Apply some informal methods to support this process, such as paper
  prototyping and "discount usability testing".

We hope this will make you both a more informed designer of software (if you
happen to be someone who designs software) and consumer or user of software.
We also hope that you will more frequently include considerations of
accessibility in your work and your choices.

## Time and workload

Grinnell has indicated that a 2-credit course, like this one, should involve approximately 90 hours of work, which matches some guidance from the U.S. government.
Across a 7-week term (plus a half week for finals), that ends up being approximately 12 hours of work per week.
That makes me worry about those taking ten credits, which I think ends up representing sixty hours per week.
I have not been able to get anyone to answer the question of "90 hours *for whom* and *for what grade*?", I've been given the impression that I should strive for that workload for the "average" student in a course, although I've also heard it as a lower-bound.
Particularly during these difficult times, I'm shooting for that to be the upper bound on work for the class for more methodical students students intent on earning high A's.
Hence, most of you should be able to work less.
If you find yourself working more than the expected amount in this course, please let me know; I *will* make adjustments.

So, how will you spend those twelve or so hours per week?

* 4 hours in class;
* 3-4 hours reading and journaling about readings; and
* 3-4 hours completing investigations and smaller tasks.

## Diversity and inclusion

I believe that any college-level course should challenge you and put you outside of your comfort zone.
My mission as an instructor is to help you manage that discomfort so that you can grow in knowledge and maturity.
Therefore, I strive to create a fully inclusive setting so that we all can ultimately succeed in the classroom.

### Learning needs, adjustments, and accommodations

I welcome you to talk to me as early as possible about your distinctive learning needs.
I particularly encourage students with disabilities to meet with me and discuss how our classroom and course activities could impact their work and what accommodations would be essential.
I will also make adjustments for students without documented disabilities.  However, I do recommend that you seek official accommodations.
As part of the accommodations process, I recommend talking to our Coordinator for Student Disability Resources for guidance and further instructions:

+ Jae Hirschman, Goodnow Hall, 3rd floor (x3089)

You can find some additional details in [my statement on
accommodations and adjustments](../handouts/accommodations).

### Religious observance policy

I also support the class's religious diversity and anyone who needs to balance academic work with religious observations.
Please let me know by **week two** if you will need to be absent from class for any religious holidays this semester, and we can work out an appropriate schedule for making up absences or missed work.

### Community guidelines

Our class is a community.  We should behave as such.  Among other things, that means treating others with respect, not only in the language that we use (no slurs, please), but also in taking ideas, approaches, and perspectives seriously.

### Other accommodations

There are a limitless number of dimensions to diversity and inclusion, the totality of which are unaddressable with a finite set of policies.
These may include other issues best addressed earlier in the semester (*e.g.*, student-athlete scheduling) or as they arise (*e.g.*, chronic health flare-ups).
I will do my best to be flexible in these cases with the overall goal of facilitating your growth in this course.
To do this, I prefer to receive advance notice from you **at least one week in advance** so that we can make suitable arrangements.

## Evaluation and grading

Because of some issues we will discuss in class, I do not yet have
the grading policies for the class worked out.  I do not grade on
a curve; I believe that if every student does A-level work, every
student should have the opportunity to earn an A.  I've also started
moving toward a form of "mastery grading"; I want to see that you've
mastered the material by the end of the semester, not that you've
mastered it by a certain point earlier in the semester.  Hence,
while we will have interim assignments, I will permit you to re-do
any work for which you receive a lower grade than you are satisfied
with.

I will base your grade on the following components:

* Participation: 10%.  Regular participation in class. 
* Reading journals: 30%.  Regular responses to the readings (and, as
  appropriate, the reading prompts), posted to Teams.
* Assignments: 40%.  Weekly assignments to guide you through one iteration
  of UI design.  These can be done individually or in small groups.
* Tasks: 20%: A variety of smaller tasks throughout the term.

### Final deadline for all work

Note that *all* work must be submitted by {{ site.all_work_deadline }}.
This is College policy and cannot be waived for any reason.
If you find yourself needing to turn in work past this deadline, you must consult with me as soon as possible to submit an *incomplete request* for the course.
If you take an incomplete in the course, the only work you can make up will be the mini projects.

### Academic alerts

_This text is adapted from a statement by Angelo Mercado and Cynthia
Hansen._

Because I value your success as a student in my course, there may
be times when I will reach out to our Academic Advising staff. Most
frequently, I will reach out if I notice you experiencing difficulties.
For instance, if you miss more than one class, do not turn in an
assignment, or fail an assignment or exam, I will submit an academic
alert using the college’s SAL system. I will do my best to notify
you ahead of submitting an alert but may need to act quickly depending
on the circumstances. The academic alert is a way for us to invite
one or more trained professionals on campus to work in partnership
with you and me to address these difficulties and to ensure your
ultimate success in the course and at Grinnell. You are always
welcome to reach out to me if there is a significant issue impacting
your learning, and I will be happy to help you connect directly
with campus resources.

## Software, textbooks, references, technology, and such

There are several software packages we use in this course both for learning how to program as well as conducting learning online.

+ Your [Grinnell Office365 account](https://office365.grinnell.edu) for the following services:
+ [Microsoft Teams](https://teams.microsoft.com): a collaboration tool for discussion, Q&A, and video/voice conferencing.

Please make sure you can access all of these resources, and please let me know if you have any problems with access.

There is no required textbook for this course. 
I will rely on Web-based resources for most of the course.

**Internet Connectivity**

In addition to software, you will also need a stable Internet connection capable of streaming audio and video.
Because of the importance of collaborative work in this class, participating in synchronous lab sessions is required.
If your Internet connection does not meet these requirements, please contact me as soon as possible so we can work with Grinnell's Information Technology Services (ITS) group to get you an adequate connection.

## Help, collaboration, academic honesty, and academic integrity

To help expedite your learning, you can rely on me, our class mentor, and your peers as outlets in this course.

**The Instructor, course staff, and other resources**

When contacting the course staff, please use direct messages (DM) on Microsoft Teams.
While we will generally not respond immediately—we will check our messages at fixed times throughout the day—we will prioritize responses to student questions over Teams versus queries sent through other means, *e.g.*, email.

The **course mentor** may also hold optional *mentor sessions* outside of regular class time.
In these sessions, the mentors guide you through practice problems designed to help you master the material and answer any questions you have about the material.
I highly recommend you attend each of these sessions, even if you feel like you understand the material.
You never know what you don't know, and the purpose of these sessions is to bring these blind spots to light!

The CS department also provides **individual tutors** as needed.  If you find yourself struggling with the material, please let me know and I'll work with our peer education coordinator to get one assigned to you.

Finally, if you would like to discuss things in more detail—--course content, more general questions about computer science, or other things—--feel free to schedule a (virtual) meeting with me, either [during office hours](https://bit.ly/book-samr) or, if those don't work, by sending me a message with available times.

Note that if I find that you have fallen behind on assignments or are showing difficulty on quizzes or learning assessments, I will invite you to meet with me.  Please accept those invitations; they are intended to be supportive, not punative.

**Peer learning**

Utilizing discussion with peers to facilitate your learning is a critical skill for success in computer science.
However, at the same time, you must be aware that getting stuck and pushing through challenging problems is essential for robust learning.
To this end, we allow the following forms of collaboration.

+ You are encouraged to collaborate with your peers on reading exercises, labs, and projects.
  You may also consult the course staff as well as other people and external resources.
  In all cases, you (or your group in the case of group work) should independently write up your solutions and cite all the resources you used in authoring your work.
+ You may only discuss learning assessments and quizzes with the course staff.
  When completing assessments and quizzes, you may only consult the course website and the Racket Documentation page in developing your program.
  You may not collaborate with peers, consult external resources beyond the ones mentioned above, or share information about these assignments with others.

Keep in mind that *adaptation of pre-existing code* whether it comes from a peer, myself, or the Internet, requires a citation in cases where it is allowed.
Also, whenever you are expected to show your code's output, you are expected to reproduce the output faithfully.
In other words, you should not forge the results of your programs!

In all cases, the work that you produce should be your own.
The golden rule is that you should be capable of reproducing your deliverable on the spot with minimal effort if it was accidentally deleted.

If you feel that the stress and pressure of the course are compelling you to violate the academic honesty policies of the course and the college as explained in the [student handbook](https://catalog.grinnell.edu/content.php?catoid=12&navoid=2537#Honesty
_in_Academic_Work), **please talk to me as soon as possible**.
The course's grading policies as designed to help you manage your time in light of the different stressors in your life.
I will do my best to work with you to figure out how to help you better manage your time relative to your learning goals and desired achievement level for the course.

And just if that wasn't enough, you should check out [my extended statement
on academic honesty and integrity](../handouts/academic-honesty).

**Sharing of course materials**

Our goal is to create an inclusive learning environment where people feel free to share, fail, and ultimately grow in knowledge.
To create such an environment, it is imperative that we be mindful of what we share outside of our learning space.
To this end, I request that you refraining from sharing any recordings of our class meetings with others.
Recordings of class meetings that we provide, *e.g.*, recorded through Microsoft Teams, are meant for your *personal use* and should not be shared outside of the class.

Furthermore, while you retain [copyright](https://www.plagiarism.org/blog/2017/09/25/do-i-own-my-work-even-if-im-just-a-student) of the work you produce in this course, we must still uphold the academic integrity of this course.
To this end, you may not share copies of your assignments with others (unless otherwise allowed by the course policies) or upload your assignments to third party websites unless substantial changes are made to the assignment (*e.g.*, significant extensions and improvements to your code) so that it is clear that the end product is significantly different from what was asked in original assignment.
I do recognize that there are times where you want to do this, *e.g.*, uploading projects to Github for your resume or to show to friendds and family, and so I encourage you come talk to me in advance, so that we can ensure that you upload a meaningful project that does not run afoul of this policy.

ITS has also recently released [policies that may limit your ability to share your work with others](https://grinco.sharepoint.com/sites/IT/SitePages/The%20Software%20Review%20Process.aspx).  I consider those policies inappropriate for many reasons.  I have asked the College to revisit them, and I hope our administrators will do so soon.  (It appears that my request led to the College taking down those policies to reconsider them.)

## Other issues

**Technology**

Our clasess remain online.
Online classes can be a challenge.
And each online learning environment brings its own set of challanges.
We will work together to help smooth online learning process.

This may be your first semester learning with Teams.
Things will likely mess up from time to time.
That's okay; it's part of the process.
(I can almost guarantee that if we were in person, some aspect of the technology would break.  It has every other time. Usually it's the projection system.)

This is likely your first semester using Gradescope.
Gradescope does some things well and some things less wel.
Things will likely mess up from time to time.
That's okay; it's part of the process.
I'll make adjustments when you have difficulty.
I hope you'll accept my apologies when I do something wrong
(or at least fail to adjust my processes to the way Gradescope thinks they
should be done).

Technology helps, particularly in this time of remote learning.  But it
also gets in the way from time to time.  Of course, you probably knew that
already.

**Learning online**

I don't have a lot to say about learning online.  Okay, that's a lie.
I have a lot to say about almost anything, or at least anything related
to higher education, liberal education, and/or technology.  Perhaps "I
don't have a lot to say _at this moment_."

I do not think that most online small-class education is as good
as the corresponding form of in-person education.  I worry about
equity issues.  I don't like that my class requires a good Internet
connection and a certain level of technology.  I apologize for all
three issues.

As you could likely tell from the first day of class, I consider
teaching a type of performance.  Like all performative art, online
teaching needs to embrace different modes and models.  I am working
to discover which approaches are best for my own performances.

Know that I will do my best to make this an excellent class, and,
from what I've seen, we come close to matching the learning outcomes
and community building in online Grinnell CS classes that we achieve
in our in-person classes.

**Names**

I get names wrong.  I get names wrong all the time.  Evidence
suggests that I am not just bad at remembering names, I also have
some brain differencees that regularly lead me to mix up peoples'
names.  I think, for example, of two of my favorite research students,
one with blonde hair, from Minnesota, who also served as a teaching
assistant for my software design course; the other with dark hair,
from Massachusetts, who brought a wealth of background in education
to my research projects.  I can tell you a lot about each student
(although I wouldn't without their permission), including hobbies,
where they studied abroad, what they are doing now (or at least
what they were doing before the pandemic hit), and more.  But I
inevitably reversed their names, calling Minnesota Massachusetts
and Massachusetts Minnesota.

When I discussed this issue with my family, my sons laughed and said "Dad,
you get *our* names backwards, too; we just ignore you when you do so."
And I've heard from other students I value highly that I do this and
don't always notice. 

If I use the wrong name for you, it is not a sign that I do not
respect your or that I do not care about you.  It's a deficiency
in my processing, and one that I seem unable to fix.  Please accept
and understand that disability, just as I will do my best to accept
and understand your own differences.

**Feeling overwhelmed**

You may feel a bit overwhelmed by this point.  I know that I do
after re-reading most of it and re-writing some of it.  But **don't
worry**.  We'll get through this together.

## Acknowledgements

Much of this syllabus was taken and adapted, with permission, from Peter-Michael
Osera's syllabus for a Fall 2020 section of CSC-151 and Janet Davis's syllabus for the Spring 2015 section of CSC-232.  I am particularly grateful to Dr. Davis for a model for the course.
