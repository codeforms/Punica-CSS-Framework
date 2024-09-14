## Punica CSS Framework 3.0 Beta
<p>
    <a href="https://github.com/codeforms/punica-themes" target="_blank"><strong>Nightly Builds</strong></a> |  
    <a href="https://github.com/codeforms/punica-templates"><strong>Templates</strong></a> |  
    <a href="https://github.com/codeforms/Punica-CSS-Framework/releases">Changelog</a>
</p>

<p>
    Punica CSS is a clean, lightweight, responsive, modern and fully customizable (even class names) pure CSS Framework based on SASS/SCSS with multi-theme support.
</p>

<p>
    <a href="https://github.com/codeforms/Punica-CSS-Framework/blob/master/LICENSE"><img src="https://img.shields.io/github/license/codeforms/Punica-CSS-Framework"></a>
    <a href="https://github.com/codeforms/Punica-CSS-Framework/releases"><img src="https://img.shields.io/github/v/release/codeforms/Punica-CSS-Framework"></a>
</p>

### Your custom CSS Framework
Punica also lets you create your custom CSS Framework. You can customize all the class names, apply your color scheme, enable or disable features of element/component, change all variables as your need and create your themes according to your taste. You are completely free!

### API for Developers
Punica API is based on SCSS maps for various options, values, generating class names, and themes. The Punica SCSS maps contain a key list of options/values/class names/theme variables. For example, you can customize the Punica as you wish with the ```options.scss``` and ```classnames.scss``` API files and of course generate your custom themes with [Punica's theme maps](https://github.com/codeforms/punica-themes). Take a look at the official [SASS docs](https://sass-lang.com/documentation/values/maps) to get started about SASS maps. 

### Install From CDN
If you want to quickly add the Punica CSS to your project, you can use the JsDelivr CDN;
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/codeforms/Punica-CSS-Framework@2.x.x/dist/punica.min.css" crossorigin="anonymous">
```

### HTML Markup & Including Material Symbols and Icons library
For your default setup, add the Punica CSS file to the <head> element of your HTML5 document. Also Punica CSS uses <a href="https://fonts.google.com/icons" target="_blank">Material Symbols and Icons</a> library, therefore you should include this library as well. That's it!
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Title</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
        <link rel="stylesheet" href="punica.min.css" />
    </head>
    <body>
    </body>
</html>
```
