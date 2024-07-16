# Peter Kannam 
<img src="docs\assests\images\peterkannam_headshot.png" align="right" width="200px"/>
Hello! I am a professional environmental geologist and data scientist working for TetraTech. The focus of my work is... I primarily support the following projects:

- *Chicago Cumulative Impact Assessment; Data and Methods Working Group* for the Chicago Department of Public Health
- *Superfund Technical Assessment and Response Team* for Region 5 of the US EPA Region 5
- *Navajo Abandoned Uranium Mines; Response, Assessment, and Evaluation Services* for US EPA Region 9
<br clear="left"/>

My CV can be found [here](). For an example of a project I have worked on I suggest the [Chicago Environmental Justin Index](#project-highlight-chicago-environmental-justice-index): a composite indicator model that scores all the census tracts in Chicago using 28 indicators of environmental health. For an example of my code, I suggest  [`CompoisteIndicators.jl`](https://github.com/peterkannam/CompositeIndicators.jl?tab=readme-ov-file#compositeindicatorsjl): a package I wrote for the calculation and analysis of composite indicator models in [`Julia`](https://julialang.org/).

## Professional Experience

My technical expertise in field instrumentation is well complimented by my background in data science, allowing me to provide complete analysis and visualization for varied statistical studies. 

### Data Science and Statistics

I conduct analyses on environmental datasets that account for the limitations imposed by instrumentation and sampling methods. This frequently involves using different regression methods, hypothesis testing, and timeseries analyses to evaluate relationships between sources of data and summarize trends. Because the data I handle is often compared to permissible exposure limits it is important to ensure that conservative estimates are calculated. This requires a complete understanding of measurement errors and how they propagate through different analyses. 

#### Project Highlight: Chicago Environmental Justice Index

<img src="docs\assests\images\ceji_structure.png" align="right" width="400px"/>

I was the lead statistical analyst of the Chicago Environmental Justice Index (CEJI), part of the larger Cumulative Impact Assessment conducted by the Chicago Department of Public Health. The CEJI is a composite indicator model that assigns an Index score to each census tract in Chicago by aggregating the information in 28 indicators of environmental health. It was created to inform decisions made by policymakers who wish to enact equitable improvements to the city's environmental health. 

I was asked to calculate the Index, run a set of sensitivity analyses, and analyze its relationship to racial demographic data based on the methods published by the [CalEnviroScreen 4.0](https://oehha.ca.gov/calenviroscreen/report/calenviroscreen-40). However, the sensitivity analyses implemented by the CalEnviroScreen were limited to the analysis of the rankings in the top 10% of scores and did not have a robust analysis of how different indicators influenced the Index. When I pointed out these limitations, I was asked to perform a literature review of composite indicator methods and a more rigourous sensitivity analysis. 

The ensuing *Statistical Coherence Assessment* characterized the structure of the of the CEJI and the influence of individual indicators. The code used for this analysis was further developed into [`CompoisteIndicators.jl`](https://github.com/peterkannam/CompositeIndicators.jl?tab=readme-ov-file#compositeindicatorsjl).

### Emergency Responder - Air Monitoring and Telemetry Specialist

As a memeber of the *Superfund Technical Assessment and Response Team* I was specialist in quickly establishing effective air monitoring networks during environmental distasters. This involved the deployment and maintience of air monitoring instruments, using network specific devices to connect instruments to telemetry software, and using that software to push synced data to relevent servers. 

Telemety was primarily established using the [Viper](https://response.epa.gov/site/site_profile.aspx?site_id=5033) system developed by US EPA, and required the manipulation of insturment and computer network settings. Network connections through Viper use cell, wi-fi, and radio communication and synced using Precision Time Management protocols, meaning that through training and troubleshooting I developed a practical knowledge on how to establish and manipulate real time time data flows.

My experience is such that *Superfund Technical Assessment and Response Team* management asked me to design and run a training for all TetraTech responders on the contract.

#### Project Highlight: East Palistine Train Derailment 

I helped establish and maintain the air monitoring network around the East Palistine Train Derailment.  Because of its size and longevity, this project taught me how to effectively scale air monitoring networks and many telemetry best practices that are not normally considered in emergency conditions. 

I was also in charge of computing daily air monitoring summaries tables for US EPA to distrubute, a process with I largely automated. An example can be found [here](https://www.epa.gov/system/files/documents/2023-06/Continuous%20Monitoring%20Summary%20Table_20230611_Community_508T.pdf), all of summary tables can be found [here](https://www.epa.gov/east-palestine-oh-train-derailment/air-monitoring-documents).


## Education 

### Dartmouth College - Class of 2022
#### Major: Earth Sciences

#### Research Experience

- Honors Thesis: *Changing Host Phases of Sedimentary Mercury in the Road River Group of Yukon, Cananda and Implications of its use as a geochemical proxy*
    - Advisor: Justin Strauss
- Member of the Struass Lab for four years
- Lab research assistant
- Field research assistant

#### Relevent Coursework


### Baltimore City College High School - Class of 2017

## Research Interests

Interacting with government, community, and academic stakeholders in this way has helped me develop an interest in how studies can be desgined and communicated to conduct the best science that can satisfy different interests. 

