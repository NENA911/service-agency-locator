# Service/Agency Locator

The ESInet will connect to many services and public safety agencies. A directory (“white pages” and “yellow pages”) of agencies, together with key information about the service or agency, is the function of the Service/Agency Locator. The Service/Agency Locator is a distributed database. There are several mechanisms by which the Service/Agency Locator can be searched to locate a specific service or agency. One primary way to search the Service/Agency Locator is by name. The Service/Agency Locator provides a name (white page) search function, with wild cards, to find a specific service or agency. The search by name is more useful for agencies than services. The name that is searched comes from the “org” field of the Agency jCard that is returned in the Service/Agency Locator Record. Another method to search is by location and agency type. 

A Service/Agency Locator Service is provided in the ESInet. Every service and every Public Safety Agency connected to the ESInet is listed in the Service/Agency Locator. The Service/Agency Locator has two components:

* A Service/Agency Locator Record Store (SALRS) which holds the actual data record for the service or agency; ab=nd
* A search component, which uses the ECRF and a LoST query to find a given service or agency by type and location.

## Owner

The owner of this repository approves all changes to the repository. 

This repository is owned by the NENA Core Services Committee, i3 Architecture working group.

#### Rules:

Specification Required. 

#### Contact:

[https://www.nena.org/page/911CoreSvcs](https://www.nena.org/page/911CoreSvcs) 

## Version History

### Service/Agency Locator v 1.0

Version 1 OpenAPI schema for this service was originally defined in NENA-STA-010.3.2021. See https://www.nena.org/page/i3_Stage
