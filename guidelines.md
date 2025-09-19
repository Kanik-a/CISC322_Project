 PDF To Markdown Converter
Debug View
Result View
guidelines
Project Purpose
The purpose of this project is to give you an appreciation of software architecture in the context of a
large software system. You will create a detailed architecture report for a large software system. The
report will be updated throughout the term and will be posted online on your group’s webpage. At the
end of this project, you would have:

Gained an overall view of the architecture of a large software system,
Recognized the strengths and limitations of the architecture,
Verified the architecture against the actual implementation (i.e., conceptual vs. concrete),
Proposed an enhancement or a new feature based your gained understanding,
Described the steps needed to implement your proposal,
Compared alternative implementations,
Presented all your findings and proposals to your coworkers and the management team.
Project Overview
The project will be performed in groups of six students (in addition to a virtual AI teammate). The
project consists of four deliverables (A0, A1, A2, and A3):

A0 – creation of a website about the studied software system.
A1 – recovery of the conceptual architecture based on reading documentations.
A2 – recovery of the concrete architecture from source code and studying differences.
A3 – proposal for enhancements.
You will have to present your findings for A1, A2, A3 online or in class (see Appendix B for
presentation guidelines). The specific format of the presentation (online vs. in class) will be announced
ahead of time, depending on the pandemic circumstances.

Project Deadlines
Check the syllabus for deadline dates for this term.
Note:

For each deliverable, a single group submission is required (i.e., only one submission from your
group).
For deliverables (A1, A2, A3), each member of your group must submit a confidential peer
review via onQ within 24 hours following the submission of a deliverable (see Appendix C)
Do not make your report longer than necessary. Write clearly. Organize your report so it is easy
to find things in it. Avoid repetition. In general, shorter reports that contain appropriate
information are preferred. Your report must not be longer than 1 7 pages (in the hard copy
version), including all diagrams, appendices and the (2-page) AI teammate collaboration report
(see Appendix D).
4. Like much work in software development, you are being asked to do more than you have
time to do. Part of your job is to choose what you will actually do for each deliverable (hint:
make sure you consult the marking scheme for each deliverable).
Project Details
Assignment 0: Webpage and Links
For the first deliverable, you are to create a webpage with various links (e.g., tutorials, documents, books,
discussion groups, group policy, and source code location) about the studied software system. The
webpage should contain sufficient information to help a newcomer to a software project get up to speed.

Submission Process: By the deadline date,

You should submit the URL of your webpage via onQ.
Assignment 1: Conceptual Architecture
For this deliverable, you will submit a report (up to 17 pages long) that gives the abstract (i.e.,
conceptual) architecture of the studied software system (see Appendix A). Your report should be posted
online. It should be web-readable, with appropriate links to web-accessible related content. The report
should contain sufficient information to help a newcomer to a software project get up to speed. It should
also contain a 2-page AI collaboration report (see Appendix D).

Your report should present the conceptual structure of the software system rather than discuss the details
of its implementation. When presenting the conceptual architecture, you should include information
about:

What the system does (its functionality) and how it is broken into interacting parts? What are the
parts? How do they interact?
How does the system evolve?
What is the control and data flow among parts?
What concurrency if any is present?
What are the implications for division of responsibilities among participating developers?
At least two sequence diagrams to explain the flow of noteworthy use cases using the presented
conceptual architecture.
Submission Process:

By the deadline date, you should submit a PDF of your report via onQ.
Starting the fourth day, and not any earlier , after the deadline date (to avoid plagiarism of
the current assignment), your report should be accessible on your group’s webpage.
Your group will also be given the task to constructively review the presentation of 1 or 2
other groups, producing a 1-page document with constructive feedback for each such
group. This feedback should consist of 3 positive points about the other group's
presentation and work, with some explanation of your points, as well as 3 points of
improvement, containing not only an explanation of your points but also suggestions on
how to address these issues. This feedback is anonymous, i.e., do not mention your group
number, name, etc. Since the members of the other group will read your (anonymous)
feedback, it is important to be constructive, fair and clear.
Assignment 2: Concrete Architecture
For this deliverable, you will submit a report (10-15 pages long) that gives the as-built (concrete)
architecture of the studied software system (see Appendix A). Your report should be posted online. It
should be web-readable, with appropriate links to web-accessible related content. It should also contain
a 2-page AI collaboration report (see Appendix D).

