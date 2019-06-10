

# Introduction

Which language should be used in a CS1? There isn't very much research to suggest conclusively what makes the biggest difference in a classroom, and it doesn't seem like the Language debate is over. However, here are the reasons why Racket is less preferable than Python here at UD right now.

Fundamentally, the argument here is about pragmatics. The language we use is far less important than the way we teach. You can teach an amazing CS1 with Cobol, if you are a good enough teacher. However, teachers need to be able to rely on external resources, good pedagogical training, and a host of extrinsic factors. At the end of the day, the Racket community isn't able to provide such resources as well as the Python community.

## What is Racket and HtDP?

Racket is a programming language, a community, an environment, and a way of life.

HtDP stands for "How to Design Programs".

## My History with Racket

I have perhaps one of the most unique relationships with Racket that is possible in the CS Education community. 10 years ago, in Fall 2008, I started at the University of Delaware as as freshman Computer Science major in "CISC-108 Introduction to Computer Science I". I didn't know it at the time, but this semester was the pilot of a new introductory curriculum based on a textbook named "How to Design Programs". What I did know was a weird amount of Computer Science. As a straight-white-middle-class-son-of-a-computer-scientist, I had a lot of programming experience. Mostly game development, but I had gone through my father's old Pascal textbooks a few times. I wasn't able to make any sense of the examples in the Java textbooks I had found, but I thought the ideas sounded cool. I was thrilled to see what "Computer Science" was.

CISC108 was a fascinating experience, and I seem to have had a good time. The professor was enthusiastic and the ideas were all very novel to me. I distinctly remember a reading by Jeannette Wing (the now-famous Computational Thinking paper) that made me feel that I was learning something very special. The fact that everything was *so weird* was great. I was one of the special elect, and clearly some truly brillant minds had figured out the *optimal* CS learning experience. I didn't talk to many classmates at that point, so I don't know what the rest of the class thought about it.

A few years later, I was chosen as a TA for the course. It was an amazing experience as well. However, I do remember some students struggled with the curriculum. I was energized by my meetings with students, even when they didn't understand things. I didn't have context for whether things were normal or not - I just knew that teaching was fun, and I really wanted to figure out how to make this perfect curriculum just a little more accessible. I even started an outline of an online website that would act as a "Everything You Need to Know to Pass 108".

When I decided to pursue a PhD focused on Computer Science Education, I naturally assumed that the HtDP curriculum would figure into things. I was surprised that so few of my professors at Virginia Tech were aware of it. If I had been more aware of VT's standing in the CS Ed community, this would probably have raised more flags. It seemed natural to me that the CORGIS project would support Racket, just as it would support Python and Java. In fact, I think supporting Racket is one of the key reasons we were able to publish so effectively at Splash-E. I had a particularly positive review by one of the HtDP authors - my advisor even remarked that it was unusual that A) the author in question was so effusive, and B) the author signed their name.

Over the next few years, as I immersed myself into CS Education, I was surprised by what I learned about the HtDP curriculum. Or rather, what I did not learn. There is a simple, awful truth about the curriculum: not much research has been done with it. If you review the publications, you can find one very interesting, well-done study by Kathi Fisler that looks at the Rainfall Problem [TODO](TODO). This paper suggests that the curriculum leads to better Functional Decomposition skills by students, and that this may push some students to better results. That's great, but is hardly a large base to draw upon - for a decade old project, I would say it is actually a pitiful amount of evidence. I don't know what exactly triggered the realization, but some time by the end of my dissertation, I recall an uncomfortable feeling - were those beautiful arguments I heard freshman year based on hypothesis or evidence?

In Fall 2018, I was excited to start an Assistant Professorship at University of Delaware and to finally teach CISC-108. I had expressed doubts about the 108 curriculum before, but I agreed strongly with the advice I had been given: give it a chance. I wanted to see first-hand what it was like to teach. I did my best to present the language and ideas as strongly as I could (obviously, without lying to the students about reality). I was... pleased... I think, that students afterwards were surprised to hear my opinions about the language that I developed as an instructor.

