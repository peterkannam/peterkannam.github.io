# Peter Kannam 
<img src="docs\assests\images\peterkannam_headshot.png" align="right" width="200px"/>

Hello! I am a professional environmental geologist and data scientist working for TetraTech. The focus of my work has been aiding government officals in public health and regulatory decision making through the use of technical instrumentation and by applying statistical best practices to environmental datasets. My CV can be found [here](https://peterkannam.github.io/docs/assests/Kannam_CV_Test.pdf). 



I primarily support the following projects:
- [Chicago Environmental Justice Index](#project-highlight-chicago-environmental-justice-index) for the Chicago Department of Public Health: a composite indicator model that scores all the census tracts in Chicago using 28 indicators of environmental health
   - I developed the code I wrote for this project into [`CompoisteIndicators.jl`](https://github.com/peterkannam/CompositeIndicators.jl?tab=readme-ov-file#compositeindicatorsjl): a dynamic [`Julia`](https://julialang.org/) package for the computation and senstivity analysis of composite indicator models that can be used by cities and groups undertaking similar efforts
- [Superfund Technical Assessment and Response Team](https://www.epa.gov/east-palestine-oh-train-derailment) for US EPA Region 5
- [Navajo Abandoned Uranium Mines; Response, Assessment, and Evaluation Services](https://www.epa.gov/navajo-nation-uranium-cleanup) for US EPA Region 9
<br clear="left"/>

## Professional Experience - Tetra Tech

My technical expertise in field instrumentation is well complimented by my background in data science, allowing me to provide complete analysis and visualization for varied studies. 

### Data Science and Statistics

I conduct analyses on environmental datasets that account for the limitations imposed by instrumentation and sampling methods. This frequently involves using different regression methods, hypothesis testing, and timeseries analyses to evaluate relationships between sources of data and characterize trends. Because the data I handle is often compared to permissible exposure limits for human and environmental heatlth, it is important to ensure that conservative estimates are calculated. This requires a complete understanding of measurement errors and how they propagate through different analyses. 

#### Project Highlight: Chicago Environmental Justice Index

<img src="docs\assests\images\ceji_structure.png" align="left" width="400px"/>

I am the lead statistical analyst of the Chicago Environmental Justice Index (CEJI), part of the larger Cumulative Impact Assessment being conducted by the Chicago Department of Public Health. The CEJI is a composite indicator model that assigns an Index score to each census tract in Chicago by aggregating the information in 28 indicators of environmental health. It was created to inform decisions made by policymakers who wish to enact equitable improvements to the city's environmental health. 

I was asked to calculate the Index, run a set of sensitivity analyses, and analyze its relationship to racial demographic data based on the methods published by the [CalEnviroScreen 4.0](https://oehha.ca.gov/calenviroscreen/report/calenviroscreen-40). However, the sensitivity analyses implemented by the CalEnviroScreen were limited to the analysis of the rankings in the top 10% of scores and did not have a robust analysis of how different indicators influenced the Index. When I pointed out these limitations, I was asked to perform a literature review of composite indicator methods and a more rigourous sensitivity analysis. 
<br clear="left"/>

The ensuing *Statistical Coherence Assessment* characterized the structure of the of the CEJI and the influence of individual indicators. The code used for this analysis was further developed into [`CompoisteIndicators.jl`](https://github.com/peterkannam/CompositeIndicators.jl?tab=readme-ov-file#compositeindicatorsjl).

### Emergency Responder - Air Monitoring and Telemetry Specialist

As a memeber of the *Superfund Technical Assessment and Response Team* I was specialist in quickly establishing effective air monitoring networks during environmental distasters. This involved the deployment and maintience of air monitoring instruments, using network specific devices to connect instruments to telemetry software, and using that software to push synced data to relevent servers. 

Telemety was primarily established using the [Viper](https://response.epa.gov/site/site_profile.aspx?site_id=5033) system developed by US EPA, and required the manipulation of insturment and computer network settings. Network connections through Viper use cell, wi-fi, and radio communication and synced using Precision Time Management protocols, meaning that through training and troubleshooting I developed a practical knowledge on how to establish and manipulate real time time data flows.

My experience is such that *Superfund Technical Assessment and Response Team* management asked me to design and run a training for all TetraTech responders on the contract.

#### Project Highlight: East Palistine Train Derailment 

<img src="docs\assests\images\air-monitoring-within-the-community-small.png" align="right" width="300px"/>

I helped establish and maintain the air monitoring network around the East Palistine Train Derailment.  Because of its size and longevity, this project taught me how to effectively scale air monitoring networks and many telemetry best practices that are not normally considered under emergency conditions. 

I was also in charge of computing daily air monitoring summaries tables for US EPA to distrubute, a process which I largely automated. An example can be found [here](https://www.epa.gov/system/files/documents/2023-06/Continuous%20Monitoring%20Summary%20Table_20230611_Community_508T.pdf), all of summary tables can be found [here](https://www.epa.gov/east-palestine-oh-train-derailment/air-monitoring-documents).
<br clear="left"/>

## Research Experience - *Earth History and Tectonics Laboratory Group*, Dartmouth College

For all four years of my Earth Sciences major at Dartmouth College, I was a member of the *Earth History and Tectonics Laboratory Group* under principle investigator Justin Strauss. This experience allowed me to gain expertise processing geochemical samples, develop my own geochemical dataset, and use that dataset to complete independent research and untimately a senior thesis. 

### Senior Thesis: **XXX**

My senior thesis focus on the use of a large geochemical dataset to evaulate the use of a geochemical proxy: sedimentary Hg concentrations as a proxy for regional volcanic emissions. An important step for the use of this proxy was to determine the host material of sedimentary Hg, so that normalized concentrations can be compared along at different points of the sedimentary section. My sophmore year was spent independenty running 762 geochemical samples from the road river group of yukon canada, a sedimentary section. By combining this information with previous geochemical assessment of the section, I was able to investigate the relationship between Hg concentrations and indicators of Hg's host phase in a complete sedimentary record from the XXX to the XXX. 



After establishing myself as a competant technion in the processing of diterital zircon geochonology samples, I was given my own sample set to process and measure for sedimentary Hg in my sophmore year. This sample set came from the Road River Group of Yukon, Canada and represented a strech of continous deposition from the xxx to the xxx. By adding sedimentary Hg to this aready well characterized dataset, the idea was that we could robustly measure the Hg of the road river group and the methods that researchers use Hg as a proxy for regional volcanism. 

Once a dataset was complied, I spent much of my junior and senior year analyzing the relationship between Hg concentrations and concentrations of analytes that are used to find the host phase of Hg, to decide how to best normalize  Hg concentrations to its host phase and therefore interperate Hg anomalies.

I immeadiately found that unlike other studies, the Road River Group did not have a distinct host phase of sedimentary host phase indicators, but this sedimentary section also descibes a much larger timespan that other sections found in Hg studies, because they are primarily focused on extintion events and linking them to volcanic emissions.

To account for the larger sample time span availible to me, I began to use time series analysis on geochemical dataset of the Road River Group. Specificially, I applied the typical tests used in the field, correlations and mulitple regression, to a moving window analysis. I futhermore used applied Dominance Analysis, a type of recursive regression that defines how much of the [variance] each predivtive variable explains. 

<img src="docs\assests\images\MovingDominance.png" width="800px"/>

This reserach lead to a senior thesis titled: *Changing Host Phases of Sedimentary Mercury in the Road River Group of Yukon, Cananda and Implications of its use as a geochemical proxy*. This was one of the first studies to identify a sedimentary section with a changing host phase of sedimentary Hg, it also characterized how

- Honors Thesis: *Changing Host Phases of Sedimentary Mercury in the Road River Group of Yukon, Cananda and Implications of its use as a geochemical proxy*
    - Advisor: Justin Strauss
- Member of the Struass Lab for four years
- Lab research assistant
- Field research assistant


## Education 

### Dartmouth College - Class of 2022
#### Major: Earth Sciences

#### Relevent Coursework
- 


### Baltimore City College High School - Class of 2017

## Research Interests

Interacting with government, community, and academic stakeholders in this way has helped me develop an interest in how studies can be desgined and communicated to conduct the best science that can satisfy different interests. 

how do we do the best science and how do we communicate it

