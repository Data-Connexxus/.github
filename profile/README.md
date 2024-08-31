# Hello and Welcome to the Synthetic Data Platform Git Hub site 👋
This is the updated work that was started within Project-Herophilus's Data Synthesis 
project (https://github.com/Project-Herophilus/DataSynthesis). We have moved this work into its own organization 
to help us give it a long term viable future as a free-standing asset. There are many more repositories now and we can focus 
on how to continue the great work done over the last three years by amazing individuals and companies like Red Hat, IBM, 
Microsoft and others.

# Background
As we thought about how to continue to help the community of developers and data resources we 
believed that having this work be unbounded by a specific industry or underneath a specific other GitHub organization was the 
bestlong term decision. We are continuing to focus and believe that <b>data being the asset</b> and that
must be core as part of everyone's mindset. A key part we want to ensure is a focus on a wide variety of data enablement
capabilities. Our logic is simple, for years companies have focused on most aspects of development, from the tooling to developing
the next generation of solutions to support their business needs and provide value. However, building great software
to help today's modern needs require data, in many cases, massive amounts of data. It is a HUGE business and technical
benefit if that data can closely resemble production data. Since data is the electricity that powers business and the
cornerstone of companies’ success in the digital era, we wanted to take a more comperehensive focus on enabling
organizations around synthetic data.

Synthetic data is defined as: "any production data applicable to a given situation that are not obtained by direct
measurement" according to the McGraw-Hill Dictionary of Scientific and Technical Terms; where Craig S. Mullins,
an expert in data management, defines production data as "information that is persistently stored and used by
professionals to conduct business processes." With these definitions it is easy to understand the creation of
synthetic data is an involved process that can be achieved by numerous measures and ways. Our way was to create a platform to
synthesize data (Data Synthesis) for multiple needs based on items like industry standards, coded ontologies,
vendor data models, custom defined models all in an on-demand manner. With a focus on data and specifically synthetic
data we wanted our platform to clearly express our focus, the name we settled on was the Synthetic Data Platform.

<i>The idea for the Synthetic Data Platform is in NO WAY new or unique</i>, it purpose and usage is fueled to help reduce and/or remove
the struggle that every organization experiences around their data needs. What we believe makes this plaform unique is our
approach.

* While there are numerous offerings available, from libraries to technology platforms that range from open source to freemium 
  (some free and some paid within technologies). Our goal and intent is to be a "powered by" technology platform that can be molded 
  like clay for to benefit groups from testing to data to integration to applicaton development.
* This project has always intended to be operated under the open/community source model. the Synthetic Data Platform open source
  licensing model is <a href="https://opensource.org/licenses/Apache-2.0" target="_blank">Apache-2.0</a>.
  Our model is not some "freemium" or offering based model with versions and scaled capabilities.
* The Synthethic Data Platform is designed around a very flexible computational data model that can Our initial first years focus was on 
  enabling a massive amounts of extensible data to be used very quickly for a large
  amount of needs. Why should organizations risk <a href="https://www.breachlevelindex.com/" target="_blank">data breaches</a> or the
  potential leakage of <a href="https://en.wikipedia.org/wiki/Protected_health_information" target="_blank">PHI (in healthcare)</a>
  or <a href="https://en.wikipedia.org/wiki/Personal_data" target="_blank">PII (In any other industry)</a>?
* We focused on delivering some core basic RDBMS and EDW level support. The data model and loaders are present for
  PostgresQL, SQL Server, SnowFlake, and DataBricks/Apache Spark. Our most actively maintained platforms are PostgresQL and SQL Server.
* While we tried to build APIs we had a complete lack of technology focus. As we entered mid 2023 we decided to focus on Python as 
  the core technology that we would leverage going forward. Its powerful data capabilities make it the right decision.
* The Synthetic Data Platform is built upon a simple concept of associated or tagged data, the data is associated/tagged with 
  organizations and applications. The platform uses the concept of data attributes (21 different data attributes as part of the 
  base platform) that can be extended based on implementation and specific needs. To enable the platform 
  even further users can configure data structures from their data attributes (9 are pre-configured). 
* If you load the provided data scripts you will have well over 100B data attributes to start using within an hour of loading
  platform.

# The Synthetic Data Platform: Repository Layout
As we moved to a new GitHub organization we also wanted to rethink or repository needs versus maintaining everything in one 
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
