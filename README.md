# GitHub Organisation

## Justification

This document aims to convey the reasons why and how curation and re-organisation of the organisation GitHub instance should take place.

### Background (Problem)

A GitHub organisation is not just a collection of software repositories, but has multiple purposes such as:
- A place to collect all the software created by an organisation
- A way to showcase and share those research outputs
- A location for templates and resources for staff.

The [UKCEH Organisation on GitHub](https://github.com/NERC-CEH/) has grown organically as a way to share code. At the moment the UKCEH organisation exists only as a collection of software and ideas; there are a few templates, but these are hard to find. There is an opportunity to showcase research outputs, and present an attractive portfolio, which is being missed.

### What can we change? (Opportunity)

We now have a team of RSEs within UKCEH who are able to devote time and effort to support researchers in creating software and using version control. The RSE team is starting to create courses and as such are able to encourage best practices amongst researchers.

### What should we do? (Practical Steps)

We need to work with researchers to understand how they use GitHub and recommend some minimal guidance which should be followed when using GitHub and sharing code/software. 

### What is the result? (Promise)

By creating guidance on how to use GitHub it will be we will be able to showcase the software created at UKCEH.  Utilising categorisation through clearly labelled with topics users would be able to allow quick filtering of repositories by type. This makes it easier to share software and templates inside UKCEH reducing time spent reinventing things.


## GitHub Organisation use Guidance

### What is the organisational repository for?

The UKCEH GitHub organisation exists to hold and showcase as much of UKCEH software outputs as possible.

- Any UKCEH work, or work done on UKCEH time that does not have a specific project repo (such as FDRI) / or existing repository (for example contributing to or expanding an R existing package)
  - A repository should be created in the UKCEH organisational repository, but then forking to a personal repository and pushing back is encouraged.
- Repositories should adopt a public by default approach, but a private repository in the UKCEH organisation is preferable to a personal (public or private) repository

### Minimal Requirements for a repository

The following files should be included in a repository

- README.md
- LICENSE.md
- CODE_OF_CONDUCT.md
- CONTRIBUTING.md
- CITATION.cff


#### `README.md`

The `README.md` file should contain the following as a minimum:

- Title
- Brief description / purpose of software/code
- Feel free to add disclaimer (work in progress, script and so on)
- Grant / Partners / funding timeline/scale

An good example of a readme can be found in the [jsdmstan: joint Species Distribution Models in Stan](https://github.com/NERC-CEH/jsdmstan) repository

#### `LICENCE.md`

A similar approach should be take for the LICENSE file.  Guidelines on a default first choice, and how to choose a license (there may be external factors such as funders requirements) should be developed.

[](Format to 1 heading per file and cleanup)

#### Code of conduct and Contri

The *Code of conduct*(`CODE_OF_CONDUCT.md`) and *Contribution Guidelines*(`CONTRIBUTING.md`) let people know how to contribute to a repository.  You can create your own ([see guidance](guidance_contributing.md)) or the default ones will be inherited from the UKCEH GitHub organisation when the repository is created.

### Archiving 
- [ ] (you can always un-archive.  Great way to communicate that this is no longer under active development and may not be again)
- [ ] (can people still fork or generate PRs? or raise issues?)
- [ ] (is there any guidance on it?)
- [ ] (JMR to look at this section)

### Forking


### Topics

- [ ] (Re word to introduce GH language, but use move conventional phrasing of tags)
- [ ] (Flag as work-in-progess, open to suggestions)
- [ ] (Split to separate document for more hand wavey guidance)
- [ ] (These are topics, they are used for X, think about using them)
The use of topics (which are essentially labels on repositories) would allow better sharing and understanding of the vast software in the organisation GitHub instance.   The aim would not be to overload users with required (or suggested) topics, but to create a small list to support finding repositories.  Suggestions inlude:

- template
- tutorial

- [ ] (Change the instructions to link to GitHubs documentation on 'topics')
These would not only support finding repositories but would provide quick labels making it clear what they are. A good example of topics can be seen on [GitHub's organisation](https://github.com/github)

#### Tagging External Repositories as **UKCEH**

- [ ] (Move into stuff we are thinking but don't know if the best way
- [ ] (Ignore as replace with catalogue.)
- [ ] (org zenodo guidance)
- [ ] (Should be all or non as topic would be wrong)
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
   
