# Use Cases for Circle CI
Authors: Pradeep Makkena and Cody Rigney

## Simple Small Project With Continous Integration Tests on CircleCI

- Develop a very simple example app with Node JS.
   - Post on Github.
   - Add a couple simple tests into npm.
- Add app to CircleCI to start automated builds with continuous integration.
   - Tests will automatically start and won't require any additional configuration.
- Review build status once complete - pass or fail.
- Make a commit to the app that breaks the tests and see the failure in CircleCI.
- Make a commit to the app to fix the tests and see the successful build in CircleCI.


## Custom Configuration of CircleCI on a Large Open Source Project

- Find a large open source project that runs unit tests and requires some specific configuration.
- Fork the open source project to add a custom `circle.yml` to the project for configuration in CircleCI.
  - `circle.yml` will run commands needed to install libraries for build, etc.
 - Add the large open source project to CircleCI which will build the project and run tests.
 - Review results of tests.

## Collabarations using Slack

- Send notifications to everyone in the team with latest build status information.
- We can see which commit triggered that build and who was reponsible for pushing that code in to github.

## SSH access to builds

- Using circleci we can ssh into running or completed build and troubleshoot the problem.
