# truncateMe
Jquery Plugin to truncate Text easily


## Requirements
  - Jquery


## Usages

```html

<p class="info truncateMe" data-truncateMe="100">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

<p class="info truncateMe" data-truncateMe="50">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

<p class="info truncateMe">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
```



## Js

```javascript
$.truncateMe();
```

## Default options Applied

```javascript
$.truncateMe({
    class: '.truncateMe', // Default
    trimTo: 50, // Default
    add: '.....' // Default
});
```


## Options Available

```javascript
$.truncateMe({
  class: '.truncateMe', // Default
  trimTo: 50, // Default
  trimEach: 'data-truncateMe', // Default - null  [Use attr]
  add: '....' // Default
});
```



## Basic Usage

```html
<p class="info truncateMe">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta, repellendus odio excepturi sequi, libero voluptatem laboriosam maiores tenetur, accusantium dolor ipsa laborum? Quos adipisci doloremque tempora fugit quisquam deleniti sunt nobis libero modi rem vitae ad, earum ab assumenda. Autem qui numquam blanditiis odio eius tempore mollitia asperiores facere molestiae.</p>
```

```javascript
$.truncateMe({
  trimTo: 100, // Characters
});
```

## Thank you.
