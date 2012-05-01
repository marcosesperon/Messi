# Messi
A simple message plugin for jQuery.

Copyright 2012, Marcos Esperón: http://marcosesperon.es

## About
Messi is a jQuery plugin to show clean, elegant messages in a simple way. With Messi you will avoid to use default JavaScript alert notifications or new windows to provide extended information to the user.

Display text, html content, images and ajax requests with 5KB code.

![Sample Image](http://marcosesperon.es/apps/messi/messi-white.png)

## Demo
[http://marcosesperon.es/apps/messi/](http://marcosesperon.es/apps/messi/)

## Setup instructions
Messi requires jQuery framework to work, so include it first of all in your project. After that, include in the `head` of your page the stylesheet:

```html
<link rel="stylesheet" href="messi.min.css" />
```
And before the `</body>` the script:

```html
<script src="messi.min.js"></script>
```

Now you can start using Messi in your page, for example:

```js
new Messi('This is a message with Messi.', {title: 'Title'});
```

You will find more examples at [http://marcosesperon.es/apps/messi/](http://marcosesperon.es/apps/messi/)

Enjoy it!

## Requirements
* [jQuery](http://jquery.com/) v. 1.6+

## License
Released under the [MIT license](http://www.opensource.org/licenses/MIT).