# defram

CSS device frames.  
[Demo](https://vvvkor.github.io/defram/)

## Get started

### Install manually

Add the [distributed](https://github.com/vvvkor/defram/archive/master.zip) CSS to the head of your document.

```
<link rel="stylesheet" href="/css/defram.min.css">
``` 

### Use from CDN

### [jsDelivr](https://www.jsdelivr.com/package/npm/defram)

```html
<link href="https://cdn.jsdelivr.net/npm/defram/defram.min.css" rel="stylesheet">
```

## Usage

Default is medium sized white phone with portrait orientation.

```html
<div class="device">
  <img src="..." alt="">
</div>
```

[More examples](https://vvvkor.github.io/defram/)

### Modificator classes

- ``device-landscape``
- ``device-button-round``
- ``device-scroll`` (extra nested ``div`` required)
- ``device-scroll-thin``
- ``device-black``
- ``device-silver``
- ``device-tablet``
- ``device-laptop``
- ``device-desktop``
- ``device-xxs``
- ``device-xs``
- ``device-s``
- ``device-l``
- ``device-xl``
- ``device-xxl``

## Browser Support

* IE 10+ (CSS ``object-fit`` is not supported, so image can be distorted)
* Edge
* Up-to-date versions of Chrome, Firefox, Opera, Safari
* iOS 6+
* Android 4+

## License

[MIT](./LICENSE)