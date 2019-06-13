# Partner Onboarding

This document outlines the process for onboarding a parnter into the Volentix ecosystem.

  * [Documenation Strategy](#documenation-strategy)
  * [Definition Of Responsibilities](#definition-of-responsibilities)
  * [Community Communication Strategy](#community-communication-strategy)
    + [Introductory Video](#introductory-video)
    + [Messaging](#messaging)
    + [Volentix Developer Update](#volentix-developer-update)
  * [Escalation](#escalation)
  * [Internal Communication](#internal-communication)
    + [Daily Standup](#daily-standup)
    + [Marketing Standup](#marketing-standup)
    + [Bi-weekly Review](#bi-weekly-review)
    + [Bi-weekly Planning](#bi-weekly-planning)
    + [Governance Committee Review](#governance-committee-review)
    + [Steering Committee Review](#steering-committee-review)
    + [Steering Committee Planning](#steering-committee-planning)
  * [Tools](#tools)
  * [Reports](#reports)

## Documenation Strategy

Organization managing repos must adhere to the general patterns and principles for the management of documenation within their repo.

All repos have the following documenation:

1. ReadTheDocs: Any documenation about the product, such as its architecture, or features, will be documented on the `docs` folder. ReadTheDocs listens to this folder and will automatically generate the website. For example, the current docuemation for this repo can be found [here](https://volentixdocumenation.readthedocs.io/en/latest/)
2. README.md: Adds  generic desciption based on the [Standard Read Me](https://github.com/RichardLitt/standard-readme).
3. .github/CONTRIBUTING.md: Although this repo has the general CONTRIBUTING.md doc, however, repos may extend the CONTRIBUTING.md file for their own purpose.
4. Github Issues: For the management of issues, features, and pull requests.

## Definition Of Responsibilities

A simple document outlining who, from a high level, is responsible for what. Note that a simple table with the following headers is considered adequate:
1. Responsibility Title: A title that describes the responsiblity.
2. Description: A short description of the responsibilty.
3. Owner: Who owns the responsibility.

This responsibility table will be found within the individual repos.

## Community Communication Strategy
The following outlines the way in which the teams .will work together in order to provide mechanics for the communication with the larger community.

### Introductory Video

The team will create a video introducing each other and making the handoff officially. This video will talk about backgrounds and should also include talk about the V1 roadmap, its intent, features, timeline, and outcome.

### Messaging

The team can determine what platform they prefer (Discord, Telegram, etc), and may change it over time, however, regardeless of the decision, it will be documented in the ‘.github/CONTRIBUTING.md’ file. Additionally, the channel itself will need to be owned by the Foundation in case the repo requires transfer to another organization, however, the organization responsible for the repo will have full admin writes to the tool.

### Volentix Developer Update

VDU's are short form videos to be produced, at a minimum, once a week. The videos are two mins in duration and are intentionally designed to support low budget design.

When the organization is onboarded, they will be provided with a location to upload the file and a list of team members to inform of the upload on the Volentix marketing team.

## Escalation

Things happen, and/or are forgotten. In these cases a clear escalation process needs to be defined. The following defines the escalation strategy for the team. Note that escalation is considered anything that is urgent or critical. In general all escalations are managed by the first tier, and must go through them in all cases, however, the additional tiers exist in case the other tiers are not responding.

Note that, for all intensive purposes, the first tier will be the only tier required for escalation. It should not be common practice to leverage the other tiers.

Finally, all escalations have a maximum response time of 24hrs. This means that communication has been established not that the problem has been fixed. If an issue has no response in 24hrs then the second tier is contacted.

Finally, you are not bound to any one channel for escalation. For example, the email address is fine, however, if you have a Discord group and prefer it then feel free to escalate that way.

## Internal Communication
This section outlines the way in which the SPS and VLabs teams will communicate internally. Note that this is different than escalation in that these are more business as usual practices rather than an identified issue.

Note that all the ceremonies listed below will require scheduled commitments by all team members.

### Daily Standup
*Purpose:* Daily communication on status and escalation
Frequency: Monday to Friday daily.
Duration: 15 mins

### Marketing Standup
*Purpose:* Daily communication on status and escalation
Frequency: Monday to Friday daily.
Duration: 15 mins

### Bi-weekly Review
*Purpose:* Review the work completed on the product every 2 weeks. This is based on the bi-weekly planning session.
Frequency:  2 weeks.
Duration: 30 Mins

### Bi-weekly Planning
*Purpose:* Planning for the next 2 weeks. This includes backlog grooming and prioritization of both features and architectural stories. Note that this meeting can occur immediately after the review meeting.
Frequency:  2 weeks
Duration: 60 mins

### Governance Committee Review
*Purpose:* Ensure that the organization remains compliant within the Volentix Ecosystems guidance policies.
Frequency:  1 - 3 months.
Duration: 60 mins

### Steering Committee Review
*Purpose:* Review progress and alignment with redefined business objectives. Review financials. Review Community growth. Review Escalation, and takes the input from the Governance Committee Review.
Frequency:  1 - 3 months.
Duration: 60 mins

### Steering Committee Planning
*Purpose:* Define business objectives. Define Community growth strategy and identify objectives. Define roadmap & features for the period. Note that this can be part of the Steering Committee Review ceremony. Note that it is a much longer ceremony and requires full attendance by all team members.
Frequency:  1 - 3 months.
Duration: ½ - 1 day

## Tools

- *Discord:* Discord is the internal teams communication channel of preference. Note that the team channel is different than the community channel.
- *Zoom:* Used in ceremonies
- *Calendar:* Ceremonies will be calendar invites.
- *Email:* Email is fine if necessary.
- *Backlog:* At the time of writing, we will be leveraging GitHub's issue management project features. This is in the interest of transparency and ease of use. Additionally, many tools add plugins for Github projects that will allow 3rd party integration in the future.

## Reports
The team will be responsible for various reports on their respective project repository.

**Change Log**
At the root of all Volentix projects resides is the CHANGELOG.md file. This file is found in the root of the repo. This changelog follows the best practices defined by the Keep A Changelog website: https://keepachangelog.com/en/1.0.0/ 
Security Audit
The team will publish a rolling security audit. Note that the audit, before being made public, must go through Staider as they are responsible for all arbitrage of security risks.

**Continuous Integration**
The build must have a continuous integration mechanic that performs integrity constraints for each addition to the code base. This CI service will provide dashboards (reports) as visibility into the projects health.

**Financial Transparency**
It is premature, at the time of writing, to determine the exact mechanics of this.
