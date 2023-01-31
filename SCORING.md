# Scoring guidelines
The assignment tests many aspects of software development. When scoring the
assignment, it is important to keep in mind that an applicant does not have to
be an expert in every aspect. The most important question that needs to be
answered is:

> Can the applicant help us with our current challenges and in the existing team
composition?

This document aims to provide some guidelines for preparing and conducting the
technical interview. It is by no means a recipe for a successful interview.

The actual focus of the technical interview depends on the applicant and
solution. Sometimes it is clear from the assignment that someone is not a fit.
In that case there is no need to waste the applicant's time for an hour.

## Preparation
- Try to run the code locally
- Check the project structure and code quality
- Check if you understand the logic
- Identify some interesting examples in the code to discuss during the interview
- Prepare questions for the applicant: act as if this was a code review
- Prepare some positive feedback for the applicant

## Technical interview
Overview:
- (5 min) Everyone introduces him/herself
- (5 min) Applicant presents solution
- (5 min) Discuss the applicant's experience + process
- (40 min) Discuss the code / technical questions
- (5 min) Other questions from applicant

## Working in a team
- *Applicant can handle constructive feedback (does not get defensive)
- *Applicant asks questions to improve understanding of feedback or question
- *Applicant can explain what he/she did and why decisions were made
- *Applicant asks questions to the SensorFact team on how they would specific problems

## Time management
- *Applicant can explain how he/she spent his/her time
- Applicant uses tests, a debugger or profiler to debug code

## Assignment
The most important requirements are marked with (*).

- *High level requirements are met: does the solution match the assignment?

### Front end
React
- *Uses ReactJS
- *Applicant can explain something about the React specific features that were
used: e.g. hooks, provider
- Applicant can describe some common concepts in front end development: e.g.
event bubbling, data binding
- The render function contains no to little logic

UI
- *UI is intuitive to use
- *Applicant can describe why this layout / UI was designed
- Applicant can explain why a UI library was selected
- UI is responsive

SpaceX API
- *Applicant calls the SpaceX API with a correct and efficient call
- *Applicant can explain a bit about the options that the SpaceX API offers
- *Applicant can discuss own perspective on using GraphQL APIs
- Applicant can describe why a specific GraphQL client was selected

Deployment
- Front end project is deployed
- *Applicant knows how to deploy this project

### Serverless function
Solution
- *Applicant can explain the implemented logic adequately
- *Applicant can explain why he/she chose this API contract
- *Solution runs locally
- *Applicant handles errors
- *Applicant can explain something about HTTP status codes or returning errors
- Logic is testable

Deployment
- Applicant can explain how to deploy the solution
- Applicant can explain how to provide variables in different environments

### Code quality
- *Project is a Git repository. If not --> Check that applicant has experience
  - *Multiple commits are made
  - *Commit messages are descriptive
  - *Artifacts are ignored by source control
  - Created multiple branches for specific features
- *Project structure is clear
  - *Front end and back end code separated
  - *Multiple files
  - *Descriptive file names + consistent casing
  - *Project can be run by simple commands (use of npm scripts)
  - Consistent naming
- *Code is easy to read
  - *Descriptive function and variable names + consistent casing
  - *Reusable functions are extracted
  - *No magic numbers or hardcoded values (uses env vars)
  - *The project contains no unused code (incl. unreachable code, comments)
  - Linter is used
- *Project uses libraries effectively
  - *Applicant did not write too many functions that can be used from common
  libraries
  - *Package.json looks clean (all packages used)
  - *No errors when installing dependencies
  - *Dependencies are (relatively) up to date
  - Imports are sorted
- *JavaScript/TypeScript
  - *Applicant uses JS/TS correctly: async/await, callbacks, type definitions
  - *Applicant can answer questions about JS/TS adequately: hoisting, scope
  (arrow function vs function), const/let, ===/==, prototypical inheritance.
- Tests
  - *Code is testable or applicant knows how to improve
  - *Applicant knows the difference between unit and integration tests
  - Some part of the solution is tested

### Documentation
- *It is clear how to install and start the solution
  - A README elaborates the basic usage of the solution
  - The code contains comments if something odd happens

### Next steps
- *Applicant can explain how he/she would improve the solution further
- *Applicant can explain how to include others (e.g. product team) in next steps
