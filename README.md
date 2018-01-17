# project-neon
Easy CSS3 background blur effect inspired by Microsoft Neon effect 

**Demo:** [coderentor.com/project-neon](http://coderentor.com/project-neon/)


## Installation

### npm
```
npm install --save project-neon
```
Now add it to your project:
```html
<html>
  <head>
    ...
    <link rel="stylesheet" type="text/css" href="/path/to/neon.min.css">
  </head>
  <body>
    ...
  </body>
</html>
```
## Usage

### HTML

```HTML
<div class="demo-bg">
    <button class="neon-info-hi">Demo button</button>
</div>
```

### CSS

```CSS
    .demo-bg{
        background: url("../path/to/image.jpg")
    }
```

## Options
You can set use saven different colors & four different effect

#### `Neon options`

Main | Color | Effect | Class
------------ | ------------- | ------------- | -------------
Neon | Standard | Standard | .neon-st-st
Neon | Standard | Medium | .neon-st-md
Neon | Standard | High | .neon-st-hi
Neon | Standard | Extra High | .neon-st-ex-hi
Neon | Light | Standard | .neon-light-st
Neon | Light | Medium | .neon-light-md
Neon | Light | High | .neon-light-hi
Neon | Light | Extra High | .neon-light-ex-hi


## Licence
Notyf is under [MIT licence](https://opensource.org/licenses/mit-license.php)