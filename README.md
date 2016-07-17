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

## License

The GPLv3 License

Copyright (c) 2010-2015 Pankaj Anupam, http://pankajanupam.com