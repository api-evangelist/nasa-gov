# NASA Open APIs (nasa-gov)

API Evangelist catalog entry for **NASA Open APIs** — the National Aeronautics and Space Administration's unified, public developer portal exposing space, earth science, planetary, heliophysics, and bioscience datasets at [api.nasa.gov](https://api.nasa.gov/).

NASA is a US federal civilian agency and the data and software products surfaced here are generally in the public domain. A single API key issued through [api.data.gov](https://api.data.gov) authenticates the family of APIs.

## APIs profiled

| # | API | Base URL | Auth |
|---|-----|----------|------|
| 1 | Astronomy Picture of the Day (APOD) | `https://api.nasa.gov/planetary/apod` | api.data.gov key |
| 2 | Asteroids NeoWs | `https://api.nasa.gov/neo/rest/v1` | api.data.gov key |
| 3 | DONKI (Space Weather) | `https://api.nasa.gov/DONKI` | api.data.gov key |
| 4 | Earth Imagery | `https://api.nasa.gov/planetary/earth` | api.data.gov key |
| 5 | EONET (Natural Events) | `https://eonet.gsfc.nasa.gov/api/v3` | none |
| 6 | EPIC (DSCOVR full-disc Earth) | `https://api.nasa.gov/EPIC` | api.data.gov key |
| 7 | Exoplanet Archive (TAP/ADQL) | `https://exoplanetarchive.ipac.caltech.edu/TAP` | none |
| 8 | InSight Mars Weather (historical) | `https://api.nasa.gov/insight_weather` | api.data.gov key |
| 9 | Mars Rover Photos | `https://api.nasa.gov/mars-photos/api/v1` | api.data.gov key |
| 10 | NASA Image and Video Library | `https://images-api.nasa.gov` | none |
| 11 | TechTransfer (Patents/Software/Spinoff) | `https://api.nasa.gov/techtransfer` | api.data.gov key |
| 12 | TechPort | `https://api.nasa.gov/techport` | api.data.gov key |
| 13 | SSD/CNEOS (JPL small body) | `https://ssd-api.jpl.nasa.gov` | none |
| 14 | TLE (Two-Line Element) | `https://tle.ivanstanojevic.me/api` | none |
| 15 | Satellite Situation Center | `https://sscweb.gsfc.nasa.gov/WS/sscr/2` | none |
| 16 | GeneLab Search | `https://genelab-data.ndc.nasa.gov/genelab/data` | none |
| 17 | Vesta/Moon/Mars Trek WMTS | `https://trek.nasa.gov` | none |

## Repository layout

```
nasa-gov/
├── apis.yml                     APIs.json 0.16 catalog entry
├── README.md                    This file
├── openapi/                     OpenAPI 3.0.3 specs for each API
├── json-schema/                 JSON Schema definitions for key entities
├── json-ld/                     JSON-LD context for NASA Open APIs vocabulary
├── examples/                    Example request/response pairs
├── vocabulary/                  Domain vocabulary
├── capabilities/                Naftiko capability definitions per API
└── rate-limits/                 api.data.gov rate-limit declaration
```

## Rate limits

NASA Open APIs are fronted by [api.data.gov](https://api.data.gov/docs/rate-limits/):

- **DEMO_KEY** — 30 req/hour and 50 req/day per IP (evaluation only)
- **Registered API key** — 1000 req/hour per key default

Endpoints hosted off api.nasa.gov (EONET, SSD/CNEOS, Exoplanet Archive, TLE, images-api.nasa.gov, sscweb.gsfc.nasa.gov, genelab-data.ndc.nasa.gov, trek.nasa.gov) have their own quota and authentication patterns — most do not require a key.

## Open source

NASA maintains **617+ public repositories** at [github.com/nasa](https://github.com/nasa) including:

- [`nasa/api-docs`](https://github.com/nasa/api-docs) — canonical source for api.nasa.gov documentation
- [`nasa/apod-api`](https://github.com/nasa/apod-api) — APOD reference implementation
- [`nasa/openmct`](https://github.com/nasa/openmct) — Open Mission Control Technologies
- [`nasa/cFS`](https://github.com/nasa/cFS) — Core Flight System
- [`nasa/cumulus`](https://github.com/nasa/cumulus) — Earth science data framework
- [`nasa/trick`](https://github.com/nasa/trick) — Trick Simulation Environment
- [`nasa/eyes`](https://github.com/nasa/eyes) — NASA Eyes visualization

The [code.nasa.gov](https://code.nasa.gov/) portal indexes the broader software catalog.

## Sign up

Generate an API key from the [api.nasa.gov signup form](https://api.nasa.gov/#signUp). The same key works across every endpoint hosted on api.nasa.gov.

## Contact

- Open Innovation — `hq-open-innovation@mail.nasa.gov`
- FOIA — [nasa.gov/foia](https://www.nasa.gov/foia/)

## License

NASA content is generally a US Government Work in the public domain. See [NASA media usage guidelines](https://www.nasa.gov/multimedia/guidelines/index.html) for exceptions and attribution norms.

---

Maintained by [API Evangelist](https://apievangelist.com).
