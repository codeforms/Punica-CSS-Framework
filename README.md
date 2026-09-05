## Punica CSS Framework v3
<p>
    <a href="https://codeforms.github.io/Punica-CSS-Framework" target="_blank"><strong>Documentation</strong></a> |
    <a href="https://github.com/codeforms/Punica-CSS-Framework/releases">Changelog</a>
</p>
<p>
    Punica CSS Framework is a clean, lightweight, responsive, modern, and fully customizable <ins><b>API-Driven Framework</b></ins> built with Sass/SCSS, offering multi-theme support.
</p>
<p>
    <a href="https://github.com/codeforms/Punica-CSS-Framework/blob/master/LICENSE"><img src="https://img.shields.io/github/license/codeforms/Punica-CSS-Framework"></a>
    <a href="https://github.com/codeforms/Punica-CSS-Framework/releases"><img src="https://img.shields.io/github/v/release/codeforms/Punica-CSS-Framework"></a>
</p>

### Core Features
* Fully customizable, API-driven structure
* Modular and extensible architecture
* Flexible, fully functional multi-theme support
* Enable or disable modules, utilities, and their features
* Customize module and utility settings
* Rename module and utility class names
* Define project-specific variables
* Dynamic color scale generation from color variables
* Simple and functional debugging
* Clean and readable code structure

### Install From CDN
If you want to quickly add the Punica CSS to your project, you can use the JsDelivr CDN;
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/codeforms/Punica-CSS-Framework@3.x.x/dist/punica.min.css" crossorigin="anonymous">
```
for Default Dark Theme;
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/codeforms/Punica-CSS-Framework@3.x.x/dist/punica-dark.min.css" crossorigin="anonymous">
```
### HTML Markup
For your default setup, add the Punica CSS file to the <head> element of your HTML5 document.
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Title</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/codeforms/Punica-CSS-Framework@3.x.x/dist/punica.min.css" crossorigin="anonymous">
    </head>
    <body>
    </body>
</html>
```
## Punica 3.0 API for Developers
Punica is built around a flexible, API-driven architecture that gives developers full control over the framework's configuration, modules, utilities, and themes.

Instead of modifying the settings in the framework's API files (```options.scss``` and ```utilities.scss```), Punica allows you to define or override all configuration settings through your theme maps. This makes it possible to build a customized version of Punica without having to modify the framework itself.

## Configuration & API
Punica's core configuration can be accessed and customized through its SCSS API. The ```options.scss``` API contains the default variables and settings used throughout the framework and can be customized to match the requirements of your project.

However, directly modifying the settings in ```options.scss``` or ```utilities.scss``` is not required. You can override the framework's defaults through your own theme map, keeping your project-specific configuration separate from Punica's source code.

## Customize Without Changing the Core Files
One of the main goals of Punica's API is to keep customization separate from the framework itself. Instead of modifying framework files such as ```options.scss``` and ```utilities.scss```, you can define your own theme map and use it to customize or override all settings provided by these files. This keeps your project's customizations separate from the framework's source code and makes future upgrades easier.

The result is a framework that can be adapted to your project's design system while keeping the underlying Punica architecture intact.

## Customize the Punica
Punica is designed to be more than a collection of predefined CSS classes. Its API provides a configurable foundation that you can adapt to your own needs and preferences.

#### You decide;
* Which modules and utilities are included
* Which features are enabled
* Which utility features are available
* How module and utility class names are defined
* How colors and color scales are generated
* How individual themes are configured
* Which variables and settings are used

Punica provides the foundation. <ins>You define the rules</ins>.