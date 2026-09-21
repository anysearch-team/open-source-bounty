# AnySearch Open Source Bounty Program

Registration deadline: 2026-10-31 23:59 UTC+8

Prize Pool: CNY 100,000, available until the prize pool is exhausted.

## Registration

Registration Link: [Click to register](https://forms.gle/i3azg6dATzCvYeED6)

The official campaign form is the only valid registration channel. Chat messages, Issues, emails, and other forms of communication do not constitute registration.

Purpose of Registration: Registration is used to establish the relationship between a developer or developer team (collectively, the “Developer”) and the target project. Registration does not constitute approval for a reward.

AnySearch will confirm receipt of the registration and notify the Developer whether the submission falls within the scope of the program and provide next steps as soon as possible.

## Eligible Projects

1. Official project list: Eligible target projects are limited to the [Bounty Project List](../bounty-projects.md) published by AnySearch.

2. One active Claim ID per repository: Only one Claim ID may be active for the same target repository at a time. During the claim period, only the developer who holds the claim may submit a valid PR. If the Claim ID expires, the next Developer in the queue may take over. The bounty will be awarded to the first Developer whose compliant PR is successfully merged.

3. Self-recommended projects: Developers may recommend qualifying open-source AI Agent projects through the official registration form. AnySearch will evaluate self-nominated projects, and eligible projects will be included in the project list for the next Open Source Bounty Program.

## Bounties

1. The total prize pool is CNY 100,000, available until exhausted.

2. When the remaining prize pool is insufficient, AnySearch will stop issuing new Claim IDs. Existing valid Claim IDs and their corresponding tasks will not be affected.

3. The bounty amount for each eligible project will be determined and announced in advance by AnySearch in [Bounty Project List](../bounty-projects.md). The bounty amount published with the program is final and will not be adjusted after the program is launched.

4. During the campaign, each individual may receive a maximum of 3 bounty payments, counted by actual payments made.

5. All bounties are pre-tax. Any payment processing fees, foreign exchange fees, or other payment-related costs are the responsibility of the Developer.

---

## Eligibility

1. Developers must comply with the applicable open-source license and project rules of the target project and provide valid payment information.

2. Developers must truthfully disclose their relationship with the target repository.

3. Developers must complete official registration before participating. The merged repository must match the target project registered in the application. Changing the target project requires a new registration.

4. The bounty will only be paid to the Developer associated with the corresponding Claim ID.

5. AnySearch employees and related parties are not eligible to participate and may not arrange for others to claim bounties on their behalf.

6. AnySearch may use information including GitHub accounts, code submissions, repository contributions, and payment information to determine whether related entities or fraudulent activity are involved.

## Participation Process

### 1. Registration

The Developer submits the registration form through the official campaign link. The registration establishes the relationship between the Developer and the target project and determines the Developer’s position in the registration queue for that project.

### 2. Registration Confirmation

AnySearch will confirm the registration application as soon as reasonably possible. Eligible registrations will receive a unique Claim ID by email, and the corresponding task will be locked for that Developer.

If multiple developers register for the same target project, they will enter a queue based on registration order. When the current Claim ID expires, the next Developer in line may take over.

Claim status will be communicated by email and displayed on the official campaign page.

### 3. PR and Merge

After receiving a Claim ID, the Developer must submit a Pull Request to the target project's official repository and work with the project maintainers to complete the integration.

After receiving a claim ID, developers must submit a valid PR within 7 calendar days and email the PR link to AnySearch. Otherwise, the claim will be considered forfeited.

### 4. Merge and Reward Application

After the AnySearch integration has been successfully merged into the target project's official repository, the Developer must submit proof of the merge by email.

### 5. Review and Payment

AnySearch will review the project eligibility, Claim ID ownership, authenticity of the merge, integration usability, and overall quality.

The review is solely for determining reward eligibility and will not re-evaluate or adjust the bounty amount already published for the target project in the official project list.

After approval and confirmation of payment information, payment will normally be initiated within 14 business days.

### 6. Claim Expiration

A Claim ID will expire and be passed to the next Developer in the queue if:

- No valid PR is submitted within 7 calendar days after the Claim ID is issued;

- The Developer voluntarily gives up the claim;

- The submitted work clearly fails to meet the program requirements;

- Other circumstances make the claim ineligible.

## What Qualifies for a Bounty?

At minimum, the integration must meet the following requirements:

1. Use a built-in API, MCP, Skill, or another integration method.
   (Built-in definition: merged into the main repository, distributed with the release package, or listed as a default integration in the project’s official documentation)
   
2. Developers must choose an integration method that meets the project’s requirements and complete the final Merge. Within the project’s framework, integrate as many of the following AnySearch search capabilities as possible:

   - General search capabilities, including anonymous search and parallel search

   - Vertical search capabilities

   - Extract capabilities for web page parsing
   
3. Submit a project development document in Markdown (.md) format to facilitate future maintenance.

> **Note:** If the target project's Maintainer rejects, closes, or fails to process the PR for an extended period of time, or if the original integration approach cannot proceed due to the project's technical architecture, maintenance status, or other circumstances, AnySearch will assess the situation and determine whether to preserve the claim, adjust the integration approach, extend the processing period, or reopen the task. If no compliant Merge is ultimately completed, no bounty payment obligation will arise.

---

## Additional Terms

Developers must not intentionally remove, disable, or replace an AnySearch integration after it has been merged.

If AnySearch determines that a Developer has engaged in collusive removal, fabricated merges, artificial Star manipulation, intellectual property infringement, unauthorized disclosure of confidential information, account splitting to circumvent bounty limits, self-dealing, or other fraudulent activities, AnySearch reserves the right to reclaim any bounty already paid and disqualify the Developer from future participation.

A rollback, refactor, replacement, or discontinuation of the integration independently decided by a project maintainer does not automatically constitute a violation by the Developer. AnySearch will assess such cases based on the circumstances.

For matters not specifically covered by these rules, AnySearch will make a determination based on the program terms, project list, and materials submitted by the Developer, and will provide the basis for its decision.

For any disputed or exceptional cases not covered by these rules, AnySearch reserves the right of final decision and interpretation.

If you have any questions, please contact mkt@anysearch.com
