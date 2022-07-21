# Lesson 1:  What is Open Data?

**Module lead**

**Contributors**

## Introduction
As mentioned earlier, data is a major part of scientific research, and why wouldn’t it be? It is evident that data permeates many aspects of our daily life with significant consequences.

For instance, it has become all the more common to see news articles discussing how data and efforts like [Open Street Map](https://www.openstreetmap.us/)  are critical in supporting the disaster emergency responses all over the world [1](https://www.openstreetmap.us/). This is only an example among many others demonstrating the value of data, particularly open and public data, in our daily life and for public good.

Similarly, data shared openly in scientific research brings tremendous value which is not limited to the scientific community but extends to communities at large from indigenous communities to urban populations! Before we look further into this, let’s first look at what is data in scientific fields? What is open data? What are the key characteristics of open data? 


### 1.1 What is Data?
**Data** is any type of information, recordable or observable facts. **Research data** is thus data collected in order to answer the research questions of a project. 

Research data can be numbers, texts, measurements, images, model output, and more. 
Research data is collected in different ways, and formats. Generally speaking it can be grouped in different ways, for example:

- Qualitative data describing information in words 
- Quantitative data with defined numerical information, e.g. from measurements
- Grouped versus ungrouped data; grouped data being data that has been put into classes for next steps such as interpretation and ungrouped data referring to the raw data [2](https://keydifferences.com/difference-between-ungrouped-data-and-grouped-data.html) 
- Structured versus unstructured data: unstructured data referring to data in its raw format, and structured data referring to data formatted for storage in files or records such as relational databases [3](https://www.datamation.com/big-data/structured-vs-unstructured-data/)

In the next section we will introduce the different types of data most commonly generated/found in research. This will provide an understanding of how different data should be handled and what considerations to keep in mind when sharing it openly.  More on this can be found in lessons 3 (Responsible Open Data) & 4 (CARE and FAIR Principles).  We will also highlight one particular type of data (metadata, described below) and its role in supporting the development of Open Data and Open Science initiatives.


#### Primary (raw) data
Primary data refers to data that is directly collected or created by researchers.  Examples include surveys, questionnaires, interviews, physical samples, specimens, output from models, remote sensing data (spectral/photons), etc. Research questions guide the collection of the data. Typically, a researcher will formulate a question, develop a methodology and start collecting the data. Some examples of primary data include:

**Responses to Interviews, questionnaires, and surveys.** 

Typically, interviews generate data, in the form of recorded audio ﬁles, transcripts, and notes and other observational data. Interviews can address a broad range of quantitative or qualitative oriented research questions, and may be used on their own or as part of a mixed methods approach. In behavioral and social sciences, these data collection methods are often used to collect self-reported data. A researcher designs these questions to collect data from participants that are necessary for the research. In most cases, this type of data can be openly shared under certain conditions or considerations e.g. if they are de-identified, and if the participants consent about the data being shared, more on that in lesson 2 and 3.

**Data acquired from recorded measurements**, including remote sensing data.

In many cases, the raw primary measurements from an instrument are processed in various ways such that what is typically stored and reported is based on a variety of calibration, normalization, and even compression steps that are ideally well defined and described by a discipline or measurement protocol. For example, satellite captured imagery is often used in online map services and navigation (e.g., Google Maps). These satellite imagery is often captured by various sensors onboard space-borne satellites (e.g., [NASA Earth Observing System](https://eospso.gsfc.nasa.gov)) or airborne measuring platforms (e.g., uncrewed drones or planes) [[4](https://eospso.gsfc.nasa.gov)]. These data often need careful calibration and correction including the values recorded by the sensors and the geospatial location of the imagery before it can be used appropriately for research and application. After the calibration and corrections, remote sensing imagery are often used to create products that can help us understand the environment that we live in and useful for societal benefits (e.g., studying air quality impact on community health). 

**Data acquired from physical samples and specimens** form the base of many studies. 

Tests and analyses are conducted on these resources, such as biological specimens, rocks and minerals, soils and sediments, plants and seeds, water samples, archaeological artifacts, or DNA and human tissue samples  ([Research Data Alliance Interest Group on Physical Samples](https://www.rd-alliance.org/groups/physical-samples-and-collections-research-data-ecosystem-ig)) [[5](https://www.rd-alliance.org/groups/physical-samples-and-collections-research-data-ecosystem-ig)]. While it may be more difficult to share these types of physical resources, information about the samples and as well as data derived from using them, can be shared via thorough description, such as in the case of BioBanks, [IGSN](https://www.igsn.org/) (a persistent identifier specifically for physical samples), and [iSamples](https://isamplesorg.github.io/home/) [[6](https://www.igsn.org/)] [[7](https://isamplesorg.github.io/home/)]. For more information about how to manage physical samples, check out the 23 Things Physical Samples [[8](https://zenodo.org/record/6818076#.YtgQhITMK3B)].

**Data generated from models and simulations.** 

Not all primary data are observations collected by people or instruments. We also build mathematical models either based on physical laws or empirical relationships to understand a subject or system. The model can produce a suite of simulations driven by various input scenarios or initial conditions. For example, Coupled Model Intercomparison Project ([CMIP](https://www.wcrp-climate.org/wgcm-cmip)) is an international project with participation from more than 20 earth system modeling centers to generate the historical simulation and future projections of the earth system under different greenhouse gas emission scenarios [[9](https://www.wcrp-climate.org/wgcm-cmip)]. The Open Data generated in the most recent phase of CMIP (CMIP6) allows researchers to understand the impact of the changing climate to the ecosystem and our society. The understanding derived from CMIP6 data can then be used to inform climate policies and adaptation strategies. Model data are valuable assets because it can provide data that can be hard or sometimes impossible to collect in real world [[10](https://www.climateurope.eu/a-short-introduction-to-climate-models-cmip-cmip6/)]. 

#### Processed data
Processed data typically refers to data that is created or collected by someone else and used by others. 

Examples include data from literature, academic publications, generated statistics such as government statistics, transcripts of recordings, and a variety of streaming environmental and biological data that are deposited and made available in databases and repositories. 

This type of data is oftentimes used for a different purpose than originally intended, for example, from a previous experiment or from another research project or a different discipline. 

It is very common in the era of digital scientific research to see new primary datasets created or produced by collecting and repurposing secondary data and/or mixing them with new primary data. This kind of research practice is made possible by the promotion of Open Data. Data sharing provides opportunities for all researchers, even the novice and/or unfunded, therefore leveling the playing field [[11](https://www.sciencedirect.com/science/article/abs/pii/S0023969001910987?via%3Dihub)].  More on the benefits of Open Data in lesson 2. 

#### Metadata 
Metadata is a special type of data that describes other data or objects (e.g. samples).  It is often used to provide a standard set of information about a dataset to enable easy use and interpretation of the data.  

It can facilitate assessment of dataset quality, by answering key questions, such as including key information on: 

* How the data was collected (e.g. which equipment/instruments were used)
* Which variables/parameters are included in this dataset
* Who or which organization created or collected the data
* When the data was collected and deposited
* Where to find the data (e.g. DOI) and how to cite it 
* Which geographic region the dataset covers 
* Who can use the data and how
* Which version is the dataset
* What is the format of the data
* Whether  the dataset follows any community or international standards or guidelines

In addition, metadata allows cataloging and data discovery specially, if it follows leading practices allowing them to be indexed by search engines ([The Turing Way, 2019](https://the-turing-way.netlify.app/reproducible-research/reproducible-research.html)) [[12](https://the-turing-way.netlify.app/reproducible-research/reproducible-research.html)]. In other words, it enhances searchability and findability of the data by allowing other machines to read and interpret datasets  (see the concept Findable in lesson 4 - CARE and FAIR principles)

In later lessons, we will describe how to create metadata and where to find help (e.g. repositories) 

There are different types/categories of metadata addressing different purposes:

* **Descriptive metadata** can contain information about the context and content of your data; such as, abstract, title, subject keywords.
* **Structural metadata** is used to describe the structure of the data (e.g., file format, the dataset hierarchy).
* **Administrative metadata** explaining the information that is used to manage the data (e.g., when and how it was created, which software and the version of the software used in data creation).


### 1.2 What is Open Data?

#### Availability and accessibility

#### Reusability 

#### Inclusivity

## Conclusion

## Assessment 
