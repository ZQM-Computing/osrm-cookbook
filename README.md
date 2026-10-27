# OSRM Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **OSRM cookbook** — routing engines from OpenStreetMap data. Not yet started in the Docker remainder on Node-1 and Node-3 (port target 5000). Patterns are planned from the design, not yet from verified runs. It is intended for Developers who serve routing queries from their own engine. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** OSRM patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. Intended to provide geospatial data feeds (satellite imagery, weather, routing, geocoding) for the ZQM game platform. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Developers who serve routing queries from their own engine.

## Prerequisites

- OSRM via Docker
- An OSM extract for your region
- Bash or PowerShell

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-extract-prepare` | Extracting and preparing OSM data for routing |
| 02 | `02-route-service` | Route, nearest, table, and match services |
| 03 | `03-profile-notes` | Car, foot, and bicycle profile differences |
| 04 | `04-pgrouting-pairing` | When to use OSRM versus pgRouting (see pgrouting-cookbook) |

## Repository layout

```text
osrm-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [pgrouting-cookbook](https://github.com/ZQM-Computing/pgrouting-cookbook) — Shortest path, driving distance, isochrones, turn restrictions
- [osmnx-cookbook](https://github.com/ZQM-Computing/osmnx-cookbook) — Street networks, routing, and OpenStreetMap graphs in Python
- [maplibre-cookbook](https://github.com/ZQM-Computing/maplibre-cookbook) — Custom layers, 3D terrain, performance tuning, interactive maps
