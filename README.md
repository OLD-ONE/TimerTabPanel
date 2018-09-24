# TimerTabPanel
Auto change tab panel with timer. This is jQuery, jQuery-UI Plugin.

# Installation
Download jquery.ttpanel.js and set your page.

## Requirement
jQuery 1.7.2 or later  
jQuery-ui 1.9.0 or later  
jQuery-ui.css Optional for CSS. Use same version of jquery-ui.

## Compatibility
jQuery 2.x  
jQuery 3.x  

# Usage
Load jquery.js, jquery-ui.js and jquery.ttpanel.js, set like below.
```javascript
<script>
$(function () {
  $("#tabs").timerTabPanel();
});
</script>
```

```html
<div id="tabs">
<ul>
<li><a href="#tab1">Title 1</a></li>
<li><a href="#tab2">Title 2</a></li>
       :
</ul>
<div id="tab1">tab1 contents</div>
<div id="tab2">tab2 contents</div>
       :
</div>
```

## Options
```javascript
<script>
$(function () {
  $("#tabs").timerTabPanel({
    startTab: 3,         // start tab number: defalut 1
    timeInterval: 1000,  // time interval (ms): default: 3000
  });
});
</script>
```

# Example
Open the index.html file located in the 'example' folder.

# License
This plugin is released under the MIT License.
