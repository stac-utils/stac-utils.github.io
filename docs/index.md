# stac-utils

Tools for working with [SpatioTemporal Asset Catalogs (STAC)](https://stacspec.org/).

## How to find what you need

This organization has a large number of repositories in a variety of languages for many types of users.
Here, we categorize each repository by its utility to users as described on [STAC website](https://stacspec.org):

- 👩‍🍳 **Data providers** produce geospatial data and index those data with STAC
- 💁‍♂️ **Developers** build and maintain infrastructure to serve STAC to the world
- 😋 **Data users** use STAC to find, visualize, and use geospatial data

Each table is sorted by the number of Github stars at the time of the file render.
Any issues with or updates to these tables can be opened on the stac-utils [.github](https://github.com/stac-utils/.github).
For more information on each repository, see its respective README.

### Python

| Repository | Description | Badges | 👩‍🍳 |💁‍♂️ | 😋️ |
| -- | -- | -- | -- | -- | -- |
| [pystac](https://github.com/stac-utils/pystac) | Python library for working with any SpatioTemporal Asset Catalog (STAC) | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/pystac?style=flat-square) | ✅ | ✅ | ✅ |
| [stac-fastapi](https://github.com/stac-utils/stac-fastapi) | STAC API implementation with FastAPI.  | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-fastapi?style=flat-square) |  | ✅ |  |
| [pystac-client](https://github.com/stac-utils/pystac-client) | Python client for searching STAC APIs | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/pystac-client?style=flat-square) |  |  | ✅ |
| [stac-geoparquet](https://github.com/stac-utils/stac-geoparquet) | Convert STAC items between JSON, GeoParquet, pgstac, and Delta Lake. | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-geoparquet?style=flat-square) |  | ✅ | ✅ |
| [titiler-pgstac](https://github.com/stac-utils/titiler-pgstac) | TiTiler + PgSTAC | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/titiler-pgstac?style=flat-square) |  | ✅ |  |
| [stactools](https://github.com/stac-utils/stactools) | Command line utility and Python library for STAC | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stactools?style=flat-square) | ✅ |  |  |
| [stac-fastapi-pgstac](https://github.com/stac-utils/stac-fastapi-pgstac) | PostgreSQL backend for stac-fastapi using pgstac (https://github.com/stac-utils/pgstac) | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-fastapi-pgstac?style=flat-square) |  | ✅ |  |
| [stac-pydantic](https://github.com/stac-utils/stac-pydantic) | Pydantic data models for the STAC spec | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-pydantic?style=flat-square) |  | ✅ |  |
| [xstac](https://github.com/stac-utils/xstac) | STAC from xarray | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/xstac?style=flat-square) |  |  | ✅ |
| [stac-fastapi-elasticsearch-opensearch](https://github.com/stac-utils/stac-fastapi-elasticsearch-opensearch) | Elasticsearch backend for stac-fastapi with Opensearch support. | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-fastapi-elasticsearch-opensearch?style=flat-square) |  | ✅ |  |
| [stac-validator](https://github.com/stac-utils/stac-validator) | Validator for the stac-spec | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-validator?style=flat-square) | ✅ |  | ✅ |
| [rustac-py](https://github.com/stac-utils/rustac-py) | The power of Rust for the Python STAC ecosystem | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/rustac-py?style=flat-square) |  | ✅ | ✅ |
| [xpystac](https://github.com/stac-utils/xpystac) | For extending xarray.open_dataset to accept pystac objects | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/xpystac?style=flat-square) |  |  | ✅ |
| [stac-asset](https://github.com/stac-utils/stac-asset) | Read and download STAC Assets, using a variety of authentication schemes | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-asset?style=flat-square) |  |  | ✅ |
| [stac-fastapi-geoparquet](https://github.com/stac-utils/stac-fastapi-geoparquet) | A stac-fastapi server implementation with a stac-geoparquet backend | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-fastapi-geoparquet?style=flat-square) |  | ✅ |  |
| [stac-check](https://github.com/stac-utils/stac-check) | Linting and validation tool for STAC | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-check?style=flat-square) | ✅ |  |  |
| [stac-task](https://github.com/stac-utils/stac-task) | Provides a class interface for running custom algorithms on STAC ItemCollections | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-task?style=flat-square) |  | ✅ |  |
| [stac-api-validator](https://github.com/stac-utils/stac-api-validator) | A STAC API validation client | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-api-validator?style=flat-square) |  | ✅ |  |
| [stac-fastapi-sqlalchemy](https://github.com/stac-utils/stac-fastapi-sqlalchemy) | PostgreSQL backend for stac-fastapi using SQLAlchemy | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-fastapi-sqlalchemy?style=flat-square) |  | ✅ |  |

### Javascript

| Repository | Description | Badges | 👩‍🍳 |💁‍♂️ | 😋️ |
| -- | -- | -- | -- | -- | -- |
| [stac-server](https://github.com/stac-utils/stac-server) | A Node-based STAC API, AWS Serverless, OpenSearch | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-server?style=flat-square) |  | ✅ |  |
| [stac-fields](https://github.com/stac-utils/stac-fields) | A minimal STAC library that contains a list of STAC fields with some metadata and helper functions for styling as HTML. | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-fields?style=flat-square) | ✅ | ✅ | ✅ |
| [stac-migrate](https://github.com/stac-utils/stac-migrate) | A tool to migrate Items, Catalogs and Collections from old versions to the most recent one. | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-migrate?style=flat-square) | ✅ | ✅ |  |

### Other

These provide tooling for other languages, databases, visualizations, and other functionality.

| Repository | Description | Badges | 👩‍🍳 |💁‍♂️ | 😋️ |
| -- | -- | -- | -- | -- | -- |
| [pgstac](https://github.com/stac-utils/pgstac) | Schema, functions and a python library for storing and accessing STAC collections and items in PostgreSQL | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/pgstac?style=flat-square) |  | ✅ |  |
| [rustac](https://github.com/stac-utils/rustac) | The power of Rust for the STAC ecosystem | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/rustac?style=flat-square) | ✅ | ✅ | ✅ |
| [qgis-stac-plugin](https://github.com/stac-utils/qgis-stac-plugin) | QGIS plugin for reading STAC APIs | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/qgis-stac-plugin?style=flat-square) |  |  | ✅ |
| [stac-layer](https://github.com/stac-utils/stac-layer) | Visualize a STAC Item or Collection on a Leaflet Map | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-layer?style=flat-square) |  |  | ✅ |
| [stac-terminal](https://github.com/stac-utils/stac-terminal) | Output info on STAC Items in the terminal | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-terminal?style=flat-square) |  |  | ✅ |
| [stac4s](https://github.com/stac-utils/stac4s) | A Scala library with primitives to build applications using the SpatioTemporal Asset Catalogs specification | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac4s?style=flat-square) | ✅ | ✅ | ✅ |
| [stac-crosswalks](https://github.com/stac-utils/stac-crosswalks) | Common metadata crosswalks to help people map from their existing data into STAC | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-crosswalks?style=flat-square) | ✅ |  |  |
| [stac-geoparquet-data](https://github.com/stac-utils/stac-geoparquet-data) | Example stac-geoparquet data files. | ![GitHub Repo stars](https://img.shields.io/github/stars/stac-utils/stac-geoparquet-data?style=flat-square) | ✅ |  |  |

## Questions or issues?

For general questions, use [the "STAC software" category stac-spec discussions](https://github.com/radiantearth/stac-spec/discussions).
For repository-specific questions or issues, use that repository's discussions or issues page.
For issues with this text, use [the organization's .github repository's issues page](https://github.com/stac-utils/.github/issues).
