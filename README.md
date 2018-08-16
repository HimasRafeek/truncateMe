# truncateMe
Jquery Plugin to truncate texts easily


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

## Default options Applied / Option Available

```javascript
 $.truncateMe({
      elem: '.truncateMe',                                // Default  - jQuery Selector
      trimTo: 50,                                         // Default  - Words By Default
      trimEach: null,                                     // Default  - attr for trim Individual [data-truncateme="5"]
      add: '<span class="truncateMe-dots">.....</span>',  // Default  - after truncation (concat)
      words: true                                         // Default  - Limit with words (Set to false to limit by Characters)
  });
```



## Basic Usage

```html
<p class="info truncateMe">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta, repellendus odio excepturi sequi, libero voluptatem laboriosam maiores tenetur, accusantium dolor ipsa laborum? Quos adipisci doloremque tempora fugit quisquam deleniti sunt nobis libero modi rem vitae ad, earum ab assumenda. Autem qui numquam blanditiis odio eius tempore mollitia asperiores facere molestiae.</p>
```

```javascript
$.truncateMe({
  trimTo: 10, // Words By Default
});
```

## Version 1.5.0
More Features Added.
