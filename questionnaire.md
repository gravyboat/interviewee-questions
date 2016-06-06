# Interviewee Questionnaire

This questionnaire covers a wide range of topics an interviewee should
understand about a company before moving forward in the hiring process. While
the answers to some of these questions may fall under NDA, any answers a
company can make public should be made public to lessen the need to answer them
repeatedly on a per-candidate basis.

# Table of Contents

  * [Questions](#questions)
    * [1. Technical](#1-technical)
      * [1.1 Describe the deployment process for the primary application](#11-describe-the-deployment-process-for-the-primary-application)
        * [1.1 Answer](#11-answer)
      * [1.2 Describe the process for deploying security patches / OS updates](#12-describe-the-process-for-deploying-security-patches--os-updates)
        * [1.2 Answer](#12-answer)
      * [1.3 Describe the development environment](#13-describe-the-development-environment)
        * [1.3 Answer](#13-answer)
      * [1.4 Describe the test environment](#14-describe-the-test-environment)
        * [1.4 Answer](#14-answer)
      * [1.5 Roughly what percentage of code is in what language?](#15-roughly-what-percentage-of-code-is-in-what-language)
        * [1.5 Answer](#15-answer)
      * [1.6 Any near-term future plans to dramatically change programming languages?](#16-any-near-term-future-plans-to-dramatically-change-programming-languages)
        * [1.6 Answer](#16-answer)
      * [1.7 Describe an outage, the RCA and AAR, and any followup.](#17-describe-an-outage-the-rca-and-aar-and-any-followup)
        * [1.7 Answer](#17-answer)
      * [1.8 On-call and number of incidents / outages](#18-on-call-and-number-of-incidents--outages)
        * [1.8 Answer](#18-answer)
      * [1.9 Operational pain points](#19-operational-pain-points)
        * [1.9 Answer](#19-answer)
      * [1.10 Roadmap](#110-roadmap)
        * [1.10 Answer](#110-answer)
    * [2. Managerial](#2-managerial)
      * [2.1 Employee productivity](#21-employee-productivity)
        * [2.1 Answer](#21-answer)
      * [2.2 Employee reviews](#22-employee-reviews)
        * [2.2 Answer](#22-answer)
      * [2.3 Office hours](#23-office-hours)
        * [2.3 Answer](#23-answer)
    * [3. Employee Compensation / Quality of Life / Benefits](#3-employee-compensation--quality-of-life--benefits)
      * [3.1 Salary](#31-salary)
        * [3.1 Answer](#31-answer)
      * [3.2 Equity](#32-equity)
        * [3.2 Answer](#32-answer)
      * [3.3 Healthcare](#33-healthcare)
        * [3.3 Answer](#33-answer)
      * [3.4 Retirement fund](#34-retirement-fund)
        * [3.4 Answer](#34-answer)
      * [3.5 Employee space](#35-employee-space)
        * [3.5 Answer](#35-answer)
      * [3.6 Vacation policy](#36-vacation-policy)
        * [3.6 Answer](#36-answer)
      * [3.7 Expense policy](#37-expense-policy)
        * [3.7 Answer](#37-answer)
      * [3.8 Questions asked](#38-questions-asked)
        * [3.8 Answer](#38-answer)
    * [4. About the company](#4-about-the-company)
      * [4.1 Transparency](#41-transparency)
        * [4.1 Answer](#41-answer)
      * [4.2 Funding](#42-funding)
        * [4.2 Answer](#42-answer)
      * [4.3 Competition](#43-competition)
        * [4.3 Answer](#43-answer)
      * [4.4 Strategy](#44-strategy)
        * [4.4 Answer](#44-answer)

# Questions

## 1. Technical

### 1.1 Describe the deployment process for the primary application
One of the best indicators of the day to day quality of life for a technical
employee can be reflected in the deployment process of a company's software. A
great low friction deployment process requires a lot of tooling and thought.
Describe the process of deployment for the primary application from developer
commit to production.

#### 1.1 Answer
**Fill me out**

- [ ] Mandatory code reviews (no unreviewed code gets deployed).
- [ ] End to end fully automated. Humans only commit. Software does the rest.
- [ ] Fully automated test suite.
- [ ] 100% test coverage.
- [ ] Fully automated production deployments.
- [ ] Canary deployments.
- [ ] Staggered deployments: 0.1%,1%,10%,20%,50%,75%,100% (vs all or nothing)
- [ ] [Simian army](http://techblog.netflix.com/2011/07/netflix-simian-army.html)
      -esque testing in production.


### 1.2 Describe the process for deploying security patches / OS updates
Similar to the above, please describe the process for patching security
vulnerabilities and deploying software updates in the environment, if
applicable.

#### 1.2 Answer
**Fill me out**

- [ ] Fully automated. We patch as soon as upstream releases updated software
  and the patch has gone through automated testing.


### 1.3 Describe the development environment
Describe the development environment? How closely does it resemble the production
environment? How long does it take to set up? What OS is it based on? How
flexible is it with respect to allowing me to use whatever tools I want to use
that will make me the most productive (ex. the dev environment is CentOS 6 but I
want the latest version of emacs)?

#### 1.3 Answer
**Fill me out**


### 1.4 Describe the test environment
Similar to 1.3, if applicable.

#### 1.4 Answer
**Fill me out**


### 1.5 Roughly what percentage of code is in what language?
Are you mostly a Python shop with some Java? Explain.

#### 1.5 Answer
**Fill me out**


### 1.6 Any near-term future plans to dramatically change programming languages?
Related to 1.5, are you having any scaling pains or accumulation of technical
debt that's becoming burdensome? Any plans for a rewrite into another language?

#### 1.6 Answer
**Fill me out**


### 1.7 Describe an outage, the RCA and AAR, and any followup.
This question seeks to understand the more operational aspects of your
infrastructure. [Outages happen to
everyone](https://github.com/blog/2101-update-on-1-28-service-outage). We want
to understand what if any monitoring is in place. If someone is getting paged,
who is it? What, if any warnings were there prior to catastrophe? Were there
backups (if applicable)?  What was the followup? Was automation put in place to
ensure the situation could not happen again? Describe the AAR, if applicable. Do
you practice [Blameless
PostMortems](https://codeascraft.com/2012/05/22/blameless-postmortems/)?

#### 1.7 Answer
**Fill me out**


### 1.8 On-call and number of incidents / outages
What does the on-call rotation look like? Who carries the pager for how long?
For the average on-call shift, how often should someone expect to get paged? Is
there a separate operations group that solely carries the pager or is the burden
also shared by the development team? If developers are exempt from on-call, is
there any plan to incorporate them into the rotation?

#### 1.8 Answer
**Fill me out**


### 1.9 Operational pain points
What are the biggest operational pain points?

#### 1.9 Answer
**Fill me out**


### 1.10 Roadmap
What does the product roadmap look like? How is the backlog prioritized: new
features vs bug fixes? Roughly what percentage of time is spent developing new
features vs fixing bugs?

#### 1.10 Answer
**Fill me out**


## 2. Managerial

### 2.1 Employee productivity
How is employee productivity measured? What does success look like for a given
position?

#### 2.1 Answer
**Fill me out**


### 2.2 Employee reviews
How often and by whom are employee reviews conducted? What methodologies if any
are used for the review process? Do skip level employee 1-on-1s occur?

#### 2.2 Answer
**Fill me out**


### 2.3 Office hours
How flexible are employee office hours with respect to start/stop/lunch times?
Does the company allow telecommuting? How frequently? Are there core hours?

#### 2.3 Answer
**Fill me out**


## 3. Employee Compensation / Quality of Life / Benefits

### 3.1 Salary
Do employees get regularly occurring raises? What criteria is used to determine
the amount of the raise. Are there yearly cost of living adjustments? Is this
rolled into the raise or on top of it?

#### 3.1 Answer
**Fill me out**


### 3.2 Equity
Are employees granted equity or profit sharing? If equity, in what form? If as
stock/options: how many shares are outstanding, what is the strike price?

#### 3.2 Answer
**Fill me out**


### 3.3 Healthcare
Describe employee health coverage. What providers are available? When do health
benefits kick in? Does your company provide on site or subsidize anything with
respect to employee health (gym membership, etc).

#### 3.3 Answer
**Fill me out**


### 3.4 Retirement fund
Do you provide a 401k? Is there contribution match? What is the match?

#### 3.4 Answer
**Fill me out**


### 3.5 Employee space
Where will I work and what equipment will be provided: computer, desk, chair,
etc? What is the floor plan: open, cubicles, offices? Are the desks height
adjustable for sit/stand? Are the chairs modern and ergonomic?

#### 3.5 Answer
**Fill me out**


### 3.6 Vacation policy
Describe the vacation policy: unlimited, X hours, X mandatory hours?

#### 3.6 Answer
**Fill me out**

#### 3.7 Expense Policy
Let's pretend I want to purchase a $50 book. What do I need to do do in order
to get that approved? What does the expense process look like? How long will
I generally spend filling out that single-item expense report?

#### 3.7 Answer
**Fill me out**

#### 3.8 Questions Asked
Are there any questions you wish you had asked prior to accepting your job
offer?

#### 3.8
**Fill me out**

## 4. About the company
### 4.1 Transparency
How transparent is the company internally? Are financials freely shared with
respect (but not limited) to: revenue, profit, employee and executive
compensation?

#### 4.1 Answer
**Fill me out**


### 4.2 Funding
At the current burn rate how long until the company must secure additional
funding?

#### 4.2 Answer
**Fill me out**

### 4.3 Competition
What companies are the main competition for the market space you're in? Why work
for you instead of them?

#### 4.3 Answer
**Fill me out**


### 4.4 Strategy
Related to 4.3, what is the company strategy to succeed?

#### 4.4 Answer
**Fill me out**
