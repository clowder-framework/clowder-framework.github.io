---
layout: page
title: FAQ
description: Frequently asked questions
background: '/PATH_TO_IMAGE'
---


- ***What is the easiest way to get Clowder up and running on my machine/cluster?***
    + Docker compose can be used for most instance, both for production as well as for developers to test the software on their machines. Please see the [README](https://github.com/clowder-framework/clowder) for instructions to get started.
- ***The GitHub repository doesn't seem very active?***
    + We are in the process of moving main development activities to <a href="https://github.com/clowder-framework">GitHub</a>. Historically we have been using a <a href="https://opensource.ncsa.illinois.edu/bitbucket/projects/CATS">local instance of the Atlassian suite</a>. Much of the development can be followed there. If you want to see active PRs you will have to <a href="https://identity.ncsa.illinois.edu/login">signup here</a>.
- ***What is the easiest way to develop a new information extractor?***
    + The <a href="https://opensource.ncsa.illinois.edu/confluence/display/CATS/Writing+an+Extractor+Using+Simple+Extractor+Wrapper">Simple Python Extractor</a> is the simplest way to create a new extractor. It works for cases where you want to extract structured metadata or a preview from a single file. For more complex examples you can try creating an extractor using the more involved <a href="https://opensource.ncsa.illinois.edu/bitbucket/projects/CATS/repos/pyclowder/browse">pyClowder extractor</a>. For advanced users, extractors can be written in any language, the only requirements are a RabbitMQ driver and the ability to call HTTP endpoints and parse JSON.
