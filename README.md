## **Loadie.js** is a lightweight jQuery plugin to create a preloader that doesn't suck and that is used by big firms.

### 1. How to include Loadie.js

If you haven't already, include jQuery and the latest Loadie.js Script on the AJAX-driven page.

    <script src="http://code.jquery.com/jquery-latest.min.js">
    <script src="js/jquery.loadie.min.js">

### 2. How to initialize Loadie.js

Just put in the following jQuery code in your page to initialize Loadie.js.

    $('body').loadie(); // Change the wrapper if wanted.

### 3. How to update Loadie.js

If you haven't already, include jQuery and the latest Loadie.js Script on the AJAX-driven page.

    var percent = 0.74;
    $('body').loadie(percent); // Insert your percent as params.

### 4. Update your CSS files

If you are running a web page with a fixed header or something fixed or positioned absolute on the top, your loadie will not be visible, because there is something that is called z-index.

    .loadie { z-index: 9999; }

Insert this little snippet into your css file and everything should work fine.

## **Options**

At this moment Loadie.js (v1.0) doesn't support extensive options. If you have any ideas what Loadie.js could be, just leave us an issue at Github.

##Copyright

This nice little jQuery plugin was crafted by [@iDuuck](http://twitter.com/iDuuck) of [9elements](http://9elements.com).
