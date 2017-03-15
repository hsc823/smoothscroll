# smoothscroll.js 3.1

## Support, Questions, and Collaboration

Documentation:
>First statement this plugin can support to window Object only
> 
 * Author Benjamin Intal - Gambit Technologies Inc
 * Version 3.1
 * License: Proprietary, Gambit Technologies Inc & Benjamin Intal

>Then, i have try to develope for multi-element in use...

>Ok...

Install by handler:
> snippet into your page

```html
<script type="text/javascript" src="js/smoothscroll.js"></script>
```
>
### set Attribute on the element: 
>data-gambitsmoothscroll="true"
### set property CSS on the element:
>overflow-y: auto; Or overflow-x: auto;
### Or
>overflow-y: scroll; Or overflow-x: scroll;

```html
<div style="height: 600px;overflow-y: auto;" data-gambitsmoothscroll="true"></div>
```

## Advanced Setting:

We can apply speed and amount for wheel Event.

And we suggest to keep fresh-enviroment you should open the `smoothscroll.js` to apply.

*Find to: `c = new GambitSmoothScroll();` change to:*

```js
c = new GambitSmoothScroll({
  speed: 900,
  amount: 300
});
```
Then, Saved to Enjoy!

## Building

>The source code is open, you can develope as you far!

>Or any exceptions try mail: kolleinvinh1993@gmail.com

>Thanks!
