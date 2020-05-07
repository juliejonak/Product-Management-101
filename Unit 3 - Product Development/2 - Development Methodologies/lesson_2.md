# Table of Contents

a. [Lesson Overview](#Lesson-Overview) <br>
b. [Waterfall Methodology](#Waterfall-Methodology) <br>
c. [What is Agile?](#What-is-Agile?) <br>
d. [Kanban Methodology](#Kanban-Methodology) <br>
e. [Scrum Methodology](#Scrum-Methodology) <br>
f. [Exercise: Scrum Methodology](#Exercise:-Scrum-Methodology) <br>
g. [Work Management Tool](#Work-Management-Tool) <br>
h. [From Development to Deployment](#From-Development-to-Deployment) <br>
i. [Lesson Recap](#Lesson-Recap) <br>
<br>

# Lesson Overview

Watch [The Lesson Overview.](https://youtu.be/tmmT9NYZQEo)

<br>

As a Product Manager who has understood the various development methodologies, you will be able to share actionable feedback on what can be improved in the development team's process after following their current process for the initial few weeks.

You will learn how work is structured and managed using work management tools and how do development teams develop new features while maintaining the existing product's stability. These concepts remain largely unchanged even if the issue and project tracking software tools vary by company.

We'll cover a few main methodologies: waterfall, agile, kanban and scrum.

<br>
<br>

# Waterfall Methodology

![Waterfall Methodology](./img/Waterfall.png)

<br>

What is the Waterfall methodology?

The Waterfall process is divided into distinct phases where `each phase cannot begin unless the previous phase is completed` since it also serves as an input for the next phase. 

<br>

Let's understand each of these phases better:

`Gather Requirements` : The requirements must be fully captured and defined through rigorous documentation in the form of an elaborate requirements document.

<br>

`Design the solution` : The requirements are utilized to design the product that details the functional or system requirements and aids in defining engineering architecture. The requirements and solution may be functionality focused instead of being customer-centric.

<br>

`Develop the solution` : The scope of work is broken into smaller manageable units and developed independently. Each unit of work is tested to confirm whether the intended functionality has been developed - this is called Unit Testing.

<br>

`Test the solution` : The units developed and verified in the previous phase are combined or integrated. This integrated system is tested thoroughly for any issues or failures.

<br>

`Deploy the solution` : Once the product has been exhaustively and comprehensively tested, it is deployed to the production environment for customers to start using it.

<br>

`Maintenance and support` : When issues arise, they are fixed. Enhancements to the product go through the same process to deliver the changes.

<br>
<br>

Each phase requires a sign-off from an approver ( for e.g. in the case of Gather Requirements and Design the Solution - it could be the enterprise customer for a B2B2C product) to ensure there is no overlap between phases ( e.g. gather requirements and design the solution).

The waterfall methodology is adopted by the development and product team based on various factors, which make the linear and sequential process a more appropriate approach:

- Requirements are not ambiguous and fixed.
- Ample resources with the expertise required to develop and launch the project are available for a significant amount of time at the project’s disposal
- Project timeline is short

<br>

<details>
<summary>In a project, the requirements gathering is in progress and 85% completed. The remaining 15% will take another 2 weeks to complete. Can you kick-off designing the solution for the 85% finalized requirements because it is clear and can’t change?</summary>

No - Each phase needs to be completed prior to beginning the next phase.
</details>

<br>
<br>

# What is Agile?

Understanding the Agile Philosophy

Companies need to respond to change and adapt to evolving customer needs and constantly changing market dynamics. This requires a shift in the development methodology's focus from following rigid processes to focusing on people and how they collaborate.

<br>

Agile methodology is centered around `the need to respond to change and adapt`. It is an `iterative approach` to software development, where requirements and solutions evolve through constant collaboration and clear communication within the self-organizing cross-functional team. 

A self-organizing team decides how to get things done versus waiting for another person (e.g. project manager) to step in and lead the team to figure out what needs to be done next.

<br>

Kanban and Scrum are popular frameworks that enable teams to embrace and follow agile principles, and helping teams deliver value faster without compromising quality.

We'll learn more about both in the next sections of the lesson.

<br>
<br>

# Kanban Methodology

Watch [What is Kanban?](https://youtu.be/RUJzFg9kYbc)

<br>

With increased product complexity and distributed teams, it's difficult to avoid bottlenecks during development and delivery.

When one portion of work is done, like a developer's ticket, it needs to be reviewed by that team, to ensure it matches their standards, best practices and guidelines. We need to know that it doesn't conflict with existing features.

It's not uncommon for tickets to be stuck during this review phase because either the feedback isn't given quickly or the feedback isn't implemented. This process happens several times during the development of each part of the product.

If the review takes days, this can be a bottleneck.

<br>

Kanban utilizes the power of visualization to increase team efficiency and deliver value to the customer faster.

<br>

It enables a highly motivated team to `visualize the progress of their work` and the process through which the project has to flow through.

Kanban enforces a maximum number of items that can be in a particular stage of the process. Work In Progress (WIP) limits help avoid bottlenecks.

By helping the team see that clearly, Kanban methodology enables the team to swarm and figure out how to unblock the team.

The team focuses on taking the work from start to finish as fast as possible, which is called cycle time. This improves throughput by reducing cycle time.

<br>
<br>

### Kanban Board

Watch [What is Kanban? Part II](https://youtu.be/P8RHkmGIN0c)

_Note: In the video, the instructor defined lead time as the time taken to move an item from Ready-to-Develop to Done. It should be the time taken to move an item from Backlog to Done._

<br>

![Sample Kanban Board](./img/Kanban.png)

<br>

Let's go through the columns of a typical Kanban Board to understand each step of the process. 

These columns are filled with tickets (or cards) which are items on the to-do list, or a feature requirement. They have a topic/title and details.

<br>

`The Backlog:` This first step indicates the work that needs to be completed by the development team. 

It's managed by the product manager, in a prioritized order. The most urgent is at the top with the most details. As you descend the list, the amount of details and priority is reduced.

The least detailed tickets capture the context or scope of the ticket at a high level. You can add details later.

<br>

`Ready To Develop:` Backlogged tickets still need to be reviewed and updated before going into development. Sometimes the details change or new input from stakeholders and designers will affect the ticket.

It's the PMs job to update the ticket with the most up-to-date information, then move it into the Ready-To-Develop column, to indicate to the developers what to work on next.

This column is again ordered from top to bottom by most to least urgent.

<br>

`In Progress:` Once a developer picks a ticket from the Ready-To-Develop column, they'll move it to the In-Progress column.

To eliminate bottlenecks, the engineering team determines the maximum number of tickets that can be in this column at any time.

This is the `Work In Progress Limit` (WIP).

<br>

`In Code Review:` When a developer has finished the ticket and is ready for their engineering team to review it, an engineer moves their ticket to "In Code Review".

This column will also have a WIP limit to avoid bottlenecks. By placing this limit, it forces the team to swarm to reduce the number of tickets in this column before they can continue taking on new tasks.

<br>

`In Testing:` Once a ticket has been reviewed and approved, it's ready for testing. The WIP limit here is determined by the QA team's availability.

Once the QA team verifies the ticket, you will also step in to verify the feature is correct as well. This is called `User Acceptance Testing` or `Feature Sign-Off`.

The PM must verify that the work has been completed and meets the product requirements.

<br>

`Verified:` This column displays the work that has been verified by Engineering, QA and Product teams, and is ready to be released to customers.

<br>

`Done:` This last column indicates which tickets have been successfully deployed to customers and are "live".

<br>
<br>

### Lead time vs. Cycle time

`Cycle time` refers to the time a ticket takes to go from the Ready to Develop stage to being Done. 

`Lead time`, on the other hand, is the time taken to take the ticket from Backlog to Done.

<br>

The team will calculate the Lead Time based on the amount of time it takes for an item to actually move from Backlog to Done.

We can think of the difference between Lead and Cycle time as the difference between customer and internal perspectives.

Lead time measures how long it takes from order to delivery -- what your customer sees happening.

Cycle time measures how long it takes from the actual developer work starting to delivery -- what you internal development team experiences.

<br>

You'd calculate Lead Time by measuring how long it takes a ticket to go from a "Requested" state to "Done".

Cycle Time is measured by the moment new tickets go from "In Progress" to "Done".

<br>
<br>

<details>
<summary>True or False: Lead time is the time taken to move a ticket (scope of work) from the backlog managed by Product Manager to finish, where the value is deployed to customers.</summary>
True! Lead time is time taken to move the ticket from ready to develop to finish, where it is deployed to customers.
</details>

<br>

### Further Reading

[Kanban Defined](https://www.agilealliance.org/glossary/kanban/#)

[Kanban, according to Atlassian](https://www.atlassian.com/agile/kanban)

[Measuring Lead v Cycle Time](https://kanbanize.com/kanban-resources/kanban-software/kanban-lead-cycle-time)

<br>
<br>

# Scrum Methodology

Watch []()

### Further Reading



<br>
<br>

# Exercise: Scrum Methodology

Watch []()

### Further Reading

[]()

<br>
<br>

# Work Management Tool

Watch []()

### Further Reading

[]()

<br>
<br>

# From Development to Deployment

Watch []()

### Further Reading

[]()

<br>
<br>

# Lesson Recap

Watch []()

### Further Reading

[]()

<br>
<br>