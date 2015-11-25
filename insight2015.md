### **Conference Notes for IBM Insight 2015 - Las Vegas Nevada - Oct 25-29 2015**
#### **Apache Spark: What's in it for Your Business?**
* General description of what spark is
* Emphasize expressiveness & speed (when compared to mapreduce)
* Spark you can bring your own data
    * The data warehouse can be in a variety of places (SQL, nosql, etc)
* Could it be used to speed some of our data requests? Dashboards?
* Unlike elasticsearch you can join data
* Spark querying is simpler code than MapReduce
    * Get’s rid of a lot of the boiler plate code
* Lot’s of machine learning techniques & algorithms use Spark
    * Is that built off of Spark? Or components of? Can do it all in the Spark environment
* Hadoop is: Compute, storage, cluster management.
    * Spark doesn’t handle storage or cluster management
* IBM - has Tripled down on spark being the future of analytics
* Should experiment with Spark
#### **Best Practices in Report and Dashboard Design**
* What is the difference between a report & dashboard?
    * The differences are blurred.
    * Dashboard important info upfront, reports more detailed information
* Pie Charts = Bad
    * Pulling out slices, or centering slices will distort perceptions
* *10 Best Practises*
1. Layout
    * Top Left corner most important information (Western World)
    * Middle second most important
2. Color
    * Bright vs Mute - Color has meaning, soft is less noticeable
    * Don’t use too many colors. 5 Max, then if you need more just use different shades.
    * Every color (and shade) should be deliberate
3. Use different sizes
    * Similar to color
4. Text
    * Fonts easy to read
    * Make sure fonts match across charts and within the chart
    * abbreviate numbers (stop using decimals if they don’t matter, shorten to millions where appropriate)
    * Try to keep text horizontal. Don’t make user tilt their head
5. Borders
    * Use borders to group related information or to highlight info
6. Proximity
    * Group info using small & large amount of white space
        * Use borders if you don’t have the space
7. Simplify information
    * Don’t show useless information
    * Highlight what’s important (using techniques as mentioned)
    * Hierarchy can be used (only collapse if needed, can just use left margin indentation)
8. Choose right visualization
    * *Bar Graph - *Show individual values.
        * Scale must start at 0 unless good reason and that reason is obvious
    * *Dot Plot* - Show individual values when lots of values
        * Really interesting bar chart but easy to read when comparing many values - Might work for Revenue?
    * *Line Chart* - Trends
        * Don’t have to start at 0
        * Number of lines (series) should not exceed 5
    * *Table* - Use to lookup or to compare precise values or to show values in more than one unit of measurement
        * Totals should be distinct
        * Right align numbers for easy comparison between rows
        * Use colors for action
        * Use borders to highlight - don’t over use
        * Large white space instead of lines
            * Or light background colors if there isn’t a lot of space
    * *Line & Bar* - Two different things on same chart use with caution
    * *Stacked Bar *- Show how individual totals contribute to a group total
        * Revenue from different sources over time?
    * *Sparklines* - Shows trends, that’s it. Needs time period for proper context
        * Revenue per partner could have sparklines
        * We should leverage sparklines more often than we do
    * *Box Plot* - Shows distribution
        * Could be good when showing industry stats
    * *Scatter Plot* - Shows how much pairs correlate
        * Adding best fit line can help show trends (if one pair is time)
    * *Bubble* *Chart* - Similar to scatter plot except with another dimension for size of bubble .Could add a 4th dimension with color.
        * Tickets, Revenue, Avg time to solve per partner? Partner type with color?
    * *Bullet Graph* - Show single measurement with context
        * Bar over a gradient. Gradient shows good/bad values, bar show actual value.
    * *Small Multiples - *Some visualization repeated
        * Conversion rate for each product on bar chart grouped by vertical
    * *Icons* - Highlight one particular area
        * Up, down arrows, stars, etc.
    * AVOID
        * 3-D Charts
        * Speedometer & Thermometer (hard to understand)
        * Pie Charts
9. Interaction & Drill Down from Dashboard
    * Dashboards should allow user to go deeper and explore
10. Dashboard Delivery - Is it online or offline?
    * If printing need to design different
    * Is it mobile?
    
#### **Create a Value-Add Employee Experience for a Multi-generational Workforce**
* 41% of Americans with a smartphone have difficulty accessing work info from their phone
* Less than 10% of companies report that ability to use data to make predictions and take actions on future workforce issues
* 76% of consumers expect organizations to understand their individual needs
    * Workforce would be similar
    * Workforce not just about the job but the experience (something we excel at)
* 90% of organization lack skills they require
* 94% of workers feel overwhelmed to point of incapacity (really?)
* $25,000/employee - Disengagement loss if employee doesn’t know where they fit or how they help the organization achieve its goals
* Integration is very important for people acquisitions
    * How do you differentiate yourself from the competition to stop employees from leaving?
* Employee voice is extremely important
    * Feedback is happening more often and needs to be raised
    * Need to listen to employees
* Employees want to know and see transparency over what is happening in their workspace
* Social media platform for an internal community?
    * Idea is to watch the social media platform for disengaged or hostile employees and reengage them
* Leaders need to be role models
    * Who are our role models? Who should be our role models? Are our role models upholding the values that we want?
* There is no generational effect for who is engaged and who isn’t
    * No difference between ages (globally)
    * Everyone is using social media, everyone is using a smartphone
* Workforce analytics has to start with a business reasons
    * Lower costs, bringing in experts, etc
    * Shouldn’t just be an HR problem that stays in HR
    * Trust is required. Trust the data. Trust the user will use the data.
* HR is starting to become less "HR as a career". Most need other experience like marketing, finance/accounting, etc.
    * They need to collaborate with so many different people like CTO.
* HR needs bigger voice in the corporate strategy. The HR leaders need to step up
    * Interact with Risk Management
    * Make sure HR strategy matches company strategy
    * Have a culture strategy and ensure everyone in the company knows it
    * Position the company with a competitive advantage to drive hiring and retention
* Alternative work
    * Need to handle offsite employees, contractors, etc
    * Transparency is needed
    * More transient workforce than ever before
        * Are we doing anything to allow for a more transient workforce?
            * Can we facilitate this better?
    * Alumnis are very important
        * Former employees are coming back in larger numbers
        * Referrals are very important
        * Do we actively foster the relationship with employees who have moved on?
            * Do we have a specific strategy?
            
#### **Don’t Forget: the Human Element of Analytics**

* Do we actually use analytics to distrubt our organization?
* Organizations change in two ways, behavioral and Technical
* Behavior needs to change along with technical
* Analytical production is required (produce data)
* Analytical consumption needs to follow
    * At the corporate level - Starting to do
    * At the individual level - Not at all
        * Can help motivate employees
* We should be measuring results
    * Everything that we do, state what the expected outcome is. Was that outcome achieved?
    * We should be doing an experiment with every *Item*

#### **Improving HR Processes with Advanced Analytics and Big Data**
* Where can we assign available employees?
* When someone outside is available does their profile fit a company need?
* Internal needs, who can be placed in this need (external or internal)
* Use CV and NLP - compare to job post using algorithms
* Seems to use words instead of phrases? Words need context no?
* Don’t really understand the weighting of words? Seems to be based on word frequency? Would be easy to game for job seekers
* They tried it on LinkedIn accounts and it went well
* Skill profiles more interesting
    * Pick a skill and then see other skills that often relate to it <- would this really be used by HR?
* Detect high potential & Key profiles <- much more interesting
    * Extract a career path for individuals
    * Determine actions to allow employees to reach full potential
    * What support can we give in order for employees to reach their full potential?
    
#### **Key Strategies for Effectively Managing Data Science Teams (No Slides)**
* Data Scientists (DS) have trouble rolling out their analysis
* What do DS do?
    * They literally do Research and Development. Conduct experiments.
* Ask Good Questions
    * Graphs are convincing. Need to visualize the results
    * The DS process can’t just be a black box
* Being Data Driven
    * What’s the decision that needs to be made?
    * What data do you have? What data do you wish you had?
* Value of Information
    * Cost benefit analysis in Product Development
