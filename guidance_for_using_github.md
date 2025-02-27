# GitHub Organisation

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

#### Code of conduct and Contributing

The *Code of conduct*(`CODE_OF_CONDUCT.md`) and *Contribution Guidelines*(`CONTRIBUTING.md`) let people know how to contribute to a repository.  You can create your own ([see guidance](guidance_contributing.md)) or the default ones will be inherited from the UKCEH GitHub organisation when the repository is created.

### Archiving 
[](you can always un-archive.  Great way to communicate that this is no longer under active development and may not be again)
[](can people still fork or generate PRs? or raise issues?)
[](is there any guidance on it?)
[](JMR to look at this section)

### Forking


### Topics

[](Re word to introduce GH language, but use move conventional phrasing of tags)
[](Flag as work-in-progess, open to suggestions)
[](Split to separate document for more hand wavey guidance)
[](These are topics, they are used for X, think about using them)
The use of topics (which are essentially labels on repositories) would allow better sharing and understanding of the vast software in the organisation GitHub instance.   The aim would not be to overload users with required (or suggested) topics, but to create a small list to support finding repositories.  Suggestions inlude:

- template
- tutorial

[](Change the instructions to link to GitHubs documentation on 'topics')
These would not only support finding repositories but would provide quick labels making it clear what they are. A good example of topics can be seen on [GitHub's organisation](https://github.com/github)

#### Tagging External Repositories as **UKCEH**

[](Move into stuff we are thinking but don't know if the best way
[](Ignore as replace with catalogue.)
[](org zenodo guidance)
[](Should be all or non as topic would be wrong)
We would also advise that when a repository is in an organisation outside of the UKCEH GitHub repository then, unless it conflicts with other organisations rules, repositories worked on by UKCEH staff should be tagged with the topic **UKCEH**. This could allow further tracking of repositories through https://github.com/topics/ukceh - however it should be noted any repository could be tagged with this so using it to definitively list UKCEH work would not be recommended.