You will need to download from onQ the extracted dependency file of the software system and group
the top-level entities of the system into subsystems (and those subsystems into subsystems as necessary).
Make sure you describe the process you followed to create your concrete architecture.

In addition to presenting the top-level architecture, your report should dive into the architecture of one
top-level subsystem of the studied software system. Each group can choose this subsystem from the list
provided on onQ, or freely, if no such list is provided. Your report should describe the used architectural
styles and list any noteworthy design patterns. You need to compare your concrete architecture against
your conceptual architecture from Assignment 1 (i.e., perform a reflexion analysis). Make sure you
investigate and report the rationales for any discrepancies between both architectures.

Note that you can modify your conceptual architecture to fit your updated understanding, potentially
based on another group’s conceptual architecture. For example, you might have seen that group’s
presentation or read the A1 report the group has posted on their website. It is permitted to update one’s
conceptual architecture based on this information, as long as the report for A2 explicitly describes how
and why your current conceptual architecture is different from the architecture that you submitted in A1.

You should include diagrams of the concrete architecture based on Understand. You might need to
redraw the diagrams to make your presentation cleaner and easier to follow. You should present
noteworthy aspects of the architecture and its subsystems using sequence diagrams (or state diagrams).

Submission Process:

By the deadline date, you should submit a ZIP file containing a PDF of your report along
with your Understand project file via onQ.
Starting the fourth day after the deadline date, and not any day earlier (to avoid
plagiarism of the current assignment), your report should be accessible on your group’s
webpage.
Your group will also be given the task to constructively review the presentation of 1 or 2
other groups, producing a 1-page document with constructive feedback for each such
group. This feedback should consist of 3 positive points about the other group's
presentation and work, with some explanation of your points, as well as 3 points of
improvement, containing not only an explanation of your points but also suggestions on
how to address these issues. This feedback is anonymous, i.e., do not mention your group
number, name, etc. Since the members of the other group will read your (anonymous)
feedback, it is important to be constructive, fair and clear.
Assignment 3 : Enhancement Proposal
For the final deliverable, you will submit a report (10-15 pages long) that proposes a particular feature or
enhancement (in consultation with your TA). The proposed feature or enhancement should not be
available in the current version of the studied software system. You must clearly explain the value and
benefit of adding this enhancement.

The report should briefly discuss the changes required so the current architecture can support the
enhancement. In particular, the report should explain which components and interfaces must change and
what should change at the high level. The report should also discuss the impact your architectural
change may produce and the potential risks of these changes.

Note that you can modify your conceptual/concrete architecture to fit your updated understanding,
potentially based on another group’s conceptual/concrete architecture, similar to the instructions for A2.
The only requirement is that the report for A3 explicitly describes how and why your current
conceptual/concrete architecture is different from the architecture that you submitted in A1/A2.

Finally, you should present an SEI SAAM architectural analysis^1 of two different ways to realize your
enhancement. Such an analysis consists of:

Identifying the major stakeholders of the proposed enhancement.
Identifying, for each such stakeholder, the most important non-functional requirements (NFRs)
regarding the enhancement.
Evaluating for the two suggested ways to realize your enhancement how they impact each
identified NFR and stakeholder.
Determining which way to realize the enhancement is the overall best one based on the analysis
of the previous step.
Your report should be posted online. It should be web-readable, with appropriate links to web-accessible
related content. It should also contain a 2-page AI collaboration report (see Appendix D). Make sure you
use a sequence diagram to explain the flow of at least one use case through the proposed architectural
modifications.

Submission Process:

By the deadline date, you should submit a PDF of your report via onQ.
Starting the third day after the deadline date (to avoid plagiarism of the current
assignment), your report should be accessible on your group’s webpage.
(^1) See “SAAM: A Method for Analyzing the Properties of Software Architectures”, Kazman et al., ICSE
1994 (https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.65.8786&rep=rep1&type=pdf)

