# User Stories Are Not Requirements

In support of the main article about [my proposed requirements framework](./why-use-cases-for-agile.md), this article presents more detailed reasons why user stories are not requirements. I started by trying to pull together bits of explanation from other articles on the web. I highly recommend reading all the linked articles to get an even more detailed case against stories are requirements.

## What Others Say 
"Elephants are not giraffes and user stories are not requirements. They share some traits and you may find them in the same context, but that does not make them the same."[^elephants-are-not-giraffes] This quote is a fun way to crystalize the difference between user stories and requirements. 

"User Stories are not about what you write down but about what is understood. Common understanding is prioritized over a perfect contract. This is also why the Agile manifesto contains the line:'Customer collaboration over contract negotiation'. What you initially agreed upon is less important than what you’re trying to achieve."[^common-understanding]

Agile is making two bets at the beginning of a project[^two-bets] :
- Given the desire for a fixed schedule, the scope will flex so you don’t want to call anything *required*, especially up front.
- As the project progresses and the stakeholders see the software come into being, the desires of the stakeholders will change.

    [^elephants-are-not-giraffes]: See [User stories are not requirements](https://blog.crisp.se/2016/01/07/perlundholm/user-stories-are-not-requirements)

    [^common-understanding]: This paragraph is a quote from [User Stories are ill-suited for expressing requirements](https://mdalmijn.com/p/user-stories-are-ill-suited-for-expressing-requirements). This article presents details about how user stories are abused and how splitting the real user stories into implementable chunks pulls us away from the real requirements. 

    [^two-bets] This statement and the following bullets are quotes from [User Stories Ain’t Requirements](https://www.construx.com/blog/user-stories-aint-requirements/)

The above makes a good case and leaves us with the question of, what are user stories? Think of them as planning instruments. We prioritize by user stories, we may estimate them, and we decide in which sprint we will try to implement them. All typical for a planning instrument.
- They represent small increments of valued functionality that can be developed in a period of a day to a week. 
- They need little or no maintenance and can be thrown away after implementation.
- They, and the code that is created quickly thereafter, should serve as inputs to documentation, which is then developed incrementally as well.

When we plan work as stories we step away from requirements and enter the world of experiments. An experiment is work that aims at proving a hypothesis. Once proven we move on to the next hypothesis and experiments.[^hypothesis]

    [^hypothesis]: This paragraph is a great way to think about user stories and is taken from: [User Stories are not requirements](https://www.5dvision.com/post/user-stories-are-not-requirements/). The rest of that article makes the case for using user stories to avoid the need for requirements. That line of thinking isn't applicable to the requirements framework ideas proposed in [my proposed requirements framework](./why-use-cases-for-agile.md).

If you are doing agile with user stories in anything close to the right way then it isn't possible to understand the solution by reading the completed stories in the work management system, e.g., Jira, Polarian or a similar story tracker. Stories only make sense when seen as a sequence of events, playing out over time in the correct order. Like one of those flip book animations that you made at school. 

![Flip Book](./images/flip-book.gif)
