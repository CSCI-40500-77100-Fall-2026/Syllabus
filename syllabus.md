# CSCI 40500/77100: Software Engineering

3 hrs, 3 credits. Computer Science, City University of New York (CUNY) Hunter College.

## Details 

Field | Value
----- | -----
**Instructor:** | [Raffi Khatchadourian]
**Office:** | 1090J Hunter North Building
**Email:** | [khatchad@hunter.cuny.edu](mailto:khatchad@hunter.cuny.edu)
**Phone:** | (212) 650-3988
**Office hours:** | TTh 3:30-4:30 pm
**Semester:** | Fall 2026
**Section:** | CSCI 40500/77100-01

## Course Description

This course is an introductory survey on the fundamental concepts and principles that underlie current and emerging methods, tools, and techniques for the efficient engineering of high-quality software systems. This may include the understanding and appreciation of problems in large-scale software development such as functional analysis of information processing systems, system design concepts, timing estimates, documentation, and system testing.

Software Engineering (SE) is concerned with all facets of software development, from the early stages of requirements engineering to maintaining the system after it has been deployed. This includes technical processes of software development as well as activities such as software project management and the development of tools, methods, and theories to support software development. This course is not a "programming" course per se, instead, it focuses on surveying some of the critical facets of SE that may be less familiar to students of Computer Science, such as identifying a development process appropriate to the circumstances, eliciting and documenting requirements, using reviews and inspections plus machine-based testing in software development, understanding software evolution in large, complex systems, issues associated with developing dependable software systems, and configuration management of large systems developed by multiple engineers.

## Potential Course Topics

Topic | Book | Reading Chapter(s)/Page(s)
--- | --- | ---
Software Products | Sommerville | 1
Object-Oriented Programming Refresher | | Instructor material
Agile Software Engineering | Sommerville | 2
Features, Scenarios, and Stories | Sommerville | 3
Software Architecture (modeling with diagrams-as-code) | Sommerville | 4
Cloud-Based Software | Sommerville | 5
Microservices Architecture | Sommerville | 6
Security and Privacy | Sommerville | 7
Design Patterns | GoF | pp. 293--305
Reliable Programming | Sommerville | 8
Testing | Sommerville | 9
Static Analysis (applied lab) | Google | 20
DevOps and Code Management | Sommerville | 10
Machine Learning in a Nutshell for Software Engineers | Kastner | 1--3
Quality Assurance for ML-Enabled Systems | Kastner | 15--16
Foundation Models and AI Agents | Huyen | 1--2

Architectural and design models in this course are expressed as *diagrams-as-code* (e.g., [Mermaid] and the [C4 model]) checked into your project repository, rather than as standalone UML documents.

Students are required to read the linked articles if no chapter is specified above. The instructor will distribute any supplementary material. Chapters and pages refer to the required text unless otherwise specified.

## Prerequisites

- [CSCI 33500: Software Analysis and Design III] or equivalent.

Students must be familiar with a modern Object-Oriented programming language such as Java or Python and must be familiar with common computing terminology. The examples in the book are in Python but should be understandable by anyone with programming experience.

## [Textbooks]

