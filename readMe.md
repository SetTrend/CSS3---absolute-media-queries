# CSS3 Absolute Length Media Query Probing Page
This package gives information about whether a web browser reads OS device information and applies it to CSS3 media queries using absolute lengths.

It outputs the width of the viewport according the media queries like:

```css
@media screen and (min-width: ...cm)
```

### Reason

Currently, many CSS design frameworks, like [Bootstrap](https://getbootstrap.com/) for instance, use pixels for their media queries. Yet, using pixels as a basis for deciding which layout to use is not robust or safe:

A user may use a large screen with `HDTV` resolution or a smartphone with `UHD` resolution. So, if web designers design their media queries on pixel basis, users of large screens may be presented with a smartphone layout while users of smartphones may be presented with a desktop layout.

### Conclusion

A way better solution for deciding on which layout to use for which device is to decide based on a browser viewport's width in absolute length, e. g. `cm`.

[See here](https://www.w3.org/TR/css-values-3/#absolute-lengths) for the official list of currently valid absolute lengths.

### How to Use

Download the project and open the `mediaQueries.html` file.

The HTML page will then display your web browser window's width in cm:

![Sample Image](sampleImage.png)

HTH,<br/>
[Axel Dahmen](http://www.axeldahmen.de/)