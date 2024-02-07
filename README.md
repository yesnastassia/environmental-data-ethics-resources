# Environmental Data Ethics and Accessibility Resources (EnDEAR)
## What is this about?
This resource was produced as part of the 2024 [NCEAS Environmental Data Science Summit](https://www.nceas.ucsb.edu/environmental-data-science-summit). It is intended to help researchers/anyone who produces environmental data generate a series of questions to inform their decision-making about data sharing and communication. Data sharing presents a huge variety of accessibility, privacy, technical, and ethics challenges, and this is far from an exhaustive list. The questions are arranged into three sections depending on when they would ideally be addressed-- Pre-Research, During Research, and Pre-Publication. At the bottom there is also a list of more general resources.

## How can I help?
This document is designed to be ever-evolving. Feel free to create a PR to add to this document if you know of any additional resources. This document relies on people with a variety of backgrounds contributing their knowledge. If you have any questions about how to do this, feel free to email nastassiabot@gmail.com.

---

## Questions

### Stage 1: Pre-research

#### Accountability
* What intention are you going into research with?
* What community/stakeholders are affected by this research/data sharing?
* What social governance systems are already in place in this community?

#### Assessing Risk
* Is there any personal information in this data?
  * If so, what level of anonymization or de-identification is needed
    * Is that possible with the type of data in consideration?
  * If not, are there any broader harms to society that could result from the widespread use of this research?
* What kind of risk mitigation measures are already in place?
* What tools/risk assessments can be used to assess risk opportunity impact?

**Resources**: [Microsoft Data Ethics](https://github.com/microsoft/Data-Science-For-Beginners/blob/main/1-Introduction/02-ethics/README.md)-- info about privacy, informed consent, right to be forgotten, and other concerns

#### Funding
* Does the funding of the research require data to be open?
* Are there any costs to making data available? 
* Are there any costs to making access conditional?

#### Power and politics
* What is the political landscape of the area of research?
* Does this data span legislative boundaries?
  * If so, which ones? How does this affect the research and/or data sharing?
* Who can do something about the problem related to this data?
* Is there a power imbalance between stakeholders?

**Resources**: [American Political Science Association Ethics Guide](https://www.apsanet.org/Portals/54/diversity%20and%20inclusion%20prgms/Ethics/APSA-Ethics-Guide-Updated-May2023.pdf?ver=MVFh4bbveoaHD0uP568mig%3d%3d) provides some interdisciplinary food for thought

#### Sharing Motives
* Who owns this data “legally”? / “ethically”?
  * How do you plan to determine this?
* Do stakeholders want this data to be shared?
* Why do people want this data to be shared? 

**Resources**: [Data Governance Institute Data Ownership](https://datagovernance.com/assigning-data-ownership/)

#### Indigenous Data 
* Does indigenous land sovereignty play a role in sharing this data?

**Resources**: [Indigenous Peoples' Specialty Group Ethics Statement (AAG)](https://sites.evergreen.edu/zoltan/wp-content/uploads/sites/358/2023/09/IPSGResearchEthicsFinal.pdf)

#### Data Storage and Management
* How long should the data be kept?
* Where data will be housed/how will it be made available? 
* Will that change over time? Is it funding dependent?

**Resources**: [USFS Research Data Archive](https://www.fs.usda.gov/rds/archive/submittingData)-- managed repository for any data collected with USFS funding or on USFS land

---

### Stage 2: During Research

#### Data Created in Research
* Who owns this new data “legally”? / “ethically”?
* At what scale does the data exist?

#### Reassessing Potential Risk and Benefit
* What are the potential impacts of sharing the data? 
  * If so, how do they vary between stakeholder groups?
* Who stands to benefit from this data?
  * In what ways?
* Who might experience harm/loss from this data?
  * If so, what is the nature of this loss/harm?
  * Are there any mitigation strategies (see sections about anonymization/rescaling)
* Does this data potentially affect fiscal burdens (insurance/property value)? 
  * Is it on individuals or businesses?
  * Are there ways to anonymize/de-identify specific personal information?

#### Power and Politics
* Have new political concerns surfaced in the research process?

**Resources**: [American Political Science Association Ethics Guide](https://www.apsanet.org/Portals/54/diversity%20and%20inclusion%20prgms/Ethics/APSA-Ethics-Guide-Updated-May2023.pdf?ver=MVFh4bbveoaHD0uP568mig%3d%3d)

---

### Stage 3: Before Data Publication

#### Technical Components of Accessibility
* In what formats is the data available and how does this affect accessibility?
* What are the conditions of access of the data?
  * Does accessing your data require any paid software or subscriptions?
* Are we also sharing our process/code, if applicable?

**Resources**: [STAC Framework](https://stacspec.org/en)-- open geospatial metadata standard especially useful for making high-dimensional or nested data more accessible/queryable
[OGC Standards](https://www.ogc.org/standards/)-- well-established FAIR data standards for geospatial data including metadata, encoding, etc
[Open Source Initiative Licenses](https://opensource.org/licenses/)-- open software licensing

#### Storage, Management, Longevity
* How much/what type of security is necessary to secure the data?

#### Impacts
* Beyond the impacts on individual stakeholder lives, are there broader harms to society that could result from the widespread use of this research?
* Are there similar data available already? How is it shared?

#### Sharing Security Concerns
* Do we need to anonymize the data before sharing?
* Does the scale need to be changed to share the data?
* Can you allow queries without making all the data available?

#### Data Communication Concerns
* Are there risks of misinterpretation? or “overreaction”/ negative social consequences?
  * If so, how can you anticipate and prepare for these risks? Can you make a contingency plan for sharing?
* How can we disaggregate data to communicate social justice issues, if our research involves different populations of people?
* What kinds of analysis are allowed with the data?
* What kind of visualizations can be made to help users understand and/or preview the data?

**Resources**: [White House Vision for Equitable Data](https://www.whitehouse.gov/wp-content/uploads/2022/04/eo13985-vision-for-equitable-data.pdf)

---

## General Resources
* [The GIS Professional Ethics Project: Practical Ethics Education for GIS Pros](https://www.e-education.psu.edu/sites/default/files/ethics/DiBiase_et_al_GIS_Pro_Ethics_ICC2009.pdf)
  * Features several case studies relevant to the ethical principles outlined, dozens of further references included as well
  * [Case studies](https://sites.psu.edu/gisethics/project-description/)
* [Reflecting Sunlight: Recommendations for Solar Geoengineering Research and Research Governance](https://nap.nationalacademies.org/read/25762/chapter/5)
  * An entire book about research governance, with some applicability to data sharing specifically
* [American Association of Geographers (AAG) ethics initiative](https://www.aag.org/program/ethics-and-aag/)
* [International Cartographic Association (ICA) ethics conference and initiative](https://icaci.org/announcing-autocarto-2022-ethics-in-mapping)
  * Also contact Aileen Buckley at Esri, abuckley@esri.com
* [White House Vision for Equitable Data](https://www.whitehouse.gov/wp-content/uploads/2022/04/eo13985-vision-for-equitable-data.pdf)
* [Climate and Environmental Justice Screeing tool](https://screeningtool.geoplatform.gov/en/#3/33.47/-97.5)
* [EJ Screen](https://ejscreen.epa.gov/mapper/)
* [Data Science Ethics: Case Studies on Medium](https://samiwurm.medium.com/data-science-ethics-case-studies-988cbbc6af84)
* [Mapping for accessibility: A case study of ethics in data science for social good](https://arxiv.org/ftp/arxiv/papers/1710/1710.06882.pdf)

---

## Contributors
### Authors
* Sarah Buckingham (she/her) sbuckingham217@gmail.com
* Alex Powell (he/him)
* Emelia Williams (she/they) emelia@openenvironmentaldata.org
* Nastassia Barber (they/them) nastassiabot@gmail.com
* Beatriz Milz (she/her)

### Additional Resource Contributors
Dawn Wright
