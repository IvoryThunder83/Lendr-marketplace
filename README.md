# LENDR
## Help others, help yourself.
### https://tranquil-reaches-18328.herokuapp.com/
## About Lendr
Lendr is a community-driven two-sided marketplace that lets you rent out your belongings to others nearby. Everyday, we connect Australians who need things, with others in your neighbourhood that have it to lend. Our vision is to provide a platform where anyone and anything - from the everyday to special occasion - can be borrowed quickly and easily without needing to break the bank or buy more stuff.

Help others, help yourself. Win-win.

[![Lendr](/app/assets/readme/intro-lendr.png)](https://tranquil-reaches-18328.herokuapp.com) 

## Contributors
|[![Linda Lai](/app/assets/readme/contributors-linda-lai-70x70.jpg)](https://github.com/linda-lai) | [![Mat Wats](/app/assets/readme/contributors-IvoryThunder83-70x70.jpg)](https://github.com/IvoryThunder83) | [![Tiffany Fai](/app/assets/readme/contributors-tiffai-70x70.jpg)](https://github.com/tifffai) |
|----------|-----------|-------------|
|Linda Lai | Mat Watts | Tiffany Fai |

## Contents
https://github.com/thlorenz/doctoc
- **[Challenge](#Challenge)**
- **[Problem](#Problem)**
- **[Solution](#Solution)**
- **[Application](#Application)**
    - **[Network Infrastructure](#Network-Infrastructure)**
    - **[Software](#Software)**
    - **[Architecture](#Architecture)**
    - **[Components](#Components)**
    - **[Third Party Services](#Third-Party-Services)**
- **[Database](#Database)**
    - **[Database Justification](#Database-Justification)**
    - **[Production Database](#Production-Database)**
    - **[Market Research](#Market-Research)**
    - **[Database Relations](#Database-Relations)**
    - **[Entity Relationship Diagram](#Entity-Relationship-Diagram)** 
- **[Project Management](#Project-Management)**
    - **[User Stories](#User-Stories)**
    - **[Wireframes](#Wireframes)**
    - **[Task Management](#Task-Management)**
    - **[Agile Methodologies](#Agile-Methodologies)**
    - **[Coding](#Coding)** 
    - **[Source Control](#Source-Control)**
    - **[Deployment](#Deployment)**  
- **[Testing and Information Security](#Testing-and-Information-Security)**
    - **[Testing](#Testing)**
    - **[Information Security Requirements](#Information-Security-Requirements)**
    - **[Information Security Methodologies](#Information-Security-Methodologies)**
    - **[User Data Management](#User-Data-Management)**
- **[Minimum Viable Product](#Minimum-Viable-Product)**
    - **[Challenges](#Challenges)**
    - **[Future Enhancements](#Future-Enhancements)**
    - **[The Pitch](#The-Pitch)**
- **[Conclusion](#Conclusion)**

## <a id="Challenge"></a>Challenge
*What is the need (i.e. challenge) that you will be addressing in your project?*

In a bygone era of conspicuous consumption, we were conditioned to believe that a need to use something had to mean ownership or accumulation - rather than the reality: _access_.

Between everyday essentials and most prized possessions is that awkward range of important but infrequently used stuff that we don't want to splash out extravagantly for or waste precious space storing (think travel luggage, power drills, camping gear, that extra fridge, and so on) - well then, what's the solution?

Enter Lendr.

Following on from the old adage of borrowing a cup of sugar from your next door neighbour, here at Lendr we wondered why this couldn't this apply to well...everywhere and everything?

As a counterargument to the constant bombardment of nudges to buy, own, collect and (let's be honest) discard stuff that does a great job gathering dust on your shelf, languishing in your garage, piling up landfill or used once, Lendr taps into the current milieu to share rather than own, while empowering you to put your goods to work.

## <a id="Problem"></a>Problem
*Identify the problem you’re trying to solve by building this particular marketplace App? Why is it a problem that needs solving?*

Though access and connectivity to people and things has never been greater, simultaneously we're time-poor, distracted, our wallet needs to stretch just a bit further and the planet is choking from cheaply-made, mass-produced items. 

While in the past things were built to last and updated based on needs rather than wants, today we have been conditioned to go for the new shiny thing and to discard older but perfectly functional belongings - things that are of little or no immediate use to us but with a lot of shelf life left in it.

Instead of scouring through shops and having to buy/resell niche items after use or chasing vendors for specialised rentals, we envision a one-stop meeting place that allows you to get to the good stuff, get it quickly and get it done - on your terms.

Instead of wasting space or money for storage or discarding unused or cumbersome items in landfill, why not declutter your home and have someone else pay you to use and store it elsewhere until you need it again as the owner - on your terms?

By empowering users to act as owners and borrowers on Lendr, we allow people to work together to make each others lives (and the world) a more efficient place by making it quick and easy for them to share their belongings.

Why?

_Side Hustle, yo!_ We all have stuff that can be onverted to cold, hard cash. By renting our your belongings through Lendr, you make your stuff work for you, and save yourself the time, space and dollars required to make room for things you don't need.

_Encourage a more circular and sharing economy_.
Instead of the usual vicious make, use, dispose cycle, keep your specialised and niche items in use for as long as possible. Extract the maximum value from your belongings by keeping them available but out of sight until you need it again.

_Reduce environmental impact and encourage sustainability_.
Put the brakes on excessive landfill, unnecessary mass-manufacturing and labour-intensive systems by sharing instead of buying or discarding.

_Promote experiences, not things_. 
Call it minimalist, zero-waste or common sense living - let go of all the unnecessary clutter and be forced to consider what you really need to own instead of really need to use. With borrowing and sharing now a legitimate and normalised alternative to buying, you can aim for quality over quality, or try before you decide to buy.

_Community_. Make useful connections with people close by and find what you need, quickly, locally and efficiently. Instead of helping the big end of town, find someone you like and trust to give your hard earned dollars over to.

## <a id="Solution"></a>Solution
_Describe the project will you be conducting and how your App will address the needs._
As a community-orientated two-sided marketplace, Lendr lets you help others, help yourself and help the environment by eliminating the need for ownership and making your stuff work for you instead of the other way around. 

Our vision is to provide a fairer, lower-carbon, more transparent, participatory and socially-connected form of economy by encouraging peer-to-peer transactions/interactions in a secure and single meeting place. Through these transactions and interaction, Lendr users (acting as owners and/or lenders) can not only provide ample feedback reciprocally but also provide and/or find competitive prices compared to traditional sellers or renters for specialised or niche items.

A community-oriented two-sided marketplace creates an atmosphere of expertise and enthusiasm among comic culture buyers and hobbyists. It will not only provide ample feedback to sellers, but it will also incorporate better prices for buyers as they are guided by a specialised community.

The process is simple:
1. _Find._
Search for what you need, for a specific item or general category.

2. _Book._
Book the item for your specified days and contact the owner to validate terms.

3. _Collect._
Arrange collection from the owner - use, enjoy.

1. _Return._
Return the item to the lender per the agreed terms and timeframe, and leave them a review.

## <a id="Application"></a>Application
### <a id="Network-Infrastructure"></a>Network Infrastructure
1. Describe the network infrastructure the App may be based on.
    * Research into how we understand the hosting infrastructure
    * Heroku - host on one machine.
    * AWS - hosting our images.
    * Scalability (servers to manage requests), redundancies (if something fails)

### <a id="Software"></a>Software
5. Identify and describe the software to be used in your App.
    Describe the tech stack used for the application
    * Ruby on Rails - framework.
    * Ruby - programming language.
    * CSS (SASS) - styling.
    * HTML - semantic.

### <a id="Architecture"></a>Architecture
8. Describe the architecture of your App.
    * Is this describing MVC in relation to our map? i.e. the MVC model diagram Matt drew?
    * Yes go into detail about MVC, don’t describe any model associations yet

### <a id="Components"></a>Components
9. Explain the different high-level components (abstractions) in your App.
    * High level components examples?
    * Using Gems instead of rebuilding the code.
    * Active Record is an abstraction of SQL
    * You could talk how ruby gems are an abstraction from your own ruby code. You could also talk about how active record is an abstraction of sql.

### <a id="Third-Party-Services"></a>Third Party Services
10. Detail any third party services that your App will use.
    * APIs?
    * Heroku?
    * AWS?

### <a id="Database"></a>Database
#### <a id="Database-Justification"></a>Database Justification
6. Identify the database to be used in your App and provide a justification for your choice.
    * Why we use Postgres instead of SQLite (because SQLite can only do one thing at a time)
    * Full excellent discussion of database used
    * Pros and Cons of Postgresql over SQLite (more than one thing at a time)
    * How postgres is different to sqlite, justify how postgres is way more powerful and how it fits really nicely into rails.

#### <a id="Production-Database"></a>Production Database
7. Identify and describe the production database setup (i.e. postgres instance).
    * Database being setup on Heroku and Postgres (Postgres provided a development version and a production version)
    * Here I would talk about the specifics of postgres, how it connects to your models, how it sits in overall MVC

#### <a id="Market-Research"></a>Market Research
1.  Describe (in general terms) the data structure of marketplace apps that are similar to your own (e.g. eBay, Airbnb).
    * Market research: Things version of Airbnb, similar rental model (difference: for objects not accommodation)
    * Ziilch (difference: users are giving away items for free)
    * Gumtree, eBay (difference: users are buying/seller goods for ownership not rental)
    * Fashion Rentals/Rent Furniture, etc. (difference: companies own inventory)

#### <a id="Database-Relations"></a>Database Relations
12. Discuss the database relations to be implemented.
    * ERD - describe model associations and why.
    * This is more regarding why we need a join table in certain instances in your app, why we need a foreign keys in different tables, think about the stuff we did when we first started sql

13. Describe your project’s models in terms of the relationships (Active Record Associations) they have with each other.
    * Associations - e.g. has many, has one, etc???
    * Think about rails active record associations, has_many, has_one, belongs_to

#### <a id="Entity-Relationship-Diagram"></a>Entity Relationship Diagram
14. Provide your database schema design.
    * Flawless, complex, complete, well thought of ERD?
    * Insert schema image - provide the schema image from DB Database

## <a id="Project-Management"></a>Project Management
### <a id="User-Stories"></a>User Stories
1.  Provide User stories for your App.

### <a id="Wireframes"></a>Wireframes
16. Provide Wireframes for your App.

### <a id="Task-Management"></a>Task Management
17. Describe the way tasks are allocated and tracked in your project.

![Trello Project](/app/assets/readme/trello-lendr.png)
![Trello User Stories](/app/assets/readme/trello-user-stories.png)

    * Trello: source of truth.
    * Pinterest: inspiration and design references for UX/UI, branding.
    * Google Docs: for shared documents and note-taking.
    * Balsamiq: basic wireframes.
    * Figma: detailed wireframes.
    * Slack: daily communication.

### <a id="Agile-Methodologies"></a>Agile Methodologies
1.   Discuss how Agile methodology is being implemented in your project.
    * Discuss how Agile methodology is being implemented in your project.
    * Documents comprehensive plan for agile methodology, with extensive evidence of use
    * https://guide.freecodecamp.org/agile
    * Scrum Master - Linda
    * Daily Scrum (Standups)
    * User Stories - to describe one or more features from the perspective of the end user 
    * (Mini-Sprints - by hours/days)
    * Continuous Deployment/Delivery - deploying every day, commits 

### <a id="Coding"></a>Coding
Brief description of the coding process:
    * Using Rails
    * Using HTML & CSS
    * Desktop and Mobile First

### <a id="Source-Control"></a>Source Control
1.  Provide an overview and description of your Source control process.
    * Provide an overview and description of your Source control process.
    * Meets D criteria and demonstrates frequent commits, merges and pull requests
    * GitHub - one person to manage pull requests, less risky.
    * Commit after every working code snippet.
    * Create new branch for each feature to be worked on.

## <a id="Testing-and-Information-Security"></a>Testing and Information Security
### <a id="Testing"></a>Testing
20. Provide an overview and description of your Testing process.
  Meets D with tests documented or defined for all user stories, extensive use of unit testing on code completed thus far, and well organized test results
    * User Stories for Malicious Use?
    * https://www.railstutorial.org/book/static_pages

As Scott just mentioned on slack feedback from another student would suffice:
* When deciding when and how to test, it’s helpful to understand why to test. In my view, writing automated tests has three main benefits:
* Tests protect against regressions, where a functioning feature stops working for some reason.
* Tests allow code to be refactored (i.e., changing its form without changing its function) with greater confidence.
* Tests act as a client for the application code, thereby helping determine its design and its interface with other parts of the system.

### <a id="Information-Security-Requirements"></a>Information Security Requirements
21.  Discuss and analyse requirements related to information system security.
    * Payment Security?
    * Customer Data Protection?
    * Disputes - Reviews/Comments
    * Lost/Damaged Items

Make this a more general analysis of the ethics behind handling user data.

### <a id="Information-Security-Methodologies"></a>Information Security Methodologies
22. Discuss methods you will use to protect information and data.
    * Encryption - hashing passwords automatically.
    * Stripe - what manages and protects all credit card information
    * Pundit - controls authorisations and what users can see.
    * Timeouts - automatically logging users out after a period of inactivity??
https://www.oaic.gov.au/agencies-and-organisations/guides/guide-to-securing-personal-information
    * Encryption - hashing passwords automatically
    * Stripe - what manages and protects all credit card information
    * Pundit - controls authorisations and what users can see

### <a id="User-Data-Management"></a>User Data Management
23. Research what your legal obligations are in relation to handling user data.
* Cookies - disclaimers for use of cookies to track user data.
* Privacy - using customer data for data analytics, marketing purposes.
https://www.oaic.gov.au/agencies-and-organisations/faqs-for-agencies-orgs/businesses/
* Terms of use
* Posting policy 

## <a id="Minimum-Viable-Product"></a>Minimum Viable Product
### <a id="Challenges"></a>Challenges

### <a id="Future-Enhancements"></a>Future Enhancements
* Make the code DRY
* Geocoder

### <a id="Ethical-Considerations"></a>Ethical Considerations
* Prohibited Items: single use items, living creatures, etc.
* Malicious Use
* Insurance/Fraud

### <a id="The-Pitch"></a>The Pitch
* Attach PowerPoint Presentation
  
## <a id="Conclusion"></a>Conclusion
Final evaluation of the finished product.