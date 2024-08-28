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

- [ ] **TAG provides insight/recommendation of the project in the context of the landscape**

  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:
  TODO: add recommendation from TAG-storage here.

- [x] **All project metadata and resources are [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/).**

  <!-- (TOC Evaluation goes here) -->
  - **Neutral resources** - CubeFS has its own channels (community branded and managed), including:
    - Homepage: <cubefs.io>
    - Mailing list: <users@cubefs.groups.io>
    - Slack: <cubefs.slack.com>
    - WeChat: <https://github.com/cubefs/cubefs/issues/604>
    - Twitter: <https://x.com/cubefs_storage>
    - Community Meeting: <https://meeting.tencent.com/dm/IpNLDdT7uyEH>

  - **Governance** - [GOVERNANCE.md](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md) defined vendor-neutrality requirements on the TSC, Maintainers, Committers, including:
    - [The structure of the Technical Steering Committee Section](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#the-structure-of-the-maintainers) says: `No single vendor can exceed 50% of the total number of personnel.`
    - [The structure of the Maintainers Section](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#the-structure-of-the-maintainers) says: `No single vendor can exceed 50% of the total number of personnel.`
    - [The structure of the Committers Section](https://github.com/cubefs/cubefs/blob/6617aa1eb7bf6b63bfacc2c266eeb711c650973f/GOVERNANCE.md#the-structure-of-the-committers) says: `No single vendor can exceed 50% of the total number of personnel.`

- [ ] **Review and acknowledgement of expectations for [graduated](sandbox.cncf.io) projects and requirements for moving forward through the CNCF Maturity levels.**
  - [ ] Met during Project's application on 10-Apr-2024.
  ******* Kevin:
  TODO: add tracking docs link, and some descriptions

  <!-- (TOC Evaluation goes here) -->

Completion of this due diligence document, resolution of concerns raised, and presented for public comment satisifies the Due Diligence Review criteria.

- [x] **Additional documentation as appropriate for project type, e.g.: installation documentation, end user documentation, reference implementation and/or code samples.**

  <!-- (TOC Evaluation goes here) -->
  - [CubeFS introduction documentation](https://cubefs.io/docs/master/overview/introduction.html) introduces the CubeFS architecture and main features.
  - [CubeFS installation documentation](https://cubefs.io/docs/master/deploy/env.html) covers serveral ways of deployment.
  - [CubeFS end user documentation](https://cubefs.io/docs/master/user-guide/volume.html) includes basics operations as creating a volume, using volume and using cli tool.

## Governance and Maintainers

Note: this section may be augmented by the completion of a Governance Review from TAG Contributor Strategy.

### Suggested

- [ ] **Governance has continuously been iterated upon by the project as a result of their experience applying it, with the governance history demonstrating evolution of maturity alongside the project's maturity evolution.**

  <!-- (TOC Evaluation goes here) -->

  ******* Kevin:

  ******* Relevant Assets from the Project:

  - CubeFS Governance documentation originally draft according to [CoreDNS,Fulentd.etc..](https://github.com/cubefs/cubefs/blob/017c689013cfaef9c430680bc2c68f62c25a8fa9/GOVERNANCE.md#credits).This means that the initial project governance did not establish its own distinctive rules.
  - In the past six months, the core maintainer of CubeFS has been continuously optimizing around governance, hoping that the community will be clear, reasonable, efficient, and explicit in governance to help the community develop.[Governance documentation history](https://github.com/cubefs/cubefs/commits/master/GOVERNANCE.md)
  - Below are some governance document changes and pull requests made in response to governance documents, all of which have been voted on and presented by maintainers.
  - Update the Governance Document by most of maintainers: [link to pr](https://github.com/cubefs/cubefs/pull/3312), added Steering Committee to take charge of community highest strategy and explain the details.
  - Update the Governance Document to eliminate the role of the leader:[link to pr](https://github.com/cubefs/cubefs/pull/3382), The description of 'project lead' implies a somewhat authoritarian role, but with the establishment of a steering committee, the steering committee should be considered the highest decision-making body.Thus we delete the role of 'project lead'.
  - Update maintainer list according to activity and add steering commitee member: [link to pr](https://github.com/cubefs/cubefs/pull/3311)
  - Add a commiter through voting by steer committe and maintainers : https://github.com/cubefs/cubefs/pull/3386
  - Adding governance rules related to SIGs.: [link to pr](https://github.com/cubefs/cubefs/pull/3430)
  - Adding governance rules related to RoadMap.: [link to pr](https://github.com/cubefs/cubefs/pull/3430)

### Required

- [x] **Clear and discoverable project governance documentation.**
  <!-- (TOC Evaluation goes here) -->
  <!-- asset from project -->
  CubeFS governance documentation: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md)


- [ ] **Governance is up to date with actual project activities, including any meetings, elections, leadership, or approval processes.**

  <!-- (TOC Evaluation goes here) -->

  ******* Kevin:

  ******* Relevant Assets from the Project:

  - We can see from the olddest governance documentation that the leader is assgined to one person, that's a little authoritarianismand not healthy to comminity governance. So CubeFS Core maintainers drafted and  established  the Steering Committee,clarifying its members in CubeFS as the same time: [link to issue](https://github.com/cubefs/cubefs/pull/3311#issue-2238919813), ), approved by most of maintainers.
  - Add committer according to Governance and vote rules: [link to issue](https://github.com/cubefs/cubefs/pull/3384), approved by steering committe by votes.
  - Update the document of the roadmap to improve readability and include features that are in preparation but not yet scheduled: [link to pr](https://github.com/cubefs/cubefs/pull/3358), approved by steering committe by votes.
  - CubeFS Create SIGs according to [Member Changes and Management in SIGs](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#member-changes-and-management-in-sigs),  then nomitated the leader group of SIGS and [approved by  steering committe by votes and maintainers](https://github.com/cubefs/cubefs-community/pull/13).

- [x] **Governance clearly documents [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/) of project direction.**

  <!-- (TOC Evaluation goes here) -->
  ******* Kevin: add vendor-neutrality description besides project assets
  CubeFS has clear vendor-neutrality description the governance doc.
  
  The governance document [link](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#vendor-neutrality) clearly defines matters related to information transparency, channel transparency, decision-making, and other aspects among vendors.


  ******* Relevant Assets from the Project:

  - Roadmap Governance
    - Changes in project Roadmap rules:[link](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#changes-in-project-roadmap)
    - [Roadmap Update Example](https://github.com/cubefs/cubefs/pull/3358)
  - Management and maintainance of shared communication channels with vendors, such as social media and messaging platforms, with the rule of taking turns for being on duty.In China, we operate three WeChat groups, and we have also created a cubefs channel on Slack at <https://cubefs.slack.com>, which includes a development channel. Additionally, we have a Slack channel on CNCF at [link](https://cloud-native.slack.com/archives/C014X3T1DDJ). All of these channels include our maintainer members from various vendors.The Entrance is open:[link](https://github.com/cubefs/cubefs#community)
  - Public events of the project are open to all vendors for participation and topic involvement.  We emphasize the importance of transparent information sharing, such as external conference details and maintainer personnel list updates. We will collect feedback through the email address <cncf-cubefs-maintainers@lists.cncf.io>.
  - Community meetings, activities, and resources will be selected for participation by the leadership team. Maintainers can apply and be selected to participate.
  - Architectural decisions require community consensus and agreement by the majority of maintainers, reached during community meetings.For example:
    - Governance update [link](https://github.com/cubefs/cubefs/pull/3430)
    - Update maintainer list [link](https://github.com/cubefs/cubefs/pull/3311)

- [x] **Document how the project makes decisions on leadership, contribution acceptance, requests to the CNCF, and changes to governance or project goals.**

  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:

  ******* Relevant Assets from the Project:

  - Decision making process on leadership roles: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#decision-making-process)
  - Contribution acceptance: [link to md#section](https://github.com/cubefs/cubefs/blob/master/CONTRIBUTING.md)
  - Requests to the CNCF
    - CubeFS and cncf: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#cubefs-and-cncf)
    - Liaison officer for cncf: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#cubefs-and-cncf)
  - Changes to governance or project goals
    - Changes to governance or project goals: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#changes-in-project-governance)
    - Steering Committee Member is responsible for formulation  roadmap: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#expectations-from-the-steering-committee)

- [ ] **Document how role, function-based members, or sub-teams are assigned, onboarded, and removed for specific teams (example: Security Response Committee).**

  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:
  TODO: check if there is any other sub-teams

  ******* Relevant Assets from the Project:
  In the main CubeFS project, roles include steering committee members, maintainers, and contributors. The conditions and methods for role changes can be found in our governance documents. Apart from the main project, we have two SIG groups, with detailed governance explanations in their autonomous documents. Lastly, we also have a [security committee](https://github.com/cubefs/cubefs/blob/master/security/security-release-process.md#product-security-committee), with role descriptions outlined in the documentation

  - Main CubeFS project role update according to governance documentation:
    - [Becoming a Maintainer](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#becoming-a-maintainer)
    - [Changes in Maintainer membership](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#changes-in-maintainership)
    - [Expectations From the steering committee](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#expectations-from-the-steering-committee)
    - [Changes in Steering Committee](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#changes-in-steering-committee)
    - [Becoming a committer](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#becoming-a-committer)
    - [Changes in committer membership](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#changes-in-commitership)
  - Governance of to SIGs. Rules for assignment, onboarding, and removal: [link to pr](https://github.com/cubefs/cubefs/pull/3430)
  - Product Security Committee Membership: Rules for assignment, onboarding, and removal.[link to md#section](https://github.com/cubefs/cubefs/blob/master/security/security-release-process.md#product-security-committee-membership)


- [x] **Document complete list of current maintainers, including names, contact information, domain of responsibility, and affiliation.**

  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:
  CubeFS tracks maintainers list at: [https://github.com/cubefs/cubefs/blob/master/MAINTAINERS.md](https://github.com/cubefs/cubefs/blob/master/MAINTAINERS.md)

  ******* Relevant Assets from the Project:
  Details information about current maintainers: [link to md#section](https://github.com/cubefs/cubefs/blob/master/MAINTAINERS.md)

- [x] **A number of active maintainers which is appropriate to the size and scope of the project.**
  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:
  ******* Relevant Assets from the Project:
  CubeFS is a complex project with relevant maintainers and committers for each module, driving the evolution of modules from architecture to implementation, and maintaining the iterative development of modules on a daily basis.
  The maintainers are assigned to their respective modules, and the majority of maintainers have made a significant number of contributions in the past year.
  Details information about current maintainers: [link to md#section](https://github.com/cubefs/cubefs/blob/master/MAINTAINERS.md)

- [x] **Document a complete maintainer lifecycle process (including roles, onboarding, offboarding, and emeritus status).**
  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:
  ******* Relevant Assets from the Project:
  CubeFS has a clear maintainer lifecycle process documented in their governance doc:
  - How to become a maintainer: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#becoming-a-maintainer)
  - Document changes in maintainership, onboarding, offboarding: [link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#changes-in-maintainership)

- [ ] **Demonstrate usage of the maintainer lifecycle with outcomes, either through the addition or replacement of maintainers as project events have required.**

  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:需要举证maintainer生命周期管理的事情，比如哪人因为他的贡献被发展为了maintainer, balanced between那句表述不太妥当，会被认为是难以衡量的潜规则。

  ******* Relevant Assets from the Project:

  Currently, the maintainers of CubeFS are generally from active contributors. Changes have been made based on activity levels.

  - The latest personnel changes are based on the new governance document and voting principles.[link to pr](https://github.com/cubefs/cubefs/pull/3311)
  - Historical changes: New maintainers onboarding because individuals have been the main contributors to the project.[link to pr](https://github.com/cubefs/cubefs/pull/2228/files)
  - Historical changes: The maintainer offboarding is due to insufficient activity levels from several individuals.[link to pr](https://github.com/cubefs/cubefs/pull/3044)
  - Rules: How to become a maintainer.[link to md#section](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md?rgh-link-date=2024-03-30T12%3A39%3A54Z#changes-in-maintainership)

- [x] **Project maintainers from at least 2 organizations that demonstrates survivability.**

  According to the [Maintainers list](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/MAINTAINERS.md), CubeFS currently has top level maintainers from OPPO, JD.com, BEIKE, Bytedance, LinkedIn, and additional committers from BIGO, VIVO.

  Definition of Maintainers and Committers can be found in the [Goverance doc](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/GOVERNANCE.md)

- [x] **Code and Doc ownership in Github and elsewhere matches documented governance roles.**

  - Maintainers have expertise in the domain fields of the project and are listed in the maintainer documentation. Ref: [Maitainers.md#maintainers](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/MAINTAINERS.md#maintainers)
  - The top 6 contributors with the highest number of contributions are all maintainers. Ref: [github contribution graph](https://github.com/cubefs/cubefs/graphs/contributors?from=2019-02-20&to=2024-08-05&type=c)
- [x] **Document agreement that project will adopt CNCF Code of Conduct.**

  Documented at [GOVERNANCE.md#code-of-conduct](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/GOVERNANCE.md#code-of-conduct)
- [x] **CNCF Code of Conduct is cross-linked from other governance documents.**

  CNCF Code of conduct is cross-linked in the [Code of Conduct of CubeFS](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/CODE_OF_CONDUCT.md)

- [ ] **All subprojects, if any, are listed.**
  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:
  The project team says CubeFS has only components, no sub-projects.
  **Kevin TODO: Assets from the Project is incomplete, need to double check.**

  ******* Relevant Assets from the Project:
  The following projects are associated with CubeFS and serve as sub-project.

  - Adapt CubeFS installation to helm in the Kubernetes ecosystem: [cubefs-helm](https://github.com/cubefs/cubefs-helm)
  - Adapt CubeFS management to CSI (Container Storage Interface): [cubefs-csi](https://github.com/cubefs/cubefs-csi)
  - Dashboard for CubeFS: [cubefs-dashboard](https://github.com/cubefs/cubefs-dashboard)

  All subprojects have their own repositories but follow the same governance mechanism as the main project. [link](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md)
  [cubefs-helm Governance](https://github.com/cubefs/cubefs-csi#governance)
  [cubefs-csi Governance](https://github.com/cubefs/cubefs-csi#governance)
  [cubefs-dashboard Governance](https://github.com/cubefs/cubefs-dashboard#governance)


- [ ] **If the project has subprojects: subproject leadership, contribution, maturity status documented, including add/remove process.**
  <!-- (TOC Evaluation goes here) -->
  According to [Governance.md#sub-projects](https://github.com/cubefs/cubefs/blob/3576d88889e94d7173401e389824dd61cc485718/GOVERNANCE.md#sub-projects), sub-projects can have their own repositories but follow the same governance mechanism as the main project


  ******* Kevin: TODO: need update from the project team
  ******* Relevant Assets from the Project:

  All subprojects have their own repositories but follow the same governance mechanism as the main project. [link](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md)
  [cubefs-helm Governance](https://github.com/cubefs/cubefs-csi#governance)
  [cubefs-csi Governance](https://github.com/cubefs/cubefs-csi#governance)
  [cubefs-dashboard Governance](https://github.com/cubefs/cubefs-dashboard#governance)

## Contributors and Community

Note: this section may be augmented by the completion of a Governance Review from TAG Contributor Strategy.

### Suggested

- [x] **Contributor ladder with multiple roles for contributors.**

  Cubefs have multiple roles for contributors
  - Commiter: [GOVERNANCE.md#committer](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/GOVERNANCE.md#committer)
  - Maintainer: [GOVERNANCE.md#expectations-from-maintainers](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/GOVERNANCE.md#expectations-from-maintainers)
  - Steering committee member: [GOVERNANCE.md#expectations-from-the-steering-committee](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/GOVERNANCE.md#expectations-from-the-steering-committee)

### Required

- [x] **Clearly defined and discoverable process to submit issues or changes.**

  Defined in [CONTRIBUTING.md](https://github.com/cubefs/cubefs/blob/master/CONTRIBUTING.md), in the root path of CubeFS main repo.

- [x] **Project must have, and document, at least one public communications channel for users and/or contributors.**

  CubeFS has the following public communications channel for users and contributors documented in the [Project README](https://github.com/cubefs/cubefs#community)

  - Website: [https://cubefs.io/](https://cubefs.io/)
  - Mailing list: <users@cubefs.groups.io>
  - Slack: [https://cubefs.slack.com](https://cubefs.slack.com)
  - WeChat: [https://github.com/cubefs/cubefs/issues/604](https://github.com/cubefs/cubefs/issues/604)
  - X/Twitter: [https://x.com/cubefs_storage](https://x.com/cubefs_storage)

- [ ] **List and document all project communication channels, including subprojects (mail list/slack/etc.).  List any non-public communications channels and what their special purpose is.**
  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:
  ******* Relevant Assets from the Project:
  - The communication channels for CubeFS and it's sub-projects are shared: [link](https://github.com/cubefs/cubefs#community)
  - Besides public channels, CubeFS has a private mailing list <security@cubefs.groups.io> for users reporting security vulnerabilities. Ref: [Security](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/SECURITY.md)

- [x] **Up-to-date public meeting schedulers and/or integration with CNCF calendar.**

  CubeFS currently holds monthly community meeting, integrated with [CNCF calendar](https://www.cncf.io/calendar/)
  And meeting minutes and recordings listed at: [CubeFS meeting schedule](https://github.com/cubefs/cubefs-community/wiki/Meeting-Schedule)

- [x] **Documentation of how to contribute, with increasing detail as the project matures.**

  CubeFS contribution workflow documented at: [CONTRIBUTING.md#workflow](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/CONTRIBUTING.md#workflow)

- [ ] **Demonstrate contributor activity and recruitment.**

  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:
    Assets from project team irralevant.
  ******* Relevant Assets from the Project:
  - Contributor activity can be measured and displayed using GitHub's built-in tools to assess the current participation of contributors
  [The contributions of contributors](https://github.com/cubefs/cubefs/graphs/contributors)
  [The level of community activity, including contributors' discussions, issues, pull requests, and other activities](https://github.com/cubefs/cubefs/graphs/community)

  - Using strategies and methods such as participating in summits and events to attract new vendor and adoptors
    - 2024 KubeCon HONGKONG: CubeFS Boosts Efficiency of AI Production
    - 2023 KubeCon China:[Cloud Native Storage CubeFS, Empowering AI Acceleration](https://www.youtube.com/watch?v=JOio7Nps_II&t=1036s)
    - 2022 KubeCon NA:[The Best Practice of Machine Learning Platform Storage Based on CubeFS](https://www.youtube.com/watch?v=T8IjKLU9DWw&t=896s)
    - 2023 GOTC: [interview](https://baijiahao.baidu.com/s?id=1766755025138692049&wfr=spider&for=pc)
  - By participating in developer events attract contributors
    - [Summer of Open Source](https://www.we2shopping.com/blog/2829327/)
    - [Developer activity 2024](https://github.com/cubefs/cubefs/issues/3105)
    - [Developer activity 2023](https://github.com/cubefs/cubefs/issues/1920)

  - Ensure that new members can integrate smoothly and participate actively。For vendor enterprise users, there is a direct group chat for WeChat products. Generally, companies with technical capabilities will consider participating in development for feature customization

    - [OpenPie](https://github.com/cubefs/cubefs/pulls?q=is%3Apr+is%3Aclosed+author%3Amorphes1995)
    - [BIGO](https://github.com/cubefs/cubefs/pulls?q=is%3Apr+is%3Aclosed+author%3Aliubingxing)
    - [KE](https://github.com/cubefs/cubefs/pulls?q=is%3Apr+is%3Aclosed+author%3Ashyodx)

  - attracted 2 committers to join through the Summer of Code event, and they continue to contribute to the community
    - [NaturalSelect](https://github.com/NaturalSelect) : [Contribution record](https://github.com/cubefs/cubefs/pulls?q=is%3Apr+is%3Aclosed+author%3ANaturalSelect)
    - [setcy](https://github.com/setcy) : [Contribution record](https://github.com/cubefs/cubefs/pulls?q=is%3Apr+setcy+is%3Aclosed)

## Engineering Principles

- [ ] **Document project goals and objectives that illustrate the project’s differentiation in the Cloud Native landscape as well as outlines how this project fulfills an outstanding need and/or solves a problem differently.**
  <!-- (TOC Evaluation goes here) -->
  Project’s differentiation documented in [#why-cubefs](https://cubefs.io/docs/master/overview/introduction.html#why-cubefs)

  File storage and object storage are key in the storage domain. CubeFS is a file storage system that provides cloud-native file system capabilities and is compatible with object storage. Moreover, it offers a multitude of competitive features and capabilities. The project’s differentiation is the main feature of CubeFS: [link to md#section](https://github.com/cubefs/cubefs/blob/master/README.md#what-can-you-build-with-cubefs)

  ******* Relevant Assets from the Project:

  File storage and object storage are key in the storage domain. CubeFS is a file storage system that provides cloud-native file system capabilities and is compatible with object storage. Moreover, it offers a multitude of competitive features and capabilities.
  The project’s differentiation is the main feature of CubeFS: [link to md#section](https://github.com/cubefs/cubefs/blob/master/README.md#what-can-you-build-with-cubefs)

- [ ] **Document what the project does, and why it does it - including viable cloud native use cases.**

  <!-- (TOC Evaluation goes here) -->
  CubeFS Introduction: [link](https://cubefs.io/docs/master/overview/introduction.html)

  According to [CubeFS doc](<https://cubefs.io/docs/master/overview/introduction.html#application-scenarios>), typical use cases are:
  - Big Data Analytics
  - Deep Learning/Machine Learning
  - Container Shared Storage
  - Database & Middleware
  - Online Services
  - Traditional NAS to Cloud



  Project’s differentiation documented in [#why-cubefs](https://cubefs.io/docs/master/overview/introduction.html#why-cubefs)

  File storage and object storage are key in the storage domain. CubeFS is a file storage system that provides cloud-native file system capabilities and is compatible with object storage. Moreover, it offers a multitude of competitive features and capabilities. The project’s differentiation is the main feature of CubeFS: [link to md#section](https://github.com/cubefs/cubefs/blob/master/README.md#what-can-you-build-with-cubefs)

- [CubeFS Introduction](https://cubefs.io/docs/master/overview/introduction.html) includes what CubeFS does, and why it does it
- Use Case: How CubeFS Accelerates AI training in Hybrid Cloud platform: [link](https://cubefs.io/blog/useCases/oppo-ai.html)
- Documentation:[Integration with Kubernetes](https://cubefs.io/docs/master/ecology/k8s.html)
  



- [x] **Document and maintain a public roadmap or other forward looking planning document or tracking mechanism.**

  CubeFS has a public roadmap doc at [ROADMAP.md](https://github.com/cubefs/cubefs/blob/master/ROADMAP.md)

- [x] **Roadmap change process is documented.**

  CubeFS documentes its roadmap rules and changing process in [GOVERNANCE.md#roadmap](https://github.com/cubefs/cubefs/blob/master/GOVERNANCE.md#roadmap)

- [x] **Document overview of project architecture and software design that demonstrates viable cloud native use cases, as part of the project's documentation.**

  - CubeFS architecture overview: <https://cubefs.io/docs/master/overview/architecture.html#architecture>
  - Design details are documented under the "Design" section, an example is: <https://cubefs.io/docs/master/design/master.html>



- [ ] **Document the project's release process and guidelines publicly in a RELEASES.md or equivalent file that defines:**

  - [x] Release expectations (scheduled or based on feature implementation)
  - [x] Tagging as stable, unstable, and security related releases
  - [x] Information on branch and tag strategies
  - [x] Branch and platform support and length of support
  - [x] Artifacts included in the release.
  - Additional information on topics such as LTS and edge releases are optional. Release expectations are a social contract between the project and its end users and hence changes to these should be well thought out, discussed, socialized and as necessary agreed upon by project leadership before getting rolled out.
    <!-- (TOC Evaluation goes here) -->

  ******* Kevin:
  - Cubefs documents their release frequency as needed (beta and official releases), which can be regarded as based on feature implementation.
  - Security release process described at: https://github.com/cubefs/cubefs/blob/master/security/security-release-process.md
  - Length of support clearly documented, support latest 3 minor releases.
  - **Findings, suggeted update**: No specific description of platform supported, according to the [artifacts-included-in-the-release](https://github.com/cubefs/cubefs/blob/cef58ab3db04857b05a69d9a132e37d4d92e79c7/RELEASE.md#artifacts-included-in-the-release), seems only amd64 binaries are maintained by the community currently.

  ******* Relevant Assets from the Project:


- [x] **History of regular, quality releases.**

  History of CubeFS releases and changelogs: <https://github.com/cubefs/cubefs/releases>

## Security

Note: this section may be augemented by a joint-assessment performed by TAG Security.

### Suggested

- [ ] **Achieving OpenSSF Best Practices silver or gold badge.**

  <!-- (TOC Evaluation goes here) -->

### Required

- [x] **Clearly defined and discoverable process to report security issues.**

  CubeFS has a clear security vulnerability report guide at: [SECURITY.md](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/SECURITY.md#report-a-vulnerability)


- [ ] **Enforcing Access Control Rules to secure the code base against attacks (Example: two factor authentication enforcement, and/or use of ACL tools.)**

  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:

  ******* Relevant Assets from the Project:
1）Maintainer account security, two-factor authentication, and GitHub login requiring Authenticator two-step verification.
2）CI integration includes ci-test-unit,ci-test-s3 and ci-sast [link](https://github.com/cubefs/cubefs/blob/master/.github/workflows/ci.yml)
3）Security scanning, static and dynamic scanning

  - [gofumpt](https://github.com/cubefs/cubefs/blob/master/docker/script/run_format.sh)
  - golint:In file docker-compose.yml:469 [link](https://github.com/cubefs/cubefs/blob/master/docker/docker-compose.yml)
  - gosec:In file docker-compose.yuml:479 [link](https://github.com/cubefs/cubefs/blob/master/docker/docker-compose.yml)
  - [fuzzers:Fuzz testing][cubefs: add base fuzzers cncf/cncf-fuzzing#387](https://github.com/cncf/cncf-fuzzing/pull/387)

- [x] **Document assignment of security response roles and how reports are handled.**

  The CubeFS [Security Release Process](https://github.com/cubefs/cubefs/blob/1536a544f2d9547647ad4e260edade60163e3585/security/security-release-process.md) documents response roles and process of handling reports.

- [ ] **Document Security Self-Assessment.**
  
  https://github.com/cubefs/cubefs/blob/master/security/CubeFS-self-assessment.md
  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:

  ******* Relevant Assets from the Project:
  https://cubefs.io/docs/master/security/security_practice.html

- [ ] **Third Party Security Review.**

  - [ ] Moderate and low findings from the Third Party Security Review are planned/tracked for resolution as well as overall thematic findings, such as: improving project contribution guide providing a PR review guide to look for memory leaks and other vulnerabilities the project may be susceptible to by design or language choice ensuring adequate test coverage on all PRs.

  CubeFS has passed the Third Party Security Review, Ref: [CubeFS-Security-Audit-2023-report](https://github.com/cubefs/cubefs/blob/master/security/CubeFS-security-audit-2023-report.pdf).

  <!-- (TOC Evaluation goes here) -->
  ******* Kevin:
    Need to check if findings and recommendations are under tracking.
    Critical issues need to be fixed.

  ******* Relevant Assets from the Project:

Some advisories already be fixed [link](https://github.com/cubefs/cubefs/security/advisories?state=Triage)

- [ ] **Achieve the Open Source Security Foundation (OpenSSF) Best Practices passing badge.**

  CubeFS has achieved OpenSSF Best Practices badge: <https://www.bestpractices.dev/en/projects/6232>

## Ecosystem

### Suggested

N/A

### Required

- [x] **Publicly documented list of adopters, which may indicate their adoption level (dev/trialing, prod, etc.)**

The [ADOPTERS.md](https://github.com/cubefs/cubefs/blob/master/ADOPTERS.md) documentes adopters with adoption level and success stories.

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
