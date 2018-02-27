# Testing

#### JavaScript Testing: Unit vs Functional vs Integration Tests

_Unit tests, integration tests, and functional tests are all types of automated tests which form essential cornerstones of continuous delivery, a development methodology that allows you to safely ship changes to production in days or hours rather than months or years._

https://www.sitepoint.com/javascript-testing-unit-functional-integration/

**TL;DR**: The three main levels of testing are unit, integration and functional tests. Unit tests validate isolated modules or functions that have no side effects in order to quickly provide feedback to the developers. Integration tests assure that modules or components work well with each other and other dependencies, assuring that features are working as intended. Functional tests allow to test the overarching features of the application, in order to confirm that functionality is valid from the user's perspective.

#### Separate Unit, Integration, and Functional Tests for Continuous Delivery

https://medium.com/pacroy/separate-unit-integration-and-functional-tests-for-continuous-delivery-f4dc240d8f2f

**TL;DR**: Various levels of tests should be written for various levels of development and point in time in continuous development. Unit tests are more tailored for developers and they are writing functionality. Full test suits, including unit tests and integration tests and functional tests should be run in QA/staging, as testing speed is less of an issue. Once deployed smoke tests (green path testing) assures that the main flows are working fine. Smoke tests are a subset of the functional tests suite.
