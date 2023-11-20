# MSS-COLLECT

This organization is used for all my repositories that are about development and are using GitHub Actions or other GitHub resources that may need payment.

The following websites are driven by code from this organization:

- [Trailrunning Vienna](https://trailrunningvienna.at) and [Events](https://events.Trailrunningvienna.at)
- [Trail Explorer](https://trex.trailrunningvienna.at)
- [Notes](https://notes.mss-collect.com)


## Naming conventions

There is no exact definition about using tools or extensions.
We see multiple (inconsistent) scenarios).

- tools as global tools
- tools as libraries used in project runtime code
- tools as libraries used in project test code
- extensions (means static methods with this as main entry point, used like Microsoft.Extensions Framework)

Nuget Packages: 

- MSS.Tools.TechnologyOrProduct.Content

Special Case: Tools and Helpers for xUnit:
Namepsace: Xunit (Framework Design Guidelines)
Wording: "xUnit" Product Name
Package: MSS.Tools.Xunit
Repository: tools.xunit

### Patterns

#### MSS.Tools.Web
- Primitives
- Routing/EndpointRouting
- Layout
- Primitives
- ApplicationInsights
- HttpClient
- xUnit
  

