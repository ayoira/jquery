# jQuery to JavaScript Dictionary

### Accessing ID

```js
const $idExample = $('#example');
```

```js
const id = document.getElementById('example');
```

### Accessing Class

```js
const $classExample = $('.example');
```

```js
const classExample = document.getElementsByClassName('example');

for (let i = 0; i < classExample.length; i++) {
    classExample[i];
}
```

### Accessing Tag

```js
const $tagExample = $('div');
```

```js
const tagExample = document.getElementsByTagName('div');

for (let i = 0; i < tagExample.length; i++) {
    tagExample[i];
}
```

