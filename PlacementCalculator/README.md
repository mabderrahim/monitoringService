# Placement Calculator

## Quick Start

The following instructions lunch the calculation of a mutualized placement and a non-mutualized placement for the **users requirements** and **infrastructure** inputs in *monitoringService/PlacementCalculator/src/main/resources*.
They return the calculation time, the compute footprint and the network footprint of the solutions that are found within 10 minutes.

```
git clone https://github.com/mabderrahim/monitoringService.git
cd monitoringService/PlacementCalculator
mvn package
mvn exec:exec
```