# jQuery to JavaScript Dictionary

### Accessing ID

```js
// jQ
const element = $('#example');
```

```js
// JS
const element = document.getElementById('example');
```

### Accessing a class

```js
// jQ
const elements = $('.example');
```

```js
// JS
const elements = document.getElementsByClassName('example');

for (let i = 0; i < element.length; i++) {
    elements[i];
}
```

### Accessing a tag

```js
// jQ
const elements = $('div');
```

```js
// JS
const elements = document.getElementsByTagName('div');

for (let i = 0; i < elements.length; i++) {
    elements[i];
}
```

### Adding a class

```js
// jQ
element.addClass('selected');
```

```js
// JS
element.classList.add('selected');
```

### Removing a class

```js
// jQ
element.removeClass('selected');
```

```js
// JS
element.classList.remove('selected');
```

### Modify CSS

```js
// jQ
element.css('color', 'blue');
```

```js
// JS
element.setAttribute('style', 'color: blue;');
element.style.color = 'blue';
```
