# jQuery to JavaScript Dictionary

## Selectors

### Accessing selectors

```js
$('*');                // wildcard (all)
$('#demo');            // id
$('.demo');            // class
$('p');                // tag
$('[type="text"]');    // attribute
$('h1:first-of-type'); // pseudo
$('p, div');           // multiple
$('.footer h1');       // specific
```

```js
document.querySelector('#demo');
document.querySelector('.footer h1');
```

```js
document.querySelectorAll('*');
document.querySelectorAll('.demo');
document.querySelectorAll('p');
document.querySelectorAll('type="text"');
document.querySelectorAll('h1:first-of-type');
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
$('element').addClass('selected');
```

```js
element.classList.add('selected');
```

### Removing a class

```js
$('element').removeClass('selected');
```

```js
element.classList.remove('selected');
```

### Toggling a class

```js
$('element').toggleClass('selected');
```

```js
element.classList.toggle('selected');
```

### Getting a class

```js
$('element').hasClass('selected');
```

```js
element.classList.contains('selected');
```

## Styles

### Modifying CSS

```js
$('element').css('color', 'blue');
```

```js
element.style.color = 'blue';
```

## Attributes

### Geting attributes

```js
$('element').attr('href', 'index.html');
```

```js
element.getAttribute('href');
element.href;
```

### Setting attributes

```js
$('element').attr('href', 'index.html');
```

```js
element.setAttribute('href', 'index.html');
element.href = 'index.html';
```

## Traversing

### Parents

```js
$('element').parent();
```

```js
element.parentNode;
```

### Siblings

```js
$('element').siblings();
```

```js
element.previousSibling;
element.nextSibling;
```

### Children

## Append HTML string

```js
$('element').append('<p>A paragraph</p>');
```

```js
element.innerHTML = '<p>A paragraph</p>';
```

## Append elements

```js
var body = document.body;
var p = document.createElement('p');
p.textContent = 'A paragraph';

body.appendChild(p);
```


## Event listeners

```js
$('element').on('click', function() { 
	// ...
});
```

```js
element.addEventListener('click', function() {
	// ...
});
```

## Modifying Text

```js
$('element').text('New text');
```

```js
element.textContent = 'New text';
```

## Effects


