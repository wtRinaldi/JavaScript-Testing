# JavaScript-Testing
Project 6 - Jasmine behavior driven testing

see the source files at https://github.com/wtRinaldi/JavaScript-Testing

## Description

In this Udacity project, I was given a web-based application that reads RSS feeds.  We are tasked with writing test suites to test the functionality of the application.  
This project utilizes Jasmine.  Jasmine is a behavior-driven development framework for testing JavaScript code.

## Tests Written

- a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
- a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
- a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
- a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
- a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
- a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

## Installation

Download files from github repo and open index.html in browswer window.
The test have been written in the feedreader.js file which is located here - https://github.com/wtRinaldi/JavaScript-Testing/blob/master/jasmine/spec/feedreader.js


## Front-End Developer Nanodegree

This project was completed as part of the Udacity Front-End developer nanodegree.  The main focus of the project was to gain an understanding of test driven development.
Details about the nanodegree program can be seen here: https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001

## Contact

williamtrinaldi@gmail.com
