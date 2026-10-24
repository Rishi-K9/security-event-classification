
# Security Event Classification

## Objective
Classify synthetic security events as Normal, Suspicious, or Potentially Malicious.

## Tools
Google Sheets and GitHub.

## Method
Reviewed 12 synthetic security events and documented the reason for each classification.

## Results
- Normal: 4
- Suspicious: 5
- Potentially Malicious: 3
- Total: 12 events

## Security Triage
Security triage is the process of reviewing alerts, assessing risk, and prioritizing events for further investigation.

### What Makes an Event Suspicious?
Repeated failed logins, unfamiliar login locations, unexpected privilege requests, and unusual data access can indicate suspicious activity that requires further investigation.

## Deliverables
- `security_event_classification.csv` — classified security event dataset.
- `deployment-config.md` — deployment and publishing configuration.
- `rollback-evidence.md` — rollback procedure and evidence status.

## Deployment and Rollback
The project uses a public GitHub repository to publish the dataset and documentation. The rollback procedure describes how to restore a previous verified version. Any rollback testing and evidence must reflect the actions actually performed.

## Conclusion
This project demonstrates basic security triage skills by classifying synthetic security events and documenting the reasoning behind each decision.


