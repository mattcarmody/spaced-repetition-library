# Spaced Repetition Library
A hub for literature related to spaced repetition and using it well. Contributions encouraged.

## What is spaced repetition?

Spaced repetition systems are flexible tools for remembering just about anything.
As learners, we often put a lot of time and effort into learning something new. We read, watch and discuss new material, relating it to what we've learned before. Then we usually move on to the next thing and hope we remember it.
The goal of spaced repetition is to make memory a choice, to be a tool that we use to choose what we want to remember. And to remember it with as little effort as possible.

For more depth, check out this early feature on the creator, [Want to Remember Everything You'll Ever Learn? Surrender to This Algorithm](https://www.wired.com/2008/04/ff-wozniak/). Or check out this comic, [How to Remember Anything Forever-ish](https://ncase.me/remember/) walking through the concept.

## What does it look like practically?

Spaced repetition systems look like mini daily flashcard quizzes.
Whenever I learn new material, I create question & answer flashcards for whatever I want to remember.
Then I let the system keep track of the material and I check back daily to do the maintenance it recommends.

Once a day I sit down and do my daily reviews, like a quiz.
The system keeps track of what I remember well and what I don't. It queues up the material that it thinks I'm on the verge of forgetting and quizzes me on it.
It walks me through cards one at a time.
For each card it shows me the question, I think about the answer... then reveal it. Crucially, I tell the system if I got it right or wrong.
The system then makes a choice. If I know the answer the system schedules the next review further out into the future. If I don't, the system queues it up soon.
This means I don't have to review all that many cards a day, only the stuff I'm at risk of forgetting.
Shockingly, this way I can maintain tens of thousands of cards in only 10-15 minutes a day!

Now I'm done for the day, I'll be back later if I learn something new or I'll be back tomorrow to do those daily reviews.
If I miss a day I'll have a larger review load, but I can catch up all at once or gradually, not the end of the world.
It's become a foundational habit for me, I think of it as mental training. It's common to do physical training or exercise, this is a mental analogue.

## What do people use it for? Applications

#### Language Learning

A common use case for spaced repetion, there are many resources to be compiled here. Examples include vocabulary translations, pronunciation trainers, listening practice, grammar rules, reading comprehension, etc. There are many apps dedicated to language learning that incorporate SRS: Fluent Forever, Skritter, Duolingo, Memrise.
Books have been written that incorporate SRS into the language learning process:
[Fluent Forever](https://fluent-forever.com/book/) by Gabriel Wyner, 2014. [Fluent in 3 Months](https://www.fluentin3months.com/book-us/) by Benny Lewis, 2014

#### Medical School

[r/medicalschoolanki](https://www.reddit.com/r/medicalschoolanki/) - medicine is arguably the most codified complex subject matter with widespread SRS use. there are many high quality resources dedicated to using SRS to study for medical school, this community is dedicated to doing so with Anki

#### General Knowledge

There are many freely available decks that are used to commit general knowledge to memory. Countries on a map, capitals, flags, world leaders, periodic table elements, great works of art, birds, NATO phonetic alphabet, Olympic host cities, etc.

#### Computer Programming

[Memorizing a programming language using spaced repetition software - Derek Sivers](https://sive.rs/srs) - concise overview on the concept and making it a core habit, applies it to language learning and computer programming

Janki Method - Using SRS to Improve Programming - Jack Kinsella [Part 1](https://www.scribd.com/document/593160890/Janki-Method-Using-SRS-to-Improve-Programming-Jack-Kinsella?v=0.230) (original article appears to be lost, hence Scribd) [Part 2](https://www.semicolonandsons.com/articles/janki-method-refined) and [Part 3](https://www.youtube.com/watch?v=kshXDo8psj8) - the author's summary of their approach to improving their programming ability, which they gradually refined

[Execute Program](https://www.executeprogram.com/) - a site with programming courses that seem to include spaced repetition of the material

#### Classroom - older children / teens

Seven Years of Spaced Repetition Software in the Classroom (high school)[Year One](https://www.lesswrong.com/posts/Ww2dxwWpSfkQB4NZb/a-year-of-spaced-repetition-software-in-the-classroom) & [Year Two](https://www.lesswrong.com/posts/dtCfxYubZgRnEkGpQ/a-second-year-of-spaced-repetition-software-in-the-classroom) & [Year Seven](https://www.lesswrong.com/posts/F6ZTtBXn2cFLmWPdM/seven-years-of-spaced-repetition-software-in-the-classroom-1). Piotr Wozniak, founder of SuperMemo and SRS pioneer, shared thoughts on the article in [Spaced repetition does not work in a classroom](https://supermemo.guru/wiki/Spaced_repetition_does_not_work_in_a_classroom).

[A year of Anki in my Classroom](https://www.reddit.com/r/Anki/comments/1s4v9nf/a_year_of_anki_in_my_classroom/) - a teacher describes their informal experiment with SRS in their classroom, noting a correlation between Anki use and academic performance

#### Young Children's Education

[CoffeePie's interview with Chris Lakin](https://chrislakin.blog/p/spaced-repetition-for-teaching-two) / [Cross post on LessWrong with discussion](https://www.lesswrong.com/posts/2PLBhCbByRMaEKimo/spaced-repetition-for-teaching-two-year-olds-how-to-read) / [Cross post on HackerNews with discussion](https://news.ycombinator.com/item?id=38427034) / [Cross post by Andy Matuschak](https://notes.andymatuschak.org/z3YDGbq68pHnAkpo9bjKFZg) - experience from a father raising two young children and using Anki to practice reading and math.

#### Miscellaneous domains

Trivia: some Jeopardy contestants have been known to use SRS. For example, [Roger Craig](https://wiki.openhumans.org/wiki/Spaced_Repetition:_A_Cognitive_QS_Method_for_Knowledge_Acquisition)

Math: [Using spaced repetition systems to see through a piece of mathematics - Michael Nielsen](https://cognitivemedium.com/srs-mathematics)

Quantum Mechanics: [Quantum Country](https://quantum.country/) - an experiment in teaching quantum mechanics through a custom essay/spaced-repetion format

[Incremental Reading - Piotr Wozniak](https://supermemo.guru/wiki/Incremental_reading)

[Memorizing My Days](https://wiki.openhumans.org/wiki/Memorizing_My_Days) - Steven Jonas explores using SRS to remember the interesting things that happen over the course of his daily life

[Spaced Listening](https://wiki.openhumans.org/wiki/Spaced_Listening) - Steven Jonas needs a few listens to enjoy an album, heexperiments with using spaced repetition to schedule his listening

Personal info: birthdays, names, etc.

## What are some examples? SRS Implementations

General Purpose systems: [Anki](https://apps.ankiweb.net/) is a general purpose, mostly free, mostly open-source SRS system. [SuperMemo](https://supermemo.guru/wiki/SuperMemo) - an early pioneer of SRS, mostly paid and proprietary system. [Mnemosyne](https://mnemosyne-proj.org/) is a general purpose SRS. [Quizlet](https://quizlet.com/) is an education-focused SRS app. [Cerego](https://www.cerego.com/) - seems to be a general purpose SRS w/ an AI component. The [Leitner system](https://en.wikipedia.org/wiki/Leitner_system) is a rudiementary, analogue paper slips SRS.

Language learning systems: [Memrise](https://www.memrise.com/) is a language learning app incorporating SRS. [Fluent Forever](https://fluent-forever.com/index.html) is a subscription language learning app built with spaced repetition and other core concepts from Gabriel Wyner's book of the same name. [Duolingo](https://www.duolingo.com/) is a popular, freemium langauge learning app that incorporates SRS concepts, though it is not strict in review schedule and inflexible. [Skritter](https://skritter.com/) is a Chinese and Japanese language learning app with SRS built in.

## Why does it work? Underlying concepts

[Forgetting curve](https://en.wikipedia.org/wiki/Forgetting_curve) - a hypothesized/measured plot of the rate that memories degrade over time when no attempt is made to retain it

[Spacing effect](https://en.wikipedia.org/wiki/Spacing_effect) - phenomenon that spaced out practice is more effective for long term retention than cramming (massed practice)

[Testing effect / Active recall](https://en.wikipedia.org/wiki/Testing_effect) - phenomenon that testing one's memory enhances the long term retention of information

[Generation effect](https://en.wikipedia.org/wiki/Generation_effect) - psychological phenomenon where information is better retained in memory if it is generated by one's own mind rather than simply read. it has been suggested it is beneficial even if the generated answer is wrong

[Varied practice](https://en.wikipedia.org/wiki/Varied_practice) - using a training schedule that frequently changes the task at hand, which has been shown to enhance long term retention in many domains

[Transfer of learning](https://en.wikipedia.org/wiki/Transfer_of_learning) - does knowledge rehearsed in SRS translate to real life or other domains? is it good for more than regurgitating facts?

For a long form work that looks at much of the research on strategies to aid learning and long term retention, there is [Make It Stick: The Science of Successful Learning](https://www.goodreads.com/book/show/18770267-make-it-stick) by Brown, Roediger III & McDaniel, 2014.

## How do people use it well? Essays from power users

[Augmenting Long-term Memory - Michael Nielsen](https://augmentingcognition.com/ltm.html) - starts with an overview of how the author uses Anki. They walk through how they read a seminal research paper to become familiar with a new field, followed by their best practices for Anki use. Later they talk about memory systems generally.

[Spaced repetition for effective learning - Gwern Branwen](https://gwern.net/spaced-repetition) - an overview of the concept and research literature with some discussion of practical use

[Effective learning: Twenty rules of formulating knowledge - Piotr Wozniak](https://www.supermemo.com/en/blog/twenty-rules-of-formulating-knowledge) - a widely read write up from the creator of SuperMemo on using SRS well

[How to write good prompts: using spaced repetition to create understanding - Andy Matuschak](https://andymatuschak.org/prompts/)

## What next? Thinking about the future of SRS

[How can we develop transformative tools for thought? - Michael Nielsen and Andy Matuschak](https://numinous.productions/ttft/#improving-mnemonic-medium)

[Open Spaced Repetition](https://github.com/open-spaced-repetition) - a group researching and developing spaced repetition algorithms

## Where do users talk about it? Communities

[r/Anki](https://www.reddit.com/r/Anki/) - a subreddit dedicated to Anki discussion

[r/medicalschoolanki](https://www.reddit.com/r/medicalschoolanki/) - a subreddit dedicated specifically to use of Anki in medical school

## Other libraries

Gwern's [literature review](https://gwern.net/spaced-repetition#literature-review) - 2019

Gary Wolf's [SRS compilation](https://quantifiedself.com/blog/spaced-repetition-and-learning/) - 2012

A redditor's [compilation](https://www.reddit.com/r/Anki/comments/ujzjgq/a_compilation_of_introductory_articles_to_spaced/) - 2022
