### parallax
---
https://github.com/wagerfield/parallax

```js
var scene = $('#scene').get(0);
var parallaxinstance = new Parallax(scene);

var scene = document.getElementById('scene');
var parallaxinstance = new Parallax(scene, {
  relativeInput: true
});

parallaxinstance.friction(0.2, 0.2);

var scene = document.getElementById('scene');
var parallaxInstance = new Parallax(scene);
```

```
<div data-relative=input="true" id="scene">
  <div data-depth="0.2"></div>
</div>
```

```
```