Appendix A: Report Content
Your report should be single space 12 point font. The reports should be up to 17 pages long, and include
the following information:

Title:
About 3 to 6 words making clear what your report is about.

Authors:
List of authors, their email addresses, date, etc.

Abstract:
About 2/3 of a page giving an overview of the key points and findings in your report. This is targeted to
a manager or a developer.

Introduction and Overview:
About 1 to 3 pages summarizing the purpose of report, its organization, and its salient conclusions. A
person should be able to read just the abstract or just the introduction and have a good idea what is in the
rest of your report.

Architecture:
Give the overall structure of the studied system, with descriptions of each major component and the
interactions among them. These components are to be primarily subsystems or modules, but may also
include threads or processes, files, and databases. In your descriptions, concentrate on goals,
requirements, evolvability, testability, etc., rather than on lower-level concepts such as classes, variables
and control flow. Discuss any parts of the system that are performance critical, i.e., which might not run
fast enough. Discuss how the architecture supports future changes in the system.

You should clarify global control flow, such as units of concurrency and method of passing control from
one component to another.

Your system's architecture should be easy to understand, with simple interfaces, and modest interactions
among subsystems and modules. Clarify the architecture style (in the sense of Garlan and Shaw) that
characterizes the overall system and its various parts.

You are not to concentrate on minor components, such as classes and procedures, which are smaller than
packages or modules. However, you may wish to discuss important abstractions, patterns, classes, data
structures or algorithms that are critical to the success of the architecture.

Diagrams:
You should use diagrams that clearly illustrate the structure of your system. You may choose to use
various kinds of UML diagrams. Do not give diagrams that are too low level, e.g., do not give diagrams
of details within objects, nor within modules. You can use tools such to help you draw diagrams, but this
is not required. Do not include diagrams that are difficult to read. Make sure that all your diagrams
have a clear legend explaining the meaning of the various arrows and symbols.

Use diagrams as needed in your report. You are to include a "dependency diagram", in which the boxes
are subsystems and modules, and the arrows are dependencies. A dependency from module M to N

could be due to a call from a procedure in M to one in N, or a reference from inside M to a variable in N,
etc. These diagrams can be created using any method you choose.

External Interfaces:
List information transmitted to/from the system, such as by Graphical User Interfaces, files, databases,
messages or networks. Do not give details such as menus, but rather concentrate on information content.
Although information may be stored in a database, the exact form of this data need not be a concern.

Use Cases:
Give a small number (at least two) of essential Use Cases which illustrate the use of the system or your
proposed feature. Show or explain how each Use Case activates or uses the various major parts of the
current or proposed architecture.

Data Dictionary:
Include a glossary that briefly defines all the key terms used in your architecture, giving when
appropriate, the "type" of the item being explained.

Naming Conventions:
List any naming conventions used in the described architecture. Explain any abbreviations that you use.

Conclusions:
A summary of your key findings and proposals for future directions.

Lessons Learnt:
Document any noteworthy lessons: things you would do differently or things you wished you knew
ahead of time.

References:
List any documents that your reader may wish to or need to read in conjunction with your report. Since
the report is to be web-readable, include links to references when appropriate.

AI Collaboration Report:
A two-page description of how your group interacted with the mandatory virtual AI teammate, see
Appendix D.

Appendix B: Presentations
As a software architect, you need to have the charisma and communication skills to communicate your
architecture and your findings to the developers who will implement it and to your managers to get
funding.

In addition, you must be willing to:

take a fresh and unbiased look at your own work,
get constructive feedback from others and
backtrack and reconsider.
The presentation of your analysis is your opportunity to showcase your findings and share ideas with
your peers. Your target audience is a team of developers who are responsible for the analyzed project
and who would implement your proposals.

Style
Each group will be given a 10 mins slot to present their assignment in class or online (see instructions on
onQ). The slides must be put online on the group’s webpage starting the fourth day after the deadline of
a deliverable. Other groups are expected to comment and critique the findings (5 mins).

