# flalert
flalert is a simple (&amp; fllat) jQuery alert / notification plugin. 
The plugin supports natively icons from FontAwesome and animation from Animate.css (basic animation provided if Animate.css is not available).

## How To
The most simple way to use it is:
```
$.flalert('Hello World'); // basic call
 
$.flalert('Hello World', 'info'); // info type

$.flalert('Hello World', 'loading'); // loading mode

$.flalert('Hello World', function(){
	//see options below
});

```

### Options

type: 'success' | 'warning' | 'loading' | 'info' | 'error'
position: 'top left' | 'top right' | 'bottom' | ...
timeout: 4000
animation: 'fade'
animationSpeed: 'slow'
animateIn: null
animateOut: null
close: 'button'
classes: null
onClose: function()
onStart: function()

### Animate.css

If you are using Animate.css you can use custom In and Out animations

```
$.flalert('Hello World', { 
	animateIn: 'bounceIn', 
	animateOut: 'bounceOut', 
	close: 'self' 
});
```