The experience was awful. Whatever beauty there is from the curriculum, the majority of my students did not see it. Most of them *hated* Racket. Never before have I ever had students ask me "Why are we learning this language?" *multiple times during class throughout the entire semester*. Experienced students considered it bizarre, new students considered it frustrating. Yes, some students got very excited by its intracicies. But these students would have been excited by almost anything I showed them in Computer Science - I could have been teaching Prolog or Piet and they would have been ecstatic.

The strongest defenders among the upperclassmen would usually say some variation of, "Well, I enjoyed it... But I don't think anyone else did." At least one senior was very cross with me when they found out I was redesigning the course for the Spring to be in Python - why hadn't it been redesigned before *they* had to take the class?

I suspect some folks may attack my understanding of Racket. "Aha", they will say, "Racket is not a language, it is a meta-language for creating other languages." Yes, the vision for the Racketlang community is a beautiful, rich one that draws upon brilliant ideas. However, I am referring to a particular approach dictated around the "How to Design Programs" curriculum, the language sequence ("beginner", "intermediate", and "advanced"), and the editor ("Dr. Racket"). It is this curriculum and community that I am discussing in this website.

## Why This Site Exists

My colleague bought "ihatepython.com". I felt obligated to buy "ihateracket.com". It probably should have ended there, but I had already written the list of arguments.


# So why not Racket?

## Racket is not a very popular language in professional communities

Scheme is #49 on the Tiobe index, Racket is >#51, and neither shows up on most language popularity rankings. Students interacting with external peers and industry professionals will receive no positive feedback that they are learning a useful skill. Finding examples of "Real Racket Programs" is incredibly difficult.

## Racket is not a very popular language in teaching communities

The list of schools using Racket for CS1 is pretty short compared to other popular languages. This github page lists less than a dozen CS1 courses. The schools that do use it are not particularly notable - old adopters like MIT have since moved on to other languages (i.e., Python).

Summary of schools using Racket (from GitHub page) vs. Python (from Guo)

Racket
Python
Yale
U of Toronto
Northwestern
Grinnell
Berry College
Waterloo
U of Utah
U of British Columbia
CMU
MIT
UC Berkeley
Cornell
U of Washington
Georgia Tech
UT Austin
Caltech
U Michigan
Columbia
Brown
Purdue
Rice
USC
Duke
UMass Amherst
UNC Chapel Hill
NYU
UC Irvine
UVA
UCSB
UC Davis
U Chicago
…


The following table is from a paper analyzing introductory computing courses. Given the margin of error (roughly 4%), it’s possible that Racket is less popular than Pascal globally.

> Andrew Luxton-Reilly, Brett A. Becker, Yingjun Cao, Roger McDermott, Claudio Mirolo, Andreas Mühling, Andrew Petersen, Kate Sanders, Simon, and Jacqueline Whalley. 2018. Developing Assessments to Determine Mastery of Programming Fundamentals. In Proceedings of the 2017 ITiCSE Conference on Working Group Reports (ITiCSE-WGR '17). ACM, New York, NY, USA, 47-69. DOI: https://doi.org/10.1145/3174781.3174784


## Racket Infrastructure is Limited

Because so few schools are using Racket, there are not many infrastructure projects related to the language. Obviously, Dr. Racket is a wonderful tool with many pedagogical innovations and there are a wide set of libraries. However, there is not much else: few autograding systems have modern support for Racket, there are no web-based editors, there are no dual block/text editors, etc. The lack of autograding has serious implications for students: turn-around time on grades is highly variable and dependent on TAs (which means we also have to manage the TAs more). The lack of an online exam platform means that we are grading over a hundred paper-based exams, which are inauthentic forms of assessment and extremely time-consuming for instructional staff - stacks of paper simply do not scale.

## Racket Pedagogical Resources are Limited

Because so few people are developing lessons for Racket, the number of lessons and topics available for the language are more limited than other languages. Professional development events centered around the language are rare too.

## Students are unlikely to have had prior experience with Racket

With the growth of K-12 computing, an increasing number of students come to CISC108 with prior programming experience. Although this introduces a lot of pedagogical problems when you have students without experience, it's generally a good thing. One theory of learning is a progression of novices into competent practitioners, which requires time and experience. Ideally, courses should build on prior experience, not ignore it - this course diverges so heavily from prior experience that some students struggle to see connections, and the foundations laid in this course do not support subsequent courses. The hope that a novel experience "levels the playing field" is incorrect: students with prior experience will still adopt ideas of function calls, expressions, and atomic values and such more readily than their inexperienced peers. Better to separate students based on prior ability than to try to handicap good students unnecessarily (parallel sections are a strategy for this). Further, students will talk to each other and become aware of the inauthenticity of the course.

## Instructors are unlikely to have had prior experience with Racket

At a time when staffing classrooms is increasingly difficult, we need to lower barriers for new teachers. Since so few people use languages like Racket, the available pool of instructors is artificially lower than if a more popular and conventional language was used. Instructors who are called upon to teach Racket the first time not only have to learn how to teach novices (a complicated skill to develop), but also to learn an unfamiliar language.

## Racket's aesthetic beauty has limited relevance to CS1

Although senior programmers have a lot admire about Racket, the reality is that most of the problems in CS1 have nothing to do with how "pretty" or "elegant" a language is. The simple, consistent structure of Racket is nice, but it's still a system of rules for a student to learn. At the novice level, the students will not be more motivated by the "beauty" of the language because they do not have any perspective - all they see is parentheses and obscure words everywhere.

The argument has been proposed that Racket has a "simpler syntax" than other languages. However, this is only true on the surface level. Racket has a number of different syntactic forms that have to be integrated into students’ mental models: define vs. define-struct, cond expressions with their complicated clauses, local expressions, lambda expressions, the difference between functions and "constructs" (e.g., cond, define, or), etc. Each of these may be similar in some key ways, there is no reason to expect that they have no cognitive load. If the number of operators were the only factor that influenced student learning, then Turing Tarpit languages with only 8 operators would be used in more classrooms.

## Students do not use Racket again later in their degree

Unless going into very specialized courses, students are extremely unlikely to have another experience with Racket. This means that their introductory experience was heavily disconnected from their subsequent experiences - given the critical nature that time and experience plays into developing expertise, this is counter-productive to their learning.

## Students do not like Racket

Survey of students in CISC108 this fall (N=126/156=80.8% response rate, MOE of <4%).
62% like the course so far
76% like the instructor
75% comfortable with their classmates
71% want to take more CS classes
61% intend to major in CS (stable from start of semester)
22% like Racket so far
25% interested in learning more Racket

## Students do not carry their Racket experience Forward

Here is some data from a survey of 42 CISC320 students (predominantly Junior CS majors). Only a small number of students indicated they were comfortable and liked Racket - in an in-class informal survey, no students indicated that Racket was their most preferred language to use.

Specific, formal survey question (T/F style): "Please Indicate if you like and are comfortable with each of the following languages:"
Java: 93%
C/C++: 74%
Python: 38%
JavaScript: 21%
Racket: 7%

## Design Recipe Is Not Well-Evidenced

Despite being ten years old, there is relatively little research to demonstrate the value of “Design Recipes” as a pedagogical approach, especially one that has long term benefits. Kathi Fisler’s research indicates that students may be more prepared to apply principles of Functional Decomposition through this approach than students who do not, based on studies of the Rainfall Problem. Is this unique to using Racket? It’s a reasonable hypothesis, but not a proven fact. Beyond that, I can’t say there’s much research out there to support the bold claims made by the research group. When you dive into their literature, you will often find them citing the same set of small papers over the years. Even more frightening, there are folks citing their textbook or theory papers as arguments for the effectiveness of the research. Anecdotal evidence abounds, but a shockingly small amount of research has emerged from this pedagogical direction.