Recommendations
Rehearse and time your presentation ahead of time.
(If in class) Make sure you leave enough time for at least 1 or 2 questions, i.e., finish your talk in
10 minutes.
Use slides and make sure you have your architecture diagrams on the slides.
Explain and put a diagram legend on your slides.
Articulate the principles and key mechanisms used by your group to reach your findings.
Present some modeling alternatives that were considered and explain why they were rejected.
Highlight any tradeoffs.
Be prepared to defend your architecture decisions.
Provide constructive feedback to other groups.
Document any noteworthy lessons: things you would do differently or things you wished that
you knew ahead of time.
Appendix C: Peer Evaluations of Your Group
Members
Why peer evaluations?
Your group will have to decide how to organize itself. If you are amazingly lucky, your tasks will split
naturally into an equal-size task per person, with obvious clean boundaries between them, and the people
in the group will have equal skill levels, and everyone will get along so well that you'll want to form a
startup company right after exams. More likely, however, you will have to divide labour in some less
trivial way, have some people assist others in emergencies, co-ordinate mismatching schedules, and so
on.

We expect that all members of your group will receive the same grade for all project deliverables.
Because not everything in life works out evenly, we will allow for some accounting of this lumpiness.

In prior group projects, you will likely have experienced problems with team members not participating
at the same level as others, while still getting the same grades as the rest of the team. In an effort to
discourage this sort of practices, we have instituted a way that a student's peer evaluation can affect his
or her entire mark for the project: At the discretion of the professor of the course, a student's mark for
any project deliverable may be multiplied by his or her average peer evaluation score. Thus, for the final
deliverable, if your evaluation is 1 out of a total possible of 5, you may find your mark (out of the 10
possible for the final deliverable) multiplied by 1/5. Moreover, in the extreme case of a student not
participating at all with his or her team in a part of the project, the professor may decide to give a 0
(zero) mark to that student for that part of the project. The moral of the story is: participate, participate,
participate!!!

Therefore, we want each team member to prepare a confidential evaluation of all members (including
themselves). You will prepare three such evaluations, the first will be due within 24 hours after you hand
in A1, the second will be due within 24 hours after you hand in the A2, and the third will be due within
24 hours after you hand in the A3. You will submit the evaluations via onQ. Please submit only plain
text. No HTML! No Word!

The group evaluations will help us track the progress of your group throughout the project.

How does it work?
You are to prepare a short message to be submitted via onQ ( once again, please submit only plain text;
no HTML! No Word! ). In your message you should clearly indicate your full name, the full names of
your group members, and what your group number is.

What should the evaluation look like?
Prepare a paragraph or two on the contributions of each group member. Try to be as objective as you can.
Did they attend all of your meetings? Were they on time for the meetings? Was their work done on
schedule/as promised/with due diligence? Did they take on a leadership and/or organizational role?
Were they easy to work with? Did their work require extra checking by the rest of the group? Did they
stay late when extra effort was required?

Be sure to evaluate yourself as well. Be as honest as you can.

As part of your evaluation, assign each member a numerical grade. You will be given 5 marks per
person in your group to distribute as you see fit, plus one bonus mark if you think it to be
appropriate. That is, a group of three will have up to sixteen marks to distribute between the
group members.

How should you distribute the grades?
Here are some rough guidelines on how you might want to distribute the marks:

