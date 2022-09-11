# MSS-COLLECT


## Naming Conventions

[Design guidelines for namespaces](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/names-of-namespaces)

- CONSIDER using plural namespace names where appropriate

[Design guidelines for assemblies](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/names-of-assemblies-and-dlls)

### Rules for MSS-Collect

- literal or prfix "MSS" is never used in repo names (redundant)
- repository names for libraries (tools, api, extension) are lowercased
- repository names for products can be in any casing
- our preferred name parts for libraries are:
  - tools (tools.osm, tools.web
  - api (api.facebook, api.overpass, api.outdooractive)
  - extensions (extensions.logging)

## Repositories

### Inventory

Repository|Namespace
---|---
tools.vectortile|MSS.Tools.VectorTile.*
tools.osm|MSS.Tools.Osm.Primitives
tools.osm.wayclassifier|MSS.Tools.Osm.WayClassifier
tools.web.primitives|
tools.schema.org|
tools.pbf|MSS.Tools.Pbf.*

## Packages

