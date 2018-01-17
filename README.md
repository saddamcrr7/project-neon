# project-neon
Neon is a very simple Modern, easy to use CSS based library. Neon made with an awesome variation of CSS3 Filter, Box shadow, Background inherit property that takes neon effect from your background Image. Neon inspired by Microsof Fluent Design concept. 

Neon will provide a revolutionary user experience on your website Buttton, Modal, Hover effect, Navigation, Dropdown Menu etc. 
Neon is an eloquent CSS effect for a complex world.

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

Neon takes effect from your parent div background image.

### HTML

```HTML
<div class="demo-bg">
    <button class="neon-info-hi">Demo button</button>
</div>
```

### CSS

```CSS
    .demo-bg{
        background: url("../path/to/image.jpg") fixed;
        /* set your custom CSS */
    }
    /* customize your button  for better look  */
```

## Options
You can set saven different colors & four different effect

#### `Neon options`

Main | Color | Effect | CSS Class
------------ | ------------- | ------------- | -------------
Neon | Standard | Standard | .neon-st-st
Neon | Standard | Medium | .neon-st-md
Neon | Standard | High | .neon-st-hi
Neon | Standard | Extra High | .neon-st-ex-hi
Neon | Light | Standard | .neon-light-st
Neon | Light | Medium | .neon-light-md
Neon | Light | High | .neon-light-hi
Neon | Light | Extra High | .neon-light-ex-hi
Neon | Dark | Standard | .neon-dark-st
Neon | Dark | Medium | .neon-dark-md
Neon | Dark | High | .neon-dark-hi
Neon | Dark | Extra High | .neon-dark-ex-hi
Neon | success | Standard | .neon-success-st
Neon | success | Medium | .neon-success-md
Neon | success | High | .neon-success-hi
Neon | success | Extra High | .neon-success-ex-hi
Neon | warning | warning | .neon-warning-st
Neon | warning | Medium | .neon-warning-md
Neon | warning | High | .neon-warning-hi
Neon | warning | Extra High | .neon-warning-ex-hi
Neon | danger | Standard | .neon-danger-st
Neon | danger | Medium | .neon-danger-md
Neon | danger | High | .neon-danger-hi
Neon | danger | Extra High | .neon-danger-ex-hi
Neon | info | Standard | .neon-info-st
Neon | info | Medium | .neon-info-md
Neon | info | High | .neon-info-hi
Neon | info | Extra High | .neon-info-ex-hi
Neon | purple | Standard | .neon-purple-st
Neon | purple | Medium | .neon-purple-md
Neon | purple | High | .neon-purple-hi
Neon | purple | Extra High | .neon-purple-ex-hi

## Licence
Neon is under [MIT licence](https://opensource.org/licenses/mit-license.php)