## Welcome to Lesson 2
- [Gitter](#gitter)
- [Deciding when GitHub is the right choice for your project](#when-to-use-github)
- [How to create issues](#create-issues)
- [How to assign issues](#assign-issues)
- [How to communicate about issues](#communicate-about-issues)
- [How to organize issues](#organize-issues)
- [How to query issues](#query-issues)
- [How to assign teams](#teams)
- [Where to go when you need help](#help)
- [Miscellany that is good to know](#miscellany)
- [Edit this page in Github](#edit-this-lesson)

### Gitter

[Gitter](https://gitter.im/) is a chat platform that is linked your github account, and can be used for individuals and teams to chat/instant message.

**Start using Gitter**

- Go to the [gitter website](https://gitter.im/)
- Click on the top right SIGN IN TO START TALKING
- Sign in with github
- Click on the mangifying glass on the left hand side to search
- Search for OHSU-Library
- Click on the room and join the chat

Note - you can also download gitter to your desktop and chat through the app

### When to use GitHub
[Back to top](#welcome-to-lesson-2)

It can be tricky to figure out what technologies to use for what kinds of purposes. The table below is a simplified matrix comparing different systems for collaboratively working on documents and versions.

Legend:
````
+++ Purpose-built
++ Reasonably suited
+ Barely suited
- not supported
--- Disastrous implications when attempted
````

Note:
Native Google Docs is not the same as Google Drive. These are often conflated.

#### When to use GitHub for managing versions your (text or data) documents

| Feature | GitHub        | Native Google Docs | Office via DropBox  | Office via Box  | Office via Google Drive  |
|:-------:|:-------------:|:------------------:|:--------------------:|:--------------------:|:--------------------:|
|Concurrent collaborative editing	| + `#`	| +++| +++ (office online only) | +++ (office online only) | ?|
|Serial collaborative editing	| +++	| +++	| +++	| + `#` |+ `#`|
|Typesetting and formatting `*`	| ++	| ++	| +++	| +++|
|Version control	| +++	| ++	| +	| + |
|View either clean or marked up versions without necessarily accepting changes	| +++	| -	| +++	| +++| +++|
|Compare any two versions | 	+++	| -| 	+| 	+| + |
|Public attribution of specific contributors| 	+++	| -	| -| 	-|-|
|R/W access control at team level| 	+++| 	+| 	+| 	+|+|
|R/W access control at individual level	| -	| +++	| +++	| +++|+++|
|OHSU approved for sensitive data/communications (PHI/PII) | - | - | - | +++ | -|

`#` True serial collaborative editing is supported via Box, however at this time, Box does not warn users regarding who already has a document open. Consequently, using Box in the context of tight deadlines with multiple contributors requires extremely rigorous immediate communication regarding who has the lock on a document at any given moment. In our team's experience collaboratively writing grant proposals under tight deadlines, the lack of safeguards afforded by automatic notification (eg as supported by DropBox, by contrast) have led to confusion and lost effort. GitHub does not support simultaneous collaborative editing, however if editing happens to be carried out simultaneously by chance, conflicts are easy to assess and resolve.

`*` Note that the formatting afforded by markdown is sleek but bare bones (affords more focus on content and less on rendering as  text can be rendered differently in different contexts (desktop, mobile, etc). Thus, more about structure (headings) and emphasis and less about style (color of text). 

Except in "Office Online" mode, using Google Drive or Box to share collaboratively-edited files (eg. Office files) has terrible implications for tight deadlines: there are currently no notifications in case of version conflict. In Google drive in particular, the speed of syncrhonization is very spotty (sometimes as long as 30 minutes in our experience).

Combinations of technologies can work synergistically (eg. link a google doc to a github issue) if you understand their strengths and limitations.

Box is the only OHSU-approved system for the storage of PHI/PII; all questions related to what constitutes PHI/PII must be referred to the appropriate OHSU office.

#### When to use GitHub for your tracking and managing your projects

| Feature | GitHub issues       | [MS Project](https://products.office.com/en-us/project/compare-microsoft-project-management-software) | [JIRA](https://www.atlassian.com/software/jira)  | [Trello](http://trello.com) |
|:-------:|:-------------:|:------------------:|:--------------------:|:--------------------:|
|Free	| +++	| -- | ---| +++ |
|Transparent/attribution-friendly	| +++	| +	| ---	| + |
|Suited to digital-artifact based projects `**`	| +++	| +++	| - | ++ |
|Tight integration w GitHub	| +++	| +	| + | + |
|Tight integration w chat systems	| +++	| ?	| ? | ? |
|Detailed dependency view/control| + | +++ |+++| ? |
|Powerful but not overwhelming/feature-bloated |+++| + | -- | +++ |

TL;DR this is Julie's personal opinion: MS Project and JIRA are best reserved for gigantic multidependency projects that ALSO have a project management blackbelt at the helm AND that have the buy-in of the team for a lot of organizational overhead. For *most* projects in academia, I have found GitHub, in combination with Google Docs, to be ample tool for the PM job. Managing well has less to do with tools and more to do with discipline/organizational culture. Other PM tools exist that are GitHub integrated, such as ZenHub and Waffle.io. Our advice would be to first get really comfortable with the native basics in GitHub and workarounds (eg. specialized use of labels) and then explore the options for your use case.

`**` GitHub is not per se *poorly* suited to managing projects that are not digital artifact based, but there's less of a marginal advantage that makes it a clear win over other free tools like Trello. The caveat is that when all of someone's projects, regardless of nature, are on GitHub, their competing priorities are easier to spot and tackle.

### Create issues
[Back to top](#welcome-to-lesson-2)

**Why:**
"Issues are a great way to keep track of **tasks**, **enhancements**, and **bugs** for your projects or for anyone else's. As long as you are a registered GitHub user you can log an issue, or comment on an issue for any open repo on GitHub. Issues are a bit like email—except they can be shared, intelligently organized, and discussed with the rest of your team. GitHub’s tracker is called Issues, and has its own section in every repository." (From: https://guides.github.com/features/issues/)

**How:**

How to create an issue in GitHub:

- In [github.com](https://github.com/) navigate to the repository where you want to create a ticket:
 - On the right hand side, you should see a box with "your repositories"
 - Click on your repository of interest
- Click "issues"
- Click "New Issue" (note the word 'issue' and 'ticket' are frequently used interchangeably)
- Write an informative title
- Write a detailed explanation of your issue
- Indicate whether the issue is a task, enhancement, or bug
- If you know the sub-tasks that are involved, list these using `- [ ] ` markdown syntax before each bullet. Note, you can also add sub-tasks by clicking the 'add a task list' button in the tool bar. The status of the tasks in an issue (eg. [https://github.com/OHSU-Library/github-tutorial/issues/12](https://github.com/OHSU-Library/github-tutorial/issues/12)) will then be reflected in any summary view. Eg. [https://github.com/OHSU-Library/github-tutorial/issues](https://github.com/OHSU-Library/github-tutorial/issues).
- Click Submit new issue
- Edit the issue (if needed) (Note that post-hoc edits will not propagate to email notifications).

**Your turn:**

Follow the instructions above to create a ticket about a hypothetical issue (such as an improvement to the OHSU Library website, or a request for welcome signs in the library) that includes a sub-task list.

### Assign issues
[Back to top](#welcome-to-lesson-2)

**Assign issues to people**

- On the top right hand side, click "Assignees"
- You can assign issues to yourself or other people who are part of the repository
- In the box, start typing type their name or github handle.

**Add labels**

- On the top right hand side, click "Labels"
- Assign a relevant label to your ticket

**Your turn:**

On the ticket you previously created:

- Assign the ticket to Nicole
- Add a label for an enhancement

### Communicate about issues
[Back to top](#welcome-to-lesson-2)

**Comment on issues**

- Click on an issue in the issue tracker in the [OHSU-Library/github-tutorial](https://github.com/OHSU-Library/github-tutorial) repo
- Scroll to the bottom of the issue, and add content in the "Leave a comment" field
- Use the top tool bar to format your text, add **bold**, *italic*, lists etc.
- Preview your text to see how your formatting looks
- Click Comment. If you want to close the issue, click Close Issue. Only close the ticket if the issue has been resolved, usually someone will write a comment describing the action they did to close the ticket and click Close Issue. The ticket will no longer be dispalyed in the list of open issue, but will be archived.

**Use direct @ mentions**

- You can mention someone in a issue without assigning it to them
- In the comments section, type @github handle. For example, to mention Julie, you would type @jmcmurry. You can either start typing their name or github handle and github will autosuggest their handle.

**Link documents**

You can link documents and files by:

- copy and pasting URL
- you can attach files by dragging and dropping.
- You can link one issue to another in the same repo by typing '#' followed by the title of the ticket
- This approach also works across repos but you need to use the full URL (no autocomplete available). Doing this will also cause the referent issue to display that it has been referenced.

**Cross reference to another ticket**

- If your ticket is a duplicate or related to another ticket, you can cross reference another ticket
- Type # and you will see a list of other tickets in that repo
- Type #TicketNumber and that will link to the other ticket. For example [#10](https://github.com/OHSU-Library/github-tutorial/issues/10) will link to [this ticket](https://github.com/OHSU-Library/github-tutorial/issues/10)

**_Before saving your changes, you can preview the comment to ensure the correct formatting._**

**Your turn:**

- Follow the instructions above to comment on a ticket that someone created.
- Mention Julie
- Attach a picture of a cat (such as a picture you copy from the internet, or attach a picture you have saved on your computer)
- Include a comment that says, 'related to #10' and link to ticket [#10](https://github.com/OHSU-Library/github-tutorial/issues/10)

### Organize issues
[Back to top](#welcome-to-lesson-2)

**Milestones**

- To create a milestone, navigate to the issues page in your repository
- Next to the search field, click **Milestones**
- Click **New Milestone** to create a new milestone, click **Edit** to edit an existing one
- Create a milestone that is broad enough to be meaningful, but specific enough to be actionable.
- Set a due date for the milestone (note that specific tasks can not be formally assigned due dates, though you can mention a desired due date in the narrative text of a ticket.
- Each ticket can only be associated to ONE milestone, however it can have as many labels as appropriate.

**New Labels**

 - On GitHub, navigate to the main page of the repository Issues and pull requests tab selection
 - Under your repository name, click  Issues (or  Pull requests)
 - Click Labels button next to the search field
 - Click New Label to create a new label, or click Edit to edit an existing one.
 - In the text box, type your new label name.
 - Select a color for the label from the color bar. You can customize this color by editing the hexadecimal number above the color bar. For a list of hexadecimal numbers see [HTML color codes](http://htmlcolorcodes.com/)
 - Click Create Label to save the new label.

**Your turn**

Create a new milestone and a new label, and add the milestone and label to an existing ticket.

**Projects**

- Projects is a lot like Trello, it uses cards on a list that you can name and organize as you see fit.
- You can create as many projects within a repository as you like

To create project:

- Click on Projects
- Click New Project
- Name the project
- Write a description of the project
- Create columns and give them names
- Add 'cards' to the columns

**Your turn**

Create a new project and add columns and add cards to the columns.


### Query issues
[Back to top](#welcome-to-lesson-2)

Once you start using github for lots of things it is easy to get overwhelmed by the number of issues. I find the query dashboard (https://github.com/issues) much more relevant to me than the notification page (https://github.com/notifications).

### Teams
[Back to top](#welcome-to-lesson-2)

See this [help article on creating teams](https://help.github.com/articles/creating-a-team/)

- All issues assigned to me: [https://github.com/issues/assigned](https://github.com/issues/assigned)
- All issues on which I am @ mentioned: [https://github.com/issues/mentioned](https://github.com/issues/mentioned)

More complex queries are also possible.

- All issues either assigned to me OR on which I have commented OR am mentioned: [https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+involves%3Ajmcmurry+](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+involves%3Ajmcmurry+)
- All issues in all repos within an organization: [https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+org%3Aohsu-library](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+org%3Aohsu-library)

Further reading on [Issue querys](https://help.github.com/articles/searching-issues/)

### Help
[Back to top](#welcome-to-lesson-2)

If you have an issue with GitHub itself (bug, feature request, etc) where do you go? Ironically, there is no good place. If you want to look up things that others have reported, isaacs has a good resource. https://github.com/isaacs/github/issues/. However, this is a rogue repo and a bit contentious.

- You may find the answers you seek in  [StackOverflow](http://stackoverflow.com/questions/tagged/github), although it is primarily geared towards programmers.
- GitHub kinda monitors [https://github.com/isaacs/github/issues/](https://github.com/isaacs/github/issues/) but not with any rigor.
- To be safe, contact GitHub directly at [https://github.com/contact](https://github.com/contact), but recognize that they support literally millions of users and responsiveness is not guaranteed. Forums like isaacs sometimes offer some help because other users can help identify workarounds, for instance, as shown [here](https://github.com/isaacs/github/issues/65#issuecomment-123740194).

### Miscellany

[Back to top](#welcome-to-lesson-2)

- It is possible but not obvious how to rename a repository. [https://help.github.com/articles/renaming-a-repository/](https://help.github.com/articles/renaming-a-repository/)
- Certain things you think you *should* be able to do from the UI, you just can not:
  - Delete/rename a whole directory using the UI (this can only be done using the desktop app, or commandline).

### Edit this lesson

To make suggestions to this lesson, go to the [markdown file in the github repository](https://github.com/OHSU-Library/github-tutorial/blob/master/docs/lessons/Lesson2.md) and click the "edit" icon.

### [Back to Home](../index.md)

