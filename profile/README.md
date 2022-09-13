# MSS-COLLECT

## Repositories

Repository|Namespace|Description
---|---|---
trv.web||TRV website specific settings and tools based on TrailBlog Api TODO rename into webcontent.trv
webcontent.scenery|| scenery website specific settings and tools based on TrailBlog Api
roque-draft||should be renamed!
tools.vectiles|MSS.Tools.VectTiles.*| ex "vectortiles"
tools.osm|MSS.Tools.Osm.Primitives
tools.osm.wayclassifier|MSS.Tools.Osm.WayClassifier
tools.web.primitives|
tools.schema.org|
tools.pbf|MSS.Tools.Pbf.*
tools.pbf.benchmarks|MSS.Tools.Pbf.Benchmarks| high level benchmraks executed via Github Actions
## Packages


## Naming Conventions

[Design guidelines for namespaces](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/names-of-namespaces)

- CONSIDER using plural namespace names where appropriate

[Design guidelines for assemblies](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/names-of-assemblies-and-dlls)

### Rules for MSS-Collect

- literal or prefix "MSS" is never used in repo names (redundant)
- repository names for libraries (tools, api, extension) are lowercased
- repository names for products can be in any casing
- our preferred name parts are:
  - tools (tools.osm, tools.web) implemented as dotnet classlibraries
  - api (api.facebook, api.overpass, api.outdooractive) implemented as dotnet classlibraries
  - extensions (extensions.logging)  implemented as dotnet classlibraries
  - webcontent for web content building repositories

