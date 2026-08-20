# GeoSolutions di Giannecchini Simone & C. s.a.s.

GeoSolutions is an Italian company and one of the principal maintainers of the open-source geospatial server stack — GeoServer, GeoNetwork, MapStore and GeoNode. It sells enterprise support, deployment and custom development around those projects. Its public demonstration server is a reference OGC deployment, serving classic OGC web services alongside a modern OGC API - Features endpoint.

Profiled 2026-08-20 as part of the [OGC](../ogc/) standards-body pass — this organization is an
**OGC Explorer member** (Commercial, Italy), found in OGC's own
active-member roster and confirmed to serve a live OGC surface on its own host.

## APIs

| aid | name | base | contract |
|---|---|---|---|
| `geosolutions:ogc-web-services` | GeoSolutions OGC Web Services (WMS / WFS) | https://maps.geo-solutions.it/geoserver/ows | 2 GetCapabilities |
| `geosolutions:ogc-api-features` | GeoSolutions OGC API - Features | https://maps.geo-solutions.it/geoserver/ogc/features/v1 | 0 GetCapabilities |

## Provenance

Every GetCapabilities document under `openapi/` was retrieved **anonymously, with HTTP 200, on
2026-08-20** and is stored verbatim — it is the machine-readable contract for a classic OGC service,
which has no OpenAPI. Nothing here is derived from documentation.

Membership facts come from `https://portal.ogc.org/services/srv_active_members_csv_new.php`.
