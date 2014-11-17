#Semantic README v1.0.0-alpha

## Summary

A project contains a README.md file containing the following synopsis.

1. Project Name
2. Description
3. Changelog
4. Protocols
5. Documentation
6. Support Channels

See our example [Example Readme](demo/README.md).

##Introduction

A well formatted synopsis should be meaningful and decisive. It is the pitch deck of your project while serving as a primary support channel for your user base. 

As part of my push for semantic projects inspired by [Tom Preston-Werner](http://tom.preston-werner.com/) and (SemVer), I propose this simple set of rules and requirements to structure how projects handle their README File.

##Semantic README Specification

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in RFC 2119.

1. A README MUST be located within the projects root folder and SHALL be formatted using markdown syntax.

2. A README MUST contain sections in the following orders. Name, description, change log, protocols, Documentation, and support channels.

4. A README MUST begin with a #[Project Name].

4. The README MUST include a description and SHOULD NOT exceed 3 Paragraphs.

5. Once a project version has been released, an entry MUST be added to the change log section. Indicated using the following format. 

[Major, Minor, Patch] | [vX.Y.Z](path/to/changelog/entry) | YYYY-MM-DD

6. A README MUST contain a protocol section listing and linking to project protocols. 

7. A README MUST include a link to the projects documentation.

8. A README MUST include all available support channels for the project.
