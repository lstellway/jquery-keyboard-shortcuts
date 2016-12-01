# jQuery Keyboard Shortcuts
jQuery plugin that creates events triggered by keyboard combinations

## Options
- **debug** ([boolean](https://api.jquery.com/Types/#Boolean))
    - This option will log the keyboard shortcuts being executed in the console as they are triggered.

## Install with Bower
```
bower install --save jquery-keyboard-shortcuts
```

## Install with NPM
```
npm i jquery-keyboard-shortcuts
```

## Get Started

**Include jQuery**
```
<script type="text/javascript" src="https://code.jquery.com/jquery-3.1.1.min.js"></script>
```
**Include Keyboard Shortcuts jQuery Plugin**
```
<script type="text/javascript" src="js/jquery.keyboard-shortcuts.min.js"></script>
```
**Initialize**
```
<script type="text/javascript">
$(window).initKeyboard();
</script>
```
**Add events**
```
<script type="text/javascript">
$(window).on('Shift+▶', function(){
    // Execute function here
});
</script>
```