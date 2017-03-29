# flalert
flalert is a simple (&amp; fllat) jQuery alert / notification plugin. 
The plugin supports natively icons from FontAwesome and animation from Animate.css (basic animation provided if Animate.css is not available).

## How To
The most simple way to use it is:
```
$.flalert('Hello World');
```

### Animate.css

```
$.flalert('Hello World', { 
	animateIn: 'bounceIn', 
	animateOut: 'bounceOut', 
	close: 'self' 
});
```