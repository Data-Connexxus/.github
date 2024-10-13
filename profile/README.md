# Welcome to the Data Jedi Toolkit GitHub site 👋
This site represents the updated work that started in several separate GitHub organizations to accomplish various data needs. 
The widest adoption (commitment to, implementation, and use) started in 2020 within [Project-Herophilus](https://github.com/Project-Herophilus/). 
We have now moved this work into its organization to help us give it a long-term viable future as a series of free-standing reusable data assets. 
We can focus on how to continue the great work done over the last several years by unique individuals and companies like Red Hat, IBM, Microsoft, and others.
As we considered how to proceed, we wanted to continue helping the community of developers and data resources. 
After lots of feedback and discussion, it was evident that having the various data capabilities unbounded by a specific industry and consolidated into
one GitHub organization is the best long-term decision. We continue to focus and believe that <b>data is the asset</b>, a core belief of everything we have worked towards. 

An essential part we want to ensure is a focus on a wide variety of data enablement capabilities. Companies have focused on most aspects of development, from the tooling to developing the next generation of solutions to support their business needs and provide value. However, building great software to help today's modern needs requires data, in many cases, massive amounts of data. It would be a HUGE business and technical
benefit if that data could closely resemble production data. Since data is the electricity that powers business and the
cornerstone of companies’ success in the digital era, we wanted to focus more on enabling
organizations around synthetic data.

* As we prepare for the future needs of the platform we are also evaluating how to add in de-identification, anonymization and data crawling capabilities as well to
  continuing rounding out the platform.

# Platform 
For simplicity's sake, we break down the platform into two core areas: data model and technology.

## Data Model
The data model provides platforms with powerful capabilities that start with its extensibility 
supplied through the data it provides. The Synthetic Data Platform is no different,  as almost all of 
our core usage has been driven by directly accessing the data contained in the 
platform's data model. Because of our heavy data usage, we have focused on the data model for years.
With this focus we have substantially evolved our data tier mindset. 

We started with a traditional RDBMS-based focus and mindset and evolved towards a 
more flexible and less constrained RDBMS-based data model. In late 2023, we removed the 
very tight RDBMS mindset as it constrained our capabilities. We also 
decided to focus on a limited core set of data technologies. As we advance, we only support 
two RDBMS technologies (PostgreSQL and SQL Server), one EDW (SnowFlake) technology, and one computational platform (Spark/DataBricks). 

Now, we have a highly functional and very performant data model that is more computational 
than relational and contains billions of attributes in a very compact amount of storage, rough 
Six hundred fifty megabytes (depending upon the specific technology used). While the focus of the data tier 
has been moving to a computational model, a large amount of reference data
will be needed to help the platform tag data according to specific usage that can meet business or industry 
needs and usages. What drives the core design of the data model now is not primary-foreign 
key data relationships, the platform's key subsystems, and how the data tier supports them. 

While supporting a substantial amount of business use cases and needs, the data tier is elementary.
All the table names follow a specific notation <core area>_<capability>. The platform currently 
has five core areas:
- datamodel_<capability>: deals with the data model; we have all our data model documentation and details in these tables.
- data_<capability>: this area will be implemented as we absorb other projects and efforts into this platform to ensure consistency
  and capabilities that we can deliver to continue the platform's expansive capabilities.
- datatier_<capability>: Anything the platform provides is within this area.
- platform_<capability>: All the settings, capabilities, and extensibility the platform can address are maintained within this area.
- refdata_<capability>: The platform can tag data in all ways exists within this area.
- terms_<capability>: Any terminologies the platform might need to use depending upon the industry or general needs within this area.

## Technology
With such a focus on the data tier, we were very distracted and needed to pay adequate respect to the technology tier for this 
platform; we did not until 2024. Since the core users and contributors to our initial platform were 
all data folks. So we did not do the technology layer around the data tier any justice. Whether it
was using several technologies like SpringBoot, Node, or Quarkus, we were not committed to 
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