A mark of one or two indicates someone who is an unmitigated disaster. You rue the day they
were born, and hope you never end up with someone like this on your team when you work in
industry.
A mark of three indicates someone you really wouldn't want to work with the person again.
There are serious shortcomings to their abilities and/or attitude. (S)he is the sort of person you
will probably run into in industry, but will try to avoid as much as you can.
A mark of four means that a group member did reasonable work, but lacking in some area. Their
work was OK, but not great, or they weren't serious enough, or ... (S)he is the sort of person with
whom you could work without too much trouble, although you wish they were a bit more
diligent/easier/committed to deal with/what have you.
A mark of five indicates a group member did a really fine job on everything that was asked of
him/her. (S)he showed up on time to meetings, did their work on time and well, and chipped in
as needed. (S)he is the sort of person you would hope to work with in industry.
A mark of six indicates someone took on a leadership role, did extra work that others did not,
perhaps picked up the slack from a member who didn't perform as well, and went well above and
beyond the call of duty. You really hope that you'll get at least one person like this on your team
when you work in industry.
A mark of seven indicates someone who leaps tall buildings in a single bound, walks on water,
and solves NP-complete problems in linear time. You hope your company has at least one person
like this, and that (s)he knows you by name so that there is a chance you might one day get to
work on a project with him/her.
To re-iterate: the maximum number of marks you award must total to no more than N5+1,
where N is the number of people in your group. You may award fewer if you wish.*

Note that we will not simply take an average of the submissions to determine your mark. Instead, we
will use our common sense based on having read all of the evaluations. Thus, if one evaluation seems
out of line with the others, it will not unduly influence your grade (so don't just give yourself 7 marks
and think we won't notice!).

Notes
If you are having serious problems within your group, don't wait for the evaluations to roll
around. Have a meeting with your group and try to address the problems. If that doesn't work,
approach the TAs or instructor.
Your paragraph(s) of explanation are important. If you do not turn in reasonable justifications of
your grades, your own performance evaluation will be a 0 for this assignment.
The evaluations are due 24 hours after the major deadlines so that (a) you can get some sleep,
and (b) you have a little time to ponder what you want to say. It also allows for some cooling off
in case there were some last minute tensions.
The evaluations will be kept confidential; only the TAs and/or instructor will read them.
Don't sweat too much about these evaluations. Try to be a good group member and you'll do fine.
And remember that in industry, evaluations will be part of your working life.
An example evaluation
Here are some example evaluations for an imaginary programming assignment given on Tuesday and
due the following Tuesday.
Candorsnaffity Hixelbröd was an annoying teammate. He was late for both meetings,
and had not looked at the assignment or done any kind of preparation in advance. At the
Wednesday meeting, Candorsnaffity offered to do the whole project himself, which the
rest of us found very insulting --- maybe he's the best programmer in the class, but the
rest of us are still good enough to be successful students. Finally he agreed that he'd do
the sushi-ionization module by Sunday afternoon, but he didn't finish it until almost
midnight, and the rest of us couldn't combine his work with ours until Monday evening,
which meant we had to stay up late to get it done by Tuesday. I'd give him 2 points,
except that on Monday evening (after he finally got there), he found all the bugs that the
rest of us were missing and got the assignment working with twenty minutes work. He's
probably a great hacker when he's alone: honestly, he's the best programmer of the four
of us, and we're all annoyed that he was so little help. So he gets 3 points.

Prosnitau Sgrachita de la Mnirhoihoi was good, helpful and co-operative. She arranged
the first meeting and had worked out a module structure and a division of labour before
we met, which we adopted after a bit of bickering. She had her parts of the program
done on time, and they only had one small bug in them. And she stayed late to make sure
that the integration went smoothly, when we all know she hadn't slept the night before.
She gets 6 points.
V'snl'chm'tkn!k of the Fortress of Doom (that's me) was an effective worker in this
assignment. I had sketched algorithms in advance for two parts, which Wub and I
implemented. My code was ready on time, and worked except for one boundary case.
Also, I helped Wub with his part of the assignment. I award myself 5 points.
Wub Catcherofahundredsquids was willing and enthusiastic. He volunteered for the
hardest module, but I had to help him get it working. But he did tell us all on Friday that
he couldn't get his part working alone, so at least it wasn't an emergency. He also
brought cookies to the Monday meeting, and stayed up extra-late testing the program. I
give him 4 points on skill, and 1 more for being helpful: 5 points total.
[These examples were written by my friend, Dr. Samuel Weber of IBM's T.J. Watson
Research Lab near New York City. We apologize in advance if, despite our intentions,
these names resemble those of people you know. -- MWG]
Acknowledgement s

