# Peter Kannam 
<img src="docs\assests\images\peterkannam_headshot.png" align="right" width="200px"/>

Hello! I am a professional environmental geologist and data scientist working for TetraTech. The focus of my work has been aiding government officals in public health and regulatory decision making through the use of technical field instrumentation and by applying statistical best practices to environmental datasets. My CV can be found [here](https://peterkannam.github.io/docs/assests/Kannam_CV.pdf). 

I primarily support the following projects:    
- [Chicago Environmental Justice Index](#project-highlight-chicago-environmental-justice-index): a composite indicator model for the Chicago Department of Public Health that scores all the census tracts in Chicago using 28 indicators of environmental and social health
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

For all four years of my Earth Sciences major at Dartmouth College, I was a member of the *Earth History and Tectonics Laboratory Group* under principle investigator Justin Strauss. This experience allowed me to gain exposure to all steps of the research process. While part of this lab group I processed geochemical samples, used labratory instrumentation to develop my own geochemical dataset, and analyzed that dataset to complete independent research and ultimately a senior thesis. 

### ***Changing Host Phases of Sedimentary Mercury in the Road River Group of Yukon, Canada***: Senior Thesis (2022) and GSA Connect Poster (2021)

My senior thesis focused on the analysis of a large sedimentary dataset to evaluate the use of a geochemical proxy: sedimentary Mercury (Hg) concentrations as a proxy for regional volcanic activity. The primary source of Hg to sediments is by volcanism, so anomalies in Hg concentrations across mass extinction boundaries have been used to conclude that there was regional volcanism during these events. 

An important step in indentifing these anomalies is the identification of the host material of the Hg and then normalizing Hg concentraions by the concentrations of the host material. I rigoruously tested this step using geochemical data from the Road River Group of Yukon, Canada which recorded continuous deposition from the xxx to the xxx. 

Preliminary analysis of this dataset yielded inconclusive results on the host phase of Hg. To account for the xxx million years my dataset represented, I implimented timeseries analyis methods in the form of monving window sampling to create results that could be compared to other studies. I additionally implimented tools that better characterize the influence between variables than the correlations typically used by sedimentary Hg studies. The most useful tool was dominance analysis: a form of recursive multiple regression that calculates how much variance each predictor variable can explain of the response variable. 

The results from "Moving dominance analysis" proved that the influence of host phase indicators on Hg concentrations are varible and shared amoung the host phase indicators. These conclusions called the assumptions of a single host phase and simple normalization techniques used by sedimentary Hg studies into question.

<img src="docs\assests\images\MovingDominance.png" width="1200px"/>

## Research Interests

I am interested in how climate and environmental science can inform public health decison making and community health awareness. While these goals are interrelated, different target audiences often value seperate metrics and communication strategies. I think it is important to design studies that can meet the requirements of different audiences and spaces without sacrificing scientific integrety for simplicity. 

Specifically, I am interested in air quality and extreme heat modeling and how the quality of life described by these models is impacted by specific aspects of the urban environment. By focusing on issues at neighboorhood or city block scalesI would like to investigate how climate action and urban improvement agendas can be complimentary so they can together hold greater influence in the decision making analysis of government officials. Effective and efficent use of limited resources for a resilent future.  

## Education

### Dartmouth College - Class of 2022
Major in the Earth Sciences

#### Relevent Major Coursework:
- Technical Computation in the Earth Sciences
- Topics in historical geobiology
- Minerology
- Contaminant Hydrogeology
- Igneous and metamorphic geology
- Sedimentology and Stratigraphy
- Marine Biogeochemical Cycling

#### Relevent Coursework:
- Optimization Mathematics - Linear Programming 
- Linear Algebra
- Differential Equations
- Introductory Chemistry, Physics 
### Balitmore City College High School - Class of 2017




