#Project-Feed Reader

# Project Overview

In this project i was given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where we come in.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether we work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

###Steps to run
    - Unzip the zipped File
    - Open index.html
    - At the bottom of the page you can see the test results 
    - Red means there is error an green means the code is ok.

### Tests implemented.
	- Test to make sure that the allFeeds variable has been defined and that it is not empty. 
	- Test that loops through each feed in the allFeeds object and ensures it has a URL defined
      and that the URL is not empty.
  - Test that loops through each feedin the allFeeds object and ensures it has a name defined
      and that the name is not empty.
  - Test that ensures the menu element is hidden by default. 
  - Test that ensures the menu changes visibility when the menu icon is clicked.
  - Test that ensures when the loadFeed function is called and completes its work, there is at least
      a single .entry element within the .feed container.
  - Test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.


##Used the Udacity discussion forums for the clarification of my doubts below are the links i reffered to for clarification purpose.

###Sources and Refrences
   	1. [Udacity Forum](https://discussions.udacity.com/t/step-13-help-initial-entries/14839/8)
   	2. [Udacity Forum](https://discussions.udacity.com/t/menu-visibility-when-icon-is-clicked/183050/19)
   	3. [Udacity Forum](https://discussions.udacity.com/t/news-feed-change-testing-has-no-errors-
   		but-didnt-pass-reviewer-comments/199249)
   	4. [jquery Documentation](https://api.jquery.com/hasclass/)