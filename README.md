# angular-vimeo-upload
This is a angular directive to upload file / blob to vimeo channel.

## Installation

You can install this package with `bower`.

### bower

```shell
bower install angular-vimeo-upload
```

Add a `<script>` to your `index.html`:

```html
<script src="/bower_components/angular-vimeo-upload/angular-vimeo-upload.js"></script>
```

Then add `ngpYoutubeUpload` as a dependency for your app:

```javascript
angular.module('myApp', ['ngpVimeoUpload']);
```

##Uses

Simply use the directive in a template. 
```html
<div angular-vimeo-upload access-token="VALID ACCESS TOKEN" data-video-title="{{name}}" data-video-desc="{{desc}}" ></div>
```

## Contribute

1. Fork and clone this repository
2. Install dependencies
    npm install
    bower install

3. Build/test with grunt
    grunt deploy

4. Make a Pull Request (it will only be merged if it passes the Travis build)

Or just help by creating issues and requesting new feature. I will update fast.

## License

The GPLv3 License

Copyright (c) 2010-2015 Pankaj Anupam, http://pankajanupam.com