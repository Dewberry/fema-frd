# FEMA Flood Risk Data Extension Specification

- **Title:** FEMA Flood Risk Data
- **Identifier:** <https://https://github.com/Dewberry/fema-frd/v1.0.0/schema.json>
- **Field Name Prefix:** fema_frd
- **Scope:** Asset, Item, Collection, Catalog
- **Extension [Maturity Classification](https://github.com/radiantearth/stac-spec/tree/master/extensions/README.md#extension-maturity):** Proposal
- **Owner**: @slawler

FEMA Flood Risk Data is (currently) and R&D effort to evaluate the suitability of useing STAC to manage data associated with probabilistic flood risk analyses in large scale, cloud based modeling campaigns.

- Examples:
  - [Item example](examples/item.json): *TBD* Shows the basic usage of the extension in a STAC Item
  - [Collection example](examples/collection.json): *TBD* Shows the basic usage of the extension in a STAC Collection
- [JSON Schema](json-schema/schema.json) *TBD*
- [Changelog](./CHANGELOG.md)

## Item Fields


| Field Name           | Type                      | Description                                  |
| -------------------- | ------------------------- | -------------------------------------------- |
| fema_frd:tbd         | tbd                       | **REQUIRED**. tbd |
| fema_frd:tbd         | tbd                       | tbd                        |
| fema_frd:tbd         | tbd                       | tbd                        |

### Additional Field Information

#### fema_frd:tbd

This is a much more detailed description of the field `fema_frd:tbd`...

## Relation types

The following types should be used as applicable `rel` types in the
[Link Object](https://github.com/radiantearth/stac-spec/tree/master/item-spec/item-spec.md#link-object).

| Type           | Description                           |
| -------------- | ------------------------------------- |
| fancy-rel-type | This link points to a fancy resource. |

## Contributing

All contributions are subject to the
[STAC Specification Code of Conduct](https://github.com/radiantearth/stac-spec/blob/master/CODE_OF_CONDUCT.md).
For contributions, please follow the
[STAC specification contributing guide](https://github.com/radiantearth/stac-spec/blob/master/CONTRIBUTING.md) Instructions
for running tests are copied here for convenience.

### Running tests

The same checks that run as checks on PR's are part of the repository and can be run locally to verify that changes are valid. 
To run tests locally, you'll need `npm`, which is a standard part of any [node.js installation](https://nodejs.org/en/download/).

First you'll need to install everything with npm once. Just navigate to the root of this repository and on 
your command line run:
```bash
npm install
```

Then to check markdown formatting and test the examples against the JSON schema, you can run:
```bash
npm test
```

This will spit out the same texts that you see online, and you can then go and fix your markdown or examples.

If the tests reveal formatting problems with the examples, you can fix them with:
```bash
npm run format-examples
```