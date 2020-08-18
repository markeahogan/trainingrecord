# You Dont Know JS 13/06/19
https://github.com/getify/You-Dont-Know-JS/blob/master/README.md

Its a few years old (2015) so some of the "in the future" stuff is the present now, it doesn't teach web development at all, but for going from 0 to being able to understanding code (and kata) written in javascript its awesome, the authors tone's good, he repeats a chunk of book 5 in book 6 and he likes to make up terms by melding words together

*7 thumbs up*

# Managing Humans: Biting and Humorous Tales of a Software Engineering Manager by Michael Lopp 27/06/19
His style didn't gel with me. Worst offenders to me were he labels _everyone_ (person A is a Chatty Patty, person B is a Translator Tim), he spent a paragraph explaining without sarcasm how he judges resumes _by their fonts_, and spent and an _entire chapter_ describing how he gets into "the zone" and that coworkers (and loved ones) should rightly expect an aggressive reaction if they interrupt.

Positive messages were if you don't follow up on things you say you'll do you'll erode your credibility, listen carefully to people's concerns especially if they're panicked and babbling and try to treat any change as an opportunity, and it's not overly long

*1 thumbs up*

# JS for impatient programmers (except the quizzes) (as recommended by @alan) 08/07/19
https://exploringjs.com/impatient-js/index.html

A good guide starting from basics to advanced features, everything it teaches you is presented as unit tests which is reassuring.

It covers a chunk of ES6 in much more detail than YDKJS and includes bits that YDKJS missed out on (like async) but goes into slightly less detail on the (pre ES6) mechanisms behind it.

Most chapters end with a reference guide for whatever feature it was about which no one will ever use as reference because online docs are much better but sometimes as a listing it's useful for finding out about methods you didn't know a type had.

*9 thumbs up*

# Clean Code: Writing Code for Humans (as recommended by @peterlaw) 10/07/19
https://www.pluralsight.com/courses/writing-clean-code-humans

Covers much of the same ground as Robert C Martin's Clean Code and cites it several times, with a little bit of uncited Pragmatic Programmer thrown in at the end

All the advice is useful (maybe even essential) and should be applied when working on code you expect anyone else to read (including yourself a week from now)

The demo is the weakest part of the course, it's very improvised, I think he should have rehearsed it.
Its 98% language and paradigm agnostic with a 2% swing to object oriented and c#

*8.5 thumbs up*

# Clean Architecture by Rob Martin 16/07/19
https://www.amazon.co.uk/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164

It focuses on how to split your code into logical dlls/processes/services using layered, domain and feature led approaches.
Encourages use frameworks to make your life easier but stresses the importance of separating _your_ code (especially business logic) from frameworks.

