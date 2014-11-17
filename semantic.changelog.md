#Semantic CHANGELOG v1.0.0-alpha

## Summary

Given a version number MAJOR.MINOR.PATCH increment the CHANGELOG.md file.

1. Summary: [Major,Minor,Patch]|[vX.Y.Z]|[YYYY-MM-DD].
2. Section: A logical part of a project which contains line items.
3. line items: A labeled note identifying a change to the project. [Added, Deprecated, Removed, Fixed, Revised, Security]

See our example [Example Changelog](example/CHANGELOG.md).

##Introduction

It was the best of the times... it was the worst of times... Version control has brought sanity to project collaboration. Services such as Github and Bitbucket have brought it to the masses. New technology, methodologies, and powerful frameworks allow us to iterate through versions quickly.

Version control made sense of it all, a boon to project managers and developers everywhere. Now we're staging, crafting commits, branching and merging, pushing and pulling and thats good! But With the proliferation of version control our beloved change logs are becoming sporadic, almost non existent and thats bad.

A well formatted change log can bring light to an entire projects life cycle.

As part of my push for a semantic projects inspired by [Tom Preston-Werner](http://tom.preston-werner.com/) and (SemVer), I propose this simple set of rules and requirements to structure how projects handle change logs.

##Semantic Change Log Specification

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in RFC 2119.

1. A CHANGELOG.md file MUST be located within the projects root folder and SHALL be formatted using markdown syntax.

2. The Change log MUST begin with #[Project Name] Change Log.

3. Every change MUST be in chronological descending order and MUST provide a summary & line items.

4. A summary MUST flag whether the changes are Major, Minor, or a Patch.

5. The summary MUST take the form ###[Flag]|[vX.Y.Z]|[YYYY-MM-DD].

6. A change log SHOULD only provide sections if line items span multiple logical parts of a project. This is indicated by ####Section Name.

7. Line items are REQUIRED to use the following labels. `ADDED`, `DEPRECATED`, `REMOVED`, `FIXED`, or `REVISED`.

8. You SHOULD prepend a `SECURITY` label for security related updates.

9. Line items MUST start with a label and SHOULD NOT exceed 1 sentence.

10. Using Semantic Versioning is highly RECOMMENDED.