This peer evaluation write-up is based on a write-up by Michael Godfrey for the CS 445 at UW.
Project structure and write-up based on CS746 by Richard C. Holt at UW.
Appendix D: AI Collaboration Report
Why a mandatory virtual AI teammate?
In today's rapidly evolving technological landscape, collaboration with Artificial Intelligence is
becoming a fundamental skill across all disciplines. From software development and data analysis to
creative design and strategic planning, AI tools are integral to the modern workplace. This project
component is designed to provide you with hands-on experience in effectively and ethically leveraging
AI as a collaborative partner.

For each of the three main project deliverables (A1/A2/A3), your team is required to integrate at least
one AI tool as a "virtual AI teammate." Your goal is not simply to offload tasks to an AI, but to
thoughtfully delegate, critically evaluate, and transparently report on its contribution. This process will
be documented in a mandatory two-page appendix at the end of your deliverable report.

The purpose of this exercise is to develop your skills in:

Strategic Task Delegation: Identifying which project tasks are suitable for AI assistance.
Effective AI Communication: Crafting precise and effective prompts to elicit desired outcomes.
Critical Evaluation: Validating and refining AI-generated content for accuracy, quality, and
relevance.
Ethical Reporting: Transparently documenting the role and impact of AI in your work.
Team Dynamics: Understanding how to manage a hybrid team of human and AI collaborators.
What to include in your two-page AI collaboration report?
Your two-page AI collaboration report form the last two pages of your deliverable report, and should
again be single space 12 point font. It will be graded on the clarity of your explanations, the depth of
your critical analysis, and the thoughtfulness of your reflections. It should include the following
information:

AI Member Profile and Selection Process:
Identify the AI member(s) your team chose to work with for this deliverable. This could include large
language models (e.g., Gemini, ChatGPT, Claude), image generators (e.g., Midjourney, Sora), or
specialized data analysis tools.

In this section, you must:

State the specific name and version of the AI tool(s) used (e.g., "OpenAI GPT-4, May 2024
version").
Describe your team's process for selecting this tool. Why was it the right "hire" for the job?
Justify your choice by comparing its capabilities against the specific needs of your project
deliverable and potentially against other AI tools you considered.
Tasks Assigned to the AI Teammate:
Provide a clear, itemized list of the specific tasks you delegated to your AI team member. For each task,
provide a brief rationale explaining why you believed it was an appropriate task to assign to an AI.

Interaction Protocol and Prompting Strategy:

Detail the methodology your group used to interact with the AI. Did you designate a single member as
the primary "prompt engineer," or did the entire group collaborate on crafting prompts and queries?
Describe the workflow. Furthermore, provide at least one example of a complex or critical prompt you
used, and explain how you iterated on and refined your prompts to improve the quality of the AI's output.
For instance, did you provide context, specify a persona, or ask for outputs in a particular format?

Validation and Quality Control Procedures:
AI outputs tend to contain factual errors, biases, or subtle inaccuracies ("hallucinations"), hence a critical
part of working with an AI is verifying its contributions.

Describe the specific steps your team took to validate the AI's output. This could involve:

Fact-checking all claims and data points against primary sources.
Having human team members proofread and edit all AI-generated text for clarity, tone, and
coherence.
Cross-referencing AI-generated summaries with the original source material.
"We read it and it looked okay" is not an acceptable validation process. Be specific about your quality
control workflow.

Quantitative Contribution to Final Deliverable:
Provide a transparent, good-faith estimate of the AI's overall contribution to the final submitted
deliverable. This should be expressed as a percentage and justified by breaking down the various
contributions.

Reflection on Human-AI Team Dynamics:
Finally, reflect on how integrating a virtual AI teammate affected your group's overall workflow,
communication, and collaborative dynamics. Consider the following questions:

Did the AI's involvement save time or create new work (e.g., extensive prompt engineering and
validation)?
How did it influence your team's brainstorming and decision-making processes?
Did it lead to any disagreements or challenges within the group?
What did your team learn about effective collaboration with AI that you will apply to future
projects (both in this course and beyond)?
This is a offline tool, your data stays locally and is not send to any server!
Feedback & Bug Reports