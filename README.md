# Animation

### Setup
##### 1. Link to the CSS animation library
###
###
```sh
<link rel="stylesheet" href="css/animate.css">
```
##### 2. Link and activate WOW.js
#
#
```sh
<script src="js/wow.min.js"></script>
<script>
    new WOW().init();
</script>
```
### Reveal CSS Animations
##### 1. Make an element revealable
###
###
Add the CSS class .wow to a HTML element: it will be invisible until the user scrolls to reveal it.
  (You can change this CSS class in the WOW settings to avoid name conflicts.)
  ```sh
<div class="wow">
    Content to Reveal Here
</div>
```
##### 2. Choose the animation style
#
#
```sh
<div class="wow bounceInUp">
  Content to Reveal Here
  </div>
```
### Advanced Options
**data-wow-duration**: Change the animation duration

**data-wow-delay**: Delay before the animation starts

**data-wow-offset**: Distance to start the animation (related to the browser bottom)

**data-wow-iteration**: Number of times the animation is repeated

```sh
<section class="wow slideInLeft" data-wow-duration="2s" data-wow-delay="5s">
</section>
<section class="wow slideInRight" data-wow-offset="10"  data-wow-iteration="10">
</section>

```
### Customize Settings
##
##

**boxClass**: Class name that reveals the hidden box when user scrolls.

**animateClass**: Class name that triggers the CSS animations
            (’animated’ by default for the animate.css library)

**offset:** Define the distance between the bottom of browser viewport and the top of hidden box.
When the user scrolls and reach this distance the hidden box is revealed.

**mobile**: Turn on/off WOW.js on mobile devices.

**live**: consatantly check for new WOW elements on the page.


```sh
<section class="wow slideInLeft" data-wow-duration="2s" data-wow-delay="5s">
</section>
<section class="wow slideInRight" data-wow-offset="10"  data-wow-iteration="10">
</section>
```

License
----
Developed by Matthieu Aussaguel – Initiated & Designed by Webalys

CSS animations powered by WOW.js and Animate.css
