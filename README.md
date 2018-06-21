# Feed Reader Testing

## Table of Contents

* [Project Overview](#project_overview)
* [How to Run Appilcation](#how_to_run_appilcation)
* [Tests that have been implemented](#tests_that_have_been_implemented)

## Project Overview

Udacity Front-End Web Developer Nano-Degree Exploring-JS project. Test the Feed-Reader page using Jasmine.

## How to Run Appilcation

### Live

You just need to click on the [link](https://guschins.github.io/frontend-nanodegree-feedreader/) to Run Appilcation!

### Loсal

Clone or download this repository and open index.html in your favorite browser to Run Appilcation!

## Tests that have been implemented

- Test suite named `"RSS Feeds"`:
  - Test to make sure that the `allFeeds` variable has been defined and that it is not empty
  - Test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty
  - Test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty
- Test suite named `"The menu"`:
  - Test that ensures the menu element is hidden by default
  - Test that ensures the menu changes visibility when the menu icon is clicked. This test has two expectations: whether the menu is displayed when pressed and hidden when you click again
- Test suite named `"Initial Entries"`:
  - Test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
  - Test suite named `"New Feed Selection"`
  - Test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes