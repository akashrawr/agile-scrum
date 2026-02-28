# Scrum Template @ GitHub
Template used to create a project based on Scrum
## Label
### Epic
`Epic` labels allow grouping body of work that can be broken down into specific stories
  - `Epic: Improve Online Shopping Experience`
### User Story 
`User Story` labels that are specific requirement that describes a feature
  - `As a [type of user], I want [goal], so that [benefit].`
  - `User Story: As a customer, I want to add items to a wishlist, so that I can purchase them later.`
### Bug
- `Bug: Login button does not work on mobile devices`

## Milestone
- Sprint

## Project
Scrum Board
  
| Product Backlog | Sprint Backlog | In Progress | In Review | Done |  
| :---: | :---: | :---: | :---: | :---: |  
| open<br>unmilestoned<br>unassigned | open<br>milestoned<br>unassigned | open<br>milestoned<br>assigned | open<br>milestoned<br>assigned<br>pull request reference | closed |  

## Definition of Ready (DoR)

The Definition of Ready (DoR) describes the minimum set of criteria that must be fulfilled before a story is declared "good enough" / ready
to be included and worked upon in an upcoming sprint.

### Checklist

- [ ] The backlog item has a concise title, phrased using active verbs, avoiding technical terms
- [ ] A **User Story**
  - [ ] is written in its typical narrative-like form
      <br>_**As** [kind of user] **I want** [some feature] **so that** [some benefit]_
  - [ ] has Acceptance Criteria (AC) that are testable and fully understood by the team; they
    - [ ] may cover related functional requirements or cross-cutting concerns
          <br>_(e.g. edge cases, error handling, empty states, loading states)_
    - [ ] may include technical decisions
          <br>_(e.g. architecture, use of libraries, major implementation details)_
    - [ ] may define non-functional requirements
          <br>_(e.g. security, performance, accessibility, configuration, observability)_
- [ ] A **Bug**
  - [ ] details expected state vs. actual state
  - [ ] offers a step-by-step guide on how to reproduce the issue
  - [ ] includes environment details
        <br>_(e.g. physical device, operating system, browser)_
  - [ ] may have additional assets attached
        <br>_(e.g. screenshots, videos)_
- [ ] The team has a good idea about how to present the backlog item deliverables, to the extend possible
      <br>_(e.g. Sprint Review, presentation to non-technical people such as management)_
- [ ] The backlog item has been discussed and estimated by the team, and the estimation is not in the double-digits (8 points or lower)
      <br>_(an estimation is a combination of effort and complexity, plus risks)_
- [ ] The backlog item is not blocked by another backlog item or external dependency, or the blocker is assumed to be resolved within the same Sprint

## Definition of Done (DoD)

The Definition of Done (DoD) describes the conditions that must be satisfied before the teams deliverables (e.g. next iteration of the
product) can be considered fit for release / "done".

### Checklist

- [ ] All Acceptance Criteria (AC) are met
      <br>_(e.g. functional test is performed, no known defects exist, no regressions are introduced)_
- [ ] The code is checked into Git, and is part of the primary development branch
      <br>_(e.g. relevant feature / bugfix branches are merged via PRs, stale branches are deleted)_
- [ ] The code is tested, and tests are successfully executed as part of a CI/CD pipeline
      <br>_(e.g. unit tests, integration tests, end-to-end tests, security tests)_
- [ ] The code follows agreed upon best practices and conventions, and linters are successfully executed as part of a CI/CD pipeline
      <br>_(e.g. linting rules, code formatting, PR reviews)_
- [ ] The code has been reviewed by at least one team member other than its creator (four-eyes principle)
      <br>_(e.g. PR reviews, presentation to co-workers, pair / mob programing)_

## Burnup Charts
- How much work has been completed
- How much total work exists in the project
- It helps teams see progress toward a goal over time.

## References
* https://hugogiraudel.com/2015/08/13/github-as-a-workflow/
* https://zube.io/blog/agile-project-management-workflow-for-github-issues/
* https://wiki.status.im/Using_GitHub_labels
* https://github.com/jvandemo/github-scrum-workflow
* https://www.atlassian.com/agile/project-management/epics-stories-themes
* https://www.atlassian.com/agile/project-management/user-stories
* https://www.atlassian.com/agile/project-management/epics
* https://www.scrumdesk.com/epic-epically/
* http://rgalen.com/agile-training-news/2013/11/10/technical-user-stories-what-when-and-how
