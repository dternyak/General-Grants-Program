# Web3 Foundation Grants

## Project Overview

The goal of the Web3 Foundation Grants platform is multifold:
  * Systemize the existing grants process
  * Create a hub for community discussion & collaboration around proposals related to the grants program
  * Display a more consumable interface of the impacts of the grants program
  * **Set the groundwork for a future integration into the Polkadot/Kusama treasuries and provide a mechanism to acquire funding from the treasuries**


### Project Details 

The Grant.io platform, and Web3 Foundation Grants by extension, is made up of two primary components:  the user-facing application and the admin portal. The following specifications will be broken down based on the relevant component.
Platform specifications are best understood by interacting with the [available demo](https://grant-demo-frontend.herokuapp.com/).

#### User

The platform will provide a flow for users to publicly create, view, comment, and provide updates to proposals for grant funding for projects that improve the Web3 ecosystem.

Users will be able to:
- Create proposals that are linked to RFPs.
- Be notified (via email) whenever key events happen such as their proposals being approved or proposals they’ve made being funded.
- Dynamic Landing Page: Adding dynamic content to the landing page is a standard practice for creating “hooks” to drive exploration. The landing page will feature recent proposals and requests.
- Sign up: Users will be able to sign up for the grant system via email and password.
- Profile: Upon registration, each user will have a publicly viewable profile view where their public activity will be visible to themselves and the community.

#### Admin

- Able to review, approve, reject, and delete any proposals submitted.
- Able to approve proposals for “public review” where community members can provide feedback before the proposal is funded.
- Able to post public bounties / requests for proposals.
- Responsible for making payments to proposals that are approved to be posted on the platform.
- Responsible for sending payments outside of the platform, but will be able to update proposals once funding has been sent.
- Able to be notified whenever key events happen, such as proposal submissions, proposals reaching funding, or milestone payout requests.
- Provide tools for spam mitigation, such as basic admin functions (approving / deleting / banning users, comments & proposals).
- Will have access to an audit trail of administrator actions taken on the platform.
- Will have 2FA secured authorization.


### Deliverables
#### Web3 Foundation Grants Codebase
The platform for grant funding that meets the specifications listed above.

#### Documentation
We will document to the best of our abilities how the platform works.

#### Hosting Environment/Credentials
We will provide hosting credentials to a fully set up environment of Web3 Foundation Grants.


## Team

### Team members
* Daniel Ternyak

### Team Website	
* https://grant.io

### Legal Structure 
Grant.io Inc.

### Team's experience
We've developed the grant systems for [Zcash](https://grants.zfnd.org/) and [Urbit][https://grants.urbit.org/], among others.


### Team Code Repos
There are several Grant platforms based on the Grant.io codebase
* https://github.com/urbit/grants
* https://github.com/zcashfoundation/zcash-grant-system/

### Team LinkedIn Profiles
* https://www.linkedin.com/dternyak

## Development Roadmap

### Overview
* **Total Estimated Duration:** 2 Months
* **Total Costs:** $30,000

### Milestone 1 — Grants Platform Staging
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** $15,000

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | MIT |
| 0b. | Environment | We'll setup a working staging environment for the platform for the Web3 Foundation review. |
| 0c. | Platform | We'll white-label our base platform to match Web3 Foundation brand identity. | 


### Milestone 2 — Grants Platform Production
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** $15,000

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | MIT |
| 0b. | Changes per review | We'll implement changes to the platform based on review. These are limited to slight design / copy changes. Functionality that is desired beyond the scope of the base platform will be developed in a separate grant. |
| 0c. | Platform | We'll assist the Web3 Foundation team in the relevant steps to bring the platform to production, including DNS/Email setup & other relevant setup | 