Title | Author | ISBN | Type | Comment
-- | -- | -- | -- | --
[Engineering Software Products](https://books.google.com/books?id=M2kNuwEACAAJ) | Sommerville, I. | 978-0135210642 | Required | Main textbook
[Design Patterns: Elements of Reusable Object-Oriented Software](https://books.google.com/books?id=6oHuKQe3TjQC) | Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides | 978-0321700698 | Optional | "GoF" book
[Software Engineering at Google](https://abseil.io/resources/swe-book) | Titus Winters, Tom Manshreck, Hyrum Wright | 978-1492082798 | Recommended | Free online; static analysis, testing, and CI/CD
[Machine Learning in Production: From Models to Products](https://mlip-cmu.github.io/book/) | Christian Kastner | 978-0262382953 | Recommended | Free online; for special topics on ML systems
[AI Engineering: Building Applications with Foundation Models](https://books.google.com/books?id=98Ix0QEACAAJ) | Chip Huyen | 978-1098166304 | Recommended | For special topics on foundation models and agents

The bookstore lists the assigned material per section: [CSCI 40500][textbooks] and
[CSCI 77100][textbooks-77100]. Both sections are assigned the same required text.

## Student Expectations

For this course, you must:

- Do the chapter readings and cover the lecture slides.
- Do the homework assignments.
- Work well with your classmates and team.
- Complete a term project.

## Grading

Category | Percentage
-------- | ----------
Assignments | 15%
Midterm exam | 30%
Final exam (non-accumulative) | 30%
Project | 20%
Participation | 5%

## Key Dates

Event | Date
----- | ----
Midterm exam | 10/28
Withdrawal deadline | 11/6
No classes scheduled | 11/25
Last day of classes | 12/9
Final exam | 12/16 (5:30-7:30 pm)

## Credit/No Credit Policy &amp; Special Enrollment Permission

The instructor will not approve C/NC requests for this course. However, such requests may be approved by the college on a per-semester basis; students are encouraged to check the college policies. Students are also encouraged to discuss these options with their academic advisors. Special enrollment permissions, e.g., prerequisite waivers, will not be granted without substantial supporting evidence, e.g., sufficient professional experience.

## Organization

### Lectures

The instructor will post lecture slides for each chapter.

### Reading

The instructor will post a corresponding reading assignment for each chapter.

### Lab

Students work together with their lab partners on a semester-long project.

### Homework

Homework will be assigned after each chapter read. It may include questions at the end of the chapter or short coding assignments depending on the material. Each will be assigned in Brightspace along with submission instructions. I have designed this course to be **self-contained**. Thus, **the only resources you need to answer the questions are contained within the course**. Searching the web (e.g., Google) for answers is not only *unnecessary* but also risks [academic violations](#academic-violations), which can result in course failure.

### Project

Students will work together in assigned groups on a semester-long project. The project must incorporate the lessons learned from the week's topic. Thus, the project will be done incrementally throughout the semester. However, the project will require the following *each and every week*:

1. A working prototype of the project. This can be as simple as a project skeleton. Be prepared to "throw away" the prototype each week for the first few weeks as your knowledge of the course progresses.
1. Code hosted in a Git repository on GitHub.
1. Working tests invoked via continuous integration (CI).

The final deliverable must be a **substantial, student-authored codebase** that demonstrates the practices taught in this course, e.g., design, testing, refactoring, and version control. You are welcome to use frameworks, libraries, scaffolding, and backend-as-a-service platforms, as professional engineers do. What does not satisfy the requirement is an application authored *for* you, whether by a no-code or visual app builder or by a generative tool whose output you cannot account for. You are expected to be able to **explain and defend** any code you submit, including why it is written the way it is.

Each group's work must live in a **single Git repository** in the course GitHub organization, and the full commit history is part of what is assessed. The tooling that creates those repositories and collects them for grading is **being finalized**; the instructor will announce the specific mechanics early in the term. Until then, do not set up your project elsewhere. Please inform the instructor if your group requires any computing resources from the Computer Science department to complete your project.

### Presentation

A select number of groups may be asked to present their final projects towards the end of the semester.

## Notes

- **Deadlines** and **due dates** for assignments will be assigned in class.
- **Late assignments will be penalized.**
- No extensions will be given for extra credit assignments.
- Assignments are the result of **individual effort** unless otherwise noted (e.g., group projects).

## Exams

Test make-ups will be given if and only if:

- the request is made sufficiently in advance of the test, and
- the make-up is scheduled within three (3) business days following the exam period.

## Attendance

Attendance is expected for *each and every class* meeting. The instructor will start the class on time, and students are expected to be present on time. If students are late or miss class, it is the student's responsibility to makeup any missed material. How students do that is up to them, but I suggest asking another student in the class. Please do not ask or email the instructor about information on any missed material due to missing or being late to class. Please come on time.

## Professional Presence &amp; Communication

A central focus of this course is to simulate the professional work environment of Software Engineers. Thus, every student is expected to present themselves in a professional manner. Students are expected to participate in their group activities under a professional demeanor.

## Academic Violations

The classroom environment employed will be that of a professional one. While students may discuss course materials and assignments with others at a high level, any submitted work must result from *individual* effort *only*. Students are *strongly* advised to read the [resources regarding academic integrity](https://hunter.cuny.edu/students/student-affairs/office-of-student-conduct/academic-integrity) provided by Hunter College.

## Email

- Emails to the instructor must be via CUNY email addresses for FERPA reasons.
- Include the *class name* or *number* in the *subject* line of the email.
- Email thread *hijacking* is strongly discouraged. Ensure that the subject of your email matches its contents.
- Ensure that your *correct CUNY* email address is entered into the CUNY Brightspace.

## Bulletin Board

You should check the [Brightspace](http://brightspace.cuny.edu) site regularly since all class material will be posted there. Please make sure you have configured Brightspace to use your *CUNY email address*. You are responsible for any email the instructors might send there.

## Laptop Loans, Computer Science Facilities, &amp; Labs

- Laptops and other computing equipment is available for [loan] through Hunter College.
- All Computer Science students can (remotely) use any of the general-purpose labs throughout Hunter College.
- Computer Science majors and students enrolled in CSCI courses can obtain an account on the Computer Science Department Network. More information can be found on the [Computer Science Department's website](http://www.hunter.cuny.edu/csci/about-cs/computer-science-facilities-labs).

## Counseling &amp; Wellness Services

Counseling &amp; Wellness Services (CWS) provides mental health counseling, health promotion, and education programs aimed at enhancing your quality of life and maximizing your personal and academic growth and development. Students may find more information on the [Counseling &amp; Wellness Services website](https://hunter.cuny.edu/students/health-wellness/counseling-and-wellness-services).

## Special Needs

Students with special needs should see me for accommodation *at least* two weeks prior to the due date of any assignment or exam.

## ADA Compliance

The Office of AccessABILITY's goal is to enhance the educational experience for students with disabilities at Hunter College. Their mission is to ensure a comprehensively accessible college experience for all students with disabilities. The program is also committed to promoting access and awareness as a resource to all members of the Hunter College community. Students may find more information on the [office's website](https://hunter.cuny.edu/students/health-wellness/accessibility/).

## Family Educational Rights and Privacy Act (FERPA) 

Please review the [student rights concerning education records][ferpa].

## Sexual Misconduct

Hunter College is committed to maintaining a fair and equal environment for both its employees and student body, consistent with the requirements of Title IX of the Education Amendments Acts of 1972. Please review the [CUNY policy on sexual misconduct](https://hunter.cuny.edu/diversity-and-compliance/title-ix-and-sexual-misconduct).

## Credits

Portions of this syllabus are based on the syllabus used for the [CEN 5035 Software Engineering Fall 2016 course](http://www.cise.ufl.edu/class/cen5035/fa16.html) of the Department of Computer Science &amp; Engineering, the University of Florida by Steve Thebaut, as well as syllabi from Atanas Rountev.

[textbooks]: https://hunter.textbookx.com/institutional/index.php?action=browse#books/5457552/
[textbooks-77100]: https://hunter.textbookx.com/institutional/index.php?action=browse#books/5602169/
[GitHub]: https://github.com/CSCI-40500-77100-Fall-2026/Syllabus/commits/master
[loan]: https://cunyhunter.co1.qualtrics.com/jfe/form/SV_9viuDlTexA9rV2d
[Raffi Khatchadourian]: http://cs.hunter.cuny.edu/~khatchad
[CSCI 33500: Software Analysis and Design III]: https://hunter-undergraduate.catalog.cuny.edu/courses/0245511
[ferpa]: https://hunter.cuny.edu/students/registration/records-and-transcripts/ferpa
[Mermaid]: https://mermaid.js.org
[C4 model]: https://c4model.com
