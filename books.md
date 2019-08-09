# You Dont Know JS 13/06/19
https://github.com/getify/You-Dont-Know-JS/blob/master/README.md
Its a few years old (2015) so some of the "in the future" stuff is the present now, it doesn't teach web development at all, but for going from 0 to being able to understanding code (and kata) written in javascript its awesome, the authors tone's good, he repeats a chunk of book 5 in book 6 and he likes to make up terms by melding words together
GitHub
getify/You-Dont-Know-JS
A book series on JavaScript. @YDKJS on twitter. Contribute to getify/You-Dont-Know-JS development by creating an account on GitHub.
*7 thumbs up*

# Managing Humans: Biting and Humorous Tales of a Software Engineering Manager* by Michael Lopp 27/06/19
his style didn't gel with me.
Worst offenders to me were he labels _everyone_ (person A is a Chatty Patty, person B is a Translator Tim), he spent a paragraph explaining without sarcasm how he judges resumes _by their fonts_, and spent and an _entire chapter_ describing how he gets into "the zone" and that coworkers (and loved ones) should rightly expect an aggressive reaction if they interrupt.
Positive messages were if you don't follow up on things you say you'll do you'll erode your credibility, listen carefully to people's concerns especially if they're panicked and babbling and try to treat any change as an opportunity, and it's not overly long
*Half a thumbs up*

# JS for impatient programmers (except the quizzes) (as recommended by @alan) 08/07/19
https://exploringjs.com/impatient-js/index.html
A good guide starting from basics to advanced features
Everything it teaches you is presented as unit tests which is reassuring.
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
