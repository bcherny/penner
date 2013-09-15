# penner

A library for Penner's easing equations.

# "whose easing equations?"

See http://upshots.org/actionscript/jsas-understanding-easing

# usage

```js
	var t = 0,		// current time (ms, s, frames, ...)
		b = 10,		// initial value
		c = 100,	// change in value (final value - initial value)
		d = 2		// duration (same units as t)
		value = penner.easeOutQuad(t, b, c, d);
```

# included easing functions

`linear` `easeInQuad` `easeOutQuad` `easeInOutQuad` `easeInCubic` `easeOutCubic` `easeInOutCubic` `easeInQuart` `easeOutQuart` `easeInOutQuart` `easeInQuint` `easeOutQuint` `easeInOutQuint` `easeInSine` `easeOutSine` `easeInOutSine` `easeInExpo` `easeOutExpo` `easeInOutExpo` `easeInCirc` `easeOutCirc` `easeInOutCirc` `easeInElastic` `easeOutElastic` `easeInOutElastic` `easeInBack` `easeOutBack` `easeInOutBack` `easeInBounce` `easeOutBounce` `easeInOutBounce`

# size

| Raw					| 6400 bytes	|
| Uglified				| 3224 bytes	|
| Uglified + gzipped	| 881 bytes		|

# environment support

Any browser (as `window.penner`), AMD, CommonJS, NodeJS