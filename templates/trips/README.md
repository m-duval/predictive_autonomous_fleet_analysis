This is a minimal standalone version of the [TripsLayer example](https://deck.gl/#/examples/custom-layers/trip-routes)
on [deck.gl](http://deck.gl) website.

### Usage

Copy the content of this folder to your project. 

To see the base map, you need a [Mapbox access token](https://docs.mapbox.com/help/how-mapbox-works/access-tokens/). You can either set an environment variable:

```bash
export MapboxAccessToken=<mapbox_access_token>
```

Or set `MAPBOX_TOKEN` directly in `app.js`.

Other options can be found at [using with Mapbox GL](../../../docs/get-started/using-with-mapbox-gl.md).

```bash
# install dependencies
npm install
# or
yarn
# bundle and serve the app with webpack
npm start
```

### Data format
Sample data is stored in [deck.gl Example Data](https://github.com/uber-common/deck.gl-data/tree/master/examples/trips). To use your own data, checkout
the [documentation of TripsLayer](https://github.com/uber/deck.gl/tree/master/modules/experimental-layers/src/trips-layer).
