# Tokenizing Data 

McKinsey defines tokenization as: "Tokenization is the process of creating a digital representation 
of a real thing. Tokenization can also be used to protect sensitive data or to efficiently process 
large amounts of data." Our history for almost everything you will read is based on experience of working with 
data and databases directly. Several of the contributors and even potential contributors talked
about the topic of tokenization and why we never included anything around this topic in our repositories.
Because we leverage tokenization internally we decided to make it a more formalized capability 
versus just some code that we potentially leverage.

- Tokeniztion is not a new concept and we are not doing any patented algorithms, we are providing a 
configurable and tunable set of capabilities. These capabilities can be used from the platform 
as an API or part of the application capabilities. We also provide some configurable options so the
tokenization can be customized for the implementation needs.
- We have enhanced our data model to support the storage of the tokens and some details 
provided. We will not store all the metadata that was used to generate a specific token. 
- We do provide a metadata table to ensure organizations can reference what data attributes they use to 
create tokens.

# Key Content

| Area                                                            | 
|-----------------------------------------------------------------|
| <a href="./TBD.md" target="_blank">Tokenization: Subsystems</a> |


