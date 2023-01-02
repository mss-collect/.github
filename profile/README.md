# MSS-COLLECT

## Repositories

### Libraries

Repository|Namespace|Description
---|---|---
roque-draft||TODO rename!
||
tools.vectiles|MSS.Tools.VectTiles.*| ex "vectortiles"
tools.osm|MSS.Tools.Osm.Primitives
tools.osm.wayclassifier|MSS.Tools.Osm.WayClassifier
tools.web.primitives|
tools.schema.org|
tools.pbf|MSS.Tools.Pbf.*
tools.pbf.benchmarks|MSS.Tools.Pbf.Benchmarks| high level benchmarks executed via Github Actions
tools.osm.wayclassifier||
tools.web|MSS.Tools.Web.*|renamed from tools.web.pwa with v3.0.0, namespaces: html, layouts, resources, themes 
tools.pbf||
tools.pbf.benchmark||
||
api.outdooractive||
api.teamup||
api.facebook||

### Products

Repository|Namespace|Description
---|---|---
trailblog|TrailBlog.*|blogging and web engine
trailblog.postingbuilder|TrailBlog.PostingBuilder.*|
TrailExplorer||TRV website specific settings and tools based on TrailBlog Api 
NetTopologySuite||

### Contents (Web)

Repository|Namespace|Description
---|---|---
trv.trackanalyzer||
trv.web||TRV website specific settings and tools based on TrailBlog Api TODO rename into webcontent.trv
webcontent.scenery|| scenery website specific settings and tools based on TrailBlog Api


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

The TrailBlog universe is growing and needs some rules.

Content repository regarding our running activities should use the prefix "trv" like 

- trv.web
- trv.trackanalyzer

What about PostingBuilder ?

- uses trailblog NuGets like Markdown and client
- should not have content/project specific code => it behaves like a library/product library



### 3.10.2022 Rule conflict

Analyze naming:
- webcontent.scenery
- trv.web






