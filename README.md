# NASA Open APIs (nasa-gov)

NASA Open APIs is the National Aeronautics and Space Administration's unified, public developer portal exposing space, earth science, planetary, heliophysics, and bioscience datasets at api.nasa.gov. A single API key issued through api.data.gov authenticates the family of APIs including APOD, Asteroids NeoWs, DONKI, Earth, EONET, EPIC, Exoplanet Archive, InSight, Mars Rover Photos, NASA Image and Video Library, TechPort, TechTransfer, SSD/CNEOS, Satellite Situation Center, GeneLab, TLE, and the Vesta/Moon/Mars Trek WMTS services. Together with 617+ open-source repositories on github.com/nasa they represent one of the most comprehensive open federal API surfaces in the world. As a US federal civilian agency NASA's data and software products are generally in the public domain, supporting a global ecosystem of researchers, educators, developers, and citizen scientists.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nasa-gov/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nasa-gov/refs/heads/main/apis.yml)

## Scope

- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Government
- Federal
- Space
- Earth Science
- Open Data
- Astronomy
- Planetary Science
- Heliophysics
- Bioscience
- NASA

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### NASA Astronomy Picture of the Day (APOD)

One of the most popular NASA websites, exposed as a JSON API. Returns the picture (or video) of the day with title, explanation, image URL, HD URL, optional copyright, and media type. Supports date, start_date/end_date ranges, count for random selections, and thumbs for video thumbnails.

