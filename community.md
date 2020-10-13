---
layout: page
title: Community
description: How to join the community
background: '/PATH_TO_IMAGE'
---

### How to Contribute

There are many ways to get involved in the Clowder community. Below we have identified a few ways and pointers to get started. *The easiest way to get more information is to join us on [Slack][slack].* Before participating, please take a momente to [read our Code of Conduct](https://github.com/clowder-framework/clowder/blob/master/CODE_OF_CONDUCT.md).

Depending on your brackground and skill set there are many ways in which you can contribute the Clowder framework. 

- If you are a **software engineer**:
    + You can help scientists and researchers by wrapping their code into new [extractors](#extractors), [visualizations](#visualizations), or create special purpose [clients](#clients)
    + You can contribute to the Clowder core infrastructure
- If you are **scientist** or **researcher**:
    + You can share your code and [ask for help][slack] to embed it as a Clowder extractor or tool
    + You can share the challenges your community encounters when dealing with data so that we can try to make Clowder better support your community
- If you are **data scientist**:
    + You can develop new [extractors](#extractors)
    + You can develop new [visualizations](#visualizations)
- If you are a **technical writer**:
    + You can help us improve existing [documentation](https://clowder-framework.readthedocs.io/en/latest/)
- If you are a **designer**:
    + You can help us improve the UI and UX of the Clowder web frontend or Clowder mobile app
- If you are a **student** in any of the above areas:
    + Please join [Slack][slack] and ask how you can help. You  will be assigned a mentor that will support you. They will help you find a good match between your skills and potential areas to contribute to.
    + If you are a software developer take a look at the [good first issues](https://github.com/clowder-framework/clowder/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) in GitHub


Ready to dive in? Following is more specific information on how to contribute to specific aspects of the framework. 

#### Contributing to the Core
To contribute to the inner workings of the frameworks, a basic familiarity with the framework and the technologies used is required. The type of technical knowledge required varies greatly depending on what aspect of the system you want to modify. It is always a good idea to ask in [Slack][slack] for pointers and make sure the proposed changes are inline with current practices and future developments.
- Read our [contribuiting document](https://github.com/clowder-framework/clowder/blob/master/CONTRIBUTING.md)
- Propose improvements on the [wiki](https://opensource.ncsa.illinois.edu/confluence/display/CATS/Proposals+for+New+Features) or in [GitHub](https://github.com/clowder-framework/clowder/issues)
- Make sure you have a basic understanding of
   + the overall [architecture](https://clowder-framework.readthedocs.io/en/latest/develop/architecture.html)
   + web app development (MVC, HTML, HTTP, Javascript)
   + the [Scala programming language](https://www.scala-lang.org/)
   + [MongoDB](https://www.mongodb.com/) if you will be modifying what is stored in the database
   + If you will be working with the extraction bus, basic knowledge of [RabbitMQ](https://www.rabbitmq.com/) is required
   + For text search functionality, we use [ElasticSearch](https://www.elastic.co/elasticsearch/)

#### <a name="extractors"></a> Creating New Extractors
Existing analytics code can be wrapped into a Clowder extractor using basic [Python](https://www.python.org/).
- [Step by step guide](https://opensource.ncsa.illinois.edu/confluence/display/CATS/Writing+an+Extractor+Using+Simple+Extractor+Wrapper)
- [Webinar 1](https://www.youtube.com/watch?v=9MGtNzYOhc8), [Webinar 2](https://www.youtube.com/watch?v=BHTbCd8r-2o)

#### <a name="visualizations"></a> Creating New Visualizations
Dataset and file visualizations can be created using plain Javascript.
- [Webinar](https://www.youtube.com/watch?v=iqJDudIx5X0)

#### <a name="clients"></a> Creating New Clients
Thanks to an extensive web API, special purpose clients can be created in any programming language or framework.
- [API documentation](https://clowderframework.org/swagger/?url=https://clowder.ncsa.illinois.edu/clowder/swagger)
- Example clients: [phone app](https://github.com/clowder-framework/clowder_mobile_app), [bootstrap client](https://opensource.ncsa.illinois.edu/bitbucket/projects/CATS/repos/clowder-bootstrap/browse)

[slack]: https://join.slack.com/t/clowder-software/shared_invite/enQtMzQzOTg0Nzk3OTUzLTYwZDlkZDI0NGI4YmI0ZjE5MTZiYmZhZTIyNWE1YzM0NWMwMzIxODNhZTA1Y2E3MTQzOTg1YThiNzkwOWQwYWE