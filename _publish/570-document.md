---
title: "Documenting Data and APIs"
permalink: /publish/document/
excerpt: "Documenting Data and APIs"
last_modified_at: 2018-05-07T13:30:00 +01:00
redirect_from:
  - /theme-setup/
toc: true
---

The documentation provided with open data and APIs is important both to developers that try to understand how to use your data, and to innovators who take the decision on whether your data can be used at all.

Good documentation of data is also important for internal use of data within your own organisation.


## Challenges

Both for innovators and developers, it is important to quickly be able to determine whether the data and API is useable for their purpose. 


## Suggestions

- Provide a brief overview that explains what the data is and is not.
- Help innovators and developers to quickly determine whether your data is useable for them, so keep an intoductory part short and to the point.
- Remember that your reader may not be an expert in the domain of the data, so include enough context to make it understandable.
- Provide examples showing data content and data structures
- Provide examples showing how the APIs work
- Support testing of APIs

### OpenAPI

For documenting APIs, [OpenAPI](https://www.openapis.org) provides a  can be useful. 
As described at, the specification *"defines a standard, programming language-agnostic interface description for REST APIs, which allows both humans and computers to discover and understand the capabilities of a service without requiring access to source code, additional documentation, or inspection of network traffic."* [^1] 


OpenAPI descriptions can be created in different ways, e.g. by writing a YAML-based specification by hand or by using tools that extract the specification from annotated source code (tools exist for Java, JavaScript, Scala, .NET-based, and more). Read more about some of the options e.g. at [this blog post at swagger.io](https://swagger.io/blog/why-you-should-create-an-api-definition/). 

### Tools

At [swagger.io](https://swagger.io) you will also find links to both open source and commercial tools for documenting with OpenAPI and for using OpenAPI descriptions as part of your development projects.

One of the swagger tools is the swagger-ui which can present an interactive web-based documentation for your API based on an OpenAPI description file. This tool can also be embedded in other tools - for instance, there is an [open source extension](https://github.com/bcgov/ckanext-openapiviewer) that allows embedding it in CKAN, allowing you to present the OpenAPI description as part of the description of your dataset.

## References and further reading 

[^1]: The OpenAPI specification. [https://github.com/OAI/OpenAPI-Specification](https://github.com/OAI/OpenAPI-Specification).
