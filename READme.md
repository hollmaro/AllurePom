Configuration pom file for maven. Include:
- bonigarcia
- allure
- selenium

To run tests:
mvn clean test

To generate allure report download allure binary files and then:
- allure generate (generate offline html report)
- allure open (to open generated html report)
- allure serve /target/surefire-reports/(generate html report. openening it on running server on localhost)
