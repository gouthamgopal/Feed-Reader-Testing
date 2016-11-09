# Feed Reader Testing #

## Overview ##

The project mainly deals with the implementation of testing out the various
elements of a webpage and thus building an error free webpage for the users.
This is mainly taken care of by using the jasmine testing framework.(Jasmine 2.1.2).

## How to Use ##

1. Download the zip file and unzip it onto a folder.
2. Open index.html that is inside the folder to view the webpage and test results.
3. Open jasmine/spec/feedreader.js to find the queries used for testing.

## Testing Queries taken Care of ##

1. Suite - RSS Feeds
  1. Test to verify that all variable has been defined
  2. Test to verify that all URLs are defined and not empty
  3. Test to verify that all feeds have names defined and names are not empty

2. Suite - The Menu
  1. Test to verify that menu is changing the visibility:
  2. visible when menu icon is clicked
  3. hidden when menu icon is clicked again

3. Suite - Initial Entries
  1. Test to verify that loadFeed function is called and completes its work,
     there is at least a single .entry element within the .feed container

4. Suite - New Feed Selection
  1. Test to verify that when a new feed is loaded by the loadFeed function
     that the content actually changes.