* 4 General Categories of work for Data Scientists - ROCC
    * Regression - Finding underlying expression (model) that fits your data
    * Clustering - Finding like groups
    * Classification - Lead generation, who is a good lead?
        * Uses decision trees, regression, etc
    * Optimization - Given constraints, maximize output
* Setting Good Expectations
    * Software engineering is a major, it is a well known space
    * DS are more exploratory. They don’t always know if it can be done.
* Data Scientists - Two Types A & B
    * Analyst
        * Knows Stats
        * Loves Algorithms
        * R, Python
    * Builder
        * Knows Stats
        * Loves to implement
        * Delivers solutions
* Maybe we should define data analysts & data scientists as two different thing? Have different career paths?
* When can I have this by?
    * DS is not software, the exploration (an assessment) is needed before they can give accurate timelines
* DS should think in probabilities - data driven solutions are probabilistic
    * Confusion matrix should always be presented with a full report
        * Precision, Recall, Accuracy
        * Will run into problems when unbalanced set (if one is really small)
    * ROC curves should also be presented
* Should be able to iterate on DS projects
    * Push out simple solution, a proof of concept
        * Should always be better than random
        * Start with simple an iterate & improve
            * Check each iteration and ensure it had more predictive power than the last
* Ockham's razor - Simple solution is often the best
* Figure out what metric are you after in the confusion matrix (often accuracy)
* Will often identify new data points that should be captured
* Benchmark and watch for improvements
* Is it production worthy?
    * Often Data Scientists can’t tell, they don’t have the engineering skills to know if it will scale or not
* Real world testing is very important
    * Can use log replaying - capture then simulate, have a model that simulates data
* Capturing data cleanly is hard
    * We lose info frequently
    * DS have to clean data
* DS need production data, not dirty test data
* DS should be experimenting, trying different algorithms & techniques, be able to try different solutions in production
    * Some experiments will fail
* Data Science team is different from Development team
    * Where DS should put their code and allow it to interact with web application and developers?
    * Should have APIs that allow each other's code base to interact
* Who writes product code? Possibilities:
    * Dev team takeover code
    * Library technique
    * Wrap in API & use microservice
* Probably want the data science team to *own* the model. They can update it and nothing should change for the engineering group.
* Watch out with A/B testing. If it is something new people may use it just to try it out
* Data Skeptic Podcast?
* Data Science team must know when business changes as it may affect their model
* Evangelize
    * Celebrate successes
    * Get team to explain, people will react. Make sure the explain why the results are important.
        * How will implementation help us?
* Data Science Team’s time spent on
    * Research & Exploration
    * Solution development
    * Solution implementation
* Where should DS sit?
    * Can be anywhere, should match corporate strategy
    * More often centralized
        * Probably better to share expertise as a centralized hub
        * Hybrid
            * Centralized but team members participate in different department meetings
    * Data Science is a team sport
    
#### **Analytics, Analytics, Analytics – The Future of Talent Management**
* Internal Drives
    * Shifts in strategic direction
    * Pressing workforce challenges
    * Company-wide analytics mandate & maturity
* External Drives
    * Labour Market Trends - Transient, flexible, skill shortage
    * Regulatory & compliance issues - Legal, risk management, more transparency
    * Emerging data sources - Partner data, Social data
* More Social People we have more data we have on them. Does that bias our solutions?
    * Yes, it is hard to counteract
    * Social online versus face-to-face
        * Starting to capture more data through wearables to get physical data
        * If we measure online social interactions, will we be encouraging that more than face to face?
* Talent Analytics includes:
    * People hiring
    * Reducing turnover
    * Staffing times (seasonal, traffic, etc)
    * R&D mix from various disciplines (the different skills required)
    * Right mix of front line employees so they interact properly with customers
* Types of Analytics
    * Descriptive/Benchmarking
    * Diagnostic
    * Forecasting
    * Propensity modeling
    * Prescriptive
    * Cognitive modeling
* Says best way for small business to start using HR analytics is to use Watson
* Key skill for DS is interpreting data, most people don’t know how to and it can be dangerous in the wrong hands.
* Don’ts
    * Don’t pick an analytics problem that only helps HR (repeated from another session)
    * Don’t need perfect data before starting. Just trying to beat random
    * Don’t Position analytics as a substitute for human judgement, just augment it.
    * Don’t ignore the need for trust
        * People have to trust the data, method and analysis
        * Need integrity or loss of trust
