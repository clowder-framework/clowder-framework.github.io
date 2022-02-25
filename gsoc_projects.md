---
layout: page
title: GSOC Project Ideas
description: Google Summer of Code 2022 Project Ideas. Project ideas should focus on Clowder v2, currently in development. Below are a few ideas, but we are very open to other ideas, including taking any of the features available in v1, improving on them and implementing them in v2.
background: '/PATH_TO_IMAGE'
---

# v2 Favorites
Implement favorites functionality in v2. In v1 users can follow datasets, files, users and spaces. These resources are 
then listed under their dashboard and events on any of these resources are reported on the activity feed. At a minimum, 
implement the ability v2 for users to bookmark datasets and files. If possible also include the ability to be notified 
of updates from resources being followed. Potentially include the ability to organize bookmarks  in a collection for 
easy organization.

*Requirements:* React, Python, MongoDB

*Deliverables:* New fronted widgets and API endpoints

*Possible mentors:* Chen Wang

*Expected size of project:*  175 hours

*Difficulty:* Easy


# v2 Search Capabilities
Clowder v1 uses Elasticsearch to drive search features, but there are shortcomings and some aspects that cause confusion. 
For example the permissions are not embedded in the index and queries require post processing on the web app for proper 
filtering. Help improve basic ES search features in v2 to leverage newer ES features and syntax and make for a good user 
experience. Introduce new features such as faceted search.


*Requirements:* ElasticSearch, Python, React

*Deliverables:* New API endpoints and ElasticSearch schema

*Possible mentors:* Max Burnette

*Expected size of project:*  350 hours

*Difficulty:* Medium


# New v2 Visualizations
Build brand new data visualization specific to file types and use cases inspired by v1 previewers v1. Survey the popular 
frontend visualization tools and adopt suitable technologies for previewing files with a focus on Interactive Images. 
For example, implement the ability to zoom in/out on large images. Or implement simple line graphs and time series 
graphs for CSV files.

*Requirements:* React and relevant Javascript libraries, Python

*Deliverables:* New React components and supporting API endpoints

*Possible mentors:* Chen Wang, Rob Kooper

*Expected size of project:*  175 hours

*Difficulty:* Medium


# UI/UX Improvements
Perform usability research of  both v1 and v2. Interview users of Clowder from various domains and propose new UI designs 
to improve UX. Discuss your findings with the developers. Propose brand new features fitting the scientific communities 
Clowder supports.

*Requirements:* UI/UX experience

*Deliverables:* UI designs

*Possible mentors:* Chen Wang, Luigi Marini

*Expected size of project:*  175 hours

*Difficulty:* Medium



# Recommender System
Research modern recommending system algorithms and create a prototype system that recommends similar datasets and files 
to the ones that the user is currently browsing. May leverage information such as user’s search history, dataset metadata, 
file names and file content. The specific type of recommender system and the data used to train the model is left to the 
developer to decide.

*Requirements:* Python, MongoDB

*Deliverables:* Python scripts to analyze MongoDB schema and make recommendations

*Possible mentors:* Chen Wang, Luigi Marini

*Expected size of project:*  350 hours

*Difficulty:* Hard



# Federation
Clowder instances can be small and institution specific. Given a set of trusted Clowder instances, develop trusted ways 
for users on one instance to see data on other instances. This could be done by clustering the ElasticSearch databases 
and redirecting users to the specific instance hosting the data where user’s credentials would be validated. Or could 
use a special purpose protocol that creates copies of the data and metadata between instances.

*Requirements:* Python, ElasticSearch

*Deliverables:* Design and basic Python implementation

*Possible mentors:* Rob Kooper, Luigi Marini

*Expected size of project:*  350 hours

*Difficulty:* Hard



# v2 Mobile App
Adapt the v2 React frontend to React Native and develop a mobile app focused on collecting data in the field and the lab 
using phones and uploading them to a Clowder central instance. The app would focus on video and pictures, but support of 
other types of sensor feeds or input forms could be included. For example a simple field notebook interface to store logs 
of activities from the field.

*Requirements:* React, React Native

*Deliverables:* React Native application

*Possible mentors:* Chen Wang, Luigi Marini

*Expected size of project:*  350 hours

*Difficulty:* Medium