It make selective arguments against dogmatic YAGNI (which fits with my interpretation that it applies more to features than architecture and a little anti-YAGNI for clean code and architecture's sake is expected).
It makes a argument against dogmatic DRY, suggesting that 2 similar things in different domains that may look like they violate DRY don't count as DRY doesn't apply across domains (they change at different times for different reasons and have no logical dependency on one another)

Applies SOLID principles to software components with the aim being to create plugin architecture
Code is mostly Java but the thought process is applicable to any OO language.

Encourages a layered approach where the core logic operates without knowing implementor details beyond its domain (using interfaces and dependency inversion for ui, data persistence, input, output etc.).

The outermost layer ends up being the a "dirty" Main function responsible for constructing instances of concrete implementations before handing over to the clean core logic, I think it can be interpreted as Main being a _code is data_ style app configuration.

Chapter 34 is "The Missing Chapter" by Simon Brown, a more intense (less jovial) chapter on various techniques/methods for partitioning code, which also promotes a _private by default_ approach to all software components (internal in C#), this chapter felt like a slog to me because it over explains trivial differences between near identical techniques.

The book ends at 65%, last 35% is index, code snippets and anecdotes (quite enjoyable including the origin of 'Uncle Bob', some are familiar if you read clean coder).

_Clean Code_ is still his best book I've read

*8 thumbs up*

# React: Getting Started 20/07/19
https://app.pluralsight.com/library/courses/react-js-getting-started

Good explaination of what all the fuss regarding React is about. It's got 2 examples you'll reproduce in an online editro at jscomplete/playgraound which is a decent way to get started as you dont need to setup your environment. He says at the start and it's you'll need to pause a lot, he does talk fast. He assumes you're a web developer who is now learning React, you need to know javascript before starting this as it says in the prerequisites but I also found myself needing to more about HTML so I would recommend diong HTML and CSS courses before this one

*8 thumbs up*

# Creativity Inc by Ed Catmull 31/07/19
https://www.amazon.co.uk/dp/B00GUOEMA4/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1

It goes into a lot of detail about how to manage a company in a way that encourages honesty, creativity and mitigates fear of failure (how to build a Pixar). He goes through his principles, explains them with metaphors, then rewards your reading efforts with a story about Pixars struggles related to that principle. The stories end up in roughly chronological order so you get a good sense of the history of the company from the 1980s to 2010s. All his principles are good and deeply true but require a decent chunk of courage to apply constantly.
It ends with an homage to Steve Jobs and a summary of the key principles.

*9 thumbs up*

# HTML5 Fundamentals 05/08/19
https://www.pluralsight.com/courses/html5-fundamentals-2e

Decent course which, for me, demystified the modern features of some web apps. Covers finding parts of the DOM, input validation built into the browser, video and audio playback and drag and drop file uploading, as well as a detailed look at canvas for 2D drawing. It starts with an html focus for about 20% then the last 80% is almost entirely Javascript code acting on response to html. The main takeaway I got from it is that some parts of web dev that I expected to be time consuming are actually already built in to browsers ready to use.

*7 thumbs up*

# Introduction to CSS
https://www.pluralsight.com/courses/css-intro

Covers css history, selectors, fonts, boxes and layouts. Its a thorough introduction and as css is entirely new to me it had the most insight of the recent courses I've been through. I was surprised and disappointed when it ended as the last chapter on layouts seemed quite haphazard and I was expecting a "heres the right way to do it" chapter to come next. Overall though for an introduction it definitely delivered. The 4:3 aspect ratio was distracting.

*8 thumbs up*

# CSS Positioning 
https://www.pluralsight.com/courses/css-positioning-1834

Pretty short one, 50% was covered by Introduction to CSS, the other 50% had plenty of useful information about how centering works.

*8 thumbs up*

# Play by Play: HTML, CSS, and JavaScript with Lea Verou
https://www.pluralsight.com/courses/play-by-play-lea-verou

A bit old (2014) but very interesting to see someone using the equivalent of ES2015 classes using IIFEs amd closures, the resulting code looks very similar (she also implemented a mini JQuery). It was interesting and sometimes frustrating to watch but I learnt a decent chunk from it and would recommend it for now, though I'd keep an eye out for a newer equivalent.

*7 thumbs up*

# Reintroduction to Javascript 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript

As you'd expect its an extended article that covers the language from absolute basics up to the harder to grasp concepts that relate to using the basics.

Much is covered in previous books and in far greater detail but this one especially helped me understand how the _new_ keyword works, I was able to write my own version of _new_ and the article gives an alternative implementation of _new_ as well.

It was well worth reading just for _new_

*8 thumbs up*

# React Fundamentals
https://www.pluralsight.com/courses/react-fundamentals-update

Very good React course, it starts with the basics of React function and class components and builds up with additional libraries. It touches on Bootstrap and gives a decent explaination of React Router and a very good explaination of Redux and React-redux. It helped to understand that Redux is a library for observable state and React-redux builds on that by allowing state to be mapped to props automatically.

*9 thumbs up*

# Leadership and the One Minute Manager

Very entertaining, it teaches it's concept of Situational Leadership as an extended conversation between a few characters. It starts by outlining  four leadership styles; *directing, coaching, supporting and delegating*. It follows by describing four levels of development and what leadership style to use at each level of development, e.g. For someone inexperienced a directing style should be used, delegation should be used for experienced people. It then describes how to work with a person to agree their development level and what leadership style should be used for the required goal, and to maintain nn honest and fluid leadership style.

The book labels/groups people by their development, which is their competence and commitment. While it's overly simple I can see how these two qualities encompass a good chunk of the information a manager needs to perform, and they are quite measurable.

I was very engaged with its teachings and I hope I can use these in my work, by agreeing what support someone expects from me and agree to how much direction is needed very early on and following through on this, fluidly adapting as agreed.

*9 thumbs up*

# The Mythical Man-Month by Frederick Brooks

The book is presented as a series of 19 essays about managing software teams and construction. The original edition was published in 1975 the majority of the book is hilariously dated, many of the essays cover topics that have been made obsolete by modern techniques. There are however 6 essays that are applicable the development today 1, 2, 11, 14, 18 and 19.
These contain insights into why adding more developers to a late project makes it slower, making prototypes, day to day scheduling handling setbacks followed by a bullet pointed summary and reflection of all chapters.
I would recommend it but only reading those 6 essays, the others are only interesting for historical reasons.

*7 thumbs up*

# Code Complete by Steve McConnell 07/12/19

Book touches practically all aspects of 'code construction'; design architecture, patterns, composition, inheritance, complexity. It's littered with humourous quotes and research data to back up it's teachings.

It goes into great detail on core details (stuff I thought so small it wouldn't have been possible to have a strong opinion on) e.g. chapters dedicated to ints, bools if/else, enums, consts.

The final few chapters echo pragmatic programmer, clean code and clean coder, they explain a bit of programmer psychology and how it affects code, followed by the traits and habits of the best coders and a required reading list for working at his company.

I can guarantee that every developer will learn something from this book, simply because there is a mountain of information in its thousand pages, but only about 10% to 20% of it composes the essential facts.

I suggest reading it in order, but read the first paragraph of each chapter to decide if you want to continue with it. Every chapter ends with a bullet point summary so if you dont choose immediately to read it read the summary (and re-evaluate) before moving on.

*8 thumbs up*

# Full Stack Open 2019 by University of Helsinki 08/01/2020
https://fullstackopen.com/en/

A comprehensive but certainly not exhaustive course on full stack web development. Its 145 exercises spread over 9 parts cover Javascript (but expects a little JS knowledge already), React, Redux, Node.js, Express servers, MongoDB, CSS and GraphQL in roughly that order. By the end of the course I'd learned plenty but felt it had barely scratched the surface of the subject, given how wide and fast moving the subject of web development is. 

It took me 125 days start to finish and about 117 hours, there's an exam but it's only available to University students/persons with a Finnish social security number, you get a certificate once you've completed it.

![My certificate](https://i.gyazo.com/2eee0a89f847fa04d80daa23ad2a7600.png)

*8 thumbs up*

# Traction by Gino Wickman 26/01/20

Descibes a series of processes that it calls the EOS (Entrepreneurial Operating System), a system that we are assured will result in growth and success for your business. While it has some very good advice the book doesn't present (to me) a lot of new insights, however it has great value providing a common process and language (with many, many acronyms) so that all members of a team (who have also read the book) routinely know what to expect amd whats expected of them.

Sometimes the book uses a page of text to describe what it successfully did in thr first sentence, I ended up having to re-read pages at a time when this happened because the remainder of the page didnt sink in first time around. I think I'll have to re-read the book to cement thr acronyms in my memory. It cites only US SMEs as examples of the processes success which makes me wonder how or if it's been applied to software development.

*7 thumbs up*

# CLR via C# by Jeffrey Richter

# Refactoring: Improving the Design of Existing Code by Martin Fowler

# Mastering Regular Expressions by Jeffrey Friedl 03/08/20

# How To Write Unmaintainable Code by Roedy Green 07/08/20

# The Subtle Art of Not Giving a F\*ck by Mark manson 17/08/20