- **Human URL:** [https://api.nasa.gov/](https://api.nasa.gov/)
- **Base URL:** `https://api.nasa.gov/planetary/apod`

#### Tags

- Astronomy
- Imagery
- Space
- NASA

#### Properties

- [Documentation](https://api.nasa.gov/)
- [Source Code](https://github.com/nasa/apod-api)
- [OpenAPI](openapi/apod-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apod.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apod.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/apod-schema.json) — [JSON Schema](https://json-schema.org/specification)

### NASA Asteroids NeoWs (Near Earth Object Web Service)

RESTful web service for near earth Asteroid information. Lets you search for asteroids by closest approach date, lookup a specific asteroid by NASA JPL small body ID, and browse the overall dataset. Endpoints include /feed, /neo/{id}, and /neo/browse.

- **Human URL:** [https://api.nasa.gov/](https://api.nasa.gov/)
- **Base URL:** `https://api.nasa.gov/neo/rest/v1`

#### Tags

- Asteroids
- Astronomy
- Near Earth Objects
- NASA

#### Properties

- [Documentation](https://api.nasa.gov/)
- [Source Code](https://github.com/SpaceRocks/NeoWs)
- [OpenAPI](openapi/asteroids-neows-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/asteroids-neows.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/asteroids-neows.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA DONKI Space Weather API

Space Weather Database Of Notifications, Knowledge, Information (DONKI) — a comprehensive on-line tool for space weather forecasters, scientists, and the general public. Exposes coronal mass ejections, geomagnetic storms, interplanetary shocks, solar flares, solar energetic particles, magnetopause crossings, radiation belt enhancements, and high-speed streams.

- **Human URL:** [https://ccmc.gsfc.nasa.gov/tools/DONKI/](https://ccmc.gsfc.nasa.gov/tools/DONKI/)
- **Base URL:** `https://api.nasa.gov/DONKI`

#### Tags

- Space Weather
- Heliophysics
- Solar
- NASA

#### Properties

- [Documentation](https://ccmc.gsfc.nasa.gov/tools/DONKI/)
- [OpenAPI](openapi/donki-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/donki.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/donki.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA Earth Imagery API

Unlock the significant public investment in earth observation data. Returns Landsat 8 imagery for a given latitude/longitude and date plus assets/metadata. Useful for deforestation monitoring, natural disaster damage assessment, and other Earth surface change detection.

- **Human URL:** [https://api.nasa.gov/](https://api.nasa.gov/)
- **Base URL:** `https://api.nasa.gov/planetary/earth`

#### Tags

- Earth
- Imagery
- Landsat
- Remote Sensing
- NASA

#### Properties

- [Documentation](https://api.nasa.gov/)
- [OpenAPI](openapi/earth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/earth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/earth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA EONET (Earth Observatory Natural Event Tracker)

Continuously updated, curated source of natural events occurring on Earth — wildfires, severe storms, volcanoes, sea/lake ice, drought, dust/haze, earthquakes, floods, landslides, manmade events, snow, temperature extremes, and water color. Returns events, categories, layers, sources, and magnitudes.

- **Human URL:** [https://eonet.gsfc.nasa.gov/docs/v3](https://eonet.gsfc.nasa.gov/docs/v3)
- **Base URL:** `https://eonet.gsfc.nasa.gov/api/v3`

#### Tags

- Earth
- Natural Events
- Disasters
- Earth Observatory
- NASA

#### Properties

- [Documentation](https://eonet.gsfc.nasa.gov/docs/v3)
- [OpenAPI](openapi/eonet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/eonet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eonet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA EPIC (Earth Polychromatic Imaging Camera)

The Earth Polychromatic Imaging Camera (EPIC) instrument aboard the DSCOVR satellite provides full-disc imagery of the Earth. Returns natural and enhanced color image metadata with centroid coordinates, spacecraft position, sun position, and lunar position. Both /natural and /enhanced collections supported.

- **Human URL:** [https://epic.gsfc.nasa.gov/about/api](https://epic.gsfc.nasa.gov/about/api)
- **Base URL:** `https://api.nasa.gov/EPIC`

#### Tags

- Earth
- Imagery
- DSCOVR
- NASA

#### Properties

- [Documentation](https://epic.gsfc.nasa.gov/about/api)
- [OpenAPI](openapi/epic-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/epic.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/epic.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA Exoplanet Archive API

Programmatic access to NASA's Exoplanet Archive — confirmed planets, planetary candidates, Kepler/K2/TESS objects of interest, microlensing events, and direct imaging detections. Uses the IPAC Table Access Protocol (TAP) with ADQL queries returning CSV, JSON, VOTable, or IPAC ASCII.

- **Human URL:** [https://exoplanetarchive.ipac.caltech.edu/docs/TAP/usingTAP.html](https://exoplanetarchive.ipac.caltech.edu/docs/TAP/usingTAP.html)
- **Base URL:** `https://exoplanetarchive.ipac.caltech.edu/TAP`

#### Tags

- Exoplanets
- Astronomy
- Astrophysics
- NASA

#### Properties

- [Documentation](https://exoplanetarchive.ipac.caltech.edu/docs/TAP/usingTAP.html)
- [OpenAPI](openapi/exoplanet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/exoplanet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/exoplanet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA InSight Mars Weather Service API

Per-Sol summary data for each of the last seven available Sols (Martian days) of weather at Elysium Planitia, measured by the InSight lander. Reports atmospheric temperature, wind speed and direction, and atmospheric pressure. Note - InSight ended operations in December 2022; data is historical.

- **Human URL:** [https://mars.nasa.gov/insight/weather/](https://mars.nasa.gov/insight/weather/)
- **Base URL:** `https://api.nasa.gov/insight_weather`

#### Tags

- Mars
- Weather
- InSight
- Planetary Science
- NASA

#### Properties

- [Documentation](https://mars.nasa.gov/insight/weather/)
- [OpenAPI](openapi/insight-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/insight.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/insight.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA Mars Rover Photos API

Image data gathered by NASA's Curiosity, Opportunity, Spirit, and Perseverance rovers on Mars. Each photo can be queried by Earth date or Martian sol with optional camera filter (FHAZ, RHAZ, MAST, CHEMCAM, MAHLI, MARDI, NAVCAM, PANCAM, MINITES).

- **Human URL:** [https://api.nasa.gov/](https://api.nasa.gov/)
- **Base URL:** `https://api.nasa.gov/mars-photos/api/v1`

#### Tags

- Mars
- Rovers
- Imagery
- Planetary Science
- NASA

#### Properties

- [Documentation](https://api.nasa.gov/)
- [Source Code](https://github.com/chrisccerami/mars-photo-api)
- [OpenAPI](openapi/mars-rover-photos-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mars-rover-photos.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mars-rover-photos.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA Image and Video Library API

API to access the NASA Image and Video Library at images.nasa.gov. Supports searching the Library, retrieving asset manifests, metadata, captions, and resolving rich-text URLs. Endpoints include /search, /asset, /metadata, /captions, and /album.

- **Human URL:** [https://images.nasa.gov/docs/images.nasa.gov_api_docs.pdf](https://images.nasa.gov/docs/images.nasa.gov_api_docs.pdf)
- **Base URL:** `https://images-api.nasa.gov`

#### Tags

- Imagery
- Video
- Media
- NASA

#### Properties

- [Documentation](https://images.nasa.gov/docs/images.nasa.gov_api_docs.pdf)
- [Source Code](https://github.com/nasa/NASA-Image-and-Video-Library)
- [OpenAPI](openapi/image-video-library-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/image-video-library.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/image-video-library.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA TechTransfer API

Structured, searchable developer access to NASA's patents, software, and Spinoff publications. Patents are part of the NASA Technology Transfer Program with the goal of bringing NASA technology down to Earth. Endpoints include /patent, /patent/issued, /software, and /spinoff.

- **Human URL:** [https://api.nasa.gov/](https://api.nasa.gov/)
- **Base URL:** `https://api.nasa.gov/techtransfer`

#### Tags

- Patents
- Software
- Technology Transfer
- Innovation
- NASA

#### Properties

- [Documentation](https://api.nasa.gov/)
- [Portal](https://technology.nasa.gov/)
- [OpenAPI](openapi/techtransfer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/techtransfer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/techtransfer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA SSD/CNEOS API

Solar System Dynamics and Center for Near-Earth Object Studies APIs at JPL. Includes CAD (close-approach data), SBDB (small body database lookup and query), Sentry (impact risk), Fireball, NHATS, mission design, and scout. Provides authoritative orbital, physical, and risk data for small bodies.

- **Human URL:** [https://ssd-api.jpl.nasa.gov/](https://ssd-api.jpl.nasa.gov/)
- **Base URL:** `https://ssd-api.jpl.nasa.gov`

#### Tags

- Solar System
- Near Earth Objects
- Asteroids
- NASA

#### Properties

- [Documentation](https://ssd-api.jpl.nasa.gov/)
- [OpenAPI](openapi/ssd-cneos-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ssd-cneos.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssd-cneos.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA TechPort API

API to make NASA technology project data available in a machine-readable format. Returns project title, description, benefits, status, dates, organizations, technology areas, and program. Useful for research discovery, technology scouting, and grant analysis.

- **Human URL:** [https://techport.nasa.gov/api](https://techport.nasa.gov/api)
- **Base URL:** `https://api.nasa.gov/techport/api`

#### Tags

- Technology
- Projects
- Research
- Innovation
- NASA

#### Properties

- [Documentation](https://techport.nasa.gov/api)
- [OpenAPI](openapi/techport-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/techport.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/techport.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA TLE API (Two-Line Element Set)

Two-line element set (TLE) data for earth-orbiting objects at a given point in time. Hosted in partnership outside api.nasa.gov but listed in the NASA Open APIs catalog. Returns satellite name, NORAD ID, line1, line2, and source attribution.

- **Human URL:** [https://tle.ivanstanojevic.me/](https://tle.ivanstanojevic.me/)
- **Base URL:** `https://tle.ivanstanojevic.me/api`

#### Tags

- Satellites
- Orbital
- TLE
- Space Situational Awareness
- NASA

#### Properties

- [Documentation](https://tle.ivanstanojevic.me/)
- [OpenAPI](openapi/tle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA Satellite Situation Center API

System to cast geocentric spacecraft location information into a framework of (empirical) geophysical regions and mappings of point locations along the spacecraft trajectory to/from locations of interest (e.g. magnetic conjunctions, IMF mappings).

- **Human URL:** [https://sscweb.gsfc.nasa.gov/WebServices/REST/](https://sscweb.gsfc.nasa.gov/WebServices/REST/)
- **Base URL:** `https://sscweb.gsfc.nasa.gov/WS/sscr/2`

#### Tags

- Satellites
- Heliophysics
- Spacecraft
- NASA

#### Properties

- [Documentation](https://sscweb.gsfc.nasa.gov/WebServices/REST/)
- [OpenAPI](openapi/satellite-situation-center-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/satellite-situation-center.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/satellite-situation-center.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA GeneLab Search API

Programmatic interface for GeneLab's public data repository — space biology omics datasets (genomic, transcriptomic, proteomic, metabolomic, metagenomic) for organisms studied in spaceflight or space-relevant environments. Search by term, type, and organism.

- **Human URL:** [https://genelab.nasa.gov/genelab-help/genelab-api](https://genelab.nasa.gov/genelab-help/genelab-api)
- **Base URL:** `https://genelab-data.ndc.nasa.gov/genelab/data`

#### Tags

- Bioscience
- Genomics
- Omics
- Space Biology
- NASA

#### Properties

- [Documentation](https://genelab.nasa.gov/genelab-help/genelab-api)
- [OpenAPI](openapi/genelab-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/genelab.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/genelab.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NASA Vesta/Moon/Mars Trek WMTS

A Web Map Tile Service (WMTS) for the Vesta, Moon, and Mars Trek imagery projects. Standardized OGC WMTS tiles consumable by Leaflet, OpenLayers, ArcGIS, and QGIS for planetary mapping applications.

- **Human URL:** [https://trek.nasa.gov/](https://trek.nasa.gov/)
- **Base URL:** `https://trek.nasa.gov/tiles/Mars/EQ`

#### Tags

- Maps
- WMTS
- Mars
- Moon
- Vesta
- NASA

#### Properties

- [Documentation](https://trek.nasa.gov/)
- [OpenAPI](openapi/trek-wmts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trek-wmts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trek-wmts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://api.nasa.gov/)
- [Documentation](https://api.nasa.gov/)
- [Sign Up](https://api.nasa.gov/#signUp)
- [Documentation](https://api.data.gov/docs/)
- [Rate Limits](https://api.data.gov/docs/rate-limits/)
- [Documentation](https://www.nasa.gov/data/)
- [Portal](https://data.nasa.gov/)
- [Portal](https://catalog.data.gov/organization/nasa-gov)
- [Portal](https://www.nasa.gov/)
- [Blog](https://www.nasa.gov/news/)
- [Privacy Policy](https://www.nasa.gov/privacy/)
- [Terms of Service](https://www.nasa.gov/website-and-section508-disclaimer/)
- [Documentation](https://www.nasa.gov/about-nasa/)
- [GitHub Organization](https://github.com/nasa)
- [Portal](https://code.nasa.gov/)
- [Source Code](https://github.com/nasa/api-docs)
- [Source Code](https://github.com/nasa/apod-api)
- [Source Code](https://github.com/nasa/eyes)
- [Source Code](https://github.com/nasa/openmct)
- [Source Code](https://github.com/nasa/cumulus)
- [Source Code](https://github.com/nasa/cFS)
- [Source Code](https://github.com/nasa/trick)
- [Portal](https://images.nasa.gov/)
- [Portal](https://technology.nasa.gov/)
- [Portal](https://techport.nasa.gov/)
- [Support](mailto:hq-open-innovation@mail.nasa.gov)
- [Documentation](https://www.nasa.gov/foia/)
- [Rate Limits](rate-limits/nasa-gov-rate-limits.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
