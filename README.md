# smoothscroll.js 3.1

##Support, Questions, and Collaboration

Documentation

Install by handler:
> snippet into your page

```html
<script type="text/javascript" src="js/smoothscroll.js"></script>
```
>
###set Attribute on the element: 
>data-gambitsmoothscroll="true"
###set property CSS on the element:
>overflow-y: auto; Or overflow-x: auto;
###Or
>overflow-y: scroll; Or overflow-x: scroll;

```html
<div id="container" style="height: 600px;overflow-y: auto;" data-gambitsmoothscroll="true"></div>
```

##Advanced Setting:

We can apply speed and amount for wheel Event.

And we suggest to keep fresh-enviroment you should open the `smoothscroll.js` to apply.

*Find to: `c = new GambitSmoothScroll();` change to:*

```javascript
c = new GambitSmoothScroll({
  speed: 900,
  amount: 300
});
```
Then, Saved to Enjoy!

##Building

>The source code is open, you can develope as you far!

>Or any exceptions try mail: kolleinvinh1993@gmail.com

>Thanks!
