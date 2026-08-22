# Mapbox (mapbox)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
