---
layout: default
title: Proposal
id: litvis

narrative-schemas:
  - ../narrative-schemas/proposal.yml
  
---

@import "../css/datavis.less"

# Coursework: Project Proposal

{(questions|}

- **Q1:** How can historical sensor data be used to identify variance in microclimates of urban gardens, to identify which gardens are suitable for which crops?
- **Q2:** Can sensor data be used to identify which topographical features have an impact on local growing conditions?

{|questions)}

{(datasources|}
Data will be provided by the project work of Sara Heitlinger & Connected Seeds as json files and stored/served locally to the litvis document. Data from 6 different sensors and 5 different garden plots in London is stored as seperate files and will need to be comined into a single table for the purpose of this coursework.
{|datasources)}

{(justification|}
In Agritech, crop efficiency is improved through realtime automated monitoring and control of environmental growing conditions. The benefits are increased plant health and productivity, and, by optimising processes such as watering and heating, these processes become more efficient and therefore more sustainable. Connected Seeds was set up to identify ways cheap, smart and accessible technology and IoT could be used to support more sustainable food growing practices for hobbyist gardeners in small urban plots. Sensors built using arduino hardware and commonly available materials monitored microclimate conditions such as light, air humidity, soil humidity, air temperautre, soil temperature and air pressure in 8 gardens over 2 months in 2016. At the end of the data collection period data was incorporated into an interactive web-based dashboard. While the technology itself was largely reliable, it is not clear if the way the data was reported actually helped gardeners to make better decisions about the care of their crops.
By answering question 1, I hope to start thinking about ways to classify gardens according to the types of crops that would compliment the climate, in order to produce crop plans that might reduce pests and disease and increase yield. I also hope to produce a collaborative crop planning document that could be used by the gardeneners in all 8 plots to support coordinated crop rotation, permaculture practices and biodiversity.
By answering question 2 I will look for correlations or variances in data that might be attributable to local features such as buildings, open water or parkland and could provide insight into ways to change the physical features of a garden to support certain species of crops, or to identify which crops would be most suited to a garden with a given set of features.
{|justification)}
