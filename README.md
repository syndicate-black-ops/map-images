# map-images

Map preview images for Syndicate Black Ops, served via GitHub Pages and downloaded by the in-game server browser for maps that don't ship with one.

## URL

```
https://syndicate-black-ops.github.io/map-images/<map>.jpg
```

`<map>` is the map name in lower case, for example
https://syndicate-black-ops.github.io/map-images/co_zylom.jpg.

## Adding a picture for your map

1. Make a 512x288 JPEG of your map.
2. Name it after the map, in lower case, with a `.jpg` extension: `co_mymap.jpg`.
3. Put it at the root of this repository and open a pull request.

A check on the pull request fails if the picture is not 512x288, is not a JPEG, has an upper-case
name, or if any other kind of file is added at the root.
