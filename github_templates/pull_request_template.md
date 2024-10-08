# NOT READY FOR REVIEW
- (Edit the above to reflect status)

# Summary
- TL;DR - what's this PR for?

# Review By (Date)
- When does this need to be reviewed by?

# Criticality
- How critical is this PR on a 1-10 scale? Also see [Severity Assessment](https://stanfordits.atlassian.net/browse/D8CORE-1705).
- E.g., it affects one site, or every site and product?

# Urgency
- How urgent is this? (Normal, High)

# Review Tasks

## Setup tasks and/or behavior to test

1. Check out this branch
2. Rebuild Cache and import config `drush cr ; drush ci`
3. Navigate to...
4. Verify...

### Site Configuration Sync

- Is there a config:export in this PR that changes the config sync directory?

## Front End Validation
If you need assistance with front end validation, please create a [QA request ticket](https://github.com/SU-SWS/template_warehouse/blob/master/jira_templates/QA_request_template.txt)

- [ ] **HTML validation**: Does all new functionality [pass HTML validation](https://validator.w3.org/nu/)?
- [ ] **Automated Accessibility testing**: Does all new functionality pass [Siteimprove Browser Extension](https://www.siteimprove.com/integrations/browser-extensions/)
- [ ] **Manual Accessibility testing**: Have you verified functionality using [Accessibility Evaluation Quick Checks](https://docs.google.com/document/d/1P3DcZzQ7UuHASNbBhuzoFq_bz4tNglajHYNpgvRBBTY/edit)?
- [ ] **Cross-browser testing**: Has [cross-browser testing](https://sws-devguide.stanford.edu/front-end/testing/cross-browser-testing) been performed?
- [ ] **Visual regression testing**: Has [automated visual regression testing](https://sws-devguide.stanford.edu//front-end/testing/automated-visual-regression-testing) been performed?

## Backend / Functional Validation
### Code
- [ ] Are the naming conventions following our standards?
- [ ] Does the code have sufficient inline comments?
- [ ] Is there anything in this code that would be hidden or hard to discover through the UI?
- [ ] Are there any [code smells](https://blog.codinghorror.com/code-smells/)?
- [ ] Are tests provided? eg (unit, behat, or codeception)

### Code security
- [ ] Are all [forms properly sanitized](https://www.drupal.org/docs/8/security/drupal-8-sanitizing-output)?
- [ ] Any obvious [security flaws or new areas for attack](https://www.drupal.org/docs/8/security)?

## General
- [ ] Is there anything included in this PR that is not related to the problem it is trying to solve?
- [ ] Is the approach to the problem appropriate?

# Affected Projects or Products
- Does this PR impact any particular projects, products, or modules?

# Associated Issues and/or People
- JIRA ticket(s)
- Other PRs
- Any other contextual information that might be helpful (e.g., description of a bug that this PR fixes, new functionality that it adds, etc.)
- Anyone who should be notified? (`@mention` them here)

# Resources
- Automated Accessibility Testing:
  - [Siteimprove Browser Extension](https://www.siteimprove.com/integrations/browser-extensions/)
  - [SWS Accessibility Testing Resources](https://sws-devguide.stanford.edu/front-end/testing/accessibility-testing/accessibility-testing-resources)
- Accessibility Scanning: [Siteimprove](https://siteimprove.stanford.edu/)
- Manual Accessibility Testing Script [SWS Accessibility Process and Checklist](https://docs.google.com/document/d/1ZXJ9RIUNXsS674ow9j3qJ2g1OAkCjmqMXl0Gs8XHEPQ/edit?usp=sharing)
- HTML Validation for one URL: [HTML Validator](https://validator.w3.org/)
- HTML Validation for multiple URLs: [Bulk W3C Validator](https://www.bulkseotools.com/bulk-w3c-validator.php)
- Crossbrowser Testing: [Browserstack](https://live.browserstack.com/dashboard) and link to [Browserstack Credentials](https://asconfluence.stanford.edu/confluence/display/SWS/External+Account+Credentials)
- Visual Regression Testing: [Diffy](https://diffy.website) and link to [Diffy Credentials](https://asconfluence.stanford.edu/confluence/display/SWS/External+Account+Credentials)
