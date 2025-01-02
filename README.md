# Mapbox (mapbox)

Mapbox is a living platform of location services. We equip innovators to keep
up with a changing world through using real-time data and map rendering
technologies that make it look easy. 

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/apis-json/artisanal/main/apis/mapbox.yml)

## Scope

- **Type:** Index 
- **Position:** Consumer 
- **Access:** 3rd-Party 

## Tags:

 - Maps, Mapping

## Timestamps

- **Created:** 2023/11/22 
- **Modified:** 2024-11-14 

## APIs

### Mapbox Tiling Service

Mapbox Tiling Service (MTS) is a tool for creating vector tilesets. With
MTS, you use sets of configuration options (tileset recipes) to transform
your geospatial data into vector tiles. The resulting tiles are hosted on
Mapbox servers for use in your applications.

**Human URL:** [https://docs.mapbox.com/api/maps/mapbox-tiling-service/](https://docs.mapbox.com/api/maps/mapbox-tiling-service/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/mapbox-tiling-service/)
### Vector Tiles API

The Mapbox Vector Tiles API serves vector tiles from Mapbox-hosted vector
tilesets.

**Human URL:** [https://docs.mapbox.com/api/maps/vector-tiles/](https://docs.mapbox.com/api/maps/vector-tiles/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/vector-tiles/)
### Mapbox Raster Tiles API

The Mapbox Raster Tiles API serves raster tiles generated from satellite
imagery tilesets and tilesets generated from raster data uploaded to
Mapbox.com.

**Human URL:** [https://docs.mapbox.com/api/maps/raster-tiles/](https://docs.mapbox.com/api/maps/raster-tiles/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/raster-tiles/)
### Mapbox Static Images API

The Mapbox Static Images API serves standalone, static map images
generated from Mapbox Studio styles. These images can be displayed on web
and mobile devices without the aid of a mapping library or API. They look
like an embedded map, but do not have interactivity or controls.

**Human URL:** [https://docs.mapbox.com/api/maps/static-images/](https://docs.mapbox.com/api/maps/static-images/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/static-images/)
### Mapbox Static Tiles API

The Mapbox Static Tiles API serves raster tiles generated from Mapbox
Studio styles. Raster tiles can be used in traditional web mapping
libraries like Mapbox.js, Leaflet, OpenLayers, and others to create
interactive slippy maps. The Static Tiles API is well-suited for maps with
limited interactivity or use on devices that do not support WebGL.

**Human URL:** [https://docs.mapbox.com/api/maps/static-tiles/](https://docs.mapbox.com/api/maps/static-tiles/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/static-tiles/)
### Mapbox Styles API

The Mapbox Styles API lets you read and change map styles, fonts, and
images. This API is the basis for Mapbox Studio. If you use Studio, Mapbox
GL JS, or the Mapbox Mobile SDKs, you are already using the Styles API.
This documentation is useful for software developers who want to
programmatically read and write these resources. It isn't necessary for
you to read or understand this reference to design or use Mapbox maps. You
will need to be familiar with the Mapbox Style Specification to use the
Styles API. The Mapbox Style Specification defines the structure of map
styles and is the open standard that helps Studio communicate with APIs
and produce maps that are compatible with Mapbox libraries.

**Human URL:** [https://docs.mapbox.com/api/maps/styles/](https://docs.mapbox.com/api/maps/styles/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/styles/)
### Mapbox Tilequery API

The Mapbox Tilequery API allows you to retrieve data about specific
features from a vector tileset, based on a given latitude and longitude.
The Tilequery API makes it possible to query for features within a radius,
do point-in-polygon queries, query for features in multiple composite
layers, and augment data from the Mapbox Geocoding API with custom data.

**Human URL:** [https://docs.mapbox.com/api/maps/tilequery/](https://docs.mapbox.com/api/maps/tilequery/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/tilequery/)
### Mapbox Uploads API

The Mapbox Uploads API transforms geographic data into tilesets that can
be used with maps and geographic applications. Given a wide variety of
geospatial formats, it normalizes projections and generates tiles at
multiple zoom levels to make data viewable on the web.

**Human URL:** [https://docs.mapbox.com/api/maps/uploads/](https://docs.mapbox.com/api/maps/uploads/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/uploads/)
### Mapbox Tiling Service (MTS)

Mapbox Tiling Service (MTS) is a tool for creating vector tilesets. With
MTS, you use sets of configuration options (tileset recipes) to transform
your geospatial data into vector tiles. The resulting tiles are hosted on
Mapbox servers for use in your applications.

**Human URL:** [https://docs.mapbox.com/api/maps/mapbox-tiling-service/](https://docs.mapbox.com/api/maps/mapbox-tiling-service/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/mapbox-tiling-service/)
### Mapbox Datasets API

The Mapbox Datasets API supports reading, creating, updating, and removing
features from a dataset. Using the Datasets API involves interacting with
two types of objects: datasets and features. Datasets contain one or more
collections of GeoJSON features. When you edit a dataset object, you
change the name and description properties of the dataset itself. When you
edit a feature object, you edit the contents of the dataset, such as the
coordinates or properties of a feature.

**Human URL:** [https://docs.mapbox.com/api/maps/datasets/](https://docs.mapbox.com/api/maps/datasets/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/datasets/)
### Mapbox Fonts API

The Mapbox Fonts API accepts fonts as raw binary data, allows those fonts
to be deleted, and generates encoded letters for map renderers. Two types
of fonts are supported: TrueType fonts, usually with .ttf file extensions,
and OpenType fonts, with .otf extensions. Fonts are managed on a
per-account basis. Styles can use any font from the same account.

**Human URL:** [https://docs.mapbox.com/api/maps/fonts/](https://docs.mapbox.com/api/maps/fonts/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/fonts/)

## Common Properties

- [Support](https://docs.mapbox.com/help/)
- [SDK](https://docs.mapbox.com/api/overview/#sdk-and-library-support)
- [Authentication](https://docs.mapbox.com/api/overview/#access-tokens-and-token-scopes)
- [Versioning](https://docs.mapbox.com/api/overview/#api-versioning)
- [Rate Limits](https://docs.mapbox.com/api/overview/#rate-limits)
- [CORS](https://docs.mapbox.com/api/overview/#https-and-cors)
- [Pagination](https://docs.mapbox.com/api/overview/#pagination)
- [Login](https://account.mapbox.com/auth/signin/)
- [Sign Up](https://account.mapbox.com/auth/signup/)
- [Terms of Service](https://www.mapbox.com/tos/)
- [Privacy](https://www.mapbox.com/privacy/)
- [Security](https://www.mapbox.com/platform/security/)
- [Cheatsheet](https://labs.mapbox.com/developer-cheatsheet/)
- [Getting Started](https://docs.mapbox.com/help/getting-started)
- [Tutorials](https://docs.mapbox.com/help/tutorials)
- [Videos](https://docs.mapbox.com/help/how-to-videos)
- [Troubleshooting](https://docs.mapbox.com/help/troubleshooting)
- [Glossay](https://docs.mapbox.com/help/glossary)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com

