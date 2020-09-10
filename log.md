# 100 Days Of Code - Log

### Day 0: August 24, 2020

**Today's Progress**: Researched for project ideas and topics to learn. Made initial changes to the repo, and raised a small PR on the original repository.

**Thoughts:** Coming up with an action plan for the 100 days of the challenge is pretty difficult. Have been thinking about project ideas mostly.

**Link to work:** [PR](https://github.com/kallaway/100-days-of-code/pull/340)


### Day 1: August 25

**Today's Progress**: Started developing a simple quotes generator using HTML, CSS and JavaScript. Built the basic layout and functionality.

**Thoughts** Implemented only a basic local version. More work is needed to make it fetch data from an API, share quotes via tweet, or even host the site online.

**Link to work:** [Github](https://github.com/adbose/random-quotes-generator)


### Day 2: August 26

**Today's Progress**: Switched to an external API for fetching random quotes. Reworked the JavaScript workings to use jQuery with AJAX to call the API as well as share to Twitter.

**Thoughts** The Forismatic API documentations were not very clear about the API parameters for making requests. It was solved by adding `jsonp` in the request parameters.
[View here](https://github.com/adbose/random-quotes-generator/blob/master/scripts.js#L10)

**Link to work:** [Github](https://github.com/adbose/random-quotes-generator)


### Day 3: August 27

**Today's Progress**: Deployed the site on Github pages. Fixed a big of API request not executing successfully.

**Thoughts** The API call was failing because the site was hosten on Github Pages over HTTPS, but the API scheme was HTTP. Took a long time to figure out, but finally solved the issue by changing the scheme to HTTPS.

**Link to work:** [Github](https://adbose.github.io/random-quotes-generator)


### Day 4: August 28

**Today's Progress**: Started and completed a basic Fake Name generator app using the randomuser.me API with vanilla JavaScript's Fetch API. Also deployed it on my website hosted on Github pages.

**Thoughts** Using fetch API was simpler than AJAX using XMLHttpRequest which needs to create an object, open and then send a request. fetch achieves it all using one call.

**Link to work:** [Github](https://adbose.github.io/fake-user-generator)


### Day 5: August 29

**Today's Progress**: Started working on a simple JavaScript digital clock. Also deployed it to my website.

**Thoughts** Learnt about the JavaScript Date() module it's methods needed to display formatted output. Also learnt how to use the setTimeout() function to display time to the second.

**Link to work:** [Github](https://adbose.github.io/timekeeper)


### Day 6: August 30

**Today's Progress**: Continued on the Timekeeper project to add a new year countdown on the website. Also added a simple dark theme switcher.

**Thoughts** Learnt the use of setInterval() to do implement the timer. Also, had some issues with the theme switcher not persisting the theme on page navigation/reload. Need to fix it in the future.

**Link to work:** [Github](https://adbose.github.io/timekeeper)


### Day 7: September 1

**Today's Progress**: Built a single page app with a button to toggle between light and dark theme with persistent data from localStorage.

**Thoughts** Learnt how to use the localStorage of the browser to store any date completely client side. Learnt how to remember choice of a user action even after page/session reload by storing the data on localStorage.

**Link to work:** [Github](https://github.com/adbose/light-and-dark-toggle)


### Day 7: September 1

**Today's Progress**: Built a single page app with a button to toggle between light and dark theme with persistent data from localStorage.

**Thoughts** Learnt how to use the localStorage of the browser to store any date completely client side. Learnt how to remember choice of a user action even after page/session reload by storing the data on localStorage.

**Link to work:** [Github](https://github.com/adbose/light-and-dark-toggle)


### Day 7: September 1

**Today's Progress**: Built a single page app with a button to toggle between light and dark theme with persistent data from localStorage.

**Thoughts** Learnt how to use the localStorage of the browser to store any date completely client side. Learnt how to remember choice of a user action even after page/session reload by storing the data on localStorage.

**Link to work:** [Github](https://github.com/adbose/light-and-dark-toggle)


### Day 8: September 2

**Today's Progress**: Started working on a TODO app using HTML, CSS, JavaScript based on the Freshman Todo List Blog post [here](https://freshman.tech/todo-list/). Got the front end boilerplate up mostly.

**Thoughts** Used SVG images for the first time. Looks weird but isn't complicated.

**Link to work:** [Github](https://github.com/adbose/js-todo-app)


### Day 9: September 6

**Today's Progress**: Added JavaScript to render items on form submit.

**Thoughts**  Studied JavaScript concepts the past couple of days to better understand the concepts involved in the Todo app design.

**Link to work:** [Github](https://github.com/adbose/js-todo-app)


### Day 10: September 8

**Today's Progress**: Add more JavaScript to complete and delete tasks.

**Thoughts** Persisting tasks on the local storage, and a default empty state is still left to be implemented.

**Link to work:** [Site](https://https://adbose.github.io/js-todo-app)


### Day 11: September 9

**Today's Progress**: Started working on a new project- A JavaScript calculator based on this [video](https://www.youtube.com/watch?v=j59qQ7YWLxw) by Web Dev Simplified. Laid out the markup and styles in HTML and CSS.
**Thoughts** Thinking of also working on the pending backlogs in the 100 days journey. Would try to clear some backlog in the weekend.

**Link to work:** [Github](https://github.com/adbose/js-calculator)


### Day 12: September 10

**Today's Progress**: Wrote some JavaScript to capture inputs on button click events.

**Thoughts** Understanding how OOP works to create a calculator functionality.

**Link to work:** [Site](adbose.github.io/js-calculator)

