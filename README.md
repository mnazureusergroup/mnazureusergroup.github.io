# mnazureusergroup.github.io

All of the content is static at the moment. 

## Update next date:

**index.html** change this block:

```html

```

***js/main.js*** change this block:

```javascript
$('#countdown').countdown({ until: new Date("2021-05-06T16:00:00.000-05:00"); }); // enter event day
```

## Update the Event count and Member Count

**index.html** change this block (note the `data-to` attributes where the values are held)

```html
<div class="fact col-xs-6 col-md-3 col-lg-3">
    <p class="timer" data-to="2513" data-speed="3000"></p>
    <i class="fa fa-2x fa-users"></i>
    <p>members</p>

</div>

<div class="fact col-xs-6 col-md-3 col-lg-3">
    <p class="timer" data-to="57" data-speed="3000"></p>
    <i class="fa fa-2x fa-clock-o"></i>
    <p>past events</p>
</div>
```
