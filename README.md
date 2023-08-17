# Artemis Financial Software Security Assessment
## Overview
This repository has the insight gleaned from a well-thought-out security assessment that was conducted for Artemis Financial - a fictitious company for illustrative purposes. The assessment tries to identify and/or address security vulnerabilities within the company's code base with the intent of strengthening the company's security posture.

## Client Background
Artemis Financial is portrayed as a leading financial institution that provides a broad range of financial services to its clients. They came to us - Global Rain - for consultation services. They were worried that potential security gaps could lead to data breaches, loss of customer trust, and loss of revenue.

## Software Assessment

### Identifying Vulnerabilities
in the assessment, we painstakingly analyzed Artemis Financial's software application, identifying security vulnerabilities. These issues ranged from little to no input validation, all the way to the immediate risk of a cross site scripting (XXS) attack. Our comprehensive approach helped us lock in on insecure coding practices, remidiate them, and bring the company's risks down. 

### Added Value to the Company's Wellbeing
The enhanced security practices that we were able to provide to Artemis Financial significantly increased the company's wellbeing. By addressing these concerns, we may have prevented costly data breaches, loss of customer trust, and possible regulatory violations. Our assessment offered Artemis Financial the opportunity to proactively stop these gaps and bulwark their systems against bad actors.

### Challenges and Insights
The hardest part of the vulnerability assessment was in scanning the code for false positives. This proved to be particularly challenging when also providing manual code reviews, and code refactoring suggestions for Artemis Financial to consider. Overall, the impact of this project proved to be beneficial for all parties involved.

### Increasing Security Layers
To increase security, we decided upon multi-layered security measures. This included but was not limited to:
- input validation
- parameterized queries
- role-based access control
In the future, we would automate many of the checks against the code base, even beyond the scanning tools that we were able to integrate into the maven project build.

### Ensuring Functionality and Security
After refactoring the code to handle vulnerabilities, we conducted thorough testing to make sure the application still functioned as needed, while also accounting for the high security expectations the company needed to operate. 
