# INSPIRE Extension Specification

- **Title:** INSPIRE
- **Identifier:** <https://fiboa.org/inspire-extension/v0.3.0/schema.yaml>
- **Property Name Prefix:** inspire
- **Extension Maturity Classification:** Proposal
- **Owner**: @m-mohr

This document explains the INSPIRE Extension to the
[Field Boundaries for Agriculture (fiboa)](https://fiboa.org) and
[Vecorel](https://vecorel.org) specifications.

It adds support for a property that reflects the INSPIRE ID.

- Examples:
  - [GeoJSON](examples/geojson/)
  - [GeoParquet](examples/geoparquet/)
- [Schema](schema/schema.yaml)
- [Changelog](./CHANGELOG.md)

## Properties

| Property Name | Type   | Description |
| ------------- | ------ | ----------- |
| inspire:id    | string | **REQUIRED**. INSPIRE-compliant ID, an absolute and fully resolvable URI. Example: `https://geodaten.nrw.de/id/inspire-lc-dgl/landcoverunit/6467974` |

## Contributing

See the [contributing guideline](CONTRIBUTING.md) for more details.
