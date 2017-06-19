# fabric8-ui Automated Test Repository

## Goal of this Repository

The goal of this repository is to provide automated tests that can be easily installed and run. All the tests in this repository are configured to be run locally in a shell, locally in a docker container, and in a docker container in Centos CI. The tests can be run against a local or remove server by specifying the server's URL as a parameter to the tests.

### Planner UI Tests (tbd)

### Performance/Throughput Tests (tbd)

### End-to-End (EE) tests

The EE tests simulate a user's actions by creating spaces and projects in the UI. To run the tests locally, invoke this script:

sh ./local_run_EE_tests.sh username password http://target-URL-for-your-server

