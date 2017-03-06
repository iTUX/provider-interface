# Ändringar mot tidigare versioner

## Nytt i API 2.2

### Separation mellan Feasibility (Bulk) och Availability (per Access)

Bulk-APIt kallas framledes "Feasibility API" och "Per Access-API" kallas framledes "Availability API".
Feasibility har förenklats. Bakgrunden är att Feasibility skall bli enklare och billigare att implementera.
Availability finns endast per Access vid behov och kan därmed implementeras enklare än om det är en del av Feasibility.

* Feasibility: Services.serviceType borttaget.
* Feasibility: Services.available borttaget.
* Feasibility: Services.forcedTakeoverPossible borttaget.
* Feasibility: Active är borttaget.
* Availability: Services.serviceType borttaget.
