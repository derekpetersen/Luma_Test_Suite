# Luma Test Automation Suite
This suite contains automation test scripts for the website 'Luma' 
(https://magento.softwaretestingboard.com/). The tests consist of black-box UI tests
that focus on core functionality and stability.

## Technology Used
- Python 3.11
- Selenium Webdriver
- Pytest
- Allure (for reporting)

## Structure

The testing structure is built upon the POM (Page Object Model), where all elements
on each page are called and used by a method in the page's own file. All tests are 
contained within the tests folders, and are broken down by different testing types.
Pytest "Mark" fixtures are also implemented to further categorize tests and allow
them to be run in synchronous.