# In-toto Graduation Due Diligence

- [In-toto graduation application issue](https://github.com/cncf/toc/pull/1162/)

Project Repo(s): http://github.com/in-toto
Project Site:  https://in-toto.io/
Communication: #in-toto on CNCF Slack Workspace

Project points of contacts: Santiago Torres, santiagotorres@purdue.edu

## Graduation Criteria Summary for In-toto

### Criteria Evaluation

Lin Sun (@linsun) conducted the due diligence and adopter interview for Graduation. The project has completed the criteria that show its maturity at the applied level. The following criteria implementations are noteworthy to call out:

- A notable stable project with mature capabilities and a wide [adopter](https://github.com/in-toto/friends?tab=readme-ov-file#project-adopters) base.
- The project has a wide range of interest across academic and cross different industries.
- The project [integrates](https://github.com/in-toto/friends?tab=readme-ov-file#project-integrations) with various other projects in the cloud native ecosystem such as GitHub, GitLab, GUAC, Tekton, etc.
- Implementation of the steering committee to capture adopters' voice in the project development and roadmap.
- The project is not only vendor neutral but also has a very diversed set of maintainers, adopters and integrators.
- The project does an excellent job of making sure that its public meetings are accessible, with notes, and easy to find meeting links.

The following actions were provided to the project that were considered blocking but have since been resolved:

- Updating the list of subprojects in GitHub, found from the Governancy review.
- Provide an updated roadmap document in GitHub.
- Document the release process.
- Provide instructions of onboarding & offboarding members/roles in the community.

### Adoption Evaluation:

The adopter interviews reflect the in-toto project is in use for the level which the project applied, which is CNCF graduation. It has a good range of adopters across different industries and vendors, including GitHub, DataDog, SLAS, Solarwinds, Lockheed Martins and more. Every adopter I interviewed is quite happy with in-toto.  Highlight some of the project strengths I heard during adopter interviews:

- "Beyond the community, and diversity of others using it, the spec is also very flexible. You can add to it, or expand it or create a unique solution with it."
- "Community discussions are great and how they bring them (industry & academic & non profit OSS foundation). Really thinking ahead and anticipating needs before people need them. Continue to be an active community."
- "It's also been great to see the cross-industry and academic collaboration for in-toto and other related projects - it's a large community effort."

Only 1 adopter suggested 1 minor improvement, which is increased marketing effort. Other adopters seem happy with in-toto today.

### Final Assessment

The TOC has found the project to have satisfied the criteria for Graduation.

## Application Process Principles

### Suggested

N/A

### Required

- [X] **Give a presentation and engage with the domain specific TAG(s) to increase awareness**

[Presentation](https://zoom.us/rec/share/H4AeeCUzrh7dVDzv7udMJmK-jWHvENmyWmcZvG4-1rZbVWUTn7RAByqKSfG3g9ya.OJnqcezJAXcGMce0?startTime=1721235498000) was given to the TAG security in July 2014, which was recorded in this [issue](https://github.com/cncf/tag-security/issues/1290).

- [x]  **TAG provides insight/recommendation of the project in the context of the landscape**

[Very strong support](https://github.com/cncf/toc/pull/1162#issuecomment-2236636343) from TAG security on in-toto's CNCF graduation:

- [X]  **All project metadata and resources are [vendor-neutral](https://contribute.cncf.io/maintainers/community/vendor-neutrality/).**

No issues were found during due diligence, both code and documentation are vendor neutral. Vendor neutral is clearly mentioned twice in the governance doc. Based on the community meeting minutes, [contributor stats](https://intoto.devstats.cncf.io/d/5/companies-table?orgId=1&var-period_name=Last%20year&var-metric=contributions) and what adopters say about the project, in-toto is very diverse. It is one of the projects that started in academic and attracted a good range of interest from industries as well.

- [x] **Review and acknowledgement of expectations for graduated projects and requirements for moving forward through the CNCF Maturity levels.**
   - [x] Met during Project's application on 21-06-2024.

I met with the project lead and went over the expectation and requirements for graduated project, as recorded [here](https://github.com/cncf/toc/pull/1162#issuecomment-2190111991).

- [X] **Additional documentation as appropriate for project type, e.g.: installation documentation, end user documentation, reference implementation and/or code samples.**

Docs are available at https://in-toto.readthedocs.io/en/latest/index.html which includes install, API, code sample, and how to contribute etc.

## Governance and Maintainers

Note: this section may be augmented by the completion of a Governance Review from TAG Contributor Strategy.

### Suggested

- [ ]  **Governance has continuously been iterated upon by the project as a result of their experience applying it, with the governance history demonstrating evolution of maturity alongside the project's maturity evolution.**

[Governance doc](https://github.com/in-toto/community/blob/main/GOVERNANCE.md) is clear. There is very few changes to it since it was created in Feb, 2023.

### Required

- [X] **Clear and discoverable project governance documentation.**

Able to find it easily.

- [X] **Governance is up to date with actual project activities, including any meetings, elections, leadership, or approval processes.**

Confirmed with the team the [Governance doc](https://github.com/in-toto/community/blob/main/GOVERNANCE.md) is up to date.

- [X] **Governance clearly documents [vendor-neutrality](https://contribute.cncf.io/maintainers/community/vendor-neutrality/) of project direction.**

Vendor neutral is clearly mentioned twice in the governance doc. Steering committee composition is also diverse at the moment.

- [X] **Document how the project makes decisions on leadership roles, contribution acceptance, requests to the CNCF, and changes to governance or project goals.**

Documented [here](https://github.com/in-toto/community/tree/main/elections)

- [X]  **Document how role, function-based members, or sub-teams are assigned, onboarded, and removed for specific teams (example: Security Response Committee).**

[GOVERNANCE.md document](https://github.com/in-toto/community/blob/main/GOVERNANCE.md) shows various project roles and how decisions are made.

- [X] **Document complete list of current maintainers, including names, contact information, domain of responsibility, and affiliation.**

In-toto's [Maintainer list](https://github.com/in-toto/in-toto/blob/develop/MAINTAINERS.txt) shows maintainers from Purdue University and New York University. Details below:

  Santiago Torres
    Email: santiagotorres@purdue.edu
    GitHub username: @SantiagoTorres

  Lukas Puehringer
    Email: lukas.puehringer@nyu.edu
    GitHub username: @lukpueh

  Justin Cappos
    Email: jcappos@nyu.edu
    GitHub username: @JustinCappos

  Marina Moore
    Email: mm9693@nyu.edu
    GitHub username: @mnm678

  Sebastien Awwad
    Email: sebastien.awwad@nyu.edu
    GitHub username: @awwad

  Aditya Sirish A Yelgundhalli
    Email: aditya.sirish@nyu.edu
    GitHub username: @adityasaky

In addition, in-toto has a very diverse [steering committe members](https://github.com/in-toto/community/blob/main/STEERING-COMMITTEE.md), including members from TestifySec, ControlPlane and Datadog.

- [x] **A number of active maintainers which is appropriate to the size and scope of the project.**

For the current cadence of changes in the project and backlog of work, the project has sufficient active maintainers to sustain its current and future momentum. Adopters I spoke to are all happy with either contributing to in-toto or getting support from the in-toto community.
 
- [x] **Document a complete maintainer lifecycle process (including roles, onboarding, offboarding, and emeritus status).**

The project maintains a description of different roles and their election process in its [community repository](https://github.com/in-toto/community)

- [x] **Demonstrate usage of the maintainer lifecycle with outcomes, either through the addition or replacement of maintainers as project events have required.**

Maintainers for subprojects have been managed by the ITSC and Sub-project maintainers as pull-requests to their corresponding MAINTAINERS.txt files (e.g., [[1, self nomination](https://github.com/in-toto/in-toto-rs/pull/89)],[[2, stepping down](https://github.com/in-toto/attestation/pull/406)],[[3, community nomination](https://github.com/in-toto/witness/pull/385)]).

- [x] **Project maintainers from at least 2 organizations that demonstrates survivability.**

As an minimal security specification / framework, the project does not have a high degree of feature additions in the project.  Effort comes on either the implementations, such as the Go implementation (used by tools like Trivy and Tekton), the Python reference implementation (used by Datadog), the Java implementation (used by the Jenkins plugin and Rabobank), and the specification (where all implementations coordinate for interoperability).

Since reaching the incubation stage, the project has switched its governance model to use a steering committee. The first in-toto Steering Committee (ITSC) was voted on by the in-toto community and comprises five members from organizations spanning industry and academia. The ITSC has oversight over all in-toto sub-projects such as the specification, the Attestation Framework, and implementations maintained by the community written in Python, Go, Java, and Rust. Each sub-project has its own set of maintainers recorded in a CODEOWNERS or MAINTAINERS file in its repository. Across sub-projects, the project has contributors from a diverse set of organizations like Google, Kusari, New York University, Purdue University, Verizon, Intel, and TestifySec.

The current ITSC comprises of the following
- Santiago Torres-Arias (Purdue University)
- Justin Cappos (New York University)
- Jack Kelly (Control Plane)
- Cole Kennedy (TestifySec)
- Trishank Karthik Kuppusamy (Datadog)

- [X] **Code and Doc ownership in Github and elsewhere matches documented governance roles.**

On Jan 7, 2025, Justin Cappos walk through this with me during a screen sharing session where he confirmed that code and doc ownership in Github are assigned properly.

- [X] **Document agreement that project will adopt CNCF Code of Conduct.**

The project has CNCF CoC [recorded](https://github.com/in-toto/community/blob/main/CODE-OF-CONDUCT.md), which says "The in-toto community abides by the Cloud Native Computing Foundation's code of conduct."

- [X] **CNCF Code of Conduct is cross-linked from other governance documents.**

The CoC and the assertion of adherence is referenced in the [GOVERNANCE.md](https://github.com/in-toto/community/blob/main/GOVERNANCE.md#code-of-conduct).

- [X] **All subprojects, if any, are listed.**

Subprojects are listed in the [README.md](https://github.com/in-toto/community/blob/main/README.md#subprojects) file of in-toto/community.

- [X] **If the project has subprojects: subproject leadership, contribution, maturity status documented, including add/remove process.**

Subproject leadership is encoded in a subproject-level MAINTAINERS.txt file (e.g., [in-toto-rs](https://github.com/in-toto/in-toto-rs/blob/master/MAINTAINERS.txt)). Sub-project maturity is encoded in the project's README.md file (e.g., [in-toto-rs](https://github.com/in-toto/in-toto-rs/blob/master/README.md)). Add/remove processes are handled by the in-toto steering committee as described [here](https://github.com/in-toto/community/blob/main/GOVERNANCE.md#onboarding-and-offboarding-all-roles).

## Contributors and Community

Governance Review from TAG Contributor Strategy is performed in Oct 2024. 

The team rated the review as "Mostly Satisfactory". The steering committee style governance is perceived favorable, along with the project's transparency in different areas such as public documentation, record, and communications. Refer to the [full review](https://github.com/cncf/tag-contributor-strategy/pull/740/files) for details.

### Suggested

- [X] **Contributor ladder with multiple roles for contributors.**

The contributor ladder is encoded in the [GOVERNANCE.md document](https://github.com/in-toto/community/blob/main/GOVERNANCE.md)

### Required

- [X] **Clearly defined and discoverable process to submit issues or changes.**

A contribution guide is placed at the toplevel [community repository](https://github.com/in-toto/community/blob/main/CONTRIBUTING.md). A security disclosure process is encoded on the a separate [SECURITY.md](https://github.com/in-toto/in-toto/blob/develop/SECURITY.md) file.

- [X] **Project must have, and document, at least one public communications channel for users and/or contributors.**

Communication channels are encoded in the [website](https://in-toto.io/contact/). It contains a developer facing mailing list, a public mailng list, a slack join link, github and IRC contacts.

- [X] **List and document all project communication channels, including subprojects (mail list/slack/etc.).  List any non-public communications channels and what their special purpose is.**

Communication channels are encoded in the [website](https://in-toto.io/contact/). Non-public communication channels are described in in-toto's [security disclosure process](https://github.com/in-toto/in-toto/blob/develop/SECURITY.md).

- [X] **Up-to-date public meeting schedulers and/or integration with CNCF calendar.**

The in-toto community meetings are scheduled on the first friday of each month at 11AM et, and is displayed in the [CNCF public calendar](https://tockify.com/cncf.public.events/monthly?search=in-toto).

- [X] **Documentation of how to contribute, with increasing detail as the project matures.**

A contribution guide is placed at the top level [community repository](https://github.com/in-toto/community/blob/main/CONTRIBUTING.md)

- [X] **Demonstrate contributor activity and recruitment.**

Constant contributor activity observed on devstats, and based on community meeting notes, meetings are well attended. There has been recruitments at KubeCon and other conferences including but not limited to project booth, presenting a KubeCon NA keynote and other talks related to in-toto.

## Engineering Principles

- [X] **Document project goals and objectives that illustrate the project’s differentiation in the Cloud Native landscape as well as outlines how this project fulfills an outstanding need and/or solves a problem differently.**

One of the most pressing security problems in cloud native is software supply chain security.  in-toto  addresses this issue by providing a secure and trustworthy means for representing all the operations within the cloud-native pipeline and verifying that they were carried out to the letter.
A good way to understand the need for in-toto in the Cloud Native space is to understand the value of signed SBOMs vs in-toto metadata + layouts.  A signed SBOM indicates that some party (whose key you presumably have a reason to trust) states what the software contains.  In contrast, in-toto will have signed information about the individual steps of the supply chain cryptographically linking metadata together from various parties and validating this all against the software’s policies.  As a result, their protection modes would work quite differently in many cases.  For example, see the following table:


| Attack scenario |   Signed SBOM Result | In-toto layout + metadata result |
|-----------------|----------------------|----------------------------------|
| Software manipulated after software supply chain completed | Detect and reject the malicious software | Detect and reject the malicious software |
| Attacker compromises VCS and inserts malicious (unsigned) code where signatures are required  |Undetected.  User compromised. | Detect and reject the malicious software |
| Attacker substitutes a malicious dependency (not signed by that dependeny’s maintainer) |Undetected.  User compromised. | Detect and reject the malicious software 
| Attacker provides files to the build system which did not come from the VCS | Undetected.  User compromised | Detect and reject the malicious software |
| Attacker containerizes / packages binaries other than the ones the build system built | Undetected.  User compromised | Detect and reject the malicious software |
| Tests are not run on the software but it is (accidentally?) released to production | Undetected.  User compromised | Detect and reject the malicious software |
| The legal team has not reviewed source code licenses for included libraries | Undetected.  Impact varies | Detect and reject the software |

One important thing to note about the table above is that it isn’t impossible for someone to do many of these steps and checks before signing an SBOM.  If you did all of these checks, and signed the statements saying you did them to provide stronger validation, and distributed the root of trust for your signatures in a secure way, and managed situations where signing keys need to be revoked / rotated / expired, and handled trust delegation to different parties, and linked metadata between steps together, and let people write policies to reason about those steps, and let them link metadata in from dependencies to do so, and handled all of the above in scenarios where insiders can be maliciously interfering with your, system, then you would effectively reconstruct in-toto.
We are aware of some efforts, like the Zephyr project, where project members have worked to try to reconstruct some of the guarantees of in-toto and decided to live with the gaps in their security for other portions.  For groups that have done this work already this does make sense to us as a viable alternative in the short term.  However, we do believe that using a common, holistic approach like in-toto will be necessary as projects continually add the missing security pieces from in-toto and want to reason more and more about each other as dependencies.

Note that in-toto is not a substitute for having appropriately secure steps in the software supply chain.  For example, if you use an insecure process of building software that just curls and builds software from a website, in-toto will happily sign metadata indicating that you did the same insecure action indicated you would.  

This is why projects like SLSA and FRSCA are built as an opinionated set of steps on top of in-toto.  They specify which actions they feel are more important for software supply chain security and mandate their use.  

These projects are solving different problems at different levels.  In-toto allows you to capture information about your steps, ensure policies about them are applied, handle trust of keys, etc.  Frameworks like SLSA and FRSCA use in-toto as a mechanism to capture and enforce a specific set of policies that result in more secure supply chains.  

- [X] **Document what the project does, and why it does it - including viable cloud native use cases.**

https://in-toto.io/in-toto/ & https://github.com/in-toto/friends explain well what the project does and many integrations with other projects in the ecosystem.

- [X] **Document and maintain a public roadmap or other forward looking planning document or tracking mechanism.**

Roadmap for project with pointers to subproject ROADMAPs are encoded in a [ROADMAP.md file](https://github.com/in-toto/community/blob/main/ROADMAP.md)

- [X] **Roadmap change process is documented.**

Roadmap text [current roadmap](https://github.com/in-toto/community/tree/main/ROADMAP.md) outlines how and when the community-wide rodamap is updated (usually once a year). Each sub-project may also have their own ROADMAP that aligns to subproject-wide SLAs

- [X] **Document overview of project architecture and software design that demonstrates viable cloud native use cases, as part of the project's documentation.**

The [friends](https://github.com/in-toto/friends) repository outlines how Cloud-native applications and integrations use in-toto and how the in-toto architecture aligns with its goals. Further, in-toto is published as a [peer-reviewed paper](https://www.usenix.org/conference/usenixsecurity19/presentation/torres-arias) which outlines how it can be used in cloud-native CI/CD platforms, as well as social coding platforms and distributed buildsystems.

- [X] **Document the project's release process and guidelines publicly in a RELEASES.md or equivalent file that defines:** 

  - [X] Release expectations (scheduled or based on feature implementation)
  - [X] Tagging as stable, unstable, and security related releases
  - [X] Information on branch and tag strategies
  - [X] Branch and platform support and length of support
  - [X] Artifacts included in the release.
  - Additional information on topics such as LTS and edge releases are optional. Release expectations are a social contract between the project and its end users and hence changes to these should be well thought out, discussed, socialized and as necessary agreed upon by project leadership before getting rolled out.

in-toto has multiple implementations with varied release cadences depending on the involved stakeholders. For example, the Python implementation offers a feature-stable offering, which focuses on releasing bug-fix releases, whereas the golang implementation provides a "sandbox" for new and experimental features. As such, each subproject manages their own release cadence.

All implementations follow semver to communicate their feature support, as well as backwards and forwards compatiblity.

- [x] **History of regular, quality releases.**

A history of releases is [kept on our changelog](https://github.com/in-toto/in-toto/blob/develop/CHANGELOG.md)

## Security

Note: this section may be augemented by a joint-assessment performed by TAG Security.

### Suggested

- [X] **Achieving OpenSSF Best Practices silver or gold badge.**

[in-toto achieves a gold OpenSSF Best Practice badge](https://www.bestpractices.dev/en/projects/1523?criteria_level=2)

### Required

- [X] **Clearly defined and discoverable process to report security issues.**

Repositories describe the disclosure process using a [SECURITY.md file](https://github.com/in-toto/in-toto/blob/develop/SECURITY.md)


- [X] **Enforcing Access Control Rules to secure the code base against attacks (Example: two factor authentication enforcement, and/or use of ACL tools.)**

GitHub teams are used to provide granular access to different repositories within the organization. Protected branches are used to avoid pushes to master. Dependabot, and secret scanning is also added to all implementation repositories.

- [X] **Document assignment of security response roles and how reports are handled.**

Disclosure is handled by the ITSC. In addition, GitHub private vulnerability reporting is used (and has been successfully used before) to handle disclosures on implementations.

- [X] **Document Security Self-Assessment.**

in-toto was the [first project to carry out a security self-assessment](https://github.com/cncf/tag-security/commit/06b71c4db99ba07107cba6cf8f6fc6d4461fce82) with TAG security, and aided in developing the current process.

- [X] **Third Party Security Review.**

See the in-toto [Security Audit ‘23](https://in-toto.io/security-audit-23/).

- [X] **Achieve the Open Source Security Foundation (OpenSSF) Best Practices passing badge.**

The in-toto project has a [Gold CII (now OpenSSF) Best Practices Badge](https://bestpractices.coreinfrastructure.org/en/projects/1523?criteria_level=2).  As of 31st of July, 2023, there are only 23 projects in the world to have such a distinction.  The only other CNCF project with a Gold Badge is the [TUF project (a graduated security project)](http://theupdateframework.io). 

According to the OpenSSF Best Practices website, the in-toto project received its initial OpenSSF Best Practices badge on January 5th, 2018.

## Ecosystem

### Suggested

N/A

### Required

- [X] **Publicly documented list of adopters, which may indicate their adoption level (dev/trialing, prod, etc.)**

Adoptions are documented in the [in-toto friends repository](https://github.com/in-toto/friends)

- [X] **Used in appropriate capacity by at least 3 independent + indirect/direct adopters, (these are not required to be in the publicly documented list of adopters)**

Many adopters and integrations are [documented](https://github.com/in-toto/friends).

The project provided the TOC with a list of adopters for verification of use of the project at the level expected, i.e. production use for graduation, dev/test for incubation.

- [X] **TOC verification of adopters.**

Refer to the Adoption portion of this document.

- [X] **Clearly documented integrations and/or compatibility with other CNCF projects as well as non-CNCF projects.**

Many integrations are [documented](https://github.com/in-toto/friends?tab=readme-ov-file#project-integrations).

#### Adoption

##### Adopter 1 - Lockheed Martins/Aerospace and defense company

This adopter interview is performed in Sept 2024 and recorded a very happy adopter who also contributes to the in-toto project. Refer to the [interview summary](in-toto-adopter-interview-lockheedmartins.md) for more details.

##### Adopter 2 - GitHub/Software company

This adopter interview is performed in Oct 2024 and recorded a very happy adopter who has great expereience interacting with the in-toto community. Refer to the [interview summary](in-toto-adopter-interview-github.md) for more details.

##### Adopter 3 - Chainguard/Software company

This adopter interview is performed in Dec 2024 and recorded a very happy adopter who has great expereience interacting with the in-toto community. Refer to the [interview summary](in-toto-adopter-interview-chainguard.md) for more details.