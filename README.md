## Website Performance Optimization portfolio project

This is Front End NanoDegree Web Optimization Project.

To achieve what was asked several measures was taken:

1. Getting a PageInSight score above 90
 * CSS and JavaScript were minified by using websites (for [CSS] (http://cssminifier.com/) and for [Js] (https://jscompress.com/)  )
 * Loading fonts from Google was decreasing the score therefore it was removed. However, If you want to use a different font, you have to consider the load time of that font. In this case, default was Open Sans and loading OpenSans was unnecessary.
 * JavaScript and CSS were moved under the body tag. So, it will not affect the CRP.
 * Async tag is included for some of the JavaScript.
 * Print tag is added to the print.css for avoiding unnecessary loading.

2. Getting Rid of the jank
 * Extra style was used to decrease the slider time.
 * In main.js, There was FSL which was resolved.


Url of that page is [Here] (https://ernsnl.github.io/Web-Optimization/)
