# HBP project

*description of the project*

**Timeframe** 2026-05-28 - 2026-09-03

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/annes-project-2026](https://cra-test-arc.canada.ca/annes-project-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-06-11

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Savings and pension plans)
    node4(RRSPs and related plans)
    node5(The Home Buyers' Plan)
    node6(How to participate in the Home Buyers' Plan)
    node7(How to make withdrawals from your RRSPs under the Home Buyers' Plan)
    node8(How to repay the amounts withdrawn from your RRSPs under the Home Buyers' Plan)
    node9(How to report Home Buyers' Plan repayments on your income tax and benefit return)
    node10(How to cancel a participation in the Home Buyers’ Plan)
    node11(The Home Buyers' Plan #40;HBP#41;: Understanding eligibility and withdrawals)
    node12(Definitions for Home Buyers' Plan)
    node13(Making withdrawals)
    node14(Home Buyers' Plan & Lifelong Learning Plan withdrawals)
    node15(Digital services)
    node16(Digital services for individuals)
    node17(Sign in to your CRA account)
    node18(Income tax)
    node19(Personal income tax)
    node20(Claiming deductions, credits, and expenses)
    node21(All deductions, credits and expenses - Personal income tax)
    node22(Home buyers' amount – Personal income tax)
    node23(Canada Revenue Agency #40;CRA#41;)
    node24(CRA Newsroom)
    node25(Tax tips - 2024)
    node26(Are you a first-time home buyer? Do you know there are tax incentives that could help you purchase your first home?)
    node27(Forms and publications - CRA)
    node28(Canada Revenue Agency forms listed by number)
    node29(T1036 Home Buyers' Plan #40;HBP#41; - Request to Withdraw Funds from an RRSP)
    node30(RC471 Home Buyers' Plan #40;HBP#41; - Cancellation)
    node31(Federal government budgets)
    node32(Budget 2022 – A Plan to Grow Our Economy and Make Life More Affordable)
    node33(First-Time Home Buyers’ Tax Credit #40;HBTC#41;)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node5 --> node6
    node5 --> node7
    node5 --> node8
    node5 --> node9
    node5 --> node10
    node5 --> node11
    node5 --x node12
    node4 --x node13
    node13 --> node14
    node2 --x node15
    node15 --> node16
    node16 --> node17
    node2 --> node18
    node18 --> node19
    node19 --> node20
    node20 --> node21
    node21 --> node22
    node1 --x node23
    node23 --> node24
    node24 --x node25
    node24 --x node26
    node23 --> node27
    node27 --> node28
    node28 --> node29
    node28 --> node30
    node23 --x node31
    node31 --> node32
    node32 --> node33
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/services/taxes/savings-and-pension-plans.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/what-home-buyers-plan.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/what-home-buyers-plan/participate-home-buyers-plan.html" _blank
    click node7 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/what-home-buyers-plan/withdraw-funds-rrsp-s-under-home-buyers-plan.html" _blank
    click node8 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/what-home-buyers-plan/repay-funds-withdrawn-rrsp-s-under-home-buyers-plan.html" _blank
    click node9 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/what-home-buyers-plan/report-repayments-on-your-income-tax-benefit-return.html" _blank
    click node10 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/what-home-buyers-plan/cancel-participation-home-buyers-plan.html" _blank
    click node11 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/what-home-buyers-plan/avoid-common-home-buyers-plan-mistakes.html" _blank
    click node12 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/what-home-buyers-plan/definitions-home-buyer-s-plan.html" _blank
    click node13 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/making-withdrawals.html" _blank
    click node14 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/rrsps-related-plans/making-withdrawals/home-buyers-plan-lifelong-learning-plan-withdrawals.html" _blank
    click node15 "https://www.canada.ca/en/revenue-agency/services/e-services.html" _blank
    click node16 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals.html" _blank
    click node17 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals.html" _blank
    click node18 "https://www.canada.ca/en/services/taxes/income-tax.html" _blank
    click node19 "https://www.canada.ca/en/services/taxes/income-tax/personal-income-tax.html" _blank
    click node20 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/about-your-tax-return/tax-return/completing-a-tax-return/deductions-credits-expenses.html" _blank
    click node21 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/about-your-tax-return/tax-return/completing-a-tax-return/deductions-credits-expenses/deductions-credits-expenses.html" _blank
    click node22 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/topics/about-your-tax-return/tax-return/completing-a-tax-return/deductions-credits-expenses/line-31270-home-buyers-amount.html" _blank
    click node23 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node24 "https://www.canada.ca/en/revenue-agency/news/newsroom.html" _blank
    click node25 "https://www.canada.ca/en/revenue-agency/news/newsroom/tax-tips/tax-tips-2024.html" _blank
    click node26 "https://www.canada.ca/en/revenue-agency/news/newsroom/tax-tips/tax-tips-2023/first-time-home-buyer-tax-incentives.html" _blank
    click node27 "https://www.canada.ca/en/revenue-agency/services/forms-publications.html" _blank
    click node28 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms.html" _blank
    click node29 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms/t1036.html" _blank
    click node30 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms/rc471.html" _blank
    click node31 "https://www.canada.ca/en/revenue-agency/programs/about-canada-revenue-agency-cra/federal-government-budgets.html" _blank
    click node32 "https://www.canada.ca/en/revenue-agency/programs/about-canada-revenue-agency-cra/federal-government-budgets/budget-2022-plan-grow-economy-make-life-more-affordable.html" _blank
    click node33 "https://www.canada.ca/en/revenue-agency/programs/about-canada-revenue-agency-cra/federal-government-budgets/budget-2022-plan-grow-economy-make-life-more-affordable/first-time-home-buyers-tax-credit.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5,node6,node7,node8,node9,node10,node11,node12,node14,node22,node26,node29,node30 inscope
```
