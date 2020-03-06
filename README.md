## ADP Assignment 3: Full Stack GraphQL
**Goal:** Create a working web app that allows users to log in and create content using GraphQL.

## Requirements/Grading Criteria

### Code Quality
* You must use git version control and semantic comits. Commit often.
* Code must be properly formatted. To get full points your project should eslint correctly with https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb
* React router, react form hooks and material ui should be used to continue practicing the skills we learned in React week

### Security
* Use BCrypt to protect users' passwords* Prevent SQL injections by using the dollar sign SQL variables syntax
* Use CSRF tokens to protect your users from identity + data theft and session hijacking
* Protect your users from cross site scripting attacks by using React

### Features
* Implement at least 2 pages (routes) that use GraphQL queries* Implement at least 2 react forms that submit GraphQL mutations to the server* Implement a minimum of 2 GraphQL mutations in the server. For full points implement at least 3 GraphQL mutations.
* Implement at least 3 GraphQL Types* Implement 1 GraphQL Input Type for a mutation (per best practices the Arg should be named "input")* Implement one GraphQL query that uses a SQL join
* Implement user logins. For full points use a GraphQL mutation to log users in to your site (this can count as one of your mutations).
* Implement a user sign up form. For full points use a GraphQL mutation to sign users up (this can count as one of your mutations).

