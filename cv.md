---
layout: page
title: Curriculum Vitae
permalink: /cv/
---
## Overview
Hi there! I am a recent graduate from McMaster University with an interest in applied mathematics. Starting out as a chemist, my curiousity in modeling inorganic energy levels lead me to my discovery of complex networks. Over the course of the past year I have dipped my toes into data analytics and I am planning to continue on my data science journey.


## Educational Background
{% include cv-item.html
   title="Honours Bachelor of Integrated Science"
   date="2014 – 2019"
   location="McMaster University | Hamilton, ON"
   content="
   Summa Cum Laude
   Last three years GPA: 3.9, CGPA: 3.7 on a 4-point scale
"%}

## Research Experience
{% include cv-item.html
    title="Modelling Opinion Dynamics in Complex Networks"
    date="September – April 2019"
    content="
Completed a full-year undergraduate thesis under the supervision of Dr. George Dragomir in the Department of Mathematics $\&$ Statistics at McMaster University. The project focused on designing a complex network for which to host opinion dynamics. First, traditional models for opinion dynamics were adapted to better reflect memory and magnitude of opinions, and influence of different friendships. Next, I implemented a hyperbolic geometry in order to construct a complex network that emulated a social network structure. In this social network, I conducted opinion dynamics simulations given various initial conditions. The project was primarily completed using MATLAB, although some analysis was done in R.
" %}

{% include cv-item.html
    title="Reaction-Path Finding in Computational Chemistry"
    date="September – April 2019"
    content="
Completed a four-month research project under the supervision of Dr. Paul Ayers in the Department of Chemistry $\&$ Chemical Biology at McMaster University. The project focused on exploring the potential energy surface by characterizing and computing optimized chemical structures and using them to construct the reaction path. Five different families of reactions were studied and compared using the computational chemistry software package Gaussian. Using the data accumulated, reaction paths were normalized and fit to a quartic polynomial in Python to produce the final reaction pathway.
" %}

{% include cv-item.html
    title="Independent Project"
    date="January – April 2017"
    content="
Completed work on organic synthesis research with my project consultant Dr. Alex Adronov in the Chemistry Department, under the supervision of a graduate student. I performed a 4-step synthesis of an azide containing pillar[5]arene conjugate, and this conjugate then underwent strain-promoted alkyne-azide cycloaddition (SPAAC) with a bibenzocyclooctyne (DIBO) containing polyimine polymer. The pillar clicked polymer was suspended onto carbon nanotubes to create a network that integrated the sensing abilities of pillararenes through host-guest chemistry, as well as the signalling abilities of carbon nanotubes through resistivity measurements. This proof-of-concept study will lead to more selective, portable, and robust chemical sensors.
" %}

## Presentations

# Modelling Opinion Dynamics in Complex Networks
Little blurb here
<details>
  <summary>Abstract</summary>

   Opinion dynamics is the study of how groups of people in a society interact with one another and influence each other's opinions regarding some matter at hand. Applications of such models include marketing strategies and projecting political decisions. The classical approach to modelling these systems is using an agent-based system derived from statistical mechanics and updating opinions over repeated iterations. The current popular models for opinion dynamics are discrete in nature such that they only consider two possible opinions for each agent, and agents influence each other if they are close enough in proximity. However, continuous opinions are necessary to attribute to individuals a memory of past opinions. Incorporating these continuous aspects results in the continuous opinion discrete analysis function for updating opinions used in this thesis. Modelling a binary society is of great value because most important decisions come down to two choices -- whether it be the political party to lead, or the acceptance or dismissal of a consumer product. The traditional location based opinion models, however, are not an accurate representation of modern-day communication styles. With social media, our friends do not have to be our geographical neighbours. The result is a complex network of individuals and their influential relationships in a space where similarity among nodes is encoded as a hyperbolic distance measure. Throughout this thesis a novel tool is created for marrying the well-defined mathematical theory behind social network structure with classical opinion dynamics. This tool is proven to accurately retain the topological properties of social networks that give rise to their structure. Such a tool is very promising in understanding and forecasting how opinions formulate and change over time within a social network.
</details>

# Exploring the Driving Forces of Chemical Reactions in Order to Predict Mechanisms and Rates from First Principles
Little blurb here
<details>
  <summary>Abstract</summary>

  For a long time, chemists have predicted the interactions between molecules based on their similarity to other, well understood structures. Being able to identify a suitable synthetic pathway based on chemical properties and interactions takes a certain level of expertise and years of experience. It is now possible to assist chemists in this process using models and machine learning techniques. This entails constructing a training set of molecules and reaction paths with information about bond order, electron affinity, ionization energy, and more for each individual pathway so that correlations are possible. This project explores the driving forces for chemical reactions, with emphasis on how electrons rearrange during the process of reaction. Focus is put on aromatic substitution reactions, trying to gain detailed insights into the Hammett parameters, and to model the reactions associated thereto. Throughout this project an exisiting transition state optimization algorithm is utilized which uses redundant internal coordinates to accurately predict the optimized transition structure. This method identifies key chemical coordinates between the reactants and product in order to make a prediction, such as those associated with bond-breaking and bond-forming during the reaction. This optimized transition structure is used in Gaussian 09 to compute IRCs of the entire reaction pathway, and then manipulated in python to gain more information about various geometries along the way. Longterm applications include being able to predict reaction mechanisms and rates from first principles without a detailed modelling of the entire reaction path.
</details>

# Synthesis of a Pillar[5]arene Derivative to Create a Chemical Sensor
Little blurb here
<details>
  <summary>Abstract</summary>

   From disease diagnostics to roadside measurement of impairment, there is a need for portable, affordable, and robust chemical sensors. The conducting nature of single-walled carbon nanotubes (SWNTs) has recently gained much attention for applications in sensors. Any signal generated from the chemical sensor can be recorded between two gold electrodes. The use of “click chemistry” allows us to produce receptor-functionalized SWNTs that can be made selective. This is achieved through strain-promoted alkyne-azide cycloaddition (SPAAC) of a pillar[5]arene derivative. Conjugated polymers interact strongly with SWNTs, allowing us to readily install chemiresistive sensors that respond to binding events with electron deficient guest molecules such as 1,6-dicyanohexane via host-guest chemistry with the pillar[5]arene. The pillar[5]arene is synthesized through a condensation reaction of 1,4-diethoxybenzene with paraformaldehyde, catalyzed by the Lewis acid boron trifluoride diethyl etherate. This is followed by removal of a single ethyl group using boron tribromide, liberating a hydroxyl-functionalized pillar[5]arene. This structure is then alkylated with 1,6-dibromohexane, and the remaining terminal bromide is substituted with sodium azide. This azide containing pillararene derivative will then be introduced to a dibenzocyclooctyne (DIBO)-containing polyinime to click together via SPAAC. This polyimine undergoes efficient assembly onto the surface of SWNTs through supramolecular interactions, creating a connection between the pillararene derivative and the carbon nanotubes. If the binding affinity of the host-guest chemistry is not degraded by structural modifications to the pillar[5]arene, proof-of-concept studies will be undertaken to show that interactions of SWNT-bound pillar[5]arenes with 1,6-dicyanohexane will lead to changes in thin-film conductivity of this material.
</details>

## Awards and Distinctions

{% include cv-item.html
    title="McMaster Deans’ Honour List"
    date="2014 – 2019"
    content="
This standing is based on a minimum 9.5 average on at least 30 units of assessed courses
" %}

{% include cv-item.html
    title="McMaster President’s Entrance Award"
    date="2014"
    content="
Awarded $2500 for a final admission average to program of above 95%
" %}

{% include cv-item.html
    title="Holy Cross Catholic Secondary School Governor General’s Award"
    date="2014"
    content="
Awarded for having the highest average in the graduating class
" %}

## Work Experience
{% include cv-item.html
    title="Data Analytics Intern at Setter"
    date="September – December 2019"
    location="Toronto, ON"
    content="
Developed a model and performed analysis in R that clustered clientele performance with other factors to forcast future performance. Cleaned, analyzed, and structured raw data with SQL and R to create visualizations and dashboards to help inform strategic business decisions. Developed an ETL data pipeline template to track monthly/seasonal trends and week-to-week performance for the companies product metrics.
" %}

{% include cv-item.html
    title="Demand Engineering Intern at Setter"
    date="May – August 2019"
    location="Toronto, ON"
    content="
Focused on high-scale growth initiatives, beginning with multi-tenanting. Within six weeks our team was generating 32% of new business. In 4 months, the channels our team imagined, implemented, and automated were generating 70% of new clients and 25% of total GMV.
" %}

{% include cv-item.html
    title="Tutor at McMaster Science Society"
    date="2017 – 2019"
    location="McMaster University | Hamilton, ON"
    content="
I was provided with professional training on tutoring and leadership, and over the course of three years I tutored over 20 students in a variety of first and second year courses at McMaster University in both one-on-one settings and group settings. My main focus was on introductory science courses such as first year chemistry and calculus.
" %}

{% include cv-item.html
    title="Research Assistant at McMaster University"
    date="May – August 2018"
    location="McMaster University | Hamilton, ON"
    content="
For the summer of 2018, I was hired as a laboratory research assistant with Dr. Michael Brook in the Department of Chemistry & Chemical Biology at McMaster University. The primary goal of my work was lab work -- I was completing organic synthesis with silicones. However, this position also required me to build communication and teamwork skills, as I was working on a project with graduate students.
" %}

## Volunteer Experience
{% include cv-item.html
    title="McMaster Model United Nations"
    date="February 2019"
    location="McMaster University | Hamilton, ON"
    content="
MACMUN is a four day annual Model United Nations conference organized by students at McMaster University. Over the course of the weekend I participated in professional debate, presentations, and networking. I represented the delegate of Canada in the League of Nations, working with my committee to discuss and reach a resolution regarding the Anschluss.
" %}

{% include cv-item.html
    title="TedxMcMasterU Salon Leader"
    date="October 2017"
    location="McMaster University | Hamilton, ON"
    content="
I was one of the five chosen leaders for a Socratic style salon held at McMaster University. I led a group of five delegates on a discussion surrounding the topic \"The Way We Think\". I was trained on how to lead a successful group discussion, and had the opportunity to design the questions that I would ask to my delegates in order to spark discussion.
" %}

{% include cv-item.html
    title="Mac Bread Bin Events Coordinator"
    date="2016 – 2017"
    location="McMaster University | Hamilton, ON"
    content="
A McMaster Students Union service dedicated to addressing food insecurity and building stronger food systems in the McMaster and Hamilton community. My role was to plan and coordinate events, as well as to help promote the events and service.
" %}

{% include cv-item.html
    title="Synthesis Abstract Review Committee"
    date="March 2016"
    location="McMaster University | Hamilton, ON"
    content="
A committee that is assembled in order to assess and choose the student projects that will be presented at the annual Synthesis Symposium at McMaster University. I reviewed submitted abstracts that pertained to my major in Chemistry as I am knowledgeable in this field. I provided feedback and a quality level for the pieces of work submitted to aid in determining if the author would go on to present at the symposium.
" %}

{% include cv-item.html
    title="Synthesis Communications Committee"
    date="January – April 2016"
    location="McMaster University | Hamilton, ON"
    content="
A committee that is assembled in order to manage the communication required to plan and prepare for the annual Synthesis Symposium at McMaster University. I chaired the \"promotions\" subcommittee. I helped design and release logos, posters, and videos to promote the Symposium. I also recruited and managed eight people to help with the promotions process.
" %}

{% include cv-item.html
    title="Mac Peers"
    date="2015 – 2016"
    location="McMaster University | Hamilton, ON"
    content="
A cross-faculty peer mentorship program of the Student Wellness Centre. I helped younger and/or struggling students flourish at McMaster through one-on-one interactions.
" %}

{% include cv-item.html
    title="Grahn Lab"
    date="Summer 2015"
    location="Western University | London, ON"
    content="
I was a volunteer for the Grahn Lab at the Brain and Mind Institute. I aided in recruiting participants for music and rhythm studies; I also ran the music and rhythm experiments with participants and collected data. I booked relevant rooms to run experiments in, and set the equipment up.
" %}

## Programming Skills
{% include cv-item.html
    title="Programming Languages"
    content="
Python | R | SQL
" %}

{% include cv-item.html
    title="Markup Languages"
    content="
LaTeX
" %}

{% include cv-item.html
    title="Math Tools"
    content="
    Maple | MATLAB
" %}

{% include cv-item.html
    title="Buisiness Intelligence Tools"
    content="
Google BigQuery | Looker
" %}
