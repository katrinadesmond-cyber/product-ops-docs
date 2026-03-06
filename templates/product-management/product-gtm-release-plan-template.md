# Product GTM Release Plan Template

> Converted from Confluence export to Markdown.
> Fill in placeholders and adapt sections to your product context.

This template helps Product Managers and teams manage the technical release, coordinate internal communications, and prepare external messaging. It outlines key tasks, timelines, and responsibilities to ensure that all teams are aligned for a successful product release.

|  |  |
| --- | --- |
| Target Release Date |  |
| Epic(s) |  |
| Document Owner |  |

## Type of Product Release

This classification helps in understanding the extent of changes being introduced, ranging from significant new features and improvements (major) to smaller updates and fixes (minor) or critical patches (micro). *[By specifying the release type, this section provides clarity on the release’s scale and the necessary planning, testing, and communication efforts required for a successful deployment.]*

| Type | Example | Select |
| --- | --- | --- |
| P1 | - These represent our biggest announcements and present the greatest opportunities for attracting new customers |  |
| P2 | - New solutions to existing problems, that are most valuable to existing customers |  |
| P3 | - Quality of Life improvements to fill the gap in our product or low-hanging fruit to improve the product. Impactful small changes that existing users have been asking for |  |
| P4 | - Bug fixes and small changes in the product to make the user experience even better |  |

## About the Release Change

Outline details of new features, improvements, bug fixes, and/or any changes that users should be aware of. *[This section helps ensure that stakeholders, users, and team members understand what to expect, how it will affect their experience, and the benefits of the updates. Include links to the source material including GTM artefacts]*

## Product Details

| **Product/ Feature** | **How is this affecting our customers and/or support** |
| --- | --- |
| - Ad serving change - schema migration required | e.g. |
| - Activation Optimisation change - Web UI change - Campaign management API(s) change | no ui changes |
| - Citrus admin change |  |
| - Reporting changes | in big query, fact\_realised\_ad\_agg has the new match types  Advanced reporting has a new keyword match type reporting dashboard however there are limitations - [see FAQs](https://citrusad.atlassian.net/wiki/spaces/CORE/pages/3983441988/Feature+Behaviour+-+Close+Exact+Match#:~:text=Is%20the%20keyword%20match%20type%20advanced%20reporting%20dash%20enabled%20for%20all%20environments%3F) |
| - Customer process and behaviour change | Advertisers will need to use exact negatives to ensure they do not target keywords they do not want to target.  Customers will be checking the keyword performance via reporting |
| Which of the Gs   - Gread - Grecord - Gstat - Gaconf - Gator - Gobblin - Gateway |  |

## How Is It Enabled?

|  |  |
| --- | --- |
|  |  |
|  |  |

## Useful Insights for PlatOps

| **Epic** | **Summary** | **Potential problem areas** | **Chance of P1 or P2** |
| --- | --- | --- | --- |
|  |  |  |  |
|  |  |  |  |

## Release Plan

Outline all the essential activities needed to confidently deploy code into production.
*[It ensures that all technical, operational, and strategic aspects are addressed.]*

| Milestone date | **Activity** | **Owner(s)** | **Open / Closed** |
| --- | --- | --- | --- |
|  | The Releasable build completed   - solution has been found and is ready to launch - feature flags are ready (where required) | PM |  |
|  | Feature flag documentation   - enable / disable    - add to knowledge articles | TL |  |
|  | [Nominate the hyper care support member(s)](https://citrusad.atlassian.net/wiki/spaces/PO1/pages/edit-v2/4162584578#Hyper-Care-%2F-Support-Plan) | TL  Delivery manager |  |
|  | Training - Knowledge articles and support articles are completed | PM  TL |  |
|  | Training - knowledge transfer for   - Plat ops - Global Customer Support (GCS) | PM  TL |  |
|  | Prep for Pre environment release   - UAT scrips prepared | PM  QA |  |
|  | Approval   - Feature release ceremony with release manager and platops to get approval to move to pre environment - as at 16 Sep 2024 this is the fortnightly `feature release` meeting run by Jess | PM  TL  DM |  |
|  | Pre environment   - Feature - UAT sent to CIEs to be completed | PM  Release Manager |  |

## Rollback Strategy

Outlines the procedures and protocols for reverting to a previous version of the product in case of critical issues or failures during deployment.

| Rollback Strategy |  |
| --- | --- |
| Conduct a risk assessment to identify potential impacts on users and other parts of the platform |  |
| Define rollback procedures in case the release needs to be reverted |  |

## UAT Testing

Outline the UAT procedures, criteria, and feedback mechanisms in coordination with QA. Work with CIEs to determine who is executing to helps ensure the product is ready for launch and delivers a positive user experience.

|  |  | **pass fail** |  |
| --- | --- | --- | --- |
| Test success criteria |  |  |  |
| Test steps |  |  |  |
| **Tester** |  |  |  |
|  |  |  |  |
|  |  |  |  |

## Hypercare / Support Plan

Outlines the support framework and strategies for providing enhanced assistance immediately following the product launch. This plan includes dedicated resources, monitoring processes, and escalation procedures to address any issues or concerns that arise during the initial post-launch period.

| Hyper Care / Support plan |  |  |
| --- | --- | --- |
| Who |  |  |
| Recommended reaction | turn off? roll back? fix forward? |  |
| Escalation plan from launch plan |  |  |
| How long will hypercare run for  (weeks and days) |  |  |

## Key GTM Artifacts

| Section | Artefact Name | Links |
| --- | --- | --- |
| Support area documentation and training |  |  |
| Risk Management and Contingency Planning |  |  |
| GTM Strategy plan |  |  |
| GTM Launch plan |  |  |

## Review and Final Go/No-Go Decision

| Checklist | Status (Y/N) |
| --- | --- |
| Release management happy |  |
| Sam happy |  |
| Product happy |  |
| Engineering happy |  |
