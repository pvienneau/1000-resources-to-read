# Tape

#### Why I use Tape Instead of Mocha & So Should You

https://medium.com/pacroy/separate-unit-integration-and-functional-tests-for-continuous-delivery-f4dc240d8f2f

**TL;DR**: Various levels of tests should be written for various levels of development and point in time in continuous development. Unit tests are more tailored for developers and they are writing functionality. Full test suits, including unit tests and integration tests and functional tests should be run in QA/staging, as testing speed is less of an issue. Once deployed smoke tests (green path testing) assures that the main flows are working fine. Smoke tests are a subset of the functional tests suite.
