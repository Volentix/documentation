# Lifecycle Of A Feature

Partners within the Volentix ecosystem are expected to follow a general baseline best practices for adding features into the products they are creating/maintaining on behalf of the Volentix Foundation. The following describes these best practices.

  * [Sem Versioning](#sem-versioning)
  * [Before You Begin](#before-you-begin)
  * [Request For Comments (RFC)](#request-for-comments-rfc)
  * [Security Audit](#security-audit)
  * [Documentation](#documentation)
  * [Blog for Marketing](#blog-for-marketing)
  * [Governance Review](#governance-review)
  * [Release](#release)

## Sem Versioning

Volentix has adopted the [standard semantic versioning found here](https://semver.org/). In short, sem versioning has the following rules:

- **MAJOR:** Applied to a new version where the API is incompatable with the previous version. Additionally, version 1.0.0 can be considered the first stable version.
- **MINOR:** Applied when a new feature is introduced that does not break the API.
- **PATCH:** Bug fixes, cosmetic features, and backwards compatability.

In general, this document only applies to the **MAJOR** and **MINOR** versions as patches require less formalities.

## Before You Begin

Please read the [contributing guidelines](https://github.com/Volentix/documentation/blob/master/.github/CONTRIBUTING.md) for a more detailed description of the workflow required for new feature integration into the code base. Processes such as code reviews and clean builds are to be followed within the workflow, and, as such, are not defined here.

Additionally, note that `solution owner` is assigned to each project who acts on behalf of the community to ensure that the integrity of the product remains intacts and that all the processes and external dependancies are managed accordingly.

## Request For Comments (RFC)

RFC's are considered to be at the discression of the project owner. They are to be used when a new feature has impacts on architecture, api's, security, or other such high level concerns. Additional facets such as UX or solution workflows may also be of consideration.

Once the decision to leverage an RFC has been taken, project owners will co-ordintate the effort between the original submitter, team members, and members of the community. The RFC will require documenation that must be provided in a free and open manner through the documenation (readthedocs) stucture embedded into the project. The process of updating the documenation, the team will still be required to follow the same processes and standards as general development.

At a minimum, the RFC will require:
1. **Description:** Provide a description of the change being requested.
2. **Background:** Provide an background on why the feature is being requested.
3. **Risk analysis:** Detailed risk assesment and potential solutions to the risk.
4. **Feasibility:** Is this something that can be accomplished.
5. **Security:** In addition to the risk analysis, an deeper level of the impact to security must be identified.
6. **Estimate:** In addition to a general feasability analysis, which has more to do with technical complexity, an estimated level of effort must also be identified.
7. **Sudo Code:** In some cases, sudo code may also be provided, however, this is based on the nature of the change and is not considered mandatory.

## Security Audit

Once the change has been implemented, but before the release, the team must perform a security audit. The depth and nature of this audit is based on if the feature is **MAJOR** or **MINOR**. In the case of **MAJOR** changes, the team wil need to perform a full audit of all features and dependencies. **MINOR** changes will require that the team performs an audit, and code review, on the code that has changed and the components that are impacted.

Additionally, teams will be required to publish, within the repository, the executive level results of the audit. This means the overall summary, etc. Lower level details, particularily and security concerns that are exposes, will be shared with the Governance team in order to co-ordinate the process. Once the security concern has been overcome, the governance team will choose what information should be published to the public as a whole.

## Documentation

It is not enough to code a feature but tell no one how to use the feature or integrate it. As a result, before the release, all documenation, in all forms, must be updated or created with the relivant level to ensure that the community can use the feature. Note that this is pretty broad due to the amount of assets in the eco-system. For example, changes to Verto will require different levels as well as approaches to documentation that are different than the needs of VDex potentially. As a result, the teams will need to work with the solution owner in defining, for their community, the appropriate level of documenation required.

## Blog for Marketing

In addition to the updates in documenation, the team will need to produce content for the marketing team that can be leveraged to make more digestable content of the community at large. In general, the documenation will cover the **how** details of the new feature while the marketing material will cover the **why** of the feature.

The responsibility to ensure that the marketing team gets what they want is the solution owner. Additionally, the solution owner will be responsible, should it be required, the realease of the feature in concert with the release of the marketing material. In practical terms, the solution owner should begin coordination early (potentially at the Request for Comment phase) in order to ensure a smooth and quick release avoiding latency at all cost.

The process for releasing content (shared directory) will be managed in concert with the marketing team during the onboarding process.

## Governance Review

For each project, a 'solution owner' will be selected that represents the interests of the ecosystem and is considered to be someone outside of the projects development team. This solution owner will be required to ensure the process, defined above, has been followed and the integrity of the product is retained. In short, the solution owner works with the development to make the final go/nogo decision on releasing the feature.

## Release

Once the above has been completed, the new feature will be released.
