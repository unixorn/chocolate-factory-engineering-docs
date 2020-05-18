# Alerting Guidelines

* **Be Specific:** Include the full, human readable name AND DNS name of the service which is alerting.
* **Include Priority:** Is this a performance issue? Is this going to cause a site outage if not triaged? Or is this page indicative of a site outage? Pages should be specific about their Urgency (low, medium, high). Remember though, if everything is high priority, _nothing_ is high priority.
* **Be Actionable:** We should only alert in the case where there are actions which need to be taken by an operator.
* **Be Documented:** A runbook should be attached to the page, detailing the actions required of the operator.
* **Be Reviewed:** A monthly meeting should discuss type & volume of pages, to ensure that monitoring hygiene does not degenerate over time, and the appropriate priorities are set forth for auto-remediating high volume alerts.
* **Be Brief:** Include all the information the responder needs in the first screen. Specify which of those lines are the actual problem instead of making the responder have to guess. We're probably reading it on a phone and no one wants to wade through 40 screens to find the two lines that the page is complaining about
