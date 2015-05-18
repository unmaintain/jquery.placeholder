# jquery.placeholder.js

Useful placeholder for text input and textarea.

## Use
- Set jQuery & jQuery.Placeholder.js.
```html
<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="jquery.placeholder.min.js"></script>
```

- Add markup.
```html
<div class="text-input-block">
    <input class="text-input js-placeholder" id="textInput" type="text" name="text">
    <label class="text-input-placeholder js-placeholder-text">Enter me...</label>
</div>
```

- Init plugin.
```javascript
// Simple init
$('.js-placeholder').placeholder();

// Default options
$('.js-placeholder').placeholder({
    // Set class on focus and unset on blur or empty
    activeClass: 'text-input-placeholder_state_active',
    
    // Use to find input
    inputSelector: '.js-placeholder',
    
    // Use to find placeholder text
    textSelector: '.js-placeholder-text'
});
```

## License

Released under the MIT license.
