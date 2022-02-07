---
layout: post
title: "How to Conduct High Quality Interviews"
summary: "General processes and best practices to be an effective and high quality tech interviewer."
author: carloskidman
date: "2022-02-07 15:25:00 +0000"
category: ["interview"]
tags: QAP
thumbnail: /assets/img/posts/pexels-edmond-dantès-4344878.jpg
thumbnail-caption: "Photo by Edmond Dantès from Pexels"
thumbnail-alt: "Woman sitting at a desk being interviewed by two people"
keywords: interview, interviewer, interviews, job, how to
usemathjax: false
permalink: /blog/how-to-conduct-high-quality-interviews/
---

There are lots of vidoes and articles about how to "ace an interview", but not as much around how to be a _good interviewer_ or how to setup a _good Interview Process_. Part of the reason is that your interview strategy will differ based on things like the role or constraints of the position, but also because the approach will be slightly different from candidate to candidate since each person is unique.

In this post, we will use examples from different roles including `Software Tester`, `Automation Engineer`, and `QA Manager`. However, this is meant to be a set of generalized processes, principles, and guidelines that work for any position.

> 👀 For a more detailed breakdown for interviewing a specific role, be on the lookout for new posts in the QAP Knowledge Base!

# Table of Contents

- [Define the Problem](#define-the-problem)
  - [Questions as an exercise](#questions-as-an-exercise)
- [Create a Job Description](#create-a-job-description)
  - [What should a JD include?](#what-should-a-jd-include)
  - [Support Recruitment](#support-recruitment)
- [Prepare for the Interview](#prepare-for-the-interview)
  - [Interviewer Roles and Definitions](#interviewer-roles-and-definitions)
    - [Driver](#driver)
    - [Interviewer](#interviewer)
    - [Support](#support)
    - [Candidate](#candidate)
  - [Create the Interview Team](#create-the-interview-team)
    - [Rounds and Sessions](#rounds-and-sessions)
    - [Core Team and Backups](#core-team-and-backups)
    - [Never Interview Alone](#never-interview-alone)
  - [Create the Interview](#create-the-interview)
    - [Technical Interview](#technical-interview)
      - [Questions](#questions)
      - [Scenarios](#scenarios)
      - [Challenges](#challenges)
    - [Culture Fit Interview](#culture-fit)
- [Conduct the Technical Interview](#conduct-the-technical-interview)
  - [Review the Resume and Portfolio](#review-the-resume-and-portfolio)
  - [Curate the Interview](#curate-the-interview)
  - [Run the interview](#run-the-interview)
  - [Post Interview](#post-interview)
    - [Assess](#assess)
    - [Retrospect](#retrospect)
- [Conduct the Culture Fit Interview](#conduct-the-culture-interview)
- [Final Decision](#final-decision)

---

# Define the Problem

You want to start on the right foot by defining the problem you're looking to solve by hiring. This step is crucial, yet it is often overlooked which causes a lot of problems down the road.

For example, let's say you are asked by your manager to join an interview for a `Data Engineer` that starts in 15 minutes.

- How would you prepare?
- Do you know which team they are joining?
- Do you know what skills or experience they need to be successful?
- What problems will they be solving?
- What questions are you gonna ask?
- Why do we need this person right now??
- What are you even supposed to do in the interview so you don't look a fool???

This happened to me a few times early on in my career... I was able to B.S. my way through them, but I was more concerned about _how I looked_ in front of my boss and colleagues instead of the experience the candidate was going through in a high pressure interview. I had no idea what we needed this person for, so my questions and what I was looking for were completely generic and coming off the top of my head. I'm sure you've experienced interviews where it seems like they don't know what to ask next, or there are awkward pauses, or it feels scattered.

> 🚩 These are indicators or "red flags" that the inteviewers are not aligned and there is a lack of understanding and preparation. It doesn't look good.

## Questions as an exercise

Instead, create a document that answers the `why`, `what`, `when`, `who`, and `how` questions. Here are some good questions to answer as an [Interview Team](#create-the-interview-team):

- **What** are the problems we're facing that require us to hire externally?
- **What** are the roles and responsibilities this person will have?
- **What** risks and constraints do we have? (example: budget)
- **Why** is hiring 1 or more people the right approach or solution to these problems?
- **When** would we like our ideal candidate(s) to start?
- **When** do we need to have these problems solved by?
- **Who** is the ideal candidate and what qualities, skills, attributes, etc. do they possess?
- **Who** are the stakeholders (people that care about these problems) and what does success look like to them?
- **How** are we going to find this ideal person?
- **What** questions, scenarios, and challenges will help us identify the ideal candidate as efficiently as possible?
- **How** are we going to ensure that, once hired, they are set up for success?

> 💡 You can add this to your HR/Recruiter software like BambooHR. If that's not available, Google Docs work, but I prefer to version control this in something like GitHub.

Answering these questions together and going through this exercise creates `alignment` and `understanding` between you, hiring managers, upper management, recruiters, and stakeholders. This living document will act as your source of truth as you continue working on things like [Job Descriptions](#create-a-job-description) and the [Interview Process](#create-the-interview).

---

# Create a Job Description

Creating a Job Description (JD) is much easier once you've defined the problem. The main difference between the "problem doc" is that the Job Description is meant to be public-facing, provide a clear and concise description of the position, and **attract talent**.

> 💡 Job Descriptions should never be more than 2 pages. I recommend making it a _single_ page!

## What should a JD include?

Remember, the goal is to attract talent while conveying the most critical pieces about the position. I like to have a layout like this:

### 1. Company Title and Details

Self-explanatory. Company name with any relevant info for the candidate to follow up or submit an application.

- Company logo and/or name
- Title of position
- Hiring Manager contact info (example: email, LinkedIn)
- How or where to apply

### 2. The Opportunity

The "elevator pitch" for why they should be excited for this opportunity. Think of it as a summary of the project and role with some of the main benefits and perks.

- Company description (optional)
- Benefits or main perks
- Summary of the project and role
- **Range of pay (optional, but recommended)**

I highly recommend that you include the monetary compensation. For example, for an Automation Engineer role you may put:

```txt
Full-time (remote or hybrid): $115k - $140k USD
```

> 💡 This has many benefits including helping underrepresented groups get fair pay, but candidates will respect the transparency as well.

### 3. What you'll do

A bulleted list of expectations, responsibilities, activities, and tasks that they will have in this position. For example, a Manager may have:

- Plan work, break down larger stories, and assign tasks to engineers
- Measure progress and KPIs of various projects
- Communicate effectively with engineers and leaders
- Collaborate with other teams (ie Sales, AI)
- Propose budgets for various projects
- Create reports to give updates on projects and engineers
- Onboard and/or train new employees
- Conduct one-on-ones and help engineers grow in their careers

### 4. What you need to succeed

A bulleted list of requirements, skills, knowledge, etc., that you believe the candidate must have to yield the highest chance of success.

> 💡 It's common to also have a BONUS section of "nice to have" items.

For example, a Tester position may have:

- Experience defining personas for testing
- Knowledge of heuristics like Observability
- Comfortable leading pair and ensemble testing sessions with team members (example: devs, UX)

## Support Recruitment

The Problem Definition and Job Description should be _plenty_ for you and your recruiters to effectively find and attract talent. As a hiring manager, I always worked closely with my recruiters. Sometimes this meant pairing on a "phone screen" interview so they had an idea of the initial questions I would ask people. Or they would have a Career Fair opportunity at a university and we'd go as a team.

Recruiting is a full-time job with a lot of moving pieces and asynchronous conversations happening all at once. Do what you can to make it efficient and successful.

---

# Prepare for the Interview

While your recruiters are looking for candidates, you can work on creating the Interview Team and the actual interview. Start by defining the roles that team members will take on. This will help you pick your [core team and backups](#core-team-and-backups).

## Interviewer Roles and Definitions

Within the Interview Team, one person can take on multiple roles. Understanding these roles will help the interview run more smoothly.

> 💡 Feel free to improvise and do what feels natural in the interview.

### Driver

The person “running” the interview. They do the intro, present the agenda, “give the mic” to different people, ask interview questions, and provide the outtro/next steps.

> 🚘 This person sets the tone and rhythm of the interview.

### Interviewer

The person leading the questions, scenarios, and challenges.

Usually the Subject Matter Expert (SME) or person that will work most closely with the candidate if hired. It is up to the Interviewer to decide which questions, scenarios, and challenges to use and which to skip while keeping things flexible if “tangents” or follow-up questions are valuable. Also, allow the Driver or Support to ask follow ups as well.

### Support

The person that “keeps the flow moving smoothly”.

Keep everyone on topic, make sure we are time-boxing things appropriately, ask interview questions, etc. It’s easy for the Interviewer to dive deep into tangents or follow up questions, so make sure we manage our time for other pieces, like giving the candidate 5-10 minutes at the end to ask their questions.

### Candidate

The interviewee. They should be made to feel comfortable and welcome at all times. They should feel excited and that their time is appreciated. We want them leaving the interview with a positive experience, even if we say no.

Yes, we want to find the best candidate as quickly as possible, but never at the cost of hurting the person. I have ended interviews early, and yet the candidate has a good experience. I don't think any interviewer wants to see a candidate struggle or fail, so when that happens, guide them through and make the impact small - especially if you know they've "bombed" the interview.

> 💡 My goal is always to create an awesome experience for the candidate so that, even if we say no or end early, they know what to work on next and want to apply again when they're ready!

## Create the Interview Team

I like to use the `Rule of 3`.

- DO NOT have more than 3 interview rounds (including the "phone screen")
- DO NOT have more than 3 interviewers in a single session within each round

Taking more than 3 rounds becomes more time consuming and expensive for you and the candidate, but that usually means that your Interview Process is flawed. It shouldn't take you more than 3 rounds (~6 hours) to make a decision!

> ⚠️ As with many rules and "best practices", use them as guidelines. For example, hiring a Director or VP will probably take more time.

### Rounds and Sessions

Quick definitions:

- `Interview Process` is the "pipeline" or steps a candidate goes through from when they enter your system to when a _go_ or _no go_ decision is made.
- `Interview Round` is a scheduled day for the candidate to meet with someone from your company.
- `Interview Session` is a meeting with a group of people with a different context and goal.

I like to have three interview rounds - each with a single session - for any non-leadership role. For example:

**Round 1 (30-60 min)** - Phone Screen with a recruiter. The recruiter should know what we're looking for and what questions to ask.

- This is a single session because you get a single phone call from one recruiter

**Round 2 (1-2 hrs)** - Technical Interview with my Interview Team. Can the person do what we need them to do for our short- and long-term goals?

- Candidate meets with the Interview Team for a single session
- If we had them meet with another group to do a different assessment, that would be the second session

**Round 3 (1-2 hrs)** - Culture fit with team members and leadership. Are they the right fit for everything else? (example: culture)

- Candidate meets with their potential teammates and leaders
- You may split this into two sessions where one is with testers and another with devs if that's the org structure you have

So, it's important to know what you want your whole Interview Process to look like. Each round and each session will require more coordination and people's time. Remember, we want to be efficient and effective!

### Core Team and Backups

The overall Interview Process is most effective when you have a consistent "core" team that sees and interviews every candidate. Interviewing is a skill, so growing that skill together will not only improve the quality of the interviews, but also make it easier to train up new interviewers.

The core team for each round will consist of 2 or 3 people. As you saw in the [Roles and Definitions](#roles-and-definitions) section, you want to fill each role. For example, recently I was hiring an Automation Engineer and my core team consisted of:

#### Technical Interview Team

- Dan, Engineering Architect as `Support`
- Me, Director of Engineering as `Driver` and `Interviewer`
- [open space], maybe to train a new interviewer or show a junior- to mid-level engineer, etc.

#### Culture Fit Interview Team

- DJ, Cloud & Infrastructure Engineer as `Support`
- Our CEO as `Interviewer`
- Me, Director of Engineering as `Driver`

Then, I had backups in case anyone on my core team was unable to make it (ie on vacation, sick)

- Derek, Senior Software Engineer as `Support`
- Ujjwal, Senior Software Engineer as `Support`
- Alina, Software Engineer as `Support`
- ...

### Never Interview Alone

Never interview alone. The biggest reason is to protect you and the company legally, but other benefits include checking and balancing biases, and having insights from different perspectives.

## Create the Interview

At this point you should have [defined the problem](#define-the-problem), [created a job description](#create-a-job-description), [formed the Core Team](#core-team-and-backups), and have an [interview process](#rounds-and-sessions) in place. Now you can create the actual interview for each round. Your goal in each round is to accurately assess the candidate and answer any questions or risks you and your team have. You use questions, scenarios and challenges to do this and, as always, we create documentation for each interview.

### Technical Interview

_Does the candidate have the skills, qualities, and attributes required to be successful?_

I like to start with the Technical Interview because that is the easiest to assess. Otherwise, you may really like the person just to learn later on that they can't do the job.

> If we are using a GitHub repo for our interviews, I'd call this document something like `technical-interview.md`

#### Questions

Create a pool of 10-20 questions that your team feels will best help you assess the candidate. These are usually `open questions` which allow the candidate to answer with stories and examples, but also allows you to see their thoughts, beliefs, strategies, and philosophies.

Try to avoid closed questions. You won't get a lot of insight from them. For example:

```txt
Do you think bug counts are a good way to evaluate a tester?
```

The spirit of question is there, but it's pretty obvious what the answer is - NO! Instead, turn it into an open question to really dive into what they think:

```txt
How would you evaluate a tester to know if they are good or great?
```

> This means you will get different answers from each candidate which can make it difficult to compare, but that's much better than having 10 candidates say "no" to the closed question.

I asked the QAP Community which questions they like to ask Testers in an interview, and here are some of the results which we can add to our `Questions` section in the doc:

- How do you stay up-to-date on the current trends in testing?
- How would you test `X`? (replace `X` with things like _Vending Machine_, _Rubik's Cube_, _Water Bottle_, etc.)
- How do you start your work day?
- If you could own the entire dev process from Planning to Release, what would the ideal process look like in order to deliver the highest quality output?
- Tell me about a time when you have disagreed with a dev on a requirement. How did you resolve it?
- How do you establish acceptance criteria with test plans and test cases?
- Where do quality gates live and how do you establish them?
- What is the best use of automation for software quality?
- How would you maintain bugs and track them?
- What CI/CD tools are you familiar with? How did QA interact with those tools?
- How did test automation run within the software delivery pipelines?
- How do you stay motivated?
- How do you deal with changes in work priorities and stay organized?

This is a good starting list, and will probably change later, but you don't need to fit all of them in an interview. You may only have time for 5-10 questions, but you can pull from this list and see which questions will be most effective for any given candidate.

#### Scenarios

In this section, add 3-5 scenarios that pose a problem that the candidate must work out a solution(s) to. The candidate is now designing and implementing theoretical ideas and solutions while having to describe why.

> You join a team that is looking to add Bitcoin as a new payment option at checkout. They want your experience and expertise to make sure this is done correctly since Payments is a crucial service to the business. They are starting on the design and strategy before doing any coding. How would you start?

They have context and the beginning of a scenario, but this can go _so many ways_, so you need to define what you're looking for with this scenario. Are you hoping they say that they will add automated tests using Cucumber? What if they never mention Cucumber and mainly talk about risk storming and requirements gathering at the beginning? Would they fail your scenario or not?

I look for a few things when it comes to scenarios, but here are some examples to give you some inspiration:

> Do they ask questions? If so, which questions do they ask?

The scenario provides a good amount of context, but there are still unknowns. I've had candidates ask me a wide range of questions with this scenario:

- Do we have wireframes for what this is supposed to look like?
- Why are we adding Bitcoin as a payment option? What about other cryptocurrencies?
- How many people will be working on this with me?
- What is the timeframe?
- Do we have existing tests for the Payment Service and other payment options?
- Is this web-only or do we have a mobile app?
- What business metrics will help us know if this new feature is successful? For example, do they hypothesize that 25% of transactions will come from Bitcoin?

> Which testing activities do they gravitate to? What do they focus on?

An unfortunately common response I get is the candidate will begin to list a large amount of test cases. _"I would test it in Dark Mode"_, _"I would checkout with sufficient bitcoin funds and insufficient bitcoin funds"_, etc. Yes, I want testers to think outside the box and be creative enough to design tests like that, but not yet. This tells me that they are more used to writing a bunch of test cases and then executing them "regression-style" which I don't think is very valuable long-term.

> What kind of Tester are they? What does Holistic Quality mean to them?

The best testers I know are able to take a scenario like this and walk through everything they'd do from the inception of the idea all the way to deploying and observing it in Production. There is more to testing and quality than the bitcoin payment option working when I test it!

And this is only the beginning of the scenario! As they ask questions and we progress in our _theoretical_ scenario, I continue to add more obstacles to it. For example:

> Ok, now the feature is implemented and tested. We're ready to push to Production! Now what do you do?

As you can see, you can take these scenarios as far and as deep as you need to give you all the insights required to assess the candidate. Get creative with Scenarios!

#### Challenges

These would be things like coding challenges. You can think of it as an exercise that has a pretty clear input and output. For certain roles, you might not have any challenges or exercises and that's totally ok! However, many roles - especially programming roles - will usually have at least one challenge.

Now, this can take many forms and the most common (as of this writing) are white board challenges and homework assignments. To be clear, I DO NOT like whiteboarding or homework assignments!

##### Whiteboard Challenge

This is where the interviewer poses a challenge and the candidate uses a marker and whitebaord to solve it. As programmers, we use tools and apps to write code and build software. So when an interviewer asks us to write code with a marker, without the tools we're used to, how is that an accurate assessment of the candidate? It's not, and puts the candidate in a difficult situation that only adds more stress and makes a lower quality experience for them.

##### Homework Assignment

Ok, then let's give the candidate a project to work on at home so they can use their tools and do things on their own time without having to be in front of people. It sounds great, but these types of assignments are usually larger and require hours or days for the candidate to finish it. I've seen inteviewers give assignments and say, "This should only take about 2 hours, but get it to us as soon as you can".

The interviewer may see the assignment as small and easy, but the candidate will spend way more time because they want to submit the highest quality solution they can. They might spend the next 24 hours on this and lose sleep and time with their family because they want to do it right. It makes for multiple days of stress for the candidate which leads to a lower quality experience for them.

##### Pair and Collaborate

Instead, I like to pose a challenge to the candidate and pair with them on a solution! I will show two examples that I have used in the past to help assess programming and design ability - especially for Automation Engineers. I use Python, the language of Data and Automation, even if they don't know Python. I'm not testing their Python skills, but rather:

- How do they collaborate with me?
- What questions do they ask?
- Are the humble?
- Can they take constructive criticism?
- Do they know enough about programming principles to be successful in the role (example: design patterns, testing techniques, debugging)?
- Can they walk through code and explain their decisions?
- Can they describe pros and cons of different approaches?
- and more!

What makes this unique is that I share my screen and drive the keyboard. In other words, I will do all the coding and typing. They just need to describe what they'd like to do and I will do my best to interpret and implement it. We give each other feedback and use any tools to solve the problem (example: VS Code, search for answers on Google, etc). This takes a lot of the pressure off of them and we usually have a good time :)

> I've been told by many candidates that this part has been the best "coding challenge" that they've ever experienced!

##### Find the Bug and Fix It

For this challenge, I provide a function that takes a string and returns `True` if it is a _palindrome_ and `False` if not. Then there are test functions that use different examples to test the function. Here's the code:

```python
def is_palindrome(sequence):
    return sequence[0] == sequence[-1]


def test_aa_is_palindrome():
    assert is_palindrome('aa') is True


def test_ab_is_not_palindrome():
    assert is_palindrome('ab') is False


def test_cac_is_palindrome():
    assert is_palindrome('cac') is True
```

There are 3 steps to this challenge:

1. Identify the flaw in the code (there's a BIG one)
2. Prove it by writing a new, failing test
3. Fix the code so all tests pass

Then I share my screen and ask, "where do you want to start?". I time box this challenge for 10 minutes. It may look very simple, but when you're in a high pressure environment, it's easy for nerves to make this harder. Yes, this is an easier one, but it really breaks the ice and gets the candidate comfortable and ready for the next challenge which is a lot more complex.

##### Consume a REST API to build the game of War

In the next challenge, this is what they have to work with at the beginning:

```python
""" Build the game of War!

Using https://deckofcardsapi.com, build a Console Game of the popular game called "War"

WAR
---
1. Shuffle a deck of face cards
2. Draw two cards
3. The highest card wins!

Requirements:
-------------
* There must be tests!
* Although 100% Code Coverage is good to have, we want to have quality tests that cover the behaviors we care about
"""
import requests
```

By this time, the candidate is aware of how the pairing and collaboration with me works, but this challenge is more difficult. In my opinion, Automation Engineers should know way more than just Selenium or Cypress, and this challenge helps me assess how good their Software Engineering skills are rather than how good you are with a single library. The beauty of challenges like this is you can steer it in different directions or increase or decrease the difficulty as needed.

For example, you can make Test Driven Development (TDD) a requirement, or ask to optimize the performance of the program. You can open Postman if you want to see their familiarity with that tool or give them hints to guide them to a solution. It's up to you as the Driver and Interviewer!

> As always, your challenges should help answer questions and risks you have about the candidate so you can confidently make a decision.

### Culture Fit

If done right, there shouldn't be any more "technical" assessment required for the final round. If so, make sure this interview team is aware of the gaps or questions you want to have answered so they can address it. Otherwise, it's time to see if this person is a good match for us in terms of people and process.

You often hear the term "culture" at a company, but what does that mean exactly? Well, as with many things, it depends. However, company culture comes from a few things:

- Company
- Leaders
- Goals
- Values
- People
- Products
- Customers

> What matters to the company and its leaders, and what do they do about those things?

For example, if I say that diversity and inclusion matter to me and my company, then I better have examples of how we put that into action and _make it matter_. If I say that quality and doing things right matter here, but people commonly work 10-12 hour days because we care most about our burndown chart and velocity, our actions say that our culture is more about output and deadlines.

> If you're the candidate, you need to ask questions to make sure the company is a good fit for you too!

You and your Interview Team should know what these goals and values are. You should have an idea of what the culture really is or what you want it to be. People make the culture - especially leaders - so you want the candidate to resonate and align with the culture so it continues to grow in the right direction.

Just like the [Technical Interview](#technical-interview), come up with questions and scenarios (maybe not challenges) to help you assess the kind of person they are, and if they have the qualities and attributes you're looking for.

- How do they handle adversity?
- How would they convince upper management of an initiative they want to start?
- What kind of leader would they be?
- How would they excel in their role?
- Will they uplift others around them or bring them down?
- How do they learn?
- How do they work with others?
- Are they trustworthy and accountable?
- etc.

---

# Conduct the Technical Interview

Preparation is complete and a candidate is scheduled for the [Technical Interview](#technical-interview)! You should have a resume (aka "CV") from the candidate and hopefully a portfolio. Create a new doc for the candidate (maybe `candidate_name.md`) to track ratings, performance, and notes.

## Review the Resume and Portfolio

Make sure each Interview Team member gets a copy of the resume and portfolio, and have each member go through them on their own. While doing this, take notes and write down questions and concerns you have about the candidate against the role we're hiring for.

For example, let's say that this is the summary the candidate has for their previous role:

- Create and executed test cases utilizing Azure DevOps to verify Web Applications specifications are met by analyzing expected input/output results.

- API testing using Postman

- Executed various testing methods such as black box, functional, regression and user acceptance testing to validate requirements are met.

- Created defects found in the application and escalate to the appropriate developer

- Ensured that validated deliverables meet functional and design specifications

- Interacted and communicated with business analysts, project managers, developers, internal/external clients and senior management to manage issues throughout the software testing life cycle using Agile and Waterfall methodologies

Take a moment to write down things you like and questions or concerns you have about this person.

Some of my notes may look like this:

- `Azure DevOps (ADO)`
  - Did they actually work with ADO or were tests executed there and that's it?
  - Which services within ADO are they familiar with?
  - We use AWS instead. Would they be able to make the switch and pick it up?
- `"verify Web Application specifications are met"`
  - How did they come up with these specs?
  - Given a spec, how do they know which tests to create?
  - How are they doing CI/CD?
  - What's the process for when tests fail?
- `API testing using Postman`
  - Excellent! Our second coding challenge should be easier for them.
  - Was it as REST service? or gRPC, GraphQL, etc.
  - We use microservices and serverless architectures. Do they have experience in that kind of ecosystem?
  - How did they test their APIs (manual and automated)?
- `Executed various testing methods...`
  - It all seems like functional styles of testing. What else have they done? (ie Performance, Accessibility, Monitoring)
  - They separate black box, functional, regression, and user acceptance, but those all seem really similar to me. I'd love to hear what they did and how.
- `Created defects found in the application...`
  - What was their bug/defect processes? Did they like it? What would they change?
  - How did they triage and prioritize bugs/defects?
- `Ensured that validated deliverables meet functional and design specifications`
  - Didn't they say this already before?
  - What is a validated deliverable? Wouldn't that mean it meets functional and design specifications?
- `Interacted and communicated with [stakeholders] to manage issues throughout the software testing life cycle...`
  - Having a software testing life cycle feels like traditional testing. I want to hear how they describe this and what the pros and cons are compared to more modern approaches
- `...using Agile and Waterfall methodologies`
  - I want them to expand on these methodologies and their philosophies around Agile and overall processes and practices
  - What would the ideal "Agile" environment look like for them?

Just from this small, bulleted summary, I can get a lot of insights into what they did and how they think. It says a lot even though there are only 6 lines. There are questions and concerns that are more _severe_ than others, but I can now share this list with the rest of my team and compare notes.

> If you are a candidate, make sure every section and line in your resume is impactful and meaningful. If you'd like help with your resume, please reach out in the `#general` or `#career-prep` channels in our Slack group, or create a [Discussion](https://github.com/qa-at-the-point/base/discussions) in our Knowledge Base.

Our Job Description and recruiters tell the candidate to submit a portfolio as well. This may be a single repo, a portfolio website, or an entire GitHub profile. We review it the same way. Look through the portfolio, takes notes and write questions, compare notes with the team, and use the portfolio and notes in the interview.

> If you are a candidate, you _should_ have a portfolio. You are doing yourself a huge disservice if you don't have one. If you'd like help with your portfolio, please reach out in the `#general` or `#career-prep` channels in our Slack group, or create a [Discussion](https://github.com/qa-at-the-point/base/discussions) in our Knowledge Base.

## Curate the Interview

At this point, we have a great list of questions, scenarios, and challenges to assess the candidate. We also have a list of risks and concerns. However, we have a finite amount of time to interview. So, with your team, select which `questions`, `scenarios`, and `challenges` that will help you the best.

To help, I use a simple **5 Star** rating for each candidate. After reviewing the candidate's resume and portfolio, each member provides a _star rating_. For example, Dan may start with `4/5` and I may have `3/5`. We discuss why we gave the star rating (which gets the team aligned) and makes the curation easier.

> Ideally, when we say YES to someone, they are 5/5. However, you're really looking to check and resolve every question, concern, and risk you have so you are excited about the candidate. Curate your interview to do exactly this. The best feeling is when the entire Interview Team is genuinely excited about the candidate and ready to hire them!

- **0 stars**: Strong NO. I would never want to work with this person (very rare)
- **1 star**: No. Not what we're looking for (rare)
- **2 stars**: No. Not quite ready. Too many concerns and risks unresolved (common)
- **3 stars**: On the fence. More investigation needed since there are still unresolved concerns and risks (common)
- **4 stars**: Yes. Move the candidate to the next round since they resolve most concerns and risks (common)
- **5 stars**: Strong YES! Few concerns and risks. Can we hire the candidate right now (rare, but so exciting!)

## Run the Interview

Finally, it's time to meet the candidate for the infamous Technical Interview. We've done all the planning and preparation in previous sections, so I'll focus on agenda, flow, and tips in this section.

> COVID forced many things to be remote, so this will come from the perspective of a remote interview. There's not much difference besides maybe giving the candidate a small tour of the building and amenities.

### Agenda

Your agenda may vary, but I'll show a 2hr format as a good starting place. Make sure to provide an estimated timebox for each part.

#### Welcome and Intro (5 min) [Driver]

The Driver welcomes the candidate, introduces themselves and the other interviewers, and presents the agenda. Then ask the candidate to introduce themselves.

#### Move to Questions (30 min) [Interviewer]

> Driver "passes the mic" to the Interviewer to start on our curated list of [Questions](#questions).

It is common to dive deeper into a question or follow a tangent. That's ok and recommended since they usually help resolve concerns and risks. Just know that you will run out of time to ask other questions and the Support may nudge or remind you about the time box.

I've had times where I had 10 questions ready to go and only got through 4 or 5 of them because we dove deeper and went on tangents! Always do what feels natural.

#### Move to Scenarios (25 min) [Driver | Interviewer]

> Interviewer "passes the mic" to the Driver to start on our curated list of [Scenarios](#scenarios).

Similar to questions, you can take Scenarios as deep or as wide as you need. Usually the Candidate will have a lot of questions (as they should), so be sure to have answers for all of them. You may need to improvise on the fly to keep the scenario and context moving!

#### Move to Challenges (30 min) [Interviewer]

> The Interviewer shares their screen with the first challenge up and ready to go.

I use VS Code as the editor, but use what works for you. Remember, we aren't assessing the Candidate's "VS Code ability", so it's ok if they've never used it before. We care about how they approach the problem, the questions they ask, and how they work with me.

> I drive the mouse and keyboard while the Candidate describes what they want. With their ideas and instructions, I try to do it!

Similar to Scenarios, we can take each challenge as deep or as wide as we'd like, but collaboration and guidance from our side (without giving them the straight solution) is key to the challenge being successful. For example, if the candidate gets stuck on something or goes quiet, ask questions or provide hints that will help them move to the next step on their own.

- 1st Challenge (10 min)
- 2nd Challenge (20 min)

The second challenge is difficult to complete in 20 minutes (some do, which usually gets them a 5/5 rating on the challenge). At the beginning of the second challenge, I tell the Candidate that we most likely won't finish, but that's ok. Instead, "let's get **as far as we can** doing it the way **you feel is best**".

> Not suprisingly, the Candidates that use a TDD approach are more likely to finish the challenge with a working solution. Candidates that skip tests and go directly into creating the program almost always get stuck with no easy way to workaround or resolve it.

#### Candidate Questions (10 min) [Driver]

Give the Candidate 10 minutes to ask their questions. By default, the Driver will answer the questions unless:

- The Candidate directs the question to a specific person
- The Driver wants a specific person to answer it

This leaves control of the flow with the Driver. It's extremely rare that a "risky" question is asked, but just in case, the Driver can intercept or redirect as needed. For example, I once had a candidate ask how one of our proprietary systems worked. One of the senior engineers started diving into details and I had to quickly cut them off and intercept the question. I still provided an answer, but it was one that also had the business's interests in mind.

#### Outtro and Next Steps (5 min) [Driver]

Thank the Candidate for their time and provide next steps.

I usually say something along the lines of:

> Thank you, X, for taking the time to meet with us today! When you exit the call, we're gonna stay after and talk some more, but give us 2-3 business days to get back to you. I'll be sending you an email at example@test.com with the next steps, but feel free to reach out if there's anything else you'd like to discuss. Thanks again and have a quality day!

## Post Interview

With the Candidate gone, spend another 10-15 minutes as a team to assess the Candidate's performance and hold a small retrospective.

### Assess

With the interview fresh in our minds, talk about the Candidate and how they did. By the end, each team member should have a new star rating for the candidate. I like to use the `Fist of Five` to quickly gauge this. Each team member raises their hand and shows the number of fingers (aka stars) they want to give.

I discussed the star rating in the [Curate the Interview](#curate-the-interview) section, but we need to make a decision to reject the candidate or move them to the next round:

- 0-2 stars: Reject. The candidate was unable to convice the team and resolve questions, concerns and risks.
- 3: Reject or Next Round. This usually leads to a rejection because "being on the face" is a red flag. What's holding you back? Discuss as a team.
- 4-5: Next Round. The team is excited about the candidate and wants to move to the next round.

### Retrospect

With a decision in place, now it's time to have a mini retrospective to assess how _we_ did as an Interview Team.

- What did we do well?
- What didn't go so well?
- How will we improve?
- What will we change or try next time?

As with any retrospective, we want to genuinely reflect how we did so we can learn and get better. Interviewing isn't easy, but feedback is important for improvement.

---

# Conduct the Culture Interview

The agenda and flow are very similar to the [Technical Interview](#conduct-the-technical-interview), but now you're going to use the questions, scenarios and challenges you defined in the [Culture Fit](#culture-fit) section.

For non-remote positions, this is where I'd spend a good amount of time giving the candidate a tour and "showing off" what we have to offer. We want them to be excited about the company and opportunity, and a tour is a great ice-breaking way to do this!

> Besides that, you may have them meet key team members and leaders or visit key points in the building before going into the meeting room to start the interview.

I like to take people to lunch or coffee! Be creative with how you attract talent and make people feel special. This round, for me, would look like this:

- Meet at office, go eat lunch with candidate and Interview Team (1 hr)
- Tour of Building (15 min)
- Questions (30 min)
- Scenarios (10 min)
- Candidate Questions (10 min)
- Outtro and Next Steps

Then [Assess](#assess) and [Retrospect](#retrospect) again!

---

# Final Decision

All the evidence is gathered and it's time to make a final decision. Hopefully it's a YES so you can send that awesome email and get other accounting items finalized (stocks, salary, sign-on bonus, etc)!

I hope this post was helpful for you to get a standardized Interview Process in place. Anyone can interview, but it's hard to interview well. Now you have ideas, concepts, and practical examples to make a process where you conduct high quality interviews.

️🎉 Happy interviewing and have a quality day!
