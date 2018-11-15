frontend-nanodegree-FeedReader-Testing
=======================================

# Holly's Feed Reader Testing

Udacity Front-End Web Developer Nanodegree Part 3 Project: Feed Reader Testing.

##Table of Contents

* Project Overview
* Build Considerations
* How to Run the Application
* Acknowledgements
* [Contributing](#contributing)

## Project Overview

This project is a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/)and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

The Project is available on GitHub, titled [Hollys-Feed-Reader-Testing](https://github.com/hollyjordan13/Hollys-Feed-Reader-Testing).

##Build Considerations

1. Explore the Jasmine spec file in **./jasmine/spec/feedreader.js** and review the [Jasmine documentation](http://jasmine.github.io).
2. Edit the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualizes this failure in your application.
3. Return the `allFeeds` variable to a passing state.
4. Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
5. Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
6. Write a new test suite named `"The menu"`.
7. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
8. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
9. Write a test suite named `"Initial Entries"`.
10. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
11. Write a test suite named `"New Feed Selection"`.
12. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
13. No test should be dependent on the results of another.
14. Callbacks should be used to ensure that feeds are loaded before they are tested.
15. Implement error handling for undefined variables and out-of-bound array access.
16. When complete - all of your tests should pass. 

##How to Run the Application

File can be accessed either by downloading the zip or clone the repository from GitHub [here](https://github.com/hollyjordan13/Hollys-Feed-Reader-Testing).

To open test results, see file located in jasmine/spec titled [feedreader.js](
        Hollys-Feed-Reader-Testing/jasmine/spec/feedreader.js
      ).
Tests can be seen in the browser by opening [index.html](
        Hollys-Feed-Reader-Testing/index.html
      ).

##Acknowledgements

* [Udacity](https://www.udacity.com/), for creating this degree program, and providing me with education and endless support
* [stackoverflow](https://stackoverflow.com/), for the collaborative forums and discussions which helped answer many of my questions
* [Mozilla Developer Network](https://developer.mozilla.org/en-US/), for so many resources and instructions
* [Jasmine](http://jasmine.github.io/)
* [JavaScript](https://www.javascript.com/)

##Contributing

This repository is a project for the Udacity Front-End Web Developer Nanodegree. Therefore, we most likely will not accept pull requests.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).