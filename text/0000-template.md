- Start Date: 2019-02-24
- Relevant Team(s): Ember CLI, Steering
- RFC PR: (after opening the RFC PR, update this with a link to it and update the file name)
- Tracking: (leave this empty)

# Deprecate/Replace Travis CI as default CI in new Ember projects 

## Summary

Current new Ember projects generated via the Ember CLI are supplied with a
[default travis.yml continuous integration configuration](https://github.com/ember-cli/ember-new-output/blob/master/.travis.yml).
This means that Ember, an open source and free project, is advocating, probably unintentionally, a commercial solution that is one of many.
This RFC proposes replacing or removing the default file from the blueprint or allowing a configuration during `ember init` time.

## Motivation

> Why are we doing this? What are the problems with the deprecated feature?
What is the replacement functionality?

## Transition Path

> This is the bulk of the RFC. Explain the use-cases that deprecated functionality
covers, and for each use-case, describe the transition path.
Describe it in enough detail for someone who uses the deprecated functionality
to understand, for someone to write the deprecation guide, and for someone
familiar with the implementation to implement.

## How We Teach This

> Would the acceptance of this proposal mean the Ember guides must be
re-organized or altered? Does it change how Ember is taught to new users
at any level?
Does it mean we need to put effort into highlighting the replacement
functionality more? What should we do about documentation, in the guides
related to this feature?  
How should this deprecation be introduced and explained to existing Ember
users?

## Drawbacks

> Why should we *not* do this? Please consider the impact on teaching Ember,
on the integration of this feature with other existing and planned features,
on the impact of the API churn on existing apps, etc.
There are tradeoffs to choosing any path, please attempt to identify them here.

## Alternatives

> What other designs have been considered? What is the impact of not doing this?

## Unresolved questions

> Optional, but suggested for first drafts. What parts of the design are still
TBD?
