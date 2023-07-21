# User Stories Are Not Requirements

"Elephants are not giraffes and user stories are not requirements. They share some traits and you may find them in the same context, but that does not make them the same."[^elephants-are-not-giraffes] This article gets into the differences between user stories and requirements and the challenges of using user stories as requirements in support of the main article about [my proposed requirements framework](./why-use-cases-for-agile.md).  

> In the following there are a number of quotes with references to other articles on this topic. I recommend reading all the linked articles to get an even more detailed case against stories as requirements.

Fundamentally user stories are not about what you write down. Their origin is as a placeholder for a conversation with the users, written down on an index card. The goal of a user story is to enable us to understand what is really needed and implement it. That kind of common understanding between the user and the product team is prioritized over a perfect requirements specification written up-front as a story. This is also why the Agile manifesto contains the line:'Customer collaboration over contract negotiation'. What you initially agreed upon is less important than what you’re trying to achieve. [^common-understanding]

Agile is making two bets at the beginning of a project[^two-bets] :
- Given the desire for a fixed schedule, the scope will flex so you don’t want to call anything *required*, especially up front.
- As the project progresses and the users see the software come into being, the desires of the users will change.

    [^elephants-are-not-giraffes]: See [User stories are not requirements](https://blog.crisp.se/2016/01/07/perlundholm/user-stories-are-not-requirements)

    [^common-understanding]: This paragraph is a quote from [User Stories are ill-suited for expressing requirements](https://mdalmijn.com/p/user-stories-are-ill-suited-for-expressing-requirements). This article presents details about how user stories are abused and how splitting the real user stories into implementable chunks pulls us away from the real requirements. 

    [^two-bets] This statement and the following bullets are quotes from [User Stories Ain’t Requirements](https://www.construx.com/blog/user-stories-aint-requirements/)

So what are user stories? They are planning instruments. We prioritize by user stories, we may estimate them[^estimation-is-waste], and we decide in which sprint we will try to implement them. All typical for a planning instrument.
- They represent small increments of valued functionality that can be developed in a period of a day to a week. 
- They need little or no maintenance and can be thrown away after implementation.
- They, and the code and tests that is created quickly thereafter, should serve as inputs to and refinements of the requirements documentation, which is developing incrementally as well.

    [^estimation-is-waste]: It's a separate and big topic, but story estimation is almost always a waste of time.

When we plan work as stories we step away from requirements and enter the world of experiments. An experiment is work that aims at proving a hypothesis. Once proven we move on to the next hypothesis and experiments.[^hypothesis]

    [^hypothesis]: This paragraph is a great way to think about user stories and is taken from: [User Stories are not requirements](https://www.5dvision.com/post/user-stories-are-not-requirements/). The rest of that article makes the case for using user stories to avoid the need for requirements. That line of thinking isn't applicable to the requirements framework ideas proposed in [my proposed requirements framework](./why-use-cases-for-agile.md).

If you are doing agile with user stories in anything close to the right way then it isn't possible to understand the solution by reading the completed stories in the work management system, e.g., Jira, Polarian or a similar story tracker. Stories only make sense as requirements when assembled into the proper sequence of events, playing out over time in the correct order. Like one of those flip book animations that you made at school. 

![Flip Book](./images/flip-book.gif)

Stories, once delivered, have no further value as documentation of the system’s behavior. Useful requirements documentation, on the other hand, describes how the system behaves now -- not the incrementally created, flip book of history of how it evolved to behave like it does.  

In a project I recently completed, there were stories about how to identify sites and subjects on a clinical trial. The evolution of these stories shows how hypothesises were created, experiments conducted with many experiments failing as we moved on the path to learning what the requirements really were. The work played out as follows:
- For Iteration 1 the site and subject stories were identified as well understood, easy to implement, and small.
- The team implemented (a.k.a. did an experiment) and within that iteration made several updates to the story and its acceptance criteria in an attempt to to prove the hypothesis of what was needed.
- Demos were given and ultimately it was decided that agreement on what was needed could not be reached. We learned it was not well understood, not easy, but possibly still small.
- In later Iterations, multiple hypothesizes of what a good-enough story for site & subject were given, implementations done, and each was rejected.
- Eventually, a dramatically more flexible version was implemented as we  ultimately learned what the real requirements are.

Site & subject are very simple features compared to the rest of the scope of the release of that product. Virtually every other feature evolved in a similar way, e.g., we re-implemented parts of every story/epic in every iteration through the end of the release. This is a common situation on most projects. It's actually a good thing because it is a big part of how we ultimately learn what the real requirements are. Managing the cost of incremental learning and turning around updates fast enough to keep the users interested is a major challenge. Meeting that challenge is in no small part managed by rapid cycles of defining small stories (hypotheses), implementing them (experiments).

The amount of requirements churn and the need for a lot of small stories highlights the challenge of getting a good requirements document from the stories in the work management system. Yes, it is possible to do things like obsolete stories that were determined to be wrong and possibly get a minimal and sane set of stories from the work management history. Doing so gets complicated. For example, what do you do when some parts of some stories are correct while other parts need to be changed. You could duplicate the completed part in a new story but that messes up the work management because work is listed as a new story but it's already partially implemented. 

Using epics or features that group the user stories in the work management system doesn't solve the problem. Frequently the epics need to change to reflect the changes at story level. So the same churning requirements problem happens at this higher level. Using just the epic is not enough detail for the requirements.

Requirements traceability to design is another frequently important, and sometime regulatory necessity. Tracing from stories to design is difficult because a reasonable granularity of topics in design documents results in many stories tracing to many parts of the design in messy ways. An organized set of requirements should trace much more cleanly to the design documentation.

The bottom line is that user stories are *planning instruments*, not requirements.



