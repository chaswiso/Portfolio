
> Written with [StackEdit](https://stackedit.io/).

# Test Plan
> This document will describe the scope, approach, resources, and schedule of ***FlightAware*** intended test activities for the described project or release.
## Introduction
> Brief summary of the release or product being tested.

## Objectives
> What are the test **objectives** and **goals** of this release?

## Scope
> What functionality is new or changed and **will** be tested in this release, and specifically what **will NOT** be tested?
### Included
### Excluded

## Testing Strategy
> Describe the overall **approach** to testing and multiple **types** of test procedures that give expected test outcomes.
### Unit Testing
- work with developers and identify scenarios to arrange, act and assert
### API Testing
- endpoints
- requests and responses
- data
- permissions
### Integration and System Testing
- project team tests
- main system tests
### Smoke Testing
- site up testing
### Performance and Stress Testing
- performant queries
- user load testing
### User Acceptance Testing
- customer test scenarios
### Automated Regression Testing
- validate legacy test scenarios work properly
### Post Deployment Testing
- production checkout and wheels up!

## Hardware Requirements
> What **physical devices** will be required to test this release?
### Desktop
- Browsers
### Mobile
- iOS
- Android
### Receivers
- PiAware
- FlightFeeder

## Environment Requirements
> What **branch** and **build version** will be included in this release and **where** will it be tested?
### Branch
### Version
 - [ ] Development
 - [ ] QA
 - [ ] Staging
 - [ ] Production

## Test Schedule
> Estimate the man hours required for testing tasks and determine the schedule for test completion
 - [ ] Testing MIlestones

## Control Procedures
> What procedures will be followed if testing goes sideways?
- all problems will be reported in the defect ticketing system
- change requests must be directed through the team's Product Owner
## Features to Be Tested
> Feature functionality **included** in this release
- story
- bug
- task

## Features NOT to Be Tested
> Specific functionality **NOT included** in this release
- story
- task

## Test Criteria
> What conditions would **stop** testing?
### Suspension Criteria
- fail rate exceeds 40% of the total test run
### Exit Criteria
- run rate equals 100% of the total test run
- pass rate equals 95% of the total test run

## Resources, Roles and Responsibilities
### Human Resources
- tester
- roles
- responsibilities
### System Resources
- servers
- test tools
- network

## Schedules
> What is the **timeline** for major deliverables?
- test plan  - 3/8/2022
- test cases  - 4/8/2022
- defect report  - 4/22/2022  
- test summary report  - 4/30/2022 
## Impacted Departments
> Identify the **teams** and involved parties for this release
### Teams
- product owner
- tech lead 
## Dependencies
> Are there any known **constraints** on testing?
- builds
- resources
- deadlines
## Risks and Assumptions
> Define any known **risks** and possible contingency plans for **mitigation**
- pto days
- patching
## Tools
> What testing or automation **tools** will be used?
- defects
- automation
## Test Deliverables
> All the documents or components that have to be developed to support the testing effort
- test plan
- test cases
- test scripts
- test data
- logs
- test reports
- defect reports
- any guidelines
- release notes

## Approvals
> Names and titles of all the **individuals** that must approve this plan

 - [ ] Engineering
 - [ ] Product
 - [ ] Customer Service

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAzNDc4Mzg1NSwtMTQxMTU1NDUyNCwtMj
A2MTA0MTYxMSw1NDI0OTA5ODIsNTAxMjE0ODc0LC0xNzM3NTgw
ODcyLDE1MTczMTcwNjUsMTA1MzM1ODI2OSwxMzE2MTMxODE0LC
0yMzYxMzY5NTMsMTU4NTExMjY1NywxNjEzNjgxNDAzLDczMDk5
ODExNl19
-->