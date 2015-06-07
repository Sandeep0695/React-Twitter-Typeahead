[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/erikschlegel/React-Twitter-Typeahead?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build Status](https://travis-ci.org/erikschlegel/React-Twitter-Typeahead.svg)](https://travis-ci.org/erikschlegel/React-Twitter-Typeahead)

## React-Twitter-Typeahead
A dashing and flexible reactJS component that integrates Twitter's typeahead.js autosuggest control with ReactJS. Typeahead.js is one of the most frequently used and trusted solutions for a battle-tested autosuggest control. 

The preview below showcases configuring this component for searching against google books using a custom template.

![](https://raw.githubusercontent.com/erikschlegel/React-Twitter-Typeahead/master/assets/react-typeahead-animation.gif)

[See some examples on our Azure site](http://reactypeahead.azurewebsites.net/example/)

## Installation
```js
git clone https://github.com/erikschlegel/React-Twitter-Typeahead.git
cd React-Twitter-Typeahead
npm install
npm run build
```
## Usage
Let's start off creating a basic typeahead by customizing the bloodhound config object. Bloodhound is typeahead.js's powerful suggestion engine. 
```js
git clone https://github.com/erikschlegel/React-Twitter-Typeahead.git
cd React-Twitter-Typeahead
npm install
npm run build
```
## Dependencies
This requires NPM. Also, the underlying typeahead.js library uses jquery to hook some initial events to the control, so you'll need to include the following scripts towards the end of your html page.   
```html
    <script src="../vendor/jquery/jquery.js"></script>
    <script src="../vendor/typeahead.js/typeahead.bundle.js"></script>
```

## License
MIT Licensed