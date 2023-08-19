# Basic Web Challenge

## 1. HTML

easy:

- First connect the files to work with CSS and JavaScript
  - connect `scripts/script.js` in `index.html`
  - connect `style/styles.js` in `index.html`
- Create a `div` with the id `box-1` in `index.html` below the comment `Generating new elements`
- Create a `div` with the class `box` in `index.html` below the comment `Generating new elements`
- Add a link with the text `Link to another page`, the the class `btn` and link it to the `about.html` in `index.html` below the comment `Connecting the link`
- Add a link with the text `Toggle the light`, the id `lightswitch` and the class `btn` in `index.html` below the comment `Darkmode toggling`

medium:

- Add 3 divs with a class `item` into a div with the class `container` in `index.html` below the comment `Generating item container`

## 2. CSS

easy:

- change the background color of the `body` to `#FAEBD7`
- change the font family of the `body` to `Courier New`
- change the `hover` color of the button to `#008CBA`

medium:

- set the following properties on all elements with the `item` class:
  ```
  border: 1px solid black;
  width: 100px;
  height: 100px;
  ```
- display the container as flex and set the direction row with a gap of 4px

## 3. JavaScript

- Introduce a click function on the Link with the id `lightswitch` named `toggleLight`
  - create the function in `scripts/script.js`
  - select the html element with the help of `document.getElementsBy...`
  - depending on the existing classes in the classList add or remove the class `dark`
