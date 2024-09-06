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

# Platform 
For simplicity sake the platform we break down into two core areas: data model and technology.

## Data Model
The data model is what provides platforms powerful capabilities that start with its extensibility 
provided through the data it provides. The Synthetic Data Platform is no different,  as almost all of 
our core usage has been driven from direct accessing of the data contained with the 
platforms data model. Because of our heavy data usage our focus for years has been on the data model.
With this focus we have substantially evolved our data tier mindset. 

We started with a very traditional RDBMS-based focus and mindset and evolved towards a 
more flexible and less constrained RDBMS-based data model. In late 2023, we removed the 
very tight RDBMS mindset as it constrained our capabilities. We also 
decided to focus on a limited core set of data technologies. Going forward we only support 
two RDBMS technologies (PostgreSQL and SQL Server), one EDW (SnowFlake) technology 
and one computational platform (Spark/DataBricks). 

Now, we have a highly functional and very performant data model that is more computational 
than relational that contains billions of attributes in a very compact amount of storage, rough 
650 megabytes (depending upon the specific technology used). While the focus of the data tier 
has been moving to a computational model there will remain a large amount of reference data 
to help the platform tag data according to specific usage that can business or industry 
needs and usages. What drives the core design of the data model now is not primary-foreign 
key data relationships but the platform's key subsystems and how the data tier supports them. 

The data tier while supporting a substantial amout of business use cases and needs is very simple.
All the table names follow a specific notation <core area>_<capability>. The platform currently 
has five core areas:
- data model deals with the data model; we have all our data model documentation and details 
in these tables.
- datatier: Anything the platform provides is within this area.
- platform: All the settings, capabilities, and extensibility the platform can address are maintained 
within this area.
- refdata: The platform can tag data in all ways exists within this area.
- terms: Any terminologies the platform might need to use depending upon the industry or 
general needs within this area.

## Technology
With such a focus on the data tier we really never had adequately focused on technology to 
support the data tier. This was driven by most of the contributors to our initial platform were 
all data folks. So we did not do the technology layer around the data tier any justice. Whether it
was using several technologies like SpringBoot, Node, or Quarkus we were not committed to 
technology powering our data model and its future. As we retooled and revamped the data tier, 
it was clear we needed to focus on a technology to use to provide a variety of capabilities for 
users who wanted any form of a development experience with the platform. In late 2023, we 
settled on Python. While our work with the other technologies has been excellent, Python 
gives us the best path forward to have a coomplete and amazing technology stack that can 
be used for any need while also being an amazing data engineering, web, and analysis technology.

# Key Content
The following section is intended to provide a simple way to find key areas of content about the Synthetic Data Platform.

| Area                                                                                                                                                                | 
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a href="https://github.com/SyntheticDataPlatform/.github/blob/main/profile/PlatformSubsystems.md" target="_blank">The Synthetic Data Platform: Subsystems</a>      |
| <a href="https://github.com/SyntheticDataPlatform/.github/blob/main/profile/RepositoryLayout.md" target="_blank">The Synthetic Data Platform: Repository Layout</a> |
| <a href="https://github.com/SyntheticDataPlatform/.github/blob/main/profile/HowItWorks.md" target="_blank">The Synthetic Data Platform: How It Works</a>            |

*Enjoy and Happy Coding!!!*

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
