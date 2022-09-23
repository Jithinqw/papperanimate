# Papper Animate

An easy CSS animation library.

<div align="center">

![Version](https://img.shields.io/npm/v/papperanimate)
![License](https://img.shields.io/github/license/Jithinqw/papperanimate)
![File Size](https://img.shields.io/bundlephobia/minzip/papperanimate)
![Stars](https://img.shields.io/github/stars/Jithinqw/papperanimate)
![Forks](https://img.shields.io/github/forks/Jithinqw/papperanimate)
![Issues](https://img.shields.io/github/issues/Jithinqw/papperanimate)
![Downloads](https://img.shields.io/npm/dm/papperanimate)

</div>

# Installation

## Using NPM

This repository is distributed with [npm](https://www.npmjs.com/).
After [installing npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm),
you can install `papperanimate` with this command:

```sh
    npm install --save papperanimate
```

## Using CDN

Use as CDN link in your web site as below,

```html
<!DOCTYPE html>
<html>
  <head>
    <link
      href="https://cdn.jsdelivr.net/npm/papperanimate@0.0.8/papperanimate.min.css"
      rel="stylesheet" crossorigin="anonymous">
    <!-- or -->
    <link
      href="https://cdn.jsdelivr.net/npm/papperanimate@0.0.8/papperanimate.css"
      rel="stylesheet" crossorigin="anonymous">
  </head>
</html>
```

## Usage

Install npm module using ```npm i papperanimate```. 

```javascript
  import 'papperanimate';

  // Use papperanimate_animated class to convert any HTML
  // element into an animated HTML element.
  // Use any papperanimate class to animate.

  <h1 class="papperanimate_animated papperanimate_zoomInUp">
    Animate this heading.
  </h1>
```

## Animation List

### Basic
| Animation Name   | Class Name
|----------|:-------------
| bounce |  papperanimate_bounce |  
| flash |  papperanimate_flash |  
| pulse |  papperanimate_pulse |  
| rubberBand |  papperanimate_rubberBand |  
| shakeX |  papperanimate_shakeX |  
| shakeY |  papperanimate_shakeY |  
| tada |  papperanimate_tada |  
| Wobble |  papperanimate_wobble |  
| Jello |  papperanimate_jello |  

### Zoom
| Animation Name   | Class Name
|----------|:-------------
| ZoomIn |  papperanimate_zoomIn |  
| ZoomInDown |  papperanimate_zoomInDown |  
| ZoomInLeft |  papperanimate_zoomInLeft |  
| ZoomInRight |  papperanimate_zoomInRight |  
| ZoomInUp |  papperanimate_zoomInUp |  

### Light
| Animation Name   | Class Name
|----------|:-------------
| LightInLeft |  papperanimate_lightSpeedInLeft |  
| LightInRight |  papperanimate_lightSpeedInRight |  
| LightOutLeft |  papperanimate_lightSpeedOutRight |  
| LightOutRight | papperanimate_lightSpeedOutRight |  

### Flip
| Animation Name   | Class Name
|----------|:-------------
| Flip | papperanimate_flip |


## WebSite

A demo website lives [here](https://idyllic-cendol-aabe1b.netlify.app/), using
[TailwindCSS](https://tailwindcss.com/) and [Papperanimate](https://idyllic-cendol-aabe1b.netlify.app/).
Source code is under [site](./site/index.html) folder.

## License

[MIT](./LICENSE) &copy; [Jithin Zacharia](https://jithinqw.github.io/).
