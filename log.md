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

**Link to work:** [Random Quotes Generator](https://adbose.github.io/random-quotes-generator)
