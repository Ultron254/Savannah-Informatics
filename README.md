# Savannah-Informatics
# QA Engineer Assessment - Allan Matano

## Overview

This repository contains the completed QA Engineer assessment tasks, performed by Allan Matano. The assignment includes manual testing, test automation, API testing, and performance testing for a web application that interacts with JSONPlaceholder's API. Below is a concise summary of each task, including the tools and frameworks used.

## Contents

1. **Manual Testing**
   - **Test Case Design**: Comprehensive test cases for the application's core functionality, covering positive and negative scenarios across Landing, Login, and Authenticated pages.
   - **Bug Reporting**: Detailed bug report for a login issue, documenting steps to reproduce, expected and actual results, and severity.

2. **Test Automation**
   - **Automation Script**: A Python script using Selenium to automate the search functionality on the photo/album listing page. The script performs the following:
     - Navigates to the listing page.
     - Enters a search term into the search box.
     - Validates that the correct results are displayed.
   - **Usage**: The script can be run locally, assuming Selenium and the appropriate WebDriver are installed.

3. **API Testing**
   - **API Test Cases**: Documented test cases for each JSONPlaceholder API endpoint used in the application. The cases cover scenarios for Users, Albums, and Photos endpoints, with a focus on status codes, data integrity, and error handling.

4. **Performance Testing**
   - **Performance Test Plan**: A structured plan for Load Testing, Stress Testing, and Response Time Testing, with defined performance metrics including response time, error rate, and latency.
   - **Test Cases**: Detailed test cases for each type of performance test, designed to measure the web application's stability and responsiveness under various load conditions.

## Tools and Technologies

- **Manual Testing**: Documented test cases and bug reports
- **Test Automation**: Python, Selenium WebDriver
- **API Testing**: JSONPlaceholder API, Postman (or similar tool)
- **Performance Testing**: Apache JMeter, Locust (suggested tools)

## Repository Structure

. ├── automation-script/ │ └── test_search_functionality.py # Selenium script for automating search functionality ├── api-test-cases/ │ └── api_test_cases.md # API test case documentation ├── performance-test-plan/ │ └── performance_test_plan.md # Performance test plan and test cases ├── manual-testing/ │ ├── test_case_design.pdf # Documented test cases │ └── bug_report.md # Detailed bug report for login issue └── README.md # Project overview
