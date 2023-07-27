
This short article provides a bit of additional guidance on how I recommend using the work management system to support the way-of-working in the main article about [my proposed requirements framework](../why-use-cases-for-agile.md).

Examples of work management systems I've used recently:
- Jira and the many agile add-ons
- Github or GitLab Issue Tracking 
- Polarion
- Basecamp

There are many more. I like that people are using simple task tracking tools instead of full Application Lifecycle Management (ALM) tools. Examples of such simpler tools are: [Trello](https://trello.com/), [Smartsheet](https://www.smartsheet.com/), [Monday](https://monday.com/). I haven't used them but anything that is a light weight work and issue tracking tool seems like it will work in combination with my proposed framework.

We need such a system to plan and track the work, especially with distributed teams. The work management starts by putting the basics of the stories and other tech chores in and then tracking issues against them until they are completed. 

I recommend keeping the minimum needed in the work management system and linking to documents or other artifacts. For example, a URL to a test that demonstrates an issue rather than a detailed description of the issue. If and as needed you can copy content from git into the tool if that makes things easier but I prefer links to the source document or artifact. 

Assume that requirements evolution will frequently happen in the thread of issues and comments for a story or throught the addition, splitting, or deletion of stories. Make sure to reflect that back to the use-case-based requirements and the requirements statements in the BDD scenarios. These updates don't need to be done up-front of doing the implementation but they need to be done eventually. 

Create stories as recommended in the main article, e.g., one for each alternative possibly with variations reflecting different data. Keep in mind that the idea is to treat BDD Scenarios as the real individual stories as each one is considered a completed unit of running-tested code.

Organize the stories by use case. In Jira I recommend creating a Jira story for each use case and a task for each real story. This keeps the board reasonably organized and avoids an explosion of stories in an iteration. Try it, you'll like it. 