# Instructions

Now that you have gone through the course material, let’s resume working on the project.

Make a copy of [this Google doc template](https://docs.google.com/presentation/d/1AeHtZqSGpZQvqxnBBiDusb9jGV0uNHGf_i1FHEECFj0/copy) or download the PPT template from the Resources tab in the classroom sidebar. Make sure to complete each section. When you are ready, save your file as a PDF and submit it.

<br>
<br>

# Context

Your project’s MVP scope has been translated into a PRD and is now ready to move into the development phase. Your development team has adopted Agile Scrum methodology principles to manage their development cycle. Each sprint runs for 2 weeks followed by a release to the production environment.

<br>

| Scrum/Development Team | All Teams |
| ---------------------- | --------- |
| One Engineering Lead | Customer Service |
| One Shared DevOps | Data Analytics |
| Four Engineers | Engineering (includes QA) |
| One Shared QA Scrum master (rotational in nature) | Legal & Compliance |
| Product Designer | Finance & Accounting |
| Shared Data Analyst | Operations |
| | Marketing (includes Product Marketing) |
| | Product Management |
| | Product Design |

<br>

As part of the project, you will live through various scenarios that a PM typically faces or is expected to carry out during the development phase:

- Create a project blueprint that can be used by either you or the involved stakeholders to understand their role, task and targeted milestone.

- Plan for a sprint meeting to ensure that the team is able to understand and focus on the deliverable.

- Respond to different scenarios that may require you to reprioritize the sprint backlog or manage expectations with stakeholders accordingly.

- Apply your learnings from the course to understand the API documentation and use this information to engage with the scrum team accordingly.

<br>
<br>

# Section 1: Project Blueprint

Based on what you learned in the course and keeping in mind your project, define the coordination activities map that you either need to own or assign to another member. 

Think of this document as a single source of reference for everyone involved in the product launch to some degree to understand their roles and tasks. Use the coordinated activities map template (provided in the “starter” section) to share your answers.

<br>
<br>

# Section 2: Sprint Meeting Planning

Stay ahead of your scrum team and prepare for your upcoming sprint. Engineering design scoping and review was completed in the last sprint. 

Your development team is expecting to kickoff feature implementation in the upcoming sprint. 

100% of the sprint capacity can be utilized to build your product since there are no critical issues or pending feature request that you are aware of, to be prioritized for the upcoming sprint. Use the template (provided in the “starter” section) to share your answers.

<br>
<br>

# Section 3 : Decoding API documentation

As a PM, you will collaborate with the engineering team and influence how they build: from scratch, leverage an internal API or integrate with an external partner. 

When a product requires an API integration, sometimes PMs need to be “technical enough” to understand what information is available via the API, how is it available and possible pricing impact to refine the solution with designer and development team.

Choose the question to work on based on the scenario that you've been working on throughout the nanodegree. Use the template (provided in the “starter” section) to share your answers.

<br>

| Project Chosen | Scenario | Resources |
| -------------- | -------- | --------- |
| Kaiser Permanente Project | Your solution may require fitness, health and calorie information to be provided by the patient. You have identified Validic as a possible integration to deliver the solution to the market faster. | [Link 1](https://support.validic.com/customer/en/portal/articles/1648986-rendering-the-web-marketplace-in-an-html-iframe-tag), [Link 2](https://support.validic.com/customer/en/portal/articles/2103982-app-marketplace-syncing-process), [Link 3](https://support.validic.com/customer/en/portal/articles/2112631-connected-apps-and-devices), [Link 4](https://docs.validic.com/docs/summary) |
| DoorDash Project | Your solution requires directions and distance between robot and destination ( could be restaurant/delivery address). Your engineering lead shared Google Distance Matrix API and Google Direction API s a reference to what information would be available when you leverage Doordash API to build. Reviewing the documentation, you noticed that walking and bicycling information is available via the API with rich attributes that can be leveraged to help the Operations team in multiple ways. | [Google Distance Matrix API](https://developers.google.com/maps/documentation/distance-matrix/intro#travel_modes), [Google Direction API](https://developers.google.com/maps/documentation/directions/start) |
| LinkedIn Project | Your solution requires jobs posted on LinkedIn to be recommended. Your engineering lead share LinkedIn Job Lookup API, LinkedIn Match API and Company API as a reference to determine what attributes are available for you to match for a recommendation. | [LinkedIn Job Lookup API](https://developer.linkedin.com/docs/v1/jobs/job-lookup-api-and-fields), [LinkedIn Match API](https://docs.microsoft.com/en-us/linkedin/talent/recruiter-system-connect/linkedin-match), [Company API](https://developer.linkedin.com/docs/v1/companies/company-lookup-api) |
| Amazon Project | Your solution requires media files to be shared on Amazon website once the publishers uploads them successfully. Your engineering lead shared PutObject API documentation for your reference. Use the information to determine the file upload criteria and other design change you may want to discuss with your designer. For the sake of the exercise assume the following: - Your team has all the necessary infrastructure and permission to use AWS S3 to manage files - Your scope includes allowing publisher to upload a file to create a teaser that can be shared by the user on social platforms such as Facebook using a unique URL. | [PutObject API Documentation](https://docs.aws.amazon.com/en_pv/AmazonS3/latest/API/API_PutObject.html) |

<br>
<br>

# Section 4: Sprint Reprioritization

You are 3 days into the 2-week sprint and an issue has been reported from production in the last 5 days.

### Issue 1

Your customer service team filed a ticket as ‘bug’ [Priority = 1] that has been added to your product backlog. Users are complaining that the landing page upon logging is too slow to load. Page load time is one of the key page performance metrics that you track apart from unique visitor (daily, monthly), bounce rate, peak response, and landing page conversions. Use the template (provided in the “starter” section) to share your answers.

<br>
<br>

### Issue 2

Your customer service team filed a bug [Priority = 2, and without a screenshot] that has been added to the product backlog. The Profile Settings page updated in the last release looks weird (fields are misaligned) in the Android app. Data analytics team informed you in the past that % of total users accessing this page on a daily basis is 2%. Use the template (provided in the “starter” section) to share your answers.

<br>
<br>

### Issue 3

You receive an email from the newly joined Customer Service Manager. Use the template (provided in the “starter” section) to share your answers.

Email Request: Our internal tool’s “send an email with reset password link” is not working. We are able to trigger the email (containing the link to reset password), however, users are complaining that they are not receiving the email from us. We noticed that the email is being received by users after 12 hours of being triggered by our internal tool. This is frustrating for them and has increased the incoming call volume. Can you look into why the email (containing the link reset password) is being delivered so late, ASAP?

Additional Details: 20% of users that are unable to log due to incorrect password reach out to the customer service team, where they trigger the email with the link to reset the password using the internal tool. From previous engineering discussions, you believe the same email with a link to reset password is triggered when a user requests a password reset email from the product directly. On an average, 7% of daily total users that are unable to log into the product request this email.

<br>
<br>

# Section 5: Handle Potentially Difficult Situations

As a PM, you will be faced with many unexpected situations where you have to make a decision or push back while managing competing priorities from stakeholders and tackling issues that could potentially affect your product launch

<br>

### Situation 1

Your startup CEO or division GM is excited about your product’s future potential (for exercise sake, assume it is the product feature you have chosen to build for the project) and wants to demo it to their stakeholders in 2 days. You have received an email asking for a test account and QA environment details to log in and demo during their meeting. 

The product feature is 65% functionality complete and not fully stable yet since it is still being tested. Your development team is deploying changes to the QA environment frequently to verify the completed tickets and bug fixes. Use the template (provided in the “starter” section) to share your answers.

<br>
<br>

### Situation 2

You are stepping in as Scrum Master for the stand-up today and you have 3 more days for the sprint to end. Your back-end engineer just finished sharing their update ( pick up the analytics ticket, and there are no blockers ). Your QA team member is next in line to share their updates. In JIRA (ticket tracking tool) you notice the following:

A user story that needs to be completed has two back-end tickets assigned to the back-end engineer that just shared their update in “Code Review”. You know from attending previous standups these tickets have been in ‘Code Review’ for 2 days now. These back-end tickets are blocking two front-end tickets ( ‘code-review complete’) from being tested by QA

There is another ticket covering analytics requirements (story points =3), for which development has not yet started and is expected to be completed in this sprint. The ticket cannot be completed by the end of this sprint if it is not picked up for development by the end of today, It has 5 tracking requirements and you realize 2 out of 5 can be downgraded to ‘nice-to-have’ for the launch.

Assumption for exercise-sake: User stories being referred here are related to the product feature (the project you are working on). The tickets are costed and targeted to be completed by the end of this sprint to go live with the product feature. Use the template (provided in the “starter” section) to share your answers.
<br>
<br>

### Situation 3

There are 6 more days for the sprint to end. Your project has a shared QA team member that you are working with for the first time in the company The Head of QA informed you that your QA team member is handling 2 other major projects with other PMs simultaneously and is out on sick leave for the next 3 days. 

When the QA team member returns, tickets related to automated testing (to cover 30% of this sprint’s scope) will be still pending along with manual verification and regression for the user stories that have been completed by then. You know a product feature that is not fully tested is unstable and prone to issues. You believe this is a potential risk affecting the product launch if not addressed immediately. Use the template (provided in the “starter” section) to share your answers.

<br>
<br>

### Situation 4

You are conducting the product sign-off meeting with cross-functional stakeholders and scrum teams (10+ people) and the product being tested is expected to go live at the end of this sprint. One of the cross-functional stakeholders shared the feedback below at the meeting.
Feedback: I don’t think the product we just tested is good enough to go live. It needs to send daily push notification reminding users to open and use the product feature being launched.

Assumption for exercise-sake: Notification feature (of any sort) is not in the MVP scope. Your goal is to understand the user journey within the product better after the launch to define the trigger and other details to introduce later. Use the template (provided in the “starter” section) to share your answers.

<br>
<br>

# Submission Requirements:

- PDF copy of your final ["Developing the Product" deck](https://docs.google.com/presentation/d/1AeHtZqSGpZQvqxnBBiDusb9jGV0uNHGf_i1FHEECFj0/copy) which includes links to:
    - Coordination Activities Map
    - Video

View [the rubric here](./Unit_3_Rubric.pdf).