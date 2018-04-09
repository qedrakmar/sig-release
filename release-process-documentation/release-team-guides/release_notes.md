This is a first pass at documenting the release notes process.

# Release Notes Lead Playbook

Consistency is important.  Timing is important.  It is far too easy to leave all the release notes work until after the release candidate has been cut, forcing all release notes work to happen during the last week of the release.

## Overview

The primary purpose of Release Notes is to convey specifically which changes in a release are User-facing.

## Authority

The release notes team has authority to gather all information from the kubernetes repo, but does not have any authority to change any information within a Pull Request, nor do they have autority to fundamentally change the information being given to them.  They are expected to clarify information gramatically and presentation-wise, as well as gather supporting documentation, if needed.

## Skills Needed

The skills needed to perform this role primarily involve the ability to keep information consistent through a large editing process.  Some understanding of github is recommended, primarily around [pull requests](https://help.github.com/articles/about-pull-requests/) and [branch management](https://help.github.com/articles/managing-branches-in-your-repository/).  Some understanding of the [Github Search API](https://developer.github.com/v3/search/) would also be beneficial.

## Duties

### Subroles
The release notes team functionality consists of three separate components.  
* First, there is the gathering of the information, which is ideally performed with the [relnotes tool](https://github.com/kubernetes/release/tree/master/toolbox/relnotes).
* Second is the editing of the gathered information.  This includes first pass qualification of whether a particular note is actually user-facing or not, as well as final grammatical editing and topical sorting.
* Third is the interpersonal aspect of tracking down contributors whose notes need additional clarification or information.  This is performed by pestering individuals by slack, email, at SIG meetings, or any other way you can get in contact with them.

## Timeframe

#### During the release alpha weeks

During this time, the release notes team should be focused on preparing a space for the copious amount of text they will be processing.  The team should also be formalizing the process and distributing subroles for the coming weeks.

#### During the release beta weeks

#### After code freeze

At this point, the majority of PRs that will need release notes should have been merged.  There will logistically always be outliers, but at this point the release team should be able to 

#### After rc.1 has been cut (or the final week, if there is no rc.1)
