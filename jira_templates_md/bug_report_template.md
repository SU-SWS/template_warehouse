This template provides guidelines for recording information about a bug. If a field or category is irrelevant, feel free to mark it N/A.

This template is located in the [SU-SWS/template_warehouse](https://github.com/SU-SWS/template_warehouse) on Github.
There's an associated Jira template at [Bug template example](https://stanfordits.atlassian.net/browse/TEMP-1)

Thank you for taking the time to create a bug report.

## Description
Give a clear and concise description of the bug.

* **Date**: 1/1/2025 
* **Time**: 
* **URL(s)**:
  * [URL]

**Severity assessment total**: **0**

Provide total from the list below.

### Screenshots/recordings
Add screenshots to help explain the problem.  To screenshot in Chrome: 
1. Cmd+Shift+I to open Developer Tools
2. Cmd+Shift+P and type "screenshot."


### To reproduce
Steps to reproduce the behavior:
1. Go to 
   1. [URL]
1. Click on '....'
1. Scroll down to '....'
1. See error

### Expected behavior
When implemented correctly, what do you expect to happen?
Give a clear and concise description.

#### Acceptance criteria
What are the criteria for closing this ticket?
* Have it reviewed by [person]
* Ensure it performs [functionality]
* Ensure it meets [standard]

### Suggestions for resolution
any tips, recommendations, LMGTFY URLs, that might help with a fix?


### Process improvement
* Is this bug due to something missing in our process?
* Is this an "Escaped bug"? That is, it was missed in testing and is now in production? Client reported?
* Can we improve our process to avoid this bug in the future?

### Severity assessment
This rubric helps the team assess the relative importance of this ticket. If the answer is *Yes* or *Maybe*, enter an appropriate value in that line of the table. When you're done, enter the total in the *Severity Assessment total* field above.

* _ pts__  Issue
* _____ Does this cause data loss? (+3 points)
* _____ Does this cause your site to go offline? (+5 points)
* _____ Is this a production website? (+5 points)
* _____ Does this cause a portion of your site to be unusable? (+2 points)
* _____ Is there a workaround? (-1 point)
* _____ Is this an accessibility bug? (+1-3 points)
* _____ Is this a styling bug? (+1 point)
* _____ Is this a usability bug? (+1-3 point)
* _____ Is this a security issue? (+3-5 points)
* _____ Is there sensitive or private information publicly available? (+5 points)
* _____ Is this issue time-sensitive? (+2 points)
* _____ (For internal team assessment) Will this issue cause an increase in support tickets? (+3 points)

### Customer information
If this was customer reported, we'd like to let the customer know when it is fixed.
* Customer Name: 
* Customer Email: 

### Accessibility 
#### Standards information
If this is an accessibility issue, describe the level of violation or issues encountered.
* HTML Validation: [Error, warning, notice] 
* WCAG: [A, AA, AAA, Best practice]
* ARIA: 

#### Severity
How quickly should this be addressed:

* Urgent - talk to client ASAP
* Address soon - bring up with PM or team
* ✅ Not urgent - prioritize in sprint planning

### Device specific information:
If this bug is specific to a device or technology, give its specs. Repeat this information if there are multiple devices.
* Device: [PC laptop, Mac Laptop, mobile phone]
* OS: [MacOS, Windows, iOS, Android]
* Browser & Version [Chrome, Firefox, Safari]
* Testing technology:
  * Siteimprove app and browser extension,
  * [HeadingsMap](https://www.accessibility-developer-guide.com/setup/helper-tools/browser-extensions/headingsmap/),
  * Color contrast checker:  [WCAG Color contrast checker](https://chromewebstore.google.com/detail/plnahcmalebffmaghcpcmpaciebdhgdf?utm_source=item-share-cb)
  * Keyboard,
  * Screen reader: VoiceOver, NVDA, JAWS,
  * Other automated checkers: Axe, Arc, etc. 

### Additional context
* Related PRs: 
* Anyone to be notified? [name]
* Any other context about the problem? 
