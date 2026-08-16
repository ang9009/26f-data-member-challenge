# Interview invitation email

Hey Alvin,
Thank you for applying to be a Generate Member for the Fall 2026 semester! We appreciate your application and the time you've put into thinking about this role. We would love to sit down and have a chat with you and ask you more questions!
Interview Details:

    45 minutes, virtual.
    The format of the interview will be as follows:
        Introduction about Generate & the Branch this semester
        Talking through a required technical challenge that should be completed prior to the interview (more details are given at the end of this email)
        A walkthrough of a coding project you are proud of and passionate about (more details are given at the end of this email)
        General Questions (a few are given at the end of this email)
        Plenty of time for you to ask any questions
    Please fill out this Calendly with your availability ASAP -> calendly.com

Technical Challenge:
The following technical challenge is required and must be complete prior to your interview. Please come prepared to discuss design choices you made and the approach you took:
Your challenge is to predict developer salaries from a real survey dataset we'll provide (about 5,000 responses). Build a model that predicts annual_salary_usd. Real data is messy. Noticing how is part of the exercise.
AI tools are allowed and expected. You'll walk through your submission live in your interview and we'll ask detailed questions about your specific choices, so understand every line you submit, including anything AI wrote. A simple approach you can fully explain beats an impressive one you can't. Expect 2 to 3 hours of work.
Optional additions (pick one if you want to go further):

    a more rigorous ML pipeline with proper validation and feature engineering
    a frontend/dashboard to display the data and your predictions
    an additional API connection that enriches the dataset with outside data.

Additions are a bonus, not a requirement. A clean base submission is a complete submission.
Start the tech challenge through this repo: https://github.com/mmaaseide23/26f-data-member-challenge
Project Walkthrough:
Walk me through a coding project you've built that you are passionate about. We’ll pull it up in VS Code so you can show your interviewer the code directly. Spend a few minutes giving an overview of what the project is and how it works, then we can dig into more specifics.
A few ways to add to your walkthrough are:

    Presenting a project that involves working with data or machine learning
    Presenting a project that built some kind of web application
    Presenting a project that you worked on with a team
    Running the project live to show its usability

General Questions:
In general, you can anticipate questions about your background, your interest in Generate, and about who you are as a person. Here are some possible questions that we could ask:

    How do you use ambiguity to drive your actions in your daily life?
    Teach me about something nontechnical that you are passionate about.
    What is over-fitting, and how would you correct it?

Please note, this is NOT an extensive list of questions; we might ask more or less depending on the interviewer.
As mentioned earlier, there will be plenty of time for you to ask questions at the end!
Interview Tips:

    Evaluate your options, justify your decision, bounce ideas with your interviewer
    Successful candidates ask clarifying questions before beginning the prepared question and follow up with questions throughout

If you have any questions or would like clarifications, feel free to respond to this email!
Best,
Vichu Selvaraju

# Technical Challenge

## The challenge

Your challenge is to predict developer salaries from a real survey dataset
(about 5,000 responses), included here as `data/survey.csv`. Build a model that
predicts `annual_salary_usd`.

This survey is published as-is, so expect to spend time determining what data you actually have before starting.
Look at it column by column, decide what to do about what you find, and be ready to say why you did it that way.

There's no particular set of fixes/steps we're looking for. We just want to understand what you found, how you
went about it, and why.

**AI Usage Info**

AI tools are allowed and expected. You'll walk through your submission live in
your interview and we'll ask detailed questions about your specific choices, so
understand every line you submit, including anything AI wrote. A simple
approach you can fully explain beats an impressive one you can't.

## Optional additions 

Pick one if you want to go further:

- a more rigorous ML pipeline with proper validation and feature engineering,
- a frontend/dashboard to display the data and your predictions, or
- an additional API connection that enriches the dataset with outside data.

**Additions are a bonus, not a requirement. A clean base submission is a
complete submission.** We would much rather see a straightforward model you
understand completely than an ambitious one you're guessing about during the interview. 
Every minute spent on an addition is a minute not spent being able to explain your core work.
These additions should be built on an already solid core submission.

---

## Getting started

You're working in your own private repository, created when you accepted the
assignment. Clone it and go:

```bash
git clone <your-assignment-repo-url>
```

```bash
pip install -r requirements.txt
```


## Submitting

**Commit and push to your assignment repo before your interview time**
Your last push before your interview is what we review. There's no separate
submission step.

Your repo should contain:

1. **Your code.** However you'd normally organise it — a notebook, a script, a
   small project. It doesn't need to be production-grade.
2. **Your predictions or your metrics** — enough that we can see how well it
   worked, in whatever form makes sense for what you built.

Commit as you go rather than in one push at the end. We don't grade commit
history, but it protects you from losing work.

## Practical notes

- **Language and tools are up to you.** Most people use Python with pandas and
  scikit-learn, and `requirements.txt` covers that.
- **There is no target score.** We are not ranking submissions by accuracy. A
  model with modest error and clear reasoning scores better than a strong one
  you can't account for. This is a genuinely hard prediction problem and the
  numbers are meant to look modest.
- **Don't over-engineer.** 2 to 3 hours is the intended scope. If you find
  yourself at hour six, stop and write up what you have.
- **Bring your submission to the interview**, on your own machine, ready to open
  and run. Have it up before we start.
- **Questions?** Ask Michael Maaseide (maaseide.m@northeastern.edu) or Samuel Baldwin (baldwin.sam@northeastern.edu). Asking a
  clarifying question is not a mark against you.

## How we'll evaluate it

We're interested in your reasoning far more than your results. During the
interview we'll ask about:

- **What you noticed in the data** and how you decided what to do about it.
  Where you made a judgement call, we'll ask why you made it that way.
- **Your modelling choices** — why that model, how you know it works, what you
  compared it against.
- **Your code** — we'll pick a few specific lines and ask what they do and why
  they're there. This applies equally to code you wrote and code an AI wrote for
  you.
- **What you'd do differently** with more time, and what you think the
  weaknesses are.

---

## The data

`data/survey.csv` — 5,000 responses, one row per respondent. These are
professional developers who answered the compensation question in the **Stack
Overflow Annual Developer Survey 2025**, published by Stack Exchange under the
[Open Database License](https://opendatacommons.org/licenses/odbl/1-0/).