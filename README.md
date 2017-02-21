# WesBos JavaScript30 Challenge

## Introduction

This is a personal exercise taking the video tutorial series of [Wes Bos](https://javascript30.com/) about coding in pure plain JS. [Original exercises](https://github.com/davidlampon/JavaScript30) can be found in his own repo. The codepen exercises below are slightly different approaches to the original exercises done after seeing the videos in order to understand deeply the concepts shown in every one of them.

## Table of contents
1. [HTML Keyboard](#html-keyboard)
2. [Analog clock](#analog-clock)
3. [CSS Variables](#css-variables)
4. [Array Cardio 1](#array-cardio-1)
5. [Flex Panels Image Gallery](#flex-panels-image-gallery)
6. [Type Ahead](#type-ahead)

## Exercises

### #1 HTML Keyboard<a name="html-keyboard"></a>
[Exercise](http://codepen.io/davidlampon/pen/LxRXzQ)

* `transitionend` event listener
* `<kbd>` html tag
* `<audio>` html tag and how to use it
* JS audio file API: `play` method, `currentTime(secs)`
* Custom data selectors `document.querySelector(audio[data-key="${e.keyCode}"])`
* nodelist loop instead of for of `querySelectorAll` we can use `keys.forEach(key => key.addEventListener('transitionend', removeTransition))`


### #2 Analog clock<a name="analog-clock"></a>
[Exercise](http://codepen.io/davidlampon/pen/apmYvJ)

* `transform-origin: 0%`;
* `transform: rotate(-90deg);`
* `transform: translate(-50%, -50%);`
* ES6 templates, style object
* `setInterval`

### #3 CSS Variables<a name="css-variables"></a>
[Exercise](http://codepen.io/davidlampon/pen/XpjOEW)

* css variables
* how to change css variables from JS
* input >> range and color (min, max, value)
* HTML default value can’t be taken form css?

### #4 Array Cardio 1<a name="array-cardio-1"></a>
[Exercise](http://codepen.io/davidlampon/pen/OWbzVL)

* `filter` >> born year
* `map` - array factory (same length as original) >> full names
* `sort` >> oldest to youngest (a, b) — 1 -1
* `reduce`  >> how many years did they all live total, inventor
* document query and documentQueryAll can be called up on any dom element (not just document)
* Nodelist to array => `Array.from(nodelist)`
* Nodelist to array => ES6 `[…nodelist]`
* list of boulverdas that mountain ‘de’ >> map (name from novelist) and filter (de)
* `string.includes()` >> string inside another string
* deconstruct >> `const [last, name] = lastOne.split(‘, ‘);`

### #5 Flex Panels Image Gallery<a name="flex-panels-image-gallery"></a>
[Exercise](http://codepen.io/davidlampon/pen/JEgJXw)

* `forEach` in a node list to set event listeners
* event listener for `transitionend`
* flex box css panels

### #6 Type Ahead<a name="type-ahead"></a>
[Exercise](https://codepen.io/davidlampon/pen/oBKoeK)

* `fetch` API and promises
* array decomposition with `...` and pushing into a const empty array
* `const regex = RegExp(wordToMatch, 'gi')` and `element.match(regex)`
* `change`and `keyup` triggers in the same input (two eventListeners)
* `Array.filter` to get specific results
* `Array.map` to return an array of html elements and `.join()` to conver tit to string
* `new RegExp(value, 'gi')` and ``element.replace(regex, `<span class="hl">${value}</span>`)`` for a highlighted inline element;
