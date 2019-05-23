layout: true
name: fullheader
background-image: url(img/neonbrand-258972-unsplash-sm.jpg)
background-size: cover

---
layout: true
name: contributions
background-image: url(img/rawpixel-600782-unsplash-sm.jpg)
background-size: cover

---
layout: true
name: closing
background-image: url(img/deborah-kunzie-49758-sm.jpg)
background-size: cover

---
layout: true
name: thanks
background-image: url(img/stuart-guest-smith-150560-sm.jpg)
background-size: cover

---
layout: true
name: logorb
class: left
background-image: url(img/Apache_NA_Logo-b.png)
background-repeat: no-repeat
background-position: 98% bottom
background-size: 20%
background-origin: padding-box

---
template: fullheader
# Coming Up Next

.left-column[
## Shane Curcuru
]
.right-column[
## Who Pays For Open Source?
]

???
**Tips:** _Press '?' for help; press 'P' for speaker notes._

---
template: fullheader
# Who Pays For Open Source?
## The Funding Behind FOSS Foundations

.left-column[
### [@ShaneCurcuru](https://twitter.com/shanecurcuru)
### Punderthings LLC
]

.right-column[
### Your Open Source Lifesaver
]


---
template: logorb
# Who Pays For Open Source?
## Defining Governance, Funding, And Relationships


What does that actually mean? 
- What is **open source**?
- **How do you pay** for it?
- What **things or activites** are paid for?

???
Thinking about my talk title, I realized that the audience may have a variety of interpretations as to what this sentence means.  There's a lot of different topics we could cover - let me define just what we'll be doing here.

This is a complicated topic, and the wide world of open source projects we use is vast.  So I ask you to come with an open mind, and expect to find more questions here than answers.  I hope I can make some of the interaction between the paid commercial world and our open source frontier a little more approachable, and at least help you to be able to ask the right questions.


---
template: logorb
# What does "Open Source" mean?

Publicly available source code offered under an Open Source Initiative listed license. 

.code[https://opensource.org/osd-annotated]

???
Let's start with the simplest part first.


---
template: logorb
# "Who" are we talking about?

- Contributing work
  - Users
  - Contributors
  - Committers / Maintainers
- Contributing work or funds
  - **Commercial companies**
  - Governments
  - Research / Academic institutions

???
The who is a just plain complex topic, because every single human on the planet who has a computer is using open source.  Even those of us involved in building, testing, documenting, marketing, selling, and whatever-ing open source do in so many different ways it's hard to quantify.
What most people are curious about is: how much of the work of building and maintaining open source projects is done by individuals, in their free time or as hobbyists?  And how much of this work is done as paid work?

The ratios of who does what varies widely - but there are clear trends in major projects.


---
template: logorb
# How do we 'pay' for open source?

.left-column[
- Sponsoring
- Events
- Services
- Paying employees
]

.right-column[
- Pull requests
- Submitting bugs
- Fixing bugs
- Providing support
- Donating new projects

]

???
Hopefully we all realize that the 'paying' part - as in money - is only one part of how open source software actually gets created and maintained.  Sure, there are plenty of examples of companies or grant funders providing cash sponsorships for major projects, or running events or providing CI and cloud services to open source projects.

But the more important impact for most projects are the actual contributions of work.  All the code submitted, all the bugs reported - or bugs fixed!  All the help and support offered to other users who become contributors in the ecosystem.  While all these contributions aren't necessarily a result of cash payment, they are certainly related in how open source works - they just tend to hide how the actual money relates to the work.

I have a theory about which half is important: contributions.

---
template: contributions
# Most major open source is from companies

???
Here's my belief: most of the major open source projects used today are primarily built by companies directly paying their employees to contribute.

---
template: logorb
# Linux Kernel Development

The Linux Kernel Report tracks in detail what companies are sponsoring work.

???
The Linux Kernel Report does a thorough analysis of both who's contributing all the code, as well as who they're working for or being paid by.
SPACEBAR

--

- In 2018, **85%** of all code was paid corporate work

???
SPACEBAR

--

-  2016 it was 80%
-  2015 it was 80%
-  2013 it was 80%
-  2012 it was 75%
-  2010 it was 70%

???
The great majority of work done in the Linux kernel is done directly by corporations (having their employees make the fixes), and this number is only going up over time.

---
template: logorb
# Linux Kernel Development

Outreachy - a paid internship program for underrepresented groups in technology - has contributed a measureable amount of code to the kernel in recent years!

- Year 2017: Outreachy interns made 0.8%
- Year 2016: Outreachy interns made 1.4%
- Year 2015: Outreachy interns made 1.5%

???
Shout out to Joan's talk earlier today, and Nitya's talk later today, there are some places where outreach efforts are making a difference (albeit a small one so far)

---
template: logorb
# Apache Software Committers

The ASF ran a survey in 2016 about how committers were contributing to their projects.

- ~**50%** replied it was as an Employee (as their job)
- ~40% replied as an Individual (outside regular job)
- ~10% were Retired, students, other

.code[https://s.apache.org/2016dsurvey]

???
This is across all 200 Apache projects.

---
template: logorb
# Drupal Commits And Sponsors

Drupal uses a detailed credit system to track who paid for which commits - either as an employee, or on behalf of a customer of a consulting or contracting group.

- **49%** of code was Wholly sponsored work
- 39% was Work that's a mix or not credited
- 12% was Purely volunteer work

.code[https://dri.es/who-sponsors-drupal-development-2018]


???
Drupals' commit logs to show not just who wrote the code, but if they were sponsored or paid to do make that commit by a company or other entity.  That counts either software vendor employees, or consultants or integrators working for end users.

The ratio of sponsored to not sponsored is increasing.

---
template: logorb
# Where Do Projects Come From?

Where did today's open source projects get started?

- Passionate hobbyists?
- Academic or research projects?
- Vendor groups collaborating together?
- Single company projects being donated?

???
How do projects start being open sourced?  The answer is: all of these places

While plenty of FOSS projects you may use came from individual developers, many of the key bits of technology used in business today came from... business.

SPACEBAR

This is where opens source foundations like Apache, Eclipse, and Linux Foundation come in: they all have incubation processes to help new projects get started as true open source or open governance projects.


--

- **All of the above**
- (But mostly: companies)

???
Here's just one example from this week...

---
template: logorb
# Google's 9 million for Kubernetes

Google Transfers Kubernetes Resources To Community, Donates 9 Million in Funding

At this year’s Open Source Summit in Vancouver, Google Cloud announced that they would be transferring ownership and management of the Kubernetes project’s cloud resources to CNCF community contributors. As part of this move, Google is donating a 9 million grant of Google Cloud Platform credits to cover the infrastructure costs associated with Kubernetes development and distribution


???
This is a press release from Google a few days ago, about donating both key parts of the code and support network, but also a large donation of cloud credits to the CNCF.


---
template: contributions
# Most major open source is from companies

???
So, what do you think of my thesis now?

These contributions are effectively indirectly funded, by companies paying their staff or integrators to do the work for them.

---
template: logorb
# Direct or indirect funding?

- Direct contributions (code, cloud, services)
  - Code, cloud credits, services
  - Made by corporate employees

- Indirect contributions
  - Company hiring consultant to contribute 

- Funding
  - Sponsoring foundation or project

???
Let's review: 
We already have fairly good models for managing contributions: it's called good project governance.  Apache, Eclipse, Linux Foundation, and larger FOSS projects like Python or Drupal already have their own governance and processes for managing contributions - whoever they're from.  In many cases, foss contributors are really just corporate employees doing their dayjob - which is pushing code upstream into the FOSS that the company relies on for business.  A similar case is indirect funding of the work - when you hire a consultant to fix bugs in your open source stack; you're paying them for work, and the open source project seemingly gets it for 'free'.

The last part is direct funding: when a company gives cash to a foundation, so the foundation itself can manage doing some sort of work.  Now how funding actually gets transferred from some vendor to an open source project varies widely - for major foundations, we have established sponsorship programs and internal governance to manage the work.  For many smaller or independent FOSS projects, the process of managing the money - and convincing someone to give you funding! - is very difficult.  
There are a lot of different models for this, but I'd like to focus on foundation funding.

This is a complicated question.


---
template: logorb
# Contributing Code Vs. Managing Projects

But code alone doesn't make up a project.

Community and Governance do.

???
Yes, there's code littering the world - but the value is in continuing and comprehensive projects that provide a useful tool, and keep it maintained.

How does all the rest of the coordination and work get done for successful projects?  Who pays for legal support, trademarks, and keeping the servers (or cloud) running?

---
template: logorb
# Independent FOSS Projects - And Foundation Hosts

Foundations provide a home for long-lived focused open source projects.


???

For small projects, this is a regular struggle - keeping a project alive over time, ensuring fixes are made, marketing.

Thus, we have FOSS foundations, like Apache, Linux, Eclipse, Software Freedom Conservancy, and some others.  
 These foundations provide the fundraising, legal, infrastructure, governance and mentoring support - which is a lot of work for a successful project ,as I'm sure you all know.  How does this work get done?
 
---
template: logorb
# Support Foundations Provide

Foundations provide:
- Governance
- Mentoring
- Legal shield
- Fundraising support
- Hosting, services, clouds
- Respectability / brand management
- Events
- Community and mentoring

???
We still rely on many volunteers to help, but when it comes to reviewing contracts or doing the accounting on donations, we need hired help.  Accounting volunteers are rare to find in the coding world, and few coders want to carry a beeper for 24x7 support when the server goes down.  All these services we need money for.

Non-profit foundations attract some donations - from individuals or small businesses who want to say thanks for the software we provide.  But the bulk of funding for most software non-profits comes from corporate grants or recurring sponsors.

How do these foundations get their money?  Sponsors (primarily).

---
template: fullheader
# What kind of non-profit are you?

- 501(c)6 - Trade Association / Business League
- 501(c)3 - Public Charity

???
A quick note: when we're talking about non-profits, sometimes the details of tax laws matter, either for donors writing the money off, or for some subtle aspects of governance.

---
template: fullheader
# How Much Funding Do Foundations Get?



---
template: logorb
# Who Sponsors Apache?

Apache's eight Platinum sponsors are:

- Oath
- Microsoft
- Facebook
- Leaseweb
- Google
- Cloudera
- Comcast
- Tencent Cloud

.code[The ASF is a 501C3 Public Charity]

???
Those are just the platinum sponsors, but they represent about $800K in annual donations, or about half the income for the entire ASF.  These sponsors get a thank you and a listing on our webpage, but otherwise have no influence over how the ASF or Apache projects are run.

Two other 501C3 organizations are Software Freedom Conservancy, and Software in the Public Interest, among many others single-project or smaller foundations.

Thank you to all the ASF sponsors, Gold, Silver, Bronze, and in-kind sponsors too as well as all our ApacheCon event sponsors!


---
template: logorb
# Who Sponsors Eclipse?

The eleven Strategic Members of Eclipse are:

.left-column[
- CEA List 
- Fujitsu
- IBM
- OBED
- Oracle
]

.right-column[
- CA Technologies
- Payara Services Limited
- Red Hat
- Robert Bosch GmbH
- SAP SE
- Tomitribe
]

.code[Eclipse is a 501C6 Trade Association]

???
Eclipse has a mixed model, where there are corporate sponsors just contributing cash, but far more strategic members who contribute both funds as well as designated contributions and employee work.  

Those Strategic Members donate about 2.5M to Eclipse annually, which again is roughly half of their income which totals between 5M and 6M in recent years.


---
template: logorb
# Who Sponsors The Linux Foundation?

That's a complicated question.

The Linux Foundation, a 501C6 trade association, has over 50 collaborative projects, many with their own governance **and funding models**.


???

---
template: logorb
# Who Sponsors The Linux Foundation?

The fifteen Platinum Corporate Members of the Linux Foundation:

.left-column[
- AT&T
- Cisco
- Fujitsu
- Google
- Hitachi
- Huawei
- IBM
]
.right-column[
- Intel
- Microsoft
- NEC
- Oracle
- Qualcomm
- Samsung
- Tencent
- VMWare
]


???
Each platinum member/sponsor of the Linux Foundation as a whole reportedly pays about 500K annually, and provides representatives both on the board of the foundation as well as in various technical bodies of collaborative projects.

This list represents about 7M of annual income for the Linux Foundation

---
template: logorb
# Who Sponsors The CNCF?

The nineteen Platinum sponsors of the CNCF are:

.left-column[
- Alibaba
- AWS
- Azure
- Cisco
- Dell
- Docker
- Fujitsu
- Google
- Huawei
]
.right-column[
- IBM Cloud
- Intel
- JD.Com
- Mesosphere
- Oracle
- Pivotal
- RedHat
- Samsung
- SAP
- VMWare
]

???

The Cloud Native Computing Foundation is a subsidiary of the Linux Foundation, and just for the CNCF, they have this list of platinum sponsors, each of which are donating in the range of 250K or more annually to the CNCF.

These are just sponsoring the CNCF, and likely represents at least 4M in annual income, if not more, for the CNCF and Linux Foundation.

---
template: logorb
# Who Sponsors The Hyperledger Foundation?

The eighteen Premiere Members of Hyperledger are:

.left-column[
- Accenture
- Airbus
- AMEX
- Baidu
- Change Healthcare
- Cisco
- Deutche Bank
- Daimler
- Digital Asset
]
.right-column[
- DTCC
- Fujitsu
- Hitachi
- IBM
- Intel
- JP Morgan
- NEC
- SAP
- Tradeshift
]

???
Each of these premier members for Hyperledger likely provides an approximate 250K annual donation, as well as employees working on it.

This list represents about 4.5M in annual income for Hyperledger and the LF.

---
template: logorb
# Who Sponsors The Linux Foundation?

... and the 50 Collaborative Projects at the LF?

Answer: A lot of companies, some repeatedly.

???
There are probably a dozen major collaborative projects, each with their own sponsors (and products), and another 40 or so smaller projects - still interesting, but with fewer or little direct funding.

---
template: logorb
# Foundation Funding Levels

Approximate annual **2016** income for:

- Apache Software Foundation:  900,000 USD


???
All figures are rounded, taken from tax filings or actual projected income budgets.

--

- Eclipse Foundation:   5,400,000 USD

--

- Linux Foundation:    61,000,000 USD

???
Given the number of independent projects each of these foundations hosts, they represent a significant chunk of the major open source world.

While this comparison may be a bit startling, remember: the far more important factor for open source is actual contributions.  Much of the value in open source comes from the day-to-day contributions of everyone - both the passionate volunteers, and the legions of corporate employees working on their dayjobs that push fixes and features upstream.


---
template: logorb
# Governance, Funding, And Community All Matter

Community and governance matters too, beyond funding or license.

???
Just like you choose which license to use, think about choosing how you invest in open source projects. 

Not just the code - infra support, documentation, help on the lists, what you promote in your marketing materials - and where you sponsor projects or foundations. 

When you bring a new project to the ASF or to another foundation, you're making a fundamental choice about more than the license.  You're setting the stage for how the project is going to grow, who's going to want to contribute to it, and where it's long-term direction can end up.  Funding and governance are more important than the license choice.


---
template: thanks
name: closingslide
# Who Pays For Open Source?
# More Data Is Out There

Do Your Own Research

.code[https://projects.propublica.org/nonprofits/] 

Expect an announcement soon of some structured data on this topic!

.code[http://shaneslides.com/] 

---
name: last-page
template: thanks

## Thank You &amp; Questions!

.footnote[
By: [@ShaneCurcuru](https://twitter.com/shanecurcuru) |
<a rel="license" href="https://www.apache.org/licenses/LICENSE-2.0.html">Apache v2.0</a> |
https://shanecurcuru.github.io/slides/
]



---
template: logorb
# Other topics to investigate

- RedisLabs and the Commons Clause
- Open Source Sustainability
  - How do **I** get paid for open source?
  - Community project sustainability
- New work funding models
  - Patreon and crowdfunding
  - Tidelift and subscriptions
  - Building your own business model



???
There's a lot more to talk about out there - I look forward to your ideas!


---
template: logorb
# What Do We Pay For In Open Source?


## Using Vs. Producing


You never have to pay to **use** open source - that's part of the OSI's open source definition.  In fact, I'm using open source right now - as is everyone at this conference and most of the people in this hotel today.  

Open source software underpins everything; it's in virtually every computing device you use somewhere.  The majority of the time you never realize it.  Even when you are knowingly choosing to use an open source tool for your work, you're still not paying for it.  Just a reminder with all of the talk of open source sustainablity that you never **have** to pay just to **use** open source.

Sometimes we choose to pay to use open source - for support, or help, or hosting.  But that's a choice, and that kind of payment is more about the use of software, not the software itself.

What we're really interested in is: who pays to **build** open source software?  Software is a tool - once you've got your hammer, you can keep using it to bang away.  But you want a better hammer, one that's lighter, that pulls nails better, whatever.  For ApacheCon attendees, much of our work is involved with building, improving, or supporting the software.  So the question is, how do we pay for that building of software?

---
template: logorb

# What Is The Commons Clause?

Commons Clause is an added license restriction that only grants you rights if you are not selling something based on the software.  It is not open source; it's "source available proprietary software".



---
template: logorb

# Recent News

Who's heard of?
- Redis Labs License change

- Commons Clause from FOSSA
License restriction that forbids 'selling' atop another license


- Open Source Sustainability

Individual versus Project
How do I get paid?
How does my project get the services it needs to survive long term?

- Funding models
- Tidelift
- Patreon
- Others

---
template: logorb
# What Ways Do Companies Contribute?

- Obvious: employees contributing code
- O

There's a lot of talk about how much - or how little - money various companies and vendors pay into the open source arena.  But the discussions about money are missing a huge factor: what are all the **different ways** that Companies contribute work back to FOSS projects?

It's often not obvious to quantify some of the supporting ways that companies contribute, but they're certainly there.  Managing a full open source project needs source control, web space, continuous integration and testing, and often requires access to cloud services.  Either directly or indirectly many software vendors like github, amazon, google and more all effectively donate these kinds of services to projects.  Sometimes it's explicit and called out, often it's simply free accounts for any open source contributor

But the real value is in how much corporate employees contribute work to FOSS projects - code, documentation, tests, and more.  

While many individiual developers may feel unappreciated for their volunteer work, that's only a small part of the overall patches and code that is put into open source projects.  It depends on the kind and size of project, but in some areas the majority of work is done by employees at software vendors writing open source code as their dayjob.

---
template: logorb
# Open Source Sustainability

## Open Source is a:

- Sustainable contribution model.
- Model for broad innovation.
- **NOT** a Business model.

## What does "Open Source Sustainability" mean?

???
Brief intro of 'sustainability'.


---
template: logorb
# Conservancy
Software Freedom Conservancy hosts a number of independent projects, and merely lists substantial sponsors without amounts.

Collabra
Google
HP Enterprise
Linux Australia
Mozilla
Private Internet Access
Red Hat
Savoir Faire Linux
Target