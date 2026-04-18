
added home page and search result page   
This project is an automated test framework built for a Cleartrip-like travel booking application. It focuses on validating the core user flow of searching for flights using Selenium WebDriver and Java.

The framework is designed using the Page Object Model (POM) to ensure scalability, maintainability, and clean separation of concerns.

 My Contribution

In this project, I was responsible for designing and implementing key components of the automation framework, specifically:

 Home Page Automation

I developed the HomePage class, which handles all interactions on the landing page of the application.

Key Responsibilities:
Implemented locators for:
From City input
To City input
Date picker
Search button
Automated dynamic elements such as:
Auto-suggestion dropdowns
Calendar date selection
Handled UI challenges:
Popup handling using explicit waits and JavaScript fallback
Scroll and click issues using JavascriptExecutor
Built reusable methods:
selectFromCity()
selectToCity()
selectDate()
clickSearch()
Applied retry mechanisms for unstable elements
Integrated custom wait handling using WaitUtils
 Search Results Page Automation

I created the SearchResultsPage class to validate the results displayed after performing a search.

Key Responsibilities:
Captured and validated search results
Implemented methods to:
Verify list of available flights
Extract flight details (price, timing, airline)
Handled dynamic loading of results using explicit waits
Ensured synchronization between UI and test execution


