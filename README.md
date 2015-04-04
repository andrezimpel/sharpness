jquery-srcset
==========

use srcset in each and every browser today. display responsive and hi-res images.



## do it
<pre>
bower install jquery-srcset
</pre>

## quick start

Three quick start options are available:

- [download the latest release](https://github.com/andrezimpel/jquery-srcset/archive/master.zip).
- clone the repo: `git clone https://github.com/andrezimpel/jquery-srcset.git`.
- install with [bower](http://bower.io): `bower install jquery-srcset`.


## usage

### simple usage

just include the following scripts:

```html
<script src="http://code.jquery.com/jquery-1.9.0.js"></script>
<script src="path/to/bower_components/jquery-srcset/jquery-srcset.js"></script>
<script src="... others"></script>
```

then run:

```js
$('[data-hires]').jquery-srcset();
```

the image tag should look like this:
```html
<img src="/path/to/image.jpg" srcset="/path/to/image@2x.jpg 2x, /path/to/image-mobile.jpg 320w x1">
```

### browser based usage
```html
<script src="http://code.jquery.com/jquery-1.9.0.js"></script>
<script src="/path/to/bower_components/jquery-srcset/jquery.srcset.js"></script>
<script src="... others"></script>
```

then run:

```js
$('[srcset]').srcset();
```


## options
the following options are available
```js
$('[data-hires]').jquery-srcset({
  // check if the image is available
  ajax: true // default: true
});
```


## creator

**andre zimpel**

- <https://twitter.com/andrezimpel>
- <https://github.com/andrezimpel>

hit me up if you want to join!


## copyright and license

code and documentation copyright 2011-2014 andre zimpel. code released under [the MIT license](LICENSE).
