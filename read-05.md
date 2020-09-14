# Summary of reading for Class-05

## [Web scraping](https://www.scrapingbee.com/blog/web-scraping-javascript/)
5 different ways to go through a website and grab DOM elements and then pull the data off those DOM elements. The plain JSDOM version makes most sense, however I see how the others can be more powerful. Cheerio uses jquery.


## [querySelector](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector)
js that selects a specified element from the DOM. 
``` js
const profilePicture = document.querySelector('.profilePicture')
const pEl = document.querySelector('p')

p.classList.add('description')
```

querySelector only grabs the first element on the DOM that fits the search term.

## [querySelectorAll](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll)
js that selects all specified element from the DOM and puts them into an array. 
``` js
const li = document.querySelectorAll('.profilePicture')


li.map(listItem => listItem.classList.add('itemCard'))
```

querySelector grabs all elements on the DOM that fit the search term.