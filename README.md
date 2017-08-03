## Website Performance Optimization portfolio project

This project is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

#### Part 1: Optimize PageSpeed Insights score for index.html

Page Speed Insights Results:

* Mobile: 96/100
* Desktop: 97/100

Optimizations Used:
* put all JS files in the footer
* add @media="print" to print.css link
* inline the style.css
* use Web Fonts Loader to load Google Fonts
* minify HTML
* optimize images

#### Part 2: Optimize Frames per Second in pizza.html

Modified views/js/main.js until the frames per second rate is 60 fps or higher.

Stopped Forced Synchronous Layout at 3 places (resize pizzas, page scroll, and on page load)
by put layout property readings outside the for-loop for batch style changes.
 

The FPS Counter/HUD Display in Chrome developer tools is described here: [Chrome Dev Tools tips-and-tricks](https://developer.chrome.com/devtools/docs/tips-and-tricks).

