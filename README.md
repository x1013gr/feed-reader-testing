# Feed Reader Testing

In this project, we are testing the code given to us by [Udacity](https://www.udacity.com/), with the help of [Jasmine](http://jasmine.github.io/), an open-source tool that is making testing easier.


## How testing works

There were 7 tests needed to be written in "specs" file in the Jasmine folder as requirments for this project. Use of async functions as well as other testing functions were made.


## Academic Goal

By the use of Jasmine, we get an introduction to writing of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.
Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.
Good tests give the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.


# Reiquirments from Udacity

1. Edit the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualizes this failure in your application.
2. Return the `allFeeds` variable to a passing state.
3. Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
4. Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
5. Write a new test suite named `"The menu"`.
6. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
7. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
8. Write a test suite named `"Initial Entries"`.
9. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
10. Write a test suite named `"New Feed Selection"`.
11. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
12. No test should be dependent on the results of another.
13. When complete - all of your tests should pass. 
14. Write a README file detailing all steps required to successfully run the application. If you have added additional tests (for Udacious Test Coverage),  provide documentation for what these future features are and what the tests are checking for.
# feed-reader-testing
