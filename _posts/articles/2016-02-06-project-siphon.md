---
layout: article
title: "Project Siphon: Public Safety and Crime Incident Detection from Social Media"
categories: articles
modified: 2016-07-11T16:28:11-04:00
tags: [2016]
comments: false
ads: false
---


### Project Information

* **Organisation**: CSIR Modelling and Digital Science
* **Students**: LeeAnne Masilela, Yanga Sisilana, Gary Bezuidenhout and Nkosinathi Ndlovu
* **Project Leads**: Dr. Vukosi Marivate, Ms. Nyalleng Moorosi

### Project Description

With reports of high rates of unreported crimes in South Africa, there is a need for additional information beyond official crime statistics that are made available to the general public annually. South Africa is reported to have one of the highest crime rates in the world and as such, crime has become the most difficult challenge faced by the South African population on a daily basis. At the same time South Africa, though a developing country, is in the unique position of having a highly active social media presence with approximately 22% of the population having active social media accounts. Notably, social media platforms have enabled the sharing of incident information such as car accidents, car theft and missing persons. In this project, we developed a framework that employs social media (twitter and Facebook) content to identify public safety incidents to assist in gathering insights to either add to law enforcement cache of tools for a better understanding of where to deliver protective services or to provide point data for crime detection on a daily basis.

We used machine learning and natural language processing techniques to extract crime related information from Twitter and Facebook to create visualizations for the ease of interpretation of crime data. Data was largely collected from law enforcement community forums and users that frequently post about crimes through the use of keywords related to crime from a twitter and Facebook streaming API. Due to the fact that we were working with a large dataset, the Apache Hadoop software library framework was used for the implementation of our programming models to allow for the distributed processing the data across clusters of computers to ensure speed. A lexical normalization dictionary and a natural language processing toolkit platform for python were used to normalize the text received from the two social media platforms and remove URL’s, abbreviations and special characters. To ensure ease of interpretation of the clean text, a multi-view approach was employed to visualize the data which consists of an incident map, a heat map, and weekly / daily graphical analytics on crimes in South Africa as reported on social media. A JavaScript leaflet library was used to create the map visualizations, in which geocoordinates from addresses posted in the text were obtained using an open street map database. For the weekly / daily graphical analytics, a crossfilter JavaScript library was used. Future work involves the application of machine learning techniques for language processing as well as incident verification.

### Student's remarks:

The DSIDE internship programme has been the most rewarding academic experience for us. We continue to apply the analytical as well as project management skills and work ethic that our amazing mentors instilled in us in our various fields. We hope many more students can have the opportunity to experience this.

### Papers

* Extracting South African safety and security incident patterns from social media, 2015, *Vukosi Marivate*
* Privacy In Mining Crime Data From Social Media: A South African Perspective, 2015, *Nyalleng Moorosi and Vukosi Marivate*

**Author:** LeeAnne Masilela, MSc Epidemiology, Wits University.
