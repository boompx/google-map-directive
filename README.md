# Google Map Directive Angularjs

## Usage

### Required files
```html
<script src="https://maps.googleapis.com/maps/api/js"></script>
<script src="path-to/1.4.*/angular.js"></script>
<script src="path-to/your-app.js"></script>
```


### Directive types

```html
<!-- 'E'lement -->
<google-map></google-map>

<!-- 'A'ttribute -->
<div google-map></div>
```

### Scope Options

* zipcode type `string`
* hasSkin type `undefined` (optional)

```html
<google-map class="gmap" id="gmap" zipcode="Object.ZipCode" has-skin></google-map>
```

id attribute is required! also you need to set the height and width via class="your-class" or inline.

### Credits
* Map Style: [Vallgatan](https://snazzymaps.com/style/32070/vallgatan) made by @joel
* Bootstrap theme (for demo purpose): [Flatly](http://bootswatch.com/flatly/) made by [Thomas Park](http://thomaspark.co/)

### Links
Browse more map styles at [snazzymaps.com](https://snazzymaps.com/)

### Licensed under [MIT](/LICENSE)