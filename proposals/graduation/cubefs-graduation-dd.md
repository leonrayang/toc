# CubeFS Graduation Due Diligence

- Link to [CubeFS Graduation application](https://github.com/cncf/toc/pull/1140)

<!-- This template provides the TOC with the outline for completing due diligence of a project to move levels. This universal template is designed to capture all criteria so the TOC may ensure prior level criteria do not regress. As part of completing the due diligence, the TOC member should update the template to convey the level the project applied for the criteria by bolding the level indicated where the criteria is relevant. -->

## Graduation Evaluation Summary for CubeFS

### Criteria Evaluation

_$TOCMEMBER conducted the due diligence of $PROJECT who applied for $LEVEL. The project [has/has not] completed the criteria that show its maturity at $LEVEL. The following criteria implementations are noteworthy to call out... $NOTABLES. The following actions were provided to the project that were considered blocking but since resolved... $BLOCKERS. The following recommendations were provided to the project that are non-blocking in the TOC's assessment but should be completed by the project to ensure continued viability of the project... $RECOMMENDATIONS._

### Adoption Evaluation

_The adopter interviews reflect a project [in use/too early] for the level which the project applied. They show ... $INTERVIEWSUMMARY._

### Final Assessment

_[The TOC has found the project to have satisfied the criteria for $LEVEL/ The TOC's evaluation of the project shows a needed focus to complete the outstanding blockers and reapply when the following conditions are met ... $CONDITIONS]._

### Criteria

## Application Process Principles

### Suggested

N/A

### Required

- [x] **Give a presentation and engage with the domain specific TAG(s) to increase awareness**

<!-- (TOC Evaluation goes here) -->
Record of CubeFS presentation at the Storage TAG on April 24, 2024. [link to video](https://www.youtube.com/watch?v=UgRBZhzfr4w)

- [ ]  **TAG provides insight/recommendation of the project in the context of the landscape**

<!-- (TOC Evaluation goes here) -->
******* Kevin:
  TODO: add recommendation from TAG-storage here.

- [ ]  **All project metadata and resources are [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/).**

<!-- (TOC Evaluation goes here) -->
******* Kevin:
  // Need to Describe with rules and examples of proof

******* Relevant Assets from the Project:

- In CubeFS governance.md, we require vendur-neutrality: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md?rgh-link-date=2024-03-30T12%3A39%3A54Z#vendor-neutrality)
- Current maintainers of CubeFS coming from JD, OPPO, BEIKE etc.: [link to md#section](https://github.com/cubefs/cubefs/blob/master/MAINTAINERS.md?rgh-link-date=2024-03-30T12%3A39%3A54Z#maintainers)
- Steering committee member: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md?rgh-link-date=2024-03-30T12%3A39%3A54Z#expectations-from-the-steering-committee)

- [ ] **Review and acknowledgement of expectations for [graduated](sandbox.cncf.io) projects and requirements for moving forward through the CNCF Maturity levels.**		
  - [ ] Met during Project's application on 10-Apr-2024.

<!-- (TOC Evaluation goes here) -->

Completion of this due diligence document, resolution of concerns raised, and presented for public comment satisifies the Due Diligence Review criteria.

- [ ] **Additional documentation as appropriate for project type, e.g.: installation documentation, end user documentation, reference implementation and/or code samples.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:

CubeFS introduction documentation: [link](https://cubefs.io/docs/master/overview/introduction.html)
CubeFS installation documentation: [link](https://github.com/cubefs/cubefs/blob/master/INSTALL.md?rgh-link-date=2024-03-30T12%3A39%3A54Z)
CubeFS end user documentation: [link](https://cubefs.io/docs/master/user-guide/volume.html)


## Governance and Maintainers

Note: this section may be augmented by the completion of a Governance Review from TAG Contributor Strategy.

### Suggested

- [ ]  **Governance has continuously been iterated upon by the project as a result of their experience applying it, with the governance history demonstrating evolution of maturity alongside the project's maturity evolution.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:

- Update the Governance Document by most of maintainers: [link to pr](https://github.com/cubefs/cubefs/pull/3312)
- Update the Governance Document to eliminate the role of the leader:[link to pr](https://github.com/cubefs/cubefs/pull/3382)
- Update maintainer list according to activity and add steering commitee member: [link to pr](https://github.com/cubefs/cubefs/pull/3311)


### Required

- [x] **Clear and discoverable project governance documentation.**

<!-- (TOC Evaluation goes here) -->

<!-- asset from project -->
CubeFS governance documentation: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md?rgh-link-date=2024-03-30T12%3A39%3A54Z)


- [ ] **Governance is up to date with actual project activities, including any meetings, elections, leadership, or approval processes.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:

- CubeFS Meeting-Schedule: [link](https://github.com/cubefs/cubefs-community/wiki/Meeting-Schedule)
- 2024-Recruiting developers: [link to issue](https://github.com/cubefs/cubefs/issues/3105)
- The establishment of the Steering Committee and clarification of its members in CubeFS: [link to issue](https://github.com/cubefs/cubefs/pull/3311#issue-2238919813)
- Update the document of the roadmap to improve readability and include features that are in preparation but not yet scheduled: [link to pr](https://github.com/cubefs/cubefs/pull/3358)

- [ ] **Governance clearly documents [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/) of project direction.**

<!-- (TOC Evaluation goes here) -->
******* Kevin: add vendor-neutrality description besides project assets

******* Relevant Assets from the Project:

- Project Direction: [link to md#section](https://github.com/cubefs/cubefs#overview)
- What can you build with CubeFS: [link to md#section](https://github.com/cubefs/cubefs/blob/master/README.md?rgh-link-date=2024-03-30T12%3A39%3A54Z#what-can-you-build-with-cubefs)
- CubeFS roadmap 2024: [link to md#section](https://github.com/cubefs/cubefs/blob/master/ROADMAP.md?rgh-link-date=2024-03-30T12%3A39%3A54Z)


- [ ] **Document how the project makes decisions on leadership, contribution acceptance, requests to the CNCF, and changes to governance or project goals.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:

- Decision making process on leadership roles: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md?rgh-link-date=2024-03-30T12%3A39%3A54Z#decision-making-process)
- Contribution acceptance: [link to md#section](https://github.com/cubefs/cubefs/blob/master/CONTRIBUTING.md?rgh-link-date=2024-03-30T12%3A39%3A54Z)
- Requests to the CNCF


- [ ] **Document how role, function-based members, or sub-teams are assigned, onboarded, and removed for specific teams (example: Security Response Committee).**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Document complete list of current maintainers, including names, contact information, domain of responsibility, and affiliation.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **A number of active maintainers which is appropriate to the size and scope of the project.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Document a complete maintainer lifecycle process (including roles, onboarding, offboarding, and emeritus status).**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Demonstrate usage of the maintainer lifecycle with outcomes, either through the addition or replacement of maintainers as project events have required.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Project maintainers from at least 2 organizations that demonstrates survivability.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Code and Doc ownership in Github and elsewhere matches documented governance roles.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Document agreement that project will adopt CNCF Code of Conduct.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **CNCF Code of Conduct is cross-linked from other governance documents.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **All subprojects, if any, are listed.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **If the project has subprojects: subproject leadership, contribution, maturity status documented, including add/remove process.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


## Contributors and Community

Note: this section may be augmented by the completion of a Governance Review from TAG Contributor Strategy.

### Suggested

- [ ] **Contributor ladder with multiple roles for contributors.**

<!-- (TOC Evaluation goes here) -->

### Required

- [ ] **Clearly defined and discoverable process to submit issues or changes.**


<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Project must have, and document, at least one public communications channel for users and/or contributors.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **List and document all project communication channels, including subprojects (mail list/slack/etc.).  List any non-public communications channels and what their special purpose is.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Up-to-date public meeting schedulers and/or integration with CNCF calendar.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Documentation of how to contribute, with increasing detail as the project matures.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Demonstrate contributor activity and recruitment.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


## Engineering Principles

- [ ] **Document project goals and objectives that illustrate the project’s differentiation in the Cloud Native landscape as well as outlines how this project fulfills an outstanding need and/or solves a problem differently.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Document what the project does, and why it does it - including viable cloud native use cases.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Document and maintain a public roadmap or other forward looking planning document or tracking mechanism.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Roadmap change process is documented.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Document overview of project architecture and software design that demonstrates viable cloud native use cases, as part of the project's documentation.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Document the project's release process and guidelines publicly in a RELEASES.md or equivalent file that defines:**

  - [ ] Release expectations (scheduled or based on feature implementation)
  - [ ] Tagging as stable, unstable, and security related releases
  - [ ] Information on branch and tag strategies
  - [ ] Branch and platform support and length of support
  - [ ] Artifacts included in the release.
  - Additional information on topics such as LTS and edge releases are optional. Release expectations are a social contract between the project and its end users and hence changes to these should be well thought out, discussed, socialized and as necessary agreed upon by project leadership before getting rolled out.

<!-- (TOC Evaluation goes here) --> 
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **History of regular, quality releases.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


## Security

Note: this section may be augemented by a joint-assessment performed by TAG Security.

### Suggested

- [ ] **Achieving OpenSSF Best Practices silver or gold badge.**

<!-- (TOC Evaluation goes here) -->

### Required

- [ ] **Clearly defined and discoverable process to report security issues.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Enforcing Access Control Rules to secure the code base against attacks (Example: two factor authentication enforcement, and/or use of ACL tools.)**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Document assignment of security response roles and how reports are handled.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Document Security Self-Assessment.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Third Party Security Review.**

  - [ ] Moderate and low findings from the Third Party Security Review are planned/tracked for resolution as well as overall thematic findings, such as: improving project contribution guide providing a PR review guide to look for memory leaks and other vulnerabilities the project may be susceptible to by design or language choice ensuring adequate test coverage on all PRs.

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Achieve the Open Source Security Foundation (OpenSSF) Best Practices passing badge.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


## Ecosystem

### Suggested

N/A

### Required

- [ ] **Publicly documented list of adopters, which may indicate their adoption level (dev/trialing, prod, etc.)**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


- [ ] **Used in appropriate capacity by at least 3 independent + indirect/direct adopters, (these are not required to be in the publicly documented list of adopters)**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


The project provided the TOC with a list of adopters for verification of use of the project at the level expected, i.e. production use for graduation, dev/test for incubation.

- [ ] **TOC verification of adopters.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


Refer to the Adoption portion of this document.

- [ ] **Clearly documented integrations and/or compatibility with other CNCF projects as well as non-CNCF projects.**

<!-- (TOC Evaluation goes here) -->
******* Kevin:

******* Relevant Assets from the Project:


#### Adoption

##### Adopter 1 - $COMPANY/$INDUSTRY

_If the Adopting organization needs to remain anonymous, stating the industry vertical is sufficient._
MONTH YEAR

##### Adopter 2 - $COMPANY/$INDUSTRY

_If the Adopting organization needs to remain anonymous, stating the industry vertical is sufficient._
MONTH YEAR

##### Adopter 3 - $COMPANY/$INDUSTRY

_If the Adopting organization needs to remain anonymous, stating the industry vertical is sufficient._
MONTH YEAR
