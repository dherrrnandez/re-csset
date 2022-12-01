# RE-CSSET

An updated CSS Reset wich overrides the default browser styles to make styling easier and cross-browser

## How to Install

With [NPM](http://npmjs.com):

```command
npm install re-csset
```
or

```command
npm i re-csset
```

## How to use it

We want a reset to be a base where to work on. Therefore, we have to **apply re-csset before any other style**. Otherwise, this styles will override your project styles and everything is going to look like default

We strongly recommend to use a modern file structure for styling. This will make it easier to avoid specificity problems and bugs in general

### Importing:

The easiest way is to import in JavScript

In the main entry file with **JavaScript**:
```javascript
import "/re-csset/reset.css"
```

In **React**:
```javascript
import "re-csset/reset.css"
```

In the main entry **CSS**
```css
@import './node_modules/re-csset/reset.css'
```

In **HTML**

```html
<link rel="stylesheet"href="./node_modules/re-csset/reset.css">
```