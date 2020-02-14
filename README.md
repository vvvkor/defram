# defram

CSS device frames.  
[Demo](https://vvvkor.github.io/defram/)

## Get started

Download and add the [distributed](https://github.com/vvvkor/defram/archive/master.zip) CSS to the head of your document.

```html
<link rel="stylesheet" href="/css/defram.min.css">
``` 

Or use CDN like [jsDelivr](https://www.jsdelivr.com/package/npm/defram).

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/defram/defram.min.css">
```

## Usage

More examples on [demo page](https://vvvkor.github.io/defram/).

Default is medium sized white phone with portrait orientation.

```html
<div class="device">
  <img src="..." alt="">
</div>
```

Enable image scrolling with ``.device-scroll`` and extra nested ``div``.

```html
<div class="device device-scroll">
  <div>
    <img src="..." alt="">
  </div>
</div>
```

Embed ``iframe`` with live resource.

```html
<div class="device device-scroll">
  <iframe src="..."></iframe>
</div>
```

### Modificator classes

- ``device-tablet``
- ``device-laptop``
- ``device-desktop``
- ``device-landscape``
- ``device-button-round``
- ``device-scroll`` (extra nested ``div`` required)
- ``device-scroll-thin``
- ``device-black``
- ``device-silver``
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