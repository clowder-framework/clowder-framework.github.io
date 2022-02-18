---
layout: page
title: GSOC Project Ideas
description: Google Summer of Code 2022 Project Ideas
background: '/PATH_TO_IMAGE'
---

# V2 Favorites
Implement favorites functionality in v2. Users can bookmark datasets and files and organize them in collection for easy access.

# v2 Search Capabilities
Clowder v1 uses Elasticsearch to drive search features, but there are shortcomings and some aspects that cause confusion. 
Help improve basic ES search features in v2 to leverage newer ES features and syntax and make for a good user experience. 
Support for faceted search would be great.

# New v2 Visualizations
Build upon the previewers of Clowder v1. Survey the popular frontend visualization tools and adopt suitable technologies 
for previewing files with a focus on Interactive Images. For example, implement the ability to zoom in/out on large images.

# UI/UX Improvements
Perform usability research of the v1 and v2. Interview users of Clowder from various domains and propose new UI designs to improve UX.

# Recommender System
Research on modern recommending system algorithms and create a prototype system that recommends similar datasets to the 
ones that the user is currently browsing. May leverage information such as user’s search history, datasets metadata, file names and file content.

# Federation
Given a set of trusted Clowder instances, develop trusted ways for users on one instance to see data on other instances. 
This could be done by clustering the ElasticSearch databases and redirecting users to the specific instance hosting the 
data where user’s credentials would be validated.

# v2 Mobile App
Adapt V2 React frontend to React Native and develop a mobile app focused on collecting data in the field and the lab 
using phones and upload them to a Clowder central instance.

