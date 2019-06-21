<h1 align="center">Welcome to Feed Reader Testing 👋</h1>
<p>
  <img src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
</p>

> Udacity Front-end project 

## To run a project

- open this file [site](https://donatluffy.github.io/FeedReaderTesting/) or
- clone this project and open [index.html](index.html)

## RSS Feeds
This is our first test - it tests to make sure that the
allFeeds variable has been defined and that it is not
empty.

- first suite are given

- second suite: *have URL defined & not empty* loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.

- third suite as above, but for the name.

## The menu

- first suite: *menu hidden by default* ensures the menu element is hidden by default.

- second suite: *not hidden* ensures the menu changes visibility when the menu icon is clicked.

## Initial Entries

- *at least a single* suite:  ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.


## New Feed Selection
**It will pass if no new feed is loaded**
- *New Feed Selection* suite: ensures when a new feed is loaded by the loadFeed function that the content actually changes.

👤 **Mesh3ludacity**

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
