# Interviewee questionnaire

This is a questionnaire that covers a wide range of topics an interviewee would
like to understand about a company before moving forward in the hiring process.

# Questions

## 1. Technical

### 1.1 Describe the deployment process for the primary application
One of the best indicators of the day to day quality of life for a technical
employee can be reflected in the deployment process of a company's software. A
great low friction deployment process requires a lot of tooling and thought.
Describe the process of deployment for the primary application from developer
commit to production.

#### Answer
Please provide a description of the deployment process as well as check any
relevant boxes for things your deployment process has.

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

#### Answer
- [ ] Fully automated. We patch as soon as upstream releases updated software
  and the patch has gone through automated testing.


### 1.3 Describe the development environment
Describe the development environment? How closely does it resemble the production
environment? How long does it take to set up? What OS is it based on? How
flexible is it with respect to allowing me to use whatever tools I want to use
that will make me the most productive (ex. the dev environment is CentOS 6 but I
want the latest version of emacs)?

#### Answer


### 1.4 Describe the test environment
Similar to 1.3, if applicable.

#### Answer


### 1.5 Roughly what percentage of code is in what language?
Are you mostly a Python shop with some Java? Explain.

#### Answer


### 1.6 Any near-term future plans to dramatically change programming languages?
Related to 1.5, are you having any scaling pains or accumulation of technical
debt that's becoming burdensome? Any plans for a rewrite into another language?

#### Answer


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

### 1.8 On-call and number of incidents / outages
What does the on-call rotation look like? Who carries the pager for how long?
For the average on-call shift, how often should someone expect to get paged? Is
there a separate operations group that solely carries the pager or is the burden
also shared by the development team? If developers are exempt from on-call, is
there any plan to incorporate them into the rotation?

#### Answer


### 1.9 Operational pain points
What are the biggest operational pain points?

#### Answer


### 1.10 Roadmap
What does the product roadmap look like? How is the backlog prioritized: new
features vs bug fixes? Roughly what percentage of time is spent developing new
features vs fixing bugs?

#### Answer


## 2. Managerial

### 2.1 Employee productivity
How is employee productivity measured? What does success look like for a given
position?

#### Answer


### 2.2 Employee reviews
How often and by whom are employee reviews conducted? What methodologies if any
are used for the review process? Do skip level employee 1-on-1s occur?

#### Answer


### 2.3 Office hours
How flexible are employee office hours with respect to start/stop/lunch times?
Does the company allow telecommuting? How frequently? Are there core hours?

#### Answer


## 3. Employee Compensation / Quality of Life / Benefits

### 3.1 Salary
Do employees get regularly occurring raises? What criteria is used to determine
the amount of the raise. Are there yearly cost of living adjustments? Is this
rolled into the raise or on top of it?

#### Answer


### 3.2 Equity
Are employees granted equity or profit sharing? If equity, in what form? If as
stock/options: how many shares are outstanding, what is the strike price?

#### Answer


### 3.3 Healthcare
Describe employee health coverage. What providers are available? When do health
benefits kick in? Does your company provide on site or subsidize anything with
respect to employee health (gym membership, etc).

#### Answer


### 3.4 Retirement fund
Do you provide a 401k? Is there contribution match? What is the match?

#### Answer


### 3.5 Employee space
Where will I work and what equipment will be provided: computer, desk, chair,
etc? What is the floor plan: open, cubicles, offices? Are the desks height
adjustable for sit/stand? Are the chairs modern and ergonomic?

#### Answer


### 3.6 Vacation policy
Describe the vacation policy: unlimited, X hours, X mandatory hours?

#### Answer


## 4. About the company
### 4.1 Transparency
How transparent is the company internally? Are financials freely shared with
respect (but not limited) to: revenue, profit, employee and executive
compensation?

#### Answer


### 4.2 Competition
What companies are the main competition for the market space you're in? Why work
for you instead of them?

#### Answer


### 4.3 Strategy
Related to 4.2, what is the company strategy to succeed?

#### Answer

