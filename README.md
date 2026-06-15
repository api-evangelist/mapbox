# Mapbox (mapbox)

Mapbox is a leading mapping and location data platform that provides tools and services to help developers and businesses create custom maps, visualize geospatial data, and build location-aware applications. Their platform offers a wide range of mapping technologies, from interactive maps and map design tools to geocoding and routing services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mapbox/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mapbox/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Mapping
- Maps
- Geospatial
- Location

## Timestamps

- **Created:** 2023-11-22
- **Modified:** 2026-05-30

## APIs

### Mapbox Tiling Service

Mapbox Tiling Service (MTS) is a tool for creating vector tilesets. With MTS, you use sets of configuration options (tileset recipes) to transform your geospatial data into vector tiles. The resulting tiles are hosted on Mapbox servers for use in your applications.

- **Human URL:** [https://docs.mapbox.com/api/maps/mapbox-tiling-service/](https://docs.mapbox.com/api/maps/mapbox-tiling-service/)
- **Base URL:** `https://api.mapbox.com`

#### Tags

- Mapping
- Tiles
- Vector Tiles

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/mapbox-tiling-service/)
- [OpenAPI](openapi/mapbox-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mapbox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapbox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mapbox Vector Tiles API

The Mapbox Vector Tiles API serves vector tiles from Mapbox-hosted vector tilesets.

- **Human URL:** [https://docs.mapbox.com/api/maps/vector-tiles/](https://docs.mapbox.com/api/maps/vector-tiles/)
- **Base URL:** `https://api.mapbox.com`

#### Tags

- Mapping
- Tiles
- Vector Tiles

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/vector-tiles/)
- [Postman Collection](collections/mapbox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapbox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mapbox Raster Tiles API

The Mapbox Raster Tiles API serves raster tiles generated from satellite imagery tilesets and tilesets generated from raster data uploaded to Mapbox.com.

- **Human URL:** [https://docs.mapbox.com/api/maps/raster-tiles/](https://docs.mapbox.com/api/maps/raster-tiles/)
- **Base URL:** `https://api.mapbox.com`

#### Tags

- Mapping
- Tiles
- Raster Tiles

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/raster-tiles/)
- [Postman Collection](collections/mapbox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapbox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mapbox Static Images API

The Mapbox Static Images API serves standalone, static map images generated from Mapbox Studio styles. These images can be displayed on web and mobile devices without the aid of a mapping library or API.

- **Human URL:** [https://docs.mapbox.com/api/maps/static-images/](https://docs.mapbox.com/api/maps/static-images/)
- **Base URL:** `https://api.mapbox.com`

#### Tags

- Mapping
- Static Images

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/static-images/)
- [Postman Collection](collections/mapbox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapbox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mapbox Static Tiles API

The Mapbox Static Tiles API serves raster tiles generated from Mapbox Studio styles. Raster tiles can be used in traditional web mapping libraries like Mapbox.js, Leaflet, OpenLayers, and others to create interactive slippy maps.

- **Human URL:** [https://docs.mapbox.com/api/maps/static-tiles/](https://docs.mapbox.com/api/maps/static-tiles/)
- **Base URL:** `https://api.mapbox.com`

#### Tags

- Mapping
- Tiles
- Static Tiles

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/static-tiles/)
- [Postman Collection](collections/mapbox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapbox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mapbox Styles API

The Mapbox Styles API lets you read and change map styles, fonts, and images. This API is the basis for Mapbox Studio.

- **Human URL:** [https://docs.mapbox.com/api/maps/styles/](https://docs.mapbox.com/api/maps/styles/)
- **Base URL:** `https://api.mapbox.com`

#### Tags

- Mapping
- Styles

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/styles/)
- [Postman Collection](collections/mapbox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapbox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mapbox Tilequery API

The Mapbox Tilequery API allows you to retrieve data about specific features from a vector tileset, based on a given latitude and longitude. The Tilequery API makes it possible to query for features within a radius, do point-in-polygon queries, query for features in multiple composite layers, and augment data from the Mapbox Geocoding API with custom data.

- **Human URL:** [https://docs.mapbox.com/api/maps/tilequery/](https://docs.mapbox.com/api/maps/tilequery/)
- **Base URL:** `https://api.mapbox.com`

#### Tags

- Mapping
- Tile Query
- Geospatial

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/tilequery/)
- [Postman Collection](collections/mapbox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapbox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mapbox Uploads API

The Mapbox Uploads API transforms geographic data into tilesets that can be used with maps and geographic applications. Given a wide variety of geospatial formats, it normalizes projections and generates tiles at multiple zoom levels to make data viewable on the web.

- **Human URL:** [https://docs.mapbox.com/api/maps/uploads/](https://docs.mapbox.com/api/maps/uploads/)
- **Base URL:** `https://api.mapbox.com`

#### Tags

- Mapping
- Uploads
- Geospatial

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/uploads/)
- [Postman Collection](collections/mapbox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapbox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mapbox Datasets API

The Mapbox Datasets API supports reading, creating, updating, and removing features from a dataset. Datasets contain one or more collections of GeoJSON features.

- **Human URL:** [https://docs.mapbox.com/api/maps/datasets/](https://docs.mapbox.com/api/maps/datasets/)
- **Base URL:** `https://api.mapbox.com`

#### Tags

- Mapping
- Datasets
- GeoJSON

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/datasets/)
- [Postman Collection](collections/mapbox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapbox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mapbox Fonts API

The Mapbox Fonts API accepts fonts as raw binary data, allows those fonts to be deleted, and generates encoded letters for map renderers. Two types of fonts are supported: TrueType fonts (.ttf) and OpenType fonts (.otf).

- **Human URL:** [https://docs.mapbox.com/api/maps/fonts/](https://docs.mapbox.com/api/maps/fonts/)
- **Base URL:** `https://api.mapbox.com`

#### Tags

- Mapping
- Fonts

#### Properties

- [Documentation](https://docs.mapbox.com/api/maps/fonts/)
- [Postman Collection](collections/mapbox.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapbox.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/mapbox)
- [LinkedIn](https://www.linkedin.com/company/mapbox)
- [Support](https://docs.mapbox.com/help/)
- [SDK](https://docs.mapbox.com/api/overview/#sdk-and-library-support)
- [Authentication](https://docs.mapbox.com/api/overview/#access-tokens-and-token-scopes)
- [Versioning](https://docs.mapbox.com/api/overview/#api-versioning)
- [Rate Limits](https://docs.mapbox.com/api/overview/#rate-limits)
- [C O R S](https://docs.mapbox.com/api/overview/#https-and-cors)
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
- [Glossary](https://docs.mapbox.com/help/glossary)
- [Website](https://www.mapbox.com/)
- [Features](undefined)
- [L L Ms Txt](https://docs.mapbox.com/llms.txt)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** http://apievangelist.com
