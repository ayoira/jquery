# jQuery to JavaScript Dictionary

## Selectors

### Accessing selectors

```js
$('[type="text"]');
```

```js
document.querySelector('type="text"');
```

```js
document.querySelectorAll('footer a');
```


### Accessing an id

```js
$('#example');
```

```js
document.getElementById('example');
```

### Accessing classes

```js
$('.example');
```

```js
const elements = document.getElementsByClassName('example');

for (let i = 0; i < element.length; i++) {
    elements[i];
}
```

### Accessing tags

```js
$('div');
```

```js
const elements = document.getElementsByTagName('div');

for (let i = 0; i < elements.length; i++) {
    elements[i];
}
```

## Classes

### Adding a class

```js
$(element).addClass('selected');
```

```js
element.classList.add('selected');
```

### Removing a class

```js
$(element).removeClass('selected');
```

```js
element.classList.remove('selected');
```

### Toggling a class

```js
$(element).toggleClass('selected');
```

```js
element.classList.toggle('selected');
```

### Getting a class

```js
$(element).hasClass('selected');
```

```js
element.classList.contains('selected');
```

## Styles

### Modifying CSS

```js
$(element).css('color', 'blue');
```

```js
element.style.color = 'blue';
```

## Attributes

### Geting attributes

```js
$(element).attr('href', 'index.html');
```

```js
element.getAttribute('href');
```

### Setting attributes

```js
$(element).attr('href', 'index.html');
```

```js
element.setAttribute('href', 'index.html');
```

## Event Listeners

```js
$(element).on('click', function() { 
	// ...
});
```

```js
element.addEventListener('click, function() {
	// ...
});
```

## Modifying Text

```js
$(element).text('New text');
```

```js
element.textContent = 'New text';
```
