# srcset

Demo version: https://russmaxdesign.github.io/srcset/

A simple test to determine if devices will display different images based on their device-pixel-ratio - using the  `srcset` attribute.

```
  <img
    srcset="assets/img/image-1x.jpg 1x,
            assets/img/image-15x.jpg 1.5x,
            assets/img/image-2x.jpg 2x,
            assets/img/image-3x.jpg 3x"
    src="assets/img/image-1x.jpg"
    alt="ALT TEXT">
```


- Devices that have 1x device pixel ratio should display an image labelled "1x"
- Devices that have 1.5x device pixel ratio should display an image labelled "1.5x"
- Devices that have 2x device pixel ratio should display an image labelled "2x"
- Devices that have 3x device pixel ratio should display an image labelled "3x"

Images are sized according to the following ration:

| Ratio | Size |
|-------|------|
| 1x    | 200  |
| 1.5x  | 300  |
| 2x    | 400  |
| 3x    | 600  |

![](assets/img/image-1x.jpg)

![](assets/img/image-15x.jpg)

![](assets/img/image-2x.jpg)

![](assets/img/image-3x.jpg)

See [Licence information](LICENCE) for use.
