# [jQuery.json2HTML version 1.0](https://github.com/poweroftheforce/jquery-json2html)

A jQuery plugin for transforming a JavaScript array of objects into HTML.

### Installation for this demo

```sh
$ cd jquery-json2html
$ npm install -d
$ nodemon
```

note: The json2HTML jQuery plugin does not require node or anything else and can be downloaded by itself from here [https://github.com/poweroftheforce/jquery-json2html/blob/master/js/json2html.js](https://github.com/poweroftheforce/jquery-json2html/blob/master/js/json2html.js)

### Example Usage

```javascript
var html = [{
	nodeName: 'h1',
	html: 'Hello World'
}];

$('body').json2HTML(html);
```
