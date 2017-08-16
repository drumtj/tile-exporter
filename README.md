## Tile Exporter

[Try Tile Exporter!](http://hanbyul-here.github.io/tile-exporter/)

![tile exporter screenshot](https://s3.amazonaws.com/assets-staging.mapzen.com/images/tile-exporter/tile-exporter-screenshot.png)

 The tile exporter grabs a [Mapzen vector tile](https://mapzen.com/projects/vector-tiles), offers you 3d preview in your browser, and then creates an .OBJ file of the scene that you can download. The tile exporter gets the `buildings`, `earth`, `water`, `landuse` layers of a tile. Learn more about layers in tiles at the [Mapzen Vector Tile documentation](https://mapzen.com/documentation/vector-tiles/layers/).

### How to run locally

Search component of tile exporter uses [React](https://facebook.github.io/react/), uses [webpack](https://webpack.github.io/) to bundle everything together.

```
npm install
npm run-script dev
```
Then go to `localhost:3000` on any browser.

If you want to build on local, you can run

```
npm build
```

This command builds `index.html` and  `bundle.js` file on the directory.

There is also a [vanilla javascript version](https://github.com/hanbyul-here/vector-tile-obj-exporter) of this, if you prefer.

- If you are interested in large scale, elevation data combined 3d print, check out [Vectiler](https://github.com/karimnaaji/vectiler).
- If you are interested in SVG export, check [SVG Export tool](https://github.com/hanbyul-here/svg-exporter).