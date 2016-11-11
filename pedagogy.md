#FVI's Pedagogical Philosophy

##Introduction

Our pedagogical approach is heavily research-based. Although at times we criticize Universities and their ivory tower mentality, it is undeniable that research universities are the cornerstone of Science and scientific advancement. It is, therefore, twice ironic that universities produce all this pedagogical science that they don't apply, and that we at FVI can use to our advantage to nurture our students to achieve higher mastery than a university ever could, all other things being equal (same students, same time investment).

We at FVI strive to remain cognizant that there is almost nothing that can truly be **known**. From an epistemological standpoint, all we can do is rely on the most widely accepted Science at the time. This pedagogical training guide is written based on research findings. Whenever a claim is made that is not based on research, it is disclosed as my opinion. In order to get the whole story behind what lies within this guide, you are free to follow this reading list:

* Thinking Fast and Slow by Daniel Kahneman  
* Make it Stick: The Science of Successful Learning by Peter Brown. [Book Summary Available here](https://docs.google.com/document/d/1FaaTw-0Qfg4_GxCWfmMQHMu8q0OCPjmKgCm4Fdtz74I/edit?usp=sharing).  
* Resources on [Bloom's Taxonomy of Learning Domains](https://docs.google.com/document/d/1pIBbh5Sv9NxMuOTE42Cy2SlPnB92J8kYe3UK9oCx74I/edit?usp=sharing)  
* Kirschner, Sweller, Clarke. *Why Minimal Guidance During Instruction Does not Work: An Analysis of the Failure of Constructivist,
Discovery, Problem-Based, Experiential, and
Inquiry-Based Teaching*. [Full Text](https://docs.google.com/document/d/1UUZRivcFroXOP75MIAEJDv3ihH33dpRGIuUPJeFVDng/edit)  
* [Brain Patterns in Software Development](https://www.youtube.com/watch?v=0o98iLlVDUw)  
* Lister, *After the Gold Rush: Toward Sustainable Scholarship in Computing*. [full text](http://crpit.com/confpapers/CRPITV78Lister.pdf)
* Duckworth, Angela. *Grit*

##The Goal of Teaching Anything

The goal of teaching anything should be to affect long term memory. Without affecting long term memory, no meaningful increase in skill is being accomplished. This is as close to a **fact** as we can get. All mastery comes from long term memory. This notion often generates cognitive dissonance because it's a trendy topic to discard memorization in favor of "critical thinking." It is our view, and the currently accepted notion in academia that critical thinking itself is based on long term memory.

What makes you able to think critically is being able to apply known solutions to problems in new contexts. That's it. Thus, these known solutions must be strongly committed to memory, and the critical thinking aspect of problem solving merely refers to building an intuition (ie. an ability for pattern recognition) of which known solutions to employ when solving a new problem.

The crux of mastery in any field is therefore twofold: memorize atomic solutions to tons of commonly faced problems, and develop the ability to recognize patterns in problems so you know which solution to draw on whenever you face a new problem. Thus, mastery requires having tons of things memorized and having an intuition for when to use which bits of knowledge. We can refer to this set of correlated abilities as the **problem-pattern** ability.

As it pertains to writing software, it is my opinion that there is one more requirement: the ability to scaffold multiple tiers of this problem-pattern ability. It is commonly said that the ability to "break down larger problems into smaller ones" is the crux of programming. I feel a better way to state this is you build up smaller problem-solution-pattern sets into larger ones. This is in line with the concept of "chunking" as it pertains to the study of memory. To give an example, a student may start by memorizing solutions to relatively small problems, such as traversing an array and building variables from other variables. Then, the student might build on this and memorize the pattern to build an aggregate value out of all values in an array. Then, the student might build on this by building an array of all values which fit a certain criterion. Simultaneously, the student might have built patterns for what an expressJS route is and how it may send back a simple string. **By steadily incorporating well known atomic patterns, the student will build progressively larger problem solutions schemas into their memory, until they reach a level where they have, fully in memory, very lengthy and complex patterns** such as a CRUD API and an Angular service that consumes it. This is the essence of mastery; this is the outcome we should (arguably) seek for ourselves as developers, and certainly this is the outcome we seek to coach our students to in FVI.

#How Memory Works

Memory is simple to understand. In order for things to be committed to long term memory, they need to be repeatedly retrieved from memory (over and over again). The act of listening to a concept, reading it, or otherwise viewing it a **second** time (once it has been seen before) has a marginal contribution towards memorization of nearly zero. In other words, reading or hearing the same concept from the same source multiple times does not help you memorize it or master it. What helps you memorize it is repeatedly retrieving it from memory, over and over. This works best if you retrieve the concept at spaced intervals. For instance, retrieving a concept from memory once a day, every day, for 10 days, will be far superior to retrieving it 10 times back to back in terms of its effect on long term memory encoding. In my opinion, it's possible that retrieval once a day every day for 10 days may even be superior to 20 or 100 times back to back on the same day.

In addition, memory compounds. It builds on itself. When we are novices, we need to memorize very elementary facts. To give the example of math, once we've memorized the tons and tons of minutiae (adding tables, multiplication tables, which axis is which on the Cartesian plane, order of operations, etc.) we can build on this minutiae and memorize how to solve and graph equations. Once we have that, we might learn how to compute the monthly amortization cost of something based on a specific amortization schedule. It's the same with every field. A chess player starts by memorizing and becoming intimately familiar with the way each piece moves. Before significant progress can be made, they need to be so intimately familiar with at least a few pieces, that the possible moves jump out at them almost involuntarily. Then, chess players build on this knowledge bit by bit until they get to the point that they can glance at a board for 0.5 seconds and memorize the whole board position. This doesn't happen because they have uncannily fast eyes or gifted memories. This happens because when a chess player looks at the board in a professional chess match, they don't see 64 pieces. They see "oh, this is move 5 of the Ruy Lopez opening, white plays." That's pretty easy to remember. We need to get our students to the point that they have as many as possible of these large foundational chunks of computer science which are important to front end programming. It is imperative that we don't waste time with anything that doesn't contribute to this goal.

#The FVI Student

At FVI we serve non-traditional students. Let's face it, if you have incredible grit and desire, you can learn anything on your own from the Khan Academy. You don't need teachers. Our role at FVI is to provide students with a *service*. The scope of this service is twofold: motivation and coaching of mastery.

#Maintaining Motivation

Non-traditional students oftentimes have low self confidence and a very limited growth mindset. It is precisely because of this that one of the most important components of our job is to motivate students. Although it is undoubtedly important to motivate students by offering positive reinforcement and "growth mindset feedback" (feedback that lauds effort rather than achievement), there is another way to motivate students that has a longer lasting effect. If we make our curriculum *fun*, students will have more interest in the subject matter and be more likely to make it past the beginner phase. That is the main reason we use a project based approach to continually challenge students.

It is of utmost importance that anything we do in the classroom and any changes we make to the curriculum bear in mind any possible repercussions on students in terms of helping them maintain interest on the subject. Our job is, then, to essentially trick students into learning enough that they get past the beginner phase as web developers.

In sum, helping students to maintain interest on the subject matter is paramount to our success.

#The FVI Approach to Coaching Mastery

The biggest pitfall of k-12 and college education in the Western World is its mistaken belief in "mastering" one concept before moving on to the next. The word "mastering" is in quotes because being able to solve many equations of the line does not mean that lines have been mastered. It doesn't even mean the student understands lines or can easily graph them, or that they can even shift a line along either axis or visualize them in R3 (3d space). The reason for this is that this type of sequential learning (emphasizing repetition of the same kinds of exercises over and over before moving on) focuses too much on building the problem-solving schemas but not enough on building the pattern recognition schemas which train the student in recognizing when these problem-solving schemas are called for. In other words, this type of sequential learning focuses too much on the "problem" side of building problem-pattern ability, while giving no attention whatsoever to the "pattern" side of it. The main reason this ends up not working well is that by the time students get to training their pattern recognition abilities, their problem-solving schemas have been long forgotten. This results in very low time efficiency. You have to learn a bunch of things, completely forget them, then start learning the problem patterns and have to learn the forgotten things again from scratch.

Our approach at FVI is to consistently apply, apply, apply. We teach a few problem-solving schemas and then show them being applied in several real-world-like scenarios. We then introduce one more problem solving schema and apply it in real-world-like scenarios alongside other older ones. We continue to do this over and over again, reinforcing the problem solving schemas as often as needed. At the core of our teaching style lies the truth that students do not learn what you teach them, they only learn what they learn. Thus, they must see batteries of real-world problems where you fill in their problem-pattern gaps just enough so that they can solve the problem without struggling to the point that flow becomes impossible.

It my opinion that this is significantly more effective and time-efficient than spending large amounts of time on basic topics before moving on. Certain students will never truly grasp arrays and loops regardless of how many canned, atomic exercises they see. It isn't until they have seen the problem in a more real, relatable context that they will finally achieve profound understanding, if they ever do at all.

Because of our goals and the nature of long term memory, we at FVI have developed a highly taxing introductory module (6 weeks) where students are exposed to the biggest, most important concepts of web programming: all JS syntax, arrays, objects, AJAX, the DOM, DOM manipulation, the request/response model, server routes, server sessions, classes (within the context of object oriented programming), prototypes, methods, some tooling, and a few more. The goal of the program is to continuously bring back these concepts again and again, almost every week, so that students may eventually master them.

True mastery takes between 5 to 15 thousand hours, depending on innate ability. It is physically impossible that our students will be masters by the time they are done with our nine month program. The good news is that bachelors degree holders are far from masters also, since they have only taken about 18 Computer Science classes (each of which demands about 5 hours of study per week for 14 weeks). This amounts to roughly 360 hours of general coding practice, all of it dealing with broad-based concepts rather than specific web development techniques and web development problem-pattern chunks. Of course, there is additional coursework such as calculus and physics which adds to problem solving ability. In addition, bachelors degree students benefit from a slower pace of learning, which aids retention. All in all, however, it should be possible for our students to **destroy** a bachelor's degree holder in terms of job market value.

And thus, our focus must be on job market value. We need to aim for mastering one way of doing things in the web, not being fluent with all possible workflows. We need to get our students to the point where if they become employed, they're going to sit down and produce much faster than an average bachelor's degree holder who needs to watch 10 hours of udemy per feature they implement because they don't know shit about anything in full stack development. We need to focus on productivity and understanding of concepts, not on knowing every little shitty npm package like lodash or every little bit of useless syntax that doesn't actually enable you to do anything new.

More details pertaining to the reasoning behind and methodology we follow can be understood by reading the [document about attaining peak performance](peak.md)

#Bloom's Taxonomy of Learning Domains

Bloom's Taxonomy of learning domains refers to the steps that students must go through before mastering a concept. The first, most elementary level of learning is being able to regurgitate factoids. Then comes the ability to paraphrase, then apply the knowledge in a slightly different context, and so on. At the end, the last step in the ladder is having understanding so profound that you can make value judgments about which techniques might be better than which others in which situations.

I find Bloom's Taxonomy to be a supremely useful construct but it's level of detail is too high. I believe that the main message of Bloom's Taxonomy of learning is that there is a spectrum between verbatim regurgitation of facts and profound, sage understanding. Being able to apply concepts in new situations or create your own applications based on known concepts is near the middle of the spectrum. This is where we can and must help students get to. By engaging in apprenticeship teaching as we do, we individually nurture each student's problem solving schemas and we show them how we think and how we work so that they learn to emulate our pattern-recognition abilities. By seeing us work, they will be able to see the patterns to how we think and start being able to incorporate some of those patterns into their own thinking.

#How to develop the memory-pattern ability

Incrementally and simultaneously. We don't work on a million problems first and then work on a million projects. We work in layers, not sections. The intro modules (6 weeks) lays the first layer with all the concepts bombarding the students in quick succession. The next 5 modules repeat the same concepts, adding a few things here and there, with the instructor attentively helping each student master the concepts that each student is lagging behind in. The fact that we do "project based learning" is by no means to be construed as authorization for hands-off instruction. The instructor must be very engaged and assertively impose his/her help on students in order to facilitate the best use of their time. The ultimate goal is that students find some order in which they can get to the higher levels of Blooms in several problem-pattern chunks that pertain to full stack web development.

#Flow

It my opinion that the correct way to learn entails the pursuit of mastery. The pursuit of mastery, in turn, is executed by working just at or near the border of one's comfort zone. The state of elatedness arising from creating something new and substantive, also known as *flow* is only possible if we tackle problems within this range. Problems that are too easy produce little excitement and problems which are too hard end up being too slow to be solved (thus, they produce equal amounts of frustration and joy, and not enough joy per unit time). In either case, the pleasure of flow is not accomplished.

It is also my opinion that the notion that *all* developers constantly look things up is mistaken. This is only true of non-masters. Sadly, the industry has evolved in such a way that most programmers find themselves hopping bandwagons so frequently that they do not allow themselves the time required for any significant mastery to develop.

A true master seldom has to look things up, and when they do, it's some minutia rather than an actual problem solution. Though admittedly this view is quite controversial, it is our institutional view at FVI and it is one of the guiding principles behind our teaching philosophy. The rationale for this belief stems from the following line of reasoning. Much of the world's software was written in times before the internet, when people had to solve their own problems. Although its influence has unquestionably shrunken by now, as of 2009, the fifty-year-old legacy language COBOL [powered 200 times as many transactions every day than Google searches](https://blog.codinghorror.com/cobol-everywhere-and-nowhere/). In speaking to grizzled programming veterans, it became evident that in the old world each programmer had to become a master of their own style of problem solving. Each programmer built their own problem-pattern chunks and carried around mini-libraries of code to call on whenever faced with complex problems. Now that we have the internet and package managers like npm, the only thing that's changed is that we no longer need to build our own implementations of each problem-pattern chunk. This allows us to tackle a higher level of abstraction sooner in our careers, but the basis of mastery is still the same. Mastery is determined by the size, number and robustness (in terms of how many different contexts they have been tested in) of your problem-pattern chunks.

A beginner can easily spend 900 hours working and practicing but not advance much in skill, since a significant percentage of those 900 hours will be spent being stuck. **A very pivotal part of our job as instructors is to maximize the time each student spends in a state of flow.**

#Grit
  > "Even the most accomplished of experts start out as unserious beginners"  
  > "For now, what I hope to convey is that experts and beginners have different motivational needs. At the start of an endeavor, we need encouragement and freedom to figure out what we enjoy. We need small wins. We need Applause. Yes, we can handle a tincture of criticism and corrective feedback. Yes, we need to practice. But not too much and not too soon. Rush a beginner and you'll bludgeon their budding interest."  
  > Angela Duckworth, Grit

Although we definitely need to only admit students whose life experience has given them some grit, our curriculum and philosophy needs to be such that the least gritty of our students are nurtured. There will be *some* mistakes made; there will be *some* students who enroll in our program lacking the right combination of grit, free time, and talent. These students could amount to 10-20% of students and are unsalvageable. But when it comes to any student who does have the requisite natural gifts to succeed, and who doesn't have a pathological lack of grit (evidenced by 90%+ attendance), if we leave them behind we have failed.

Grit is not fixed. You can develop grit through a process, the first step of which is to stay motivated long enough to the point where a non-negligible amount of skill has already been developed. Once you can build or design stuff you're excited about, it's likely that enthusiasm will be more self-sustaining. Again, to this end, we design our curriculum with fun in mind. Advanced students can and should be encouraged to add features to any project and make them work across all devices. For this reason, the curriculum and projects should be chosen with the bottom half of the salvageable students in mind - since it's so easy to just add features to a project.

#The Struggle

Many professionals, especially ones with technical backgrounds,  mistakenly believe that anything worthwhile must be grueling. This is simply not true.

The following graph is taken from the book Grit, with the colored stuff added by me:

![skill-vs-time.png](Skill vs Time)

The black back refers to someone who consistently practices in the area of flow. The light grey refers to someone who quits early, and the medium grey curve refers to the person who stays in mediocrity forever (because they don't practice in the area of flow). This last one is the typical dude who's been going to the gym for 22 years and still barely benches 225 with partial range of motion, or the gal who's been running 4x a week for 14 years and still can't break an 8 minute mile. The purple and magenta curves are the constant switchers who try things and switch super fast.

When it comes to programming, the easiest way to be in the purple or magenta curves is to tackle too much to soon. There's an over-abundance of learning resources that teach CS the wrong way, not making it fun and focusing way too much on problems that are way too difficult for someone who's still just learning syntax. Our curriculum at FVI is built to avoid this and **if you experiment and modify our curriculum, you are required to maintain or improve the fun aspect.**

Our job is to get **all** of our viable students (those outside the unsalvageable bottom 10-20%) to stay on the solid black path until that 900 hour mark. This must be accomplished at all costs.

#Developing Effective Assessments

The key to assessments is frequency and variety. Ask questions on related concepts with different formats (multiple choice, short answer, free response, work problem), and do so frequently. The more frequently you assess, the better.

One idea I'm working with that seems to be producing excellent results is making the exam available to students 2-3 days before they have to take it, but focus on free response and code questions and make it closed book and closed notes. By allowing students time to review, memorize and later on come and retrieve the memories during the exam, we should in theory achieve superior learning.

The main pitfall to this technique is that if you have questions that are too simple, or too many multiple choice questions, students will study the test rather than the knowledge.

#Developing Effective Lesson Plans

Although this will vary widely by topic and course, as a rule of thumb we should be spending 25% of the time lecturing and 75% applying (by way of project or assessment).

The lecturing component may sometimes be curated but do not pull from the same resource too frequently, as this will devalue our program. Also, the ideal lecture starts with a well thought-out open-ended question (or personal anecdote) that can engage our students.
