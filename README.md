# GitHub Organisation

DRAFT

This document aims to convey the reasons why and how curation and re-organisation of the organisation GitHub instance should take place.

## Background (Problem)

A GitHub organisation is not just a collection of software repositories, but has multiple purposes such as:
- A place to collect all the software created by an organisation
- A way to showcase and share those research outputs
- A location for templates and resources for staff.

The [UKCEH Organisation on GitHub](https://github.com/NERC-CEH/) has grown organically as a way to share code. At the moment the UKCEH organisation exists only as a collection of software and ideas; there are a few templates, but these are hard to find. There is an opportunity to showcase research outputs, and present an attractive portfolio, which is being missed.

## What can we change? (Opportunity)

We now have a team of RSEs within UKCEH who are able to devote time and effort to support researchers in creating software and using version control. The RSE team is starting to create courses and as such are able to encourage best practices amongst researchers.

## What should we do? (Practical Steps)

We need to work with researchers to understand how they use GitHub and recommend some minimal guidance which should be followed when using GitHub and sharing code/software. 

## What is the result? (Promise)

By creating guidance on how to use GitHub it will be we will be able to showcase the software created at UKCEH.  Utilising categorisation through clearly labelled with topics users would be able to allow quick filtering of repositories by type. This makes it easier to share software and templates inside UKCEH reducing time spent reinventing things.


## Advice

### What is the organisational repository for?

The UKCEH GitHub organisation exists to hold and showcase as much of UKCEH software outputs as possible.

- Any UKCEH work, or work done on UKCEH time that does not have a specific project repo (such as FDRI) / or existing repository (for example contributing to or expanding an R existing package)
  - A repository should be created in the UKCEH organisational repository, but then forking to a personal repository and pushing back is encouraged.
- Repositories should adopt a public by default approach, but a private repository in the UKCEH organisation is preferable to a personal (public or private) repository

### Minimal Requirements for a repository

To ensure that software can be shown off, and to make it easy to search for repositories in the GitHub organisation, we recommend the following minimal requirements for a repository/

- LICENSE file
- README file
- Code of Conduct
- Contribution Guidelines
- Citation File

For *Code of conduct* and *Contribution Guidelines* default ones can be created at the organisational level.  We suggested that UKCEH should agree and develop default Codes of conduct and contributor guidelines which can then be used not only in repositories with the UKCEH organisation but for, or as the basis for external projects.

A similar approach should be take for the LICENSE file.  Guidelines on a default first choice, and how to choose a license (there may be external factors such as funders requirements) should be developed.

The README file should contain the following as a minimum:

- Title
- Brief description / purpose of software/code
- Feel free to add disclaimer (work in progress, script and so on)
- Grant / Partners / funding timeline/scale

An good example of a readme can be found in the [jsdmstan: joint Species Distribution Models in Stan](https://github.com/NERC-CEH/jsdmstan) repository

### Topics

The use of topics (which are essentially labels on repositories) would allow better sharing and understanding of the vast software in the organisation GitHub instance.   The aim would not be to overload users with required (or suggested) topics, but to create a small list to support finding repositories.  Suggestions inlude:

- template
- tutorial
- model
- infrastructure
- analysis
- package
- status:
  - stable
  - active development
  - archived

These would not only support finding repositories but would provide quick labels making it clear what they are. A good example of topics can be seen on [GitHub's organisation](https://github.com/github)

#### External Repositories

We would also advise that when a repository is in an organisation outside of the UKCEH GitHub repository then, unless it conflicts with other organisations rules, repositories worked on by UKCEH staff should be tagged with the topic **UKCEH**. This could allow further tracking of repositories through https://github.com/topics/ukceh - however it should be noted any repository could be tagged with this so using it to definitively list UKCEH work would not be recommended.

### Landing page and showcase

An organisation on GitHub is a landing page for anything that organisation creates.  It can be plain with limitted information, but is a great opportunity to explain who we are, and showcase our proudest / most popular repositories. A good example of this can be seen on [GitHub's organisation](https://github.com/github)   

We should aim to create a short README which explains who we are and what to expect in the repository.  This could and should link to SA/Group/Sub-Team repositories, and potentially ones we are major partners on.

### Renaming the organisation

Whilst not neccessary it might be useful to take this chance to rename the organisation on GitHub,  It is currently **nerc-CEH**, for branding and consistency changing this to **UKCEH** may be better.  There are two ways to do this: One option is to rename the organisation.  All repository url will then change, but urls using the old name will be redirected, and users would receive warnings that the name has been changed if they try to use the old one. How long these redirects persist for is unclear. What happens if someone re-creates the nerc-CEH organisation is also unclear.  The other option is to create a new **UKCEH** organisation and migrate repositories across as they are brought up to the guidlines listed in the document. This would be more managagable and the urls will redirect as before.  UKCEH will then retain control of the nerc-CEH organisation so no-one else can claim it. This would also allow IT to better control and understand the membership of the current organisation.

We caution through that github usernames should not be specific to a Company/University/Organisation.  These much like ORCIDs and names provide researchers with a history of their outputs and contributions.

### Cleaning up the Organisation

There are may repositories in the GitHub organisation that provide little to no benefit to UKCEHs external profile, and perhaps lower it.  These should be made private or deleted.  This could be done in conjunction with the second renaming option. Examples of such repositories which need pruning or cleaning up are:
 - https://github.com/NERC-CEH/hello-world 
 - https://github.com/NERC-CEH/puppet-selendroid 

## Actions

1. Review minimal required information for a repository
2. Create guidance on preferred licences, how to choose a license and relevant IP.
3. Create repository/organisation health files:
   1. Code of Conduct
   2. Contribution Guidelines
3. Create a landing page and determined **pinned** repositories
4. Decided on whether and how a name change should take place
   
