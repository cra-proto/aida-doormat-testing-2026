# AIDA doormat testing

*description of the project*

**Timeframe** 2026-05-26 - 2026-09-01

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/aida-doormat-testing-2026](https://cra-test-arc.canada.ca/aida-doormat-testing-2026)

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

**Updated:**  2026-06-09

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Income tax)
    node4(Trust income tax)
    node5(Trust income tax return)
    node6(GST/HST for businesses)
    node7(Savings and pension plans)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node2 --> node6
    node2 --> node7
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/services/taxes/income-tax.html" _blank
    click node4 "https://www.canada.ca/en/services/taxes/income-tax/trust-income-tax.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/tax/trust-administrators/t3-return.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses.html" _blank
    click node7 "https://www.canada.ca/en/services/taxes/savings-and-pension-plans.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node2,node3,node5,node6,node7 inscope
```
