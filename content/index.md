---
date: 2017-01-05T21:07:33+01:00
title: Introduction
type: index
weight: 0
---

## One line summary

A branching model, where a single branch called trunk* is where developers share code.
  
## Caveats

- Depending on the team size, and the rate of commits, very short lived feature branches may exist, allowing 
  code-review and build checking (CI) to happen before the commit lands in the trunk, for other devs to depend on.

- Depending on the intended release cadence, there may be release branches (cut from trunk on a just in time basis)
  that are 'hardened' before a release, or no release branches if the team is pushing commits to production faster
  than (say) once a day.

- Teams have to become adept with correlated practices like 'branch by abstraction', and depend on 'feature flags'
  to shape releases and facilitate 'concurrent development of consecutive releases'.

## History

Trunk Based Development isn't a new branching model. It has been a lesser known model since the mid-nineties. 
The largest of development organizations, like Google and Facebook practice it at scale.