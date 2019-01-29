# Instructions for GSoC 2019 Applicants

_Note: our participation in GSoC 2019 is not yet confirmed._

* [Application procedure](#application-procedure)
* [Selection criteria](#selection-criteria)
* [Writing the project proposal](#writing-the-project-proposal)
* [Our expectations during the project](#our-expectations-during-the-project)
* [Our expectations after the project](#our-expectations-after-the-project)
* [Contacting us](#contacting-us)
* [Project Admins](#project-admins)
* [Resources](#resources)

## Application procedure

#### Things to do/consider before applying:

1. **[Prereq] Basic Software Engineering knowledge**

   * Applicants who have done (or is doing) at least an entry-level Software Engineering course and have a basic understanding of OOP will have an advantage.
   * Those who know at least *some* of the following when you apply will have an advantage over those who do not. Note that you should be able to get a basic grasp of most of these before you start the coding phase:
     * Languages:
       * Front-end: HTML, SCSS, TypeScript
       * Back-end: Java
     * Tools and technologies:
       * Front-end: Angular, Bootstrap
       * Back-end: Servlets, TestNG, Selenium, developing Java apps for Google App Engine Standard Environment
       * General: Git

1. **Learn about TEAMMATES:**

   Visit our [project website](https://github.com/TEAMMATES/teammates) and the [ideas page](https://github.com/TEAMMATES/teammates/wiki) to get a rough idea about the what we have done so far in the TEAMMATES project and what you can do for TEAMMATES under GSoC.

#### The following optional tasks can increase your chances of selection.

1. **[Optional, encouraged] Set up dev environment:**

   * Read our [Contributor Orientation Guide](https://github.com/TEAMMATES/teammates/blob/master/docs/CONTRIBUTING.md) and try to complete phase `A`-`C` in the "Orientation task list". Not to worry if you stumble on the way; we are always ready to guide you during the process of completing those steps :-).
   * **Important**: Please pay attention to details of the instructions given and try to follow them meticulously when setting up the project and contributing PRs. Attention to details is one of the qualities we look for in a contributor. When you try to save yourself time by skipping over details/instructions, you cause others to waste their time on correcting your oversights.

1. **[Optional] Fix Issues (i.e., Submit PRs):**

   Objective: to show coding abilities and that you can follow our workflow.<br>
   You need to do the previous step before fixing issues. Steps for fixing an issue is explained in the [process document](https://github.com/TEAMMATES/teammates/blob/master/docs/process.md).
   1. When picking issues to fix, try to pick easier issues first (those labelled `d.FirstTimers` or `d.Contributors`).
   1. Do not fix more than one issue labelled `d.FirstTimers`. After fixing one of those, you are no longer a first timer.
   1. Try to avoid issues for which there are existing ongoing active pull requests. If you are not sure if an open PR is still active, you can always post a comment in that PR and ask the author.
   1. When there are multiple pull requests for the same issue, we merge the one that reaches the _ready to merge_ status (indicated by the `s.ToMerge` label) first.

   :exclamation: Note: GSoC application period is a very busy period of us due to many GSoC aspirants interacting with the project. Some of your emails and posts in the issue tracker could fall through the cracks without us realizing. Feel free to remind if you do not get a response from us within 24 hours.

1. **[Optional] Report bugs:**

    Objective: to show us that you have taken time to learn the TEAMMATES functionality.<br>
    Play around with TEAMMATES functionality (using your dev server or staging server) and report bugs or suggestions for improvements in our issue tracker.

## Selection Criteria

The main criterion is your programming skills, evaluated based on the quality of your past work. Provide links to any of your past work that is available online.

Given that TEAMMATES is based in a Computing school and the project is especially student-friendly, we receive a high number of GSoC applications out of which only the strongest applicants are likely to be selected.Even if you fail to get selected for a GSoC slot in TEAMMATES, you are encouraged to continue contributing. It will improve your programming skills and OSS credentials, which will add weight to your future GSoC/job applications.

## Writing the project proposal
Length: The project proposal need not be very long, typically, no longer than three pages.

#### Feedback for project proposals

To be fair to all applicants, we encourage you to write the proposal based entirely on the details given in the ideas page, rather than sending us generic "can you give us more details?" requests.
* Note that project ideas are open ended. We expect you to propose how those features should be, rather than asking us "what exactly you need there?".
* It is OK if your proposal is slightly different from what we had in mind. That will help us evaluate the quality of your judgement and the level of guidance you are going to need if you are to be accepted.
* If your initial proposal is good enough to interest us, we will contact you during the application evaluation period (after the submission deadline) to hammer out further details before doing the final selection.

Having said that, we are always happy to,
* Answer a pointed question about a specific detail of a project idea (e.g. "did you mean x or y?").
* Give feedback on proposals submitted early (via GSoC system). Just let us know after submitting the proposal.

#### Sections to include

* **Personal details:**
  * Name:
  * Contact email:
  * Country, university and the degree program:
  * GitHub username:
  * Online presence (home page, online CV, blog, etc.):
  * Why are you the right choice for this project?

* **Project experience:** Include details of all past programming work, including links to some sample code.
  * What other programming project experiences do you have? Please provide links where possible.
  * What have you done for other OSS projects in the past, if any? Please provide links to your contributions (PRs, Issues, etc.).

* **Skill level:**
  * State your skill level for various languages, tools, and technologies relevant to your project proposal. Give evidence of your skill level for each, if any (e.g. point to sample code written by you).
  * You may use these for rating your skill level:<br>
    `Zero` (written less than 100 LoC), `Basic` (less than 1 KLoC), `Intermediate` (1-5 KLoC), `Expert` (more than 5 KLoC).

* **Proposed design:** We would like to see some details of how you plan to implement the proposed feature. Mention the order in which you will implement various parts of the feature. This will help for us to judge whether you have given it some thought and have done your homework before applying.<br>
  Note: **It is OK to include proposals for multiple project ideas in the same application, and specify an order of preference.**

* **Availability/schedule:** We do not require you to submit a detailed project schedule. This is because we plan to define/refine the schedule on a continuous basis, based on how the project progresses. However, you should give us a confirmed schedule of your availability during the summer, i.e. during which periods you will be available full time to work on the project.<br>
  **Specify which hours of the day in Singapore time (UTC+08:00: Kuala Lumpur, Singapore) you are available to communicate with the project mentors (most of whom are based in Singapore).**

## Our expectations during the project

* **This is a full time job:** We believe one main objective of an internship is training students for real working environments. Therefore, we expect you to treat this as a real full time job during the code phase (mid May - mid Aug). Do not apply if you have any other full time engagements during that period.

* **We expect daily progress:** Our practice is to break work into small well-defined tasks that can be done in less than one day. This means we expect full time developers, including you, to complete tasks on a daily basis and push code at least 5 days a week. Of course you can have a few "off days", just like a normal job.

* **Your work can go beyond the project proposal:** During the project duration, we treat you as a project member. And as any other project member, we expect you to contribute to other project activities such as bug fixing. The project that you propose will be the core of your contribution to TEAMMATES, but it will not be the only thing you do. Consequently, do not plan to finish the project quickly and take the rest of the summer off :-).

* **We have the final word on design decisions:** You are always welcome to suggest alternatives and argue for what you think is the best solution. However, the final decision as to which approach to take lies with the project team. You are expected to accept the project team's decision and follow it sincerely.
In addition, do expect changes to the project plan along the way.

* **We are friendly:** The above makes it sound like we are heartless slave drivers. That is not true; we are really friendly, understanding, and reasonable. :-). For example, the amount of work expected from you will be similar to what many other student contributors were able to complete in the past. TEAMMATES was built by students. It is where it is now because of their hard work. In return, that hard work helped them become strong software engineers. We expect no less from you and we want you to gain no less.

* **We are serious; you should be too:** We expect to integrate your work to the main product. That means your work will be used by our user base even before the project finishes (we release a new version almost every week). This also means, after a short period in which your mentor will guide you to attain the required quality level, you are expected to produce production quality code, i.e. well-tested and compliant with our coding standards.

## Our expectations after the project

The successful completion of the project, in addition to all the goodies from Google, will also earn you committer status in TEAMMATES. If you continue to be involved in the project (even on a much lighter scale),
* You will be elevated to core member status (yup, in this page, with photo and everything).
* You will get high priority for student/mentor roles in future GSoCs.

## Contacting us

The best way to contact us is to post a message in our issue tracker. Our issue tracker doubles as a discussion forum. You can use it for things like asking questions about the project or requesting technical help.

Even queries regarding a specific project in the ideas page can be posted in the issue tracker. If the information is not suitable to post in the issue tracker, e.g. seeking feedback on a project proposal, please email our general contact email (teammates@comp.nus.edu.sg).

## Project Admins

* [**Damith C. Rajapakse**](https://www.comp.nus.edu.sg/~damithch): TEAMMATES Founder and GSoC Project Admin. Teaches at the School of Computing, National University of Singapore. Experienced in running software projects in the industry and in teaching software engineering to students. Has written several books related to software engineering. Academic advisor for past GSoC participants from NUS. Contact: `damith [at] comp.nus.edu.sg`.

* [**Wilson Kurniawan**](https://github.com/wkurniawan07): TEAMMATES Chief Maintainer and GSoC Project Admin. Past GSoC-er (2015). Project member since 2015. Currently a professional software engineer focusing on web application development and data management/warehousing.

* **Other mentors:** To be selected from senior developers listed [here](http://teammatesv4.appspot.com/about.jsp).

## Resources

* [The DOs and DON'Ts of Google Summer of Code Student Participants](http://google-opensource.blogspot.sg/2011/03/dos-and-donts-of-google-summer-of-code.html) (not specific to TEAMMATES)
