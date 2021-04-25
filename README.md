# Closing Assignment

This project is generated from an archetype. It exists out of TestNG, Selenium WebDriver, WebDriver Manager, Allure as the main dependendies.

The following browsers can be used:
`CHROME`, `FIREFOX`, `EDGE`, `OPERA`, `INTERNET_EXPLORER` and `CHROME_HEADLESS`

## Run exercises

`mvn clean test`

By default, Chrome will be used. To override the default browser, you can use the following command (and choose one of
the supporting browsers):

`mvn clean test -DseleniumBrowser=firefox`

## Generate report

`mvn allure:report`

`mvn allure:serve`
