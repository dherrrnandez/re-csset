# The RE-CSSET Reset ๐ค

An updated CSS Reset wich overrides the default browser styles

This makes styling way easier and cross-browser by default ๐

## How to Install ๐

With [NPM](http://npmjs.com):

```command
npm install re-csset
```
or

```command
npm i re-csset
```

## How to use it ๐

We want a reset to be a base where to work on

Therefore, we have to **APPLY RE-CSSET BEFORE ANY OTHER STYLE** ๐

Otherwise, the reset will override your project styles

We strongly recommend to use a modern file structure for styling

This will make it easier to avoid specificity problems and bugs in general

## Importing ๐

In **React**:
```javascript
import "re-csset/reset.css"
```

In **SASS**
```scss
@useย '../node_modules/re-csset/reset.css'
```

In **CSS**
```css
@importย '../node_modules/re-csset/reset.css'
```

In **HTML**

```html
<link rel="stylesheet"href="./node_modules/re-csset/reset.css">
```
