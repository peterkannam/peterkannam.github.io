# Peter Kannam 
<img src="docs\assests\images\peterkannam_headshot.png" align="right" width="200px"/>

Hello! I am a professional environmental geologist and data scientist working for TetraTech. The focus of my work has been aiding government officials in public health and regulatory decision making through the use of technical field instrumentation and by applying statistical best practices to environmental datasets. My CV can be found [here](https://peterkannam.github.io/docs/assests/Kannam_CV.pdf). 

I primarily support the following projects:    
- [Chicago Environmental Justice Index](#project-highlight-chicago-environmental-justice-index): a composite indicator model for the Chicago Department of Public Health that scores all the census tracts in Chicago using 28 indicators of environmental and social health
   - I developed the code I wrote for this project into [`CompoisteIndicators.jl`](https://github.com/peterkannam/CompositeIndicators.jl?tab=readme-ov-file#compositeindicatorsjl): a dynamic [`Julia`](https://julialang.org/) package for the computation and sensitivity analysis of composite indicator models that can be used by cities and groups undertaking similar efforts
- [Superfund Technical Assessment and Response Team](https://www.epa.gov/east-palestine-oh-train-derailment) for US EPA Region 5
- [Navajo Abandoned Uranium Mines; Response, Assessment, and Evaluation Services](https://www.epa.gov/navajo-nation-uranium-cleanup) for US EPA Region 9
<br clear="left"/>

## Professional Experience - Tetra Tech

My technical expertise in field instrumentation is well complimented by my background in data science, allowing me to provide complete analysis and visualization for varied studies. 

### Data Science and Statistics

I conduct analyses on environmental datasets that account for the limitations imposed by instrumentation and sampling methods. This frequently involves using different regression methods, hypothesis testing, and timeseries analyses to evaluate relationships between sources of data and characterize trends. Because the data I handle is often compared to permissible exposure limits for human and environmental health, it is important to ensure that conservative estimates are calculated. This requires a complete understanding of measurement errors and how they propagate through different methods. 

#### Project Highlight: Chicago Environmental Justice Index

<img src="docs\assests\images\ceji_structure.png" align="left" width="400px"/>

I am the lead statistical analyst of the Chicago Environmental Justice Index (CEJI), part of the larger [Cumulative Impact Assessment](https://www.chicago.gov/city/en/depts/cdph/supp_info/Environment/cumulative-impact-assessment.html) being conducted by the Chicago Department of Public Health. The CEJI is a composite indicator model that assigns an Index score to each census tract in Chicago by aggregating the information in 28 indicators of environmental health. It was created to inform decisions made by policymakers who wish to enact equitable improvements to the city's environmental health. 

I was tasked with calculating the Index, running a set of sensitivity analyses, and analyzing its relationship to racial demographic data based on the methods published by the [CalEnviroScreen 4.0](https://oehha.ca.gov/calenviroscreen/report/calenviroscreen-40). However, when I noted the limitations of the sensitivity analysis implemented by the CalEnviroScreen, I was asked to perform a literature review of composite indicator methods and a more rigorous sensitivity analysis.
<br clear="left"/>

The ensuing *Statistical Coherence Assessment* characterized the structure of the of the CEJI and the influence of individual indicators on final Index scores. The code used for this analysis was further developed into [`CompoisteIndicators.jl`](https://github.com/peterkannam/CompositeIndicators.jl?tab=readme-ov-file#compositeindicatorsjl).

### Emergency Responder - Air Monitoring and Telemetry Specialist

As a member of the *Superfund Technical Assessment and Response Team* I am a specialist in quickly establishing effective air monitoring networks during environmental disasters. This involves the deployment and maintenance of air monitoring instruments, using network specific devices to connect instruments to telemetry software, and using that software to push synced data to relevant servers. 

Telemetry is primarily established using the [Viper](https://response.epa.gov/site/site_profile.aspx?site_id=5033) system developed by US EPA, and requires the manipulation of instrument and computer network settings. Network connections through Viper use cell, wi-fi, and radio communication and synced using Precision Time Management protocols. Through training and troubleshooting I have developed a practical knowledge on how to establish and manipulate real time data flows.

My experience is such that *Superfund Technical Assessment and Response Team* management asked me to design and run a training for all TetraTech responders on the contract.

#### Project Highlight: East Palestine Train Derailment 

<img src="docs\assests\images\air-monitoring-within-the-community-small.png" align="right" width="300px"/>

I helped establish and maintain the air monitoring network around the East Palestine Train Derailment.  Because of its size and longevity, this project taught me how to effectively scale air monitoring networks and many telemetry best practices that are not normally considered under emergency conditions. 

I was also in charge of computing daily air monitoring summary tables for US EPA to distribute, a process which I largely automated. An example can be found [here](https://www.epa.gov/system/files/documents/2023-06/Continuous%20Monitoring%20Summary%20Table_20230611_Community_508T.pdf), and all of summary tables can be found [here](https://www.epa.gov/east-palestine-oh-train-derailment/air-monitoring-documents).
<br clear="left"/>

## Research Experience - *Earth History and Tectonics Laboratory Group*, Dartmouth College

For all four years of my Earth Sciences major at Dartmouth College, I was a member of the *Earth History and Tectonics Laboratory Group* under principle investigator Justin Strauss. This experience allowed me to gain exposure to all steps of the research process. While part of this lab group, I processed geochemical samples, used laboratory instrumentation to develop my own geochemical dataset, and analyzed that dataset to complete independent research and ultimately a senior thesis. 

### ***Changing Host Phases of Sedimentary Mercury in the Road River Group of Yukon, Canada***: Senior Thesis (2022) and GSA Connect Poster (2021)

My senior thesis focused on the analysis of a large sedimentary dataset to evaluate the use of a geochemical proxy: sedimentary Mercury (Hg) concentrations as a proxy for regional volcanic activity. The primary source of Hg to sediments is by volcanism, so anomalies in Hg concentrations across mass extinction boundaries have been used to conclude that there was regional volcanism during these events. 

An important step in identifying Hg anomalies is the identification of the host material of the Hg and then normalizing Hg concentrations by host material concentrations. I rigorously tested this step of the proxy using geochemical data from the Road River Group of Yukon, Canada which recorded continuous deep marine deposition from the late Cambrian to the early Devonian. 

Preliminary analysis of this dataset yielded inconclusive results on the host phase of Hg. To better compare my dataset representing ~100 million years to other sedimentary Hg studies, I implemented timeseries analysis methods in the form of moving window sampling. I also used methods that better characterize influence between variables than the correlations typically used by sedimentary Hg studies. The most useful tool was dominance analysis: a form of recursive multiple regression that calculates how much variance each predictor variable can explain of the response variable. 

The results from "moving dominance analysis" showed that the influence of host phase indicators varies greatly in the constant deposition environment of the Road River Group. This finding complicates the hypothesis of a simple deposition pathway for Hg which fundamental its use as a proxy for volcanism. Additionally, Hg concentrations were shown to be influenced by multiple host phase indicators simultaneously. As Hg normalization typically occurs by division by the single identified host material, this finding calls into question the methods used to identify Hg anomalies. Ultimately, this study showed that further work must be done to characterize the behavior of Hg in ancient sediments before concentrations can reliably be used as a proxy for regional volcanism. 

<img src="docs\assests\images\MovingDominance.png" width="1200px"/>

## Research Interests

I am interested in how climate and environmental science can inform public health decision making and community health awareness. While these goals are interrelated, different target audiences often value separate metrics and communication strategies. I think it is important to design studies that can meet the requirements of different audiences and spaces without sacrificing scientific integrity for simplicity. 

Specifically, I am interested in air quality and extreme heat modeling and how the quality of life described by these models is impacted by specific aspects of the urban environment. By focusing on issues at neighborhood or city block scales, I would like to investigate how climate action and urban improvement agendas can be complimentary so they can together hold greater influence in the decision making analysis of government officials. I believe that an effect and efficient use of limited resources is one of the keys to a resilient future. 

## Education

### Dartmouth College - Class of 2022
Major in the Earth Sciences

#### Relevent Major Coursework:
- Technical Computation in the Earth Sciences
- Contaminant Hydrogeology
- Marine Biogeochemical Cycling
- Sedimentology and Stratigraphy
- Topics in Historical Geobiology
- Igneous and Metamorphic Petrology
- Minerology

#### Other Relevant Coursework:
- Optimization Mathematics - Linear Programming 
- Linear Algebra
- Differential Equations
- Introductory Chemistry, Physics 

### Baltimore City College High School - Class of 2017