# MSS-COLLECT


## Naming Conventions

[Design guidelines for namespaces](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/names-of-namespaces)

- CONSIDER using plural namespace names where appropriate

[Design guidelines for assemblies](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/names-of-assemblies-and-dlls)

## Repositories



### Inventory

Repository|Namespace
---|---
tools.vectortile|MSS.Tools.VectorTile.*
tools.osm|MSS.Tools.Osm.Primitives
tools.web.primitives|
tools.schema.org|
tools.pbf|MSS.Tools.Pbf.*


### ToDo
- roque-draft should be moved/renamed into
  - tools.pbf
    - Tools.Pbf.IO
    - Tools.Pbf.Primitives
    - Tools.Pbf.Analysis
- tools.vectortile should be renamed/splitted into
  - tools.vectile (rename vector into vec because to often used by NTS and others)
  - Roque.ML should go into his own repo
   

## Packages

