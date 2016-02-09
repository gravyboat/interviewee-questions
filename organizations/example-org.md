## example-org

This is an example of what an organization might look like.

### Questions

* Benefits
    * Chairs
        * Are your chairs comfortable? 
            * Yes, employees choose their own chairs.
        * What kind of chairs do have?
            * Employees choose their chair type.
        * How much were they?
            * Depends on what the employee picks, our budget is $1000 USD.
        * How often are chairs replaced / upgraded?
            * Chairs are replaced whenever a new employee joins.
    * Salary and Equity
        * Do employees get stock or Is there profit sharing?
            * How much stock or what percentage profit sharing? 1%-2%, or additional salary.
        * How much stock exists in total?
            * There are 45 million shares.
        * What is the stock strike price? (value formula: (stock price - strike price) * (shares / outstanding shares))
            * Currently the price is $72 USD.
        * Do employees get regularly occurring raises (yearly, etc)?
            * Employees receive raises between 7% and 15%.
        * What criteria is used to determine the amount of a raise? 
            * Attaining organizational goals, company profit.
        * Do employees get yearly cost of living adjustments?
            * Is this rolled into a raise or on top of? Yes, this is not part of their raise.
        * Is the company in the black?
            * No.
    * Health
        * Which health care provider is used?
            * We use blah health insurance and their gold tier (link to gold tier benefits).
        * When do health benefits kick in?
            * Health benefits kick in immediatey, we do not require the monthly wait period.
        * Is there an on campus gym, or do you provide free or subsidized gym membership?
            * No gym on campus, but gyms are subsidized up to $100 USD/month.
    * Time off
        * What is the vacation policy?
            * Employees must take a minimum of 25 days of vacation per year, this policy is enforced.
        * Is employee time off split between sick/vacation/personal, or a single pool?
            * Vacation and personal are one pool, we do not count sick days.
    * WFH
        * Is WFH allowed?
            * Yes.
        * If the organization allows work from home, what percentage of employees work remotely?
            * About 70% of our employees (11) are remote.
        * What tools do you use to facilitate remote employees?
            * We use a combination of Slack, Hangouts, Kanban boards, and GitHub.
        * What percentage of work is allowed from home?
            * We allow employees that live more than 20 minutes from the office full remote if they prefer.
        * Are employees compensated for equipment purchases to facilitate WFH?
            * Laptops, chairs, desks, etc? Yes, up to a total budget of $5000 USD.
    * 401k
        * Which 401k provider is used?
            * We use blah investment company.
        * When can I start making 401k contributions?
            * The first of the month after joining the company.
        * What is the employer 401k contribution match?
            * We match 4% of the total salary.

* Reviews
    * What does success in this position look like?
        * Completion of certain projects within a specific timeframe.
    * How is employee productivity measured?
        * Employee productivity is measured by project goals, we do not track PRs/pulls.
    * How often and by whom are employee reviews conducted?
        * Reviews are quarterly and conducted by the team lead.
    * What methodologies if any are used for the review process?
        * Personal preference from the lead, stacked ranking is not allowed.
    * Do you have 1-on-1 meetings?
        * Weekly 1-on-1 meetings.
    * How often do skip level employee 1-on-1s occur?
        * These occurly once a month.
* OSS
    * What open source software does the company use?
        * We use Cassandra, Chef, Nginx, and Bootstrap.
    * Does the company contribute financially to any of those projects?
        * Yes, open source contributors who address important bugs receive donations, free accounts on our app, and recognition.
    * Are employees allowed on the clock time to contribute to those projects?
        * Yes, it is encouraged.

* How flexible are shift start, stop, and lunch times?
    * Employees make their own decisions regarding shift times, we ask for 2 hours of overlap, and 6 hours of work per day.

* Company workflow and processes
    * What sort of tools does your team use to track the progress of projects?
        * We use digital Kanban boards.
    * Are the same tools used throughout the company?
        * Yes.

* Tech questions
    * Walk me through the deployment process for the main app. If I am a dev and committed some code to the repo how does that end up in front of a user? (Looking for CI/CD, automated testing, deployment automation, handoff procedure, etc.)
        * The deployment process is fully automated, whenever a push occurs the code is tested, if it succeeds it is pushed to test for preview. Once this is confirmed accurate a merge is required from test to prod, which is then automatically deployed via containers.
    * What does the developer environment look like?
        * The developer environment uses Vagrant and Docker containers to create identical environments between users.
    * Is there a test environment?
        * Yes, all pushes are automatically moved into the test environment, to avoid collision each push creates a unique container which is later destroyed.
    * What is the patching and software update process like?
        * Software updates are automated in most cases, however we are currently locked to Ruby 2.0, and Python 2.7.
        * What does an emergency security patch deployment look like? (shell shocker for example)
            * Configuration management is used to push an update to all affected systems.
    * Are there any plans to rewrite the app (in whole or portion) to another programming language? Why or why not?
        * Not at this time, we are happy with the app and wish to simply upgrade to the latest version of the current language.
    * Walk me through a major outage. Was there any warning? How did you find out about it (monitoring or customers)? How long did it take to find root cause and fix? (check for do they have centralized logging, what does their alerting and telemetry look like, etc). Post-mortem / customer AAR?
        * A major outage would first notify us via external services which are pinging the nodes, downed servers would be identified via our logging system which would also notice a large number of errors. Once we have identified the issue a blameless post-mortem is conducted, and the issue is thoroughly documented, and a project added to the backlog to ensure this issue does not happen again.
    * What is your expectation for the amount of time it’s going to take for someone to get up to speed in this role?
        * We expect familiarity within 6 weeks, and real code contributions within 12 weeks.
    * What other technology is used in the infra?
        * Blah, blah, blah, and blah
    * How many incidents occur per week?
        * Current reporting shows 3 incidents per week, primarily during the hours of 7-11 AM PST due to a cron that occurs at this point. There were also 6 incidents between 10 PM and 4 AM PST in the last month.
    * What does the on-call rotation look like?
        * Currently the on-call rotation consists of all team members as our DevOps team is under 6 people. Rotations are a week in length, resulting in one week of on-call per 7 weeks, in addition we use time zone shifting so early mornings and evenings are covered by our remote employees.
    * Are there any plans for developers to be in the on-call rotation if they are not currently? If no why not?
        * Yes our developers are currently in the rotation due to the team size.
    * How is the backlog (if there is one) prioritized? New features vs bugs/issues.What % of time is spent developing new features?
        * Our backlog prioritizes bug fixes over new features, approximately 60% of the time is spent creating new features. When a bug is encountered (especially once which negatively impacts the on-call team) it is prioritized for a fix.
    * What does the roadmap look like?
        * Our current roadmap can be seen here: (Link to roadmap)
    * What are the biggest operational pain points?
        * Currently our largest operational pain points resolve around large volumes of traffic around certain times of day due to a lack of auto-scaling. We currently have a project to work on this.
