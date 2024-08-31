# Welcome to the Synthetic Data Platform Git Hub site 👋
This is the updated work that was started within Project-Herophilus's Data Synthesis 
project (https://github.com/Project-Herophilus/DataSynthesis). We have moved this work into its own organization 
to help us give it a long-term viable future as a free-standing asset. There are many more repositories now and we can focus 
on how to continue the great work done over the last three years by amazing individuals and companies like Red Hat, IBM, 
Microsoft and others.

# Background
As we thought about how to continue to help the community of developers and data resources we 
believed that having this work be unbounded by a specific industry or underneath a specific other GitHub organization was the 
best long-term decision. We continue to focus and believe that <b>data is the asset</b>, which
must be core as part of everyone's mindset. A key part we want to ensure is a focus on a wide variety of data enablement
capabilities. Our logic is simple: for years, companies have focused on most aspects of development, from the tooling to developing
the next generation of solutions to support their business needs and provide value. However, building great software
to help today's modern needs requires data, in many cases, massive amounts of data. It would be a HUGE business and technical
benefit if that data could closely resemble production data. Since data is the electricity that powers business and the
cornerstone of companies’ success in the digital era, we wanted to focus more on enabling
organizations around synthetic data.

Synthetic data is defined as: "any production data applicable to a given situation that is not obtained by direct
measurement" according to the McGraw-Hill Dictionary of Scientific and Technical Terms, where Craig S. Mullins,
an expert in data management, defines production data as "information that is persistently stored and used by
professionals to conduct business processes." With these definitions, it is easy to understand that the creation of
synthetic data is a process that involves numerous measures and ways. Our way was to create a platform to
synthesize data (Data Synthesis) for multiple needs based on items like industry standards, coded ontologies,
vendor data models, and custom-defined data models, all in an on-demand manner. With a focus on data and specifically synthetic
data, we wanted our platform to express our focus clearly, the name we settled on was the Synthetic Data Platform.

<i>The idea for the Synthetic Data Platform is in NO WAY new or unique</i>; its purpose and usage are fueled to help reduce and remove
the struggle that every organization experiences around their data needs. What we believe makes this platform unique is our
approach.

* While there are numerous offerings available, from libraries to technology platforms that range from open source to freemium 
  (Some are free, and some are paid within technologies). Our goal and intent is to be a "powered by" technology platform that can be molded 
  like clay for benefit groups from testing to data to integration to application development.
* This project has always intended to be operated under the open/community source model. The Synthetic Data Platform open source
  licensing model is <a href="https://opensource.org/licenses/Apache-2.0" target="_blank">Apache-2.0</a>.
  Our model is not some "freemium" or offering-based model with versions and scaled capabilities.
* The Synthetic Data Platform is designed around a very flexible computational data model that can Our initial first years focus was on 
  enabling massive amounts of extensible data to be used very quickly for a large
  amount of needs. Why should organizations risk <a href="https://www.breachlevelindex.com/" target="_blank">data breaches</a> or the
  potential leakage of <a href="https://en.wikipedia.org/wiki/Protected_health_information" target="_blank">PHI (in healthcare)</a>
  or <a href="https://en.wikipedia.org/wiki/Personal_data" target="_blank">PII (In any other industry)</a>?
* We focused on delivering some core basic RDBMS and EDW-level support. The data model and loaders are present for
  PostgreSQL, SQL Server, SnowFlake, and DataBricks/Apache Spark. Our most actively maintained platforms are PostgreSQL and SQL Server.
* While we tried to build APIs, we needed more technology focus. As we entered mid-2023, we decided to focus on Python as 
  the core technology we would leverage. Its powerful data capabilities make it the right decision.
* The Synthetic Data Platform is built upon a simple concept of associated or tagged data; the data is associated/tagged with 
  organizations and applications. The platform uses the concept of data attributes (21 different data attributes as part of the 
  base platform) that can be extended based on implementation and specific needs. To further enable the platform, users can
  configure data structures from their attributes (9 are pre-configured). 
* If you load the provided data scripts, you will have well over 100B data attributes to start using within an hour of loading
  platform.

# Platform Core
Like any platform, its power and capabilities start with its extensibility provided through the data model, which is seen
in the data the platform can leverage. It has been a journey for us to get to this point. We started with a very traditional RDBMS-based 
focus and mindset and evolved towards a more flexible and less constrained
RDBMS-based data model. In late 2022, we removed the very tight RDBMS mindset as it constrained our capabilities.
We also decided as we did this to focus on two RDBMS technologies (PostgreSQL and SQL Server), one EDW
(SnowFlake) technology and one computational platform (Spark/DataBricks). We knew that this decision
around our data model capabilities would have negative technology impacts as it would also break all the APIs 
we had been developing. Still, we decided to revamp the data tier as our primary focus as most of the community
that downloaded it was focused on just querying the data tier for random data.

Now, we have a highly functional data model that is more computational than relational. However, it does have a large contingent of
reference data to help the platform tag data according to business or industry needs and usages. What drives the core
design of the data model now is not primary-foreign key data relationships but the platform's key subsystems and how
the data tier supports them. The platform currently has five core areas:
- data model deals with the data model; we have all our data model documentation and details in these tables.
- datatier: Anything the platform provides is within this area.
- platform: All the settings, capabilities, and extensibility the platform can address are maintained within this area.
- refdata: The platform can tag data in all ways exists within this area.
- terms: Any terminologies the platform might need to use depending upon the industry or general needs within this area.

## Technology
With such a focus on the data tier and so many incredible developers that have leveraged this work, deciding on a specific technology
did not take on the correct level of importance. Additionally, with all the changes we continued to do as we grew into the
right data tier we always seemed to have more broken development artifacts than functional. As we retooled and revamped
the data tier, it was clear we needed to focus on what technology to use to provide a variety of capabilities to users
who wanted any form of a development experience with the platform. In late 2023, we settled on Python. While our work with the 
other technologies has been excellent, Python gives us the best path forward with an amazing technology
stack that can be used for any need while also being an amazing data engineering and analysis technology.

# How Does SDP - Synthetic Data Platform Work
Let's transition from the history of what we have been building to explain the power, extensibility, and simplicity
of the platform.

# The Synthetic Data Platform: Repository Layout
As we moved to a new GitHub organization, we also wanted to rethink our repository needs versus maintaining everything in one 
single repository. 

## Data Tier
Specific artifacts related to the platform's data tier

| Area                 | Repository Location                                                                                            | 
|----------------------|------------------------------------------------------------------------------------------------------------|
| DataTier DDLs      | https://github.com/SyntheticDataPlatform/DataTier-DDLs/blob/main/README.md | 
| DataTier DataLoaders|https://github.com/SyntheticDataPlatform/DataTier-DataLoaders/blob/main/README.md|

## Development Assets
Specific artifacts related to the platform's development assets provided

| Area   | Repository Location                                                                                        | 
|--------|--------------------------------------------------------------------------------------------------------|
| Python | https://github.com/SyntheticDataPlatform/Python/blob/main/README.md | 

# The Synthetic Data Platform Legacy Assets: Repository Layout
The following code is legacy and not being maintained. The goal is that in late 2024 or early 2025 these repositories will
be removed as any functionlaity is ported into Python.

## APIs - Legacy
Specific artifacts related to the platform's provided APIs. It should be noted that most of the APIs need refactoring as the data model
itself was completely refactored to help simplify it and provide greater extensibility for the future.

| Area                 | Repository Location                                                                                            | 
|----------------------|------------------------------------------------------------------------------------------------------------|
| SpringBoot-APIs      |https://github.com/SyntheticDataPlatform/APIs-SpringBoot  |
| Node APIs            |https://github.com/SyntheticDataPlatform/APIs-Node    |
| Quarkus APIs         |https://github.com/SyntheticDataPlatform/APIs-Quarkus |

## User Interfaces - Legacy
While there are projects listed, these are aspirational, as we need to refactor the APIs and reimagine the capabilities we want overall.

| Area                 | Repository Location                                                                                           | 
|----------------------|------------------------------------------------------------------------------------------------------------|
| REACTT UI            | Future - https://github.com/SyntheticDataPlatform/UIs-Web-REACT|
| Vue UI               |https://github.com/SyntheticDataPlatform/UIs-Web-Vue|



*Enjoy and Happy Coding!!!*

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
