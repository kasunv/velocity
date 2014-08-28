##Velocity (0.11.9)

**Docs**  
[VelocityJS.org](http://VelocityJS.org)

**Quickstart**  

`bower install velocity`  
`npm install velocity-animate`  

`<script src="//cdn.jsdelivr.net/jquery.velocity/0.11.9/jquery.velocity.min.js"></script>`

**Which file should I use?**

See [VelocityJS.org/#dependencies](http://VelocityJS.org/#dependencies) for more information. If you're using Velocity with jQuery, just use `jquery.velocity.js`.

###**Learn**

- **Motion design**: http://smashingmagazine.com/2014/06/18/faster-ui-animations-with-velocity-js
- **Performance comparisons**: http://davidwalsh.name/css-js-animation
- **Workflow**: http://css-tricks.com/improving-ui-animation-workflow-velocity-js

###**New**

- 1.0.0: Coming soon. `jquery.velocity.js` will be renamed to `velocity.js`. jQuery will no longer be required, but Velocity will work as normal if jQuery is present. Two backwards-incompatible changes: 1) You must iterate through begin/complete/promise/progress callback elements since they are always passed wrapped in an array now. 2) The `bounce` and `elastic` easings have been removed.
- 0.1.0: `stop` now stops animations *immediately* (instead of just clearing the remainder of the animation queue). No other backwards-incompatible changes were made.

###**Comparisons**

- **Famo.us** is a full-fledged *mobile app framework* built around a physics engine.
- **CSS transitions** are meant for simple interface flourishes triggered by hover states.
- **jQuery's $.animate()** is slow and poorly-equipped for motion design.
- **Velocity** allows you to inject rich motion design into your UI.

###**Credits**

- <a href="https://stripe.com/blog/stripe-open-source-retreat">Stripe</a> sponsors Velocity's development.
- <a href="http://browserstack.com">BrowserStack</a> provides Velocity's testing services. 

====

[MIT License](LICENSE.md). © Julian Shapiro (http://twitter.com/shapiro).