* Do’s
    * Link to overall business strategy
    * Take actions based on insights
    * Demonstrate ROI
    * Build the capacity to scale
* Start small and iterate
    * Keep it simple then go more complex
* Want to know as much about your employees as your customers
* What can we do?
    * Are leaders Emotional or Intellectual?
    * Which employees are engaged?
    * How leaders perform with low performers
    * Does leader take active role in personal development of employee?
* What is your leadership diversity? What do we need to develop and hire in?
* Internship & GPA were highly predictive of how a person performed (and over time)
    * Internship gap becomes greater as time goes on (faster growth)
        * Study only went 4 years into the job (although how often are people changing jobs anyway)

#### **Data Science and the Digital Media Transformation**
* Catalina - Company
    * Produces promotions in checkout lanes
    * Capture all transaction in all major grocers
    * Offer real time coupons
    * No one else has this data
* Google has tried, Amazon has tried, no one can amalgamate the promotions
* Can’t promot on all channels cause that would be spam
* Growth is flat in Grocery
    * Companies like Catalina are trying to help optimize and provide value to both the consume (cheaper goods) and the producer (buy the goods at their store instead of somewhere else)
* Really talking about a complete view of a consumer and how they consume goods. Then they can market towards them.
    * Talk about mutual Benefits
    * Growth Curve Need a broader focus. Not hitting local maximization
* Golden Age of Marketing. The opportunity is greater than ever before:
    * Science
    * Substance
    * Story
    * Speed
    * Simplicity
    
#### **Do Data Scientists Need Data Management?**
* How to integrate Data Scientists into an organization?
    * DS team needs to be aligned to the overall business goals (not just do what’s fun)
    * DS must be reusable and exploitable (every model needs actionable insights)
    * DS often lack domain knowledge, will discover stuff you already knew
* What’s the difference between Analysis & Science?
    * Scientists:
        * Look more at unstructured data
        * Will use special tools (R, Python, etc)
        * May produce nothing valuable
        * Very exploratory
        * Specialized skill in data mining
        * Are more entrepreneurial
        * Explore ideas
* Building & Using Decision Models
1. Information Pattern Discovery Process (mining)
2. Information Decision Definition Process (assembling) - Actionable results
3. Information Decision Making Process (scoring) - Stimulus
* Feedback is super important
    * Model needs to know what worked and what didn’t
        * Adjust the model accordingly
* When *scoring *you no longer have historical data, it is only for new data being collected
* Team
    * Data Scientist & Statisticians need to work with: IT, BA, Executive, Marketing & Sales
* Data Scientist wants one big long record that has all of the data rolled up
    * Perhaps Big Table would work?
    * Could have 1,000s of columns
    * Often called a "Spine" of knowledge.
* Apparently can use Watson to tell you which type of algorithm to use. It will spit out an initial model, then we tweak it?
* Expect Failures
    * 50 Models, 45 will suck, 3 are good, 2 are great.
    * Model will change, so need to be updated continuously
* Make sure you document failures
    * What doesn’t work and why it doesn’t work is just as important as successes
* Where does DS fit within an organization?
    * Often sees it in IT, but that is NOT the right spot
    * Should be closer to the business unit (with a good relationship with IT)
    * We should move move. We are hidden. Either more or work in different places to be more accessible and understand more problems of different departments
* Standard methodologies like[ CRISP](https://en.wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining) (Cross Industry Standard Process for Data Mining) can make repeatability easier
* Business knowledge is super important. All new DS employees need to learn it in order to be effective.

#### **Live Coding: Building a Watson Powered Application in Under 30 Minutes (No Slides)**
* Watson has a bunch of[ different APIs](http://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/services-catalog.html) that can be embedded in your application
    * Has things like:
        * tone analyzer 
        * Personality insights?
    * Has API for Node and Java (some have more, some have Python)
    * Alchemy Image Analysis <- Could be cool for SM
        * Can pick out Male/Female
        * Age
        * Name (for more famous people)
