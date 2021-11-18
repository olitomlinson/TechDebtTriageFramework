---
name: " Tech debt standard template"
about: The standard template for raising technical debt
title: ''
labels: needs triage
assignees: ''

---

## Tech Debt acceptance criteria
- [x] Products & Platforms affected have been identified - labels applied (chat, platform etc)
- [ ] Impacted characteristics have been identified - labels applied (security, availability,CI/CD etc)
- [ ] Description is completed
- [ ] Recommend actions have been defined
- [ ] 'Payback' trigger points have been identified

## Description

<!--- The description should highlight the following points where necessary --->

### What is it?
_Make sure to explain the significance of the issue_
_i.e "its going to damage our brand reputation", "its going to cost a lot of money"_

### Probability of being impacted
_i.e. "its causing problems already", "it might cause problems in the future"_

### Negatively impacted characteristics
_i.e if there is a cost impact, explain what the cost is and why it is justified as negative_

### What specific/domains resources, if any, are affected
_i.e "EdgeKit Package", "Azure Functions", "Chat Cosmos"_

###  Expected vs actual behavior
_Only relevant if this is a bug_

### Repro steps
_Only relevant if this is a bug_

### Framework / Runtime versions which may be relevant
_i.e. "Azure Functions 3" , "Vue.js 1.1"_

## Recommended Action

<!--- The recommend action should highlight the following points --->

### What is the remediation
_i.e "upgrade the nuget package" / "rearchitect this component"_

### Urgency of remediation
_i.e "The longer we leave it the worst it gets", "the urgency is static"_

### Effort estimate of remediations
_i.e. "additional Tax", "Story", "Sprint", "Project", "a programme of work"_

### External dependencies requiring co-ordination
_i.e "a person outside of the team", "an upstream piece of work"_

## Payback trigger points
_i.e "SLA drops below a threshold", "Customer complains", "Cost risen above the allocated budget"_

---

<!--- Use Issue comments for any discourse and additional context that is too bulky to maintain in the initial post, such as stack traces or exceptions. --->
