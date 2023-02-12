# CSDM-notes

## Service Graph

The Service Graph in ServiceNow is a feature that provides a visual representation of the relationships between different services and components in an IT environment. It provides a comprehensive view of the entire service landscape, including the dependencies, interconnections, and interactions between various services and components. The Service Graph allows IT teams to easily understand and monitor the health and performance of services, identify potential issues, and resolve problems more quickly and efficiently.

ServiceNow Service Graph uses data from various sources, such as service maps, discovery scans, and service-level agreements (SLAs), to create a comprehensive view of the service landscape. The graph is interactive, allowing users to drill down into specific components and services, view related data and details, and track changes over time. This makes it easier to identify trends, patterns, and correlations, and to take proactive measures to avoid service disruptions and outages.

## Relation to the CSDM

The Service Graph in ServiceNow is closely related to the Common Service Data Model (CSDM) because it relies on the data stored in the CSDM to create the visual representation of the service landscape. The CSDM is a data model that provides a standard and consistent way to organize, store, and manage information about services and components in an IT environment. It defines a set of entities, such as services, components, and relationships, that are used to model the IT landscape.

By using the CSDM, the Service Graph can provide a unified and accurate view of the service landscape, as it draws on consistent and up-to-date information from across the entire IT environment. This helps to ensure that the graph is accurate, complete, and up-to-date, and that it provides a comprehensive view of the relationships between services and components.

## What is the CSDM?
CSDM is the data framework and common model used by all ServiceNow products and integrations.

Dev = ITBM, DevOps, Agile as part of the DESIGN domain.
Ops = ITOM, ITAM as part of the MANAGE domain
Service = ITSM, CSM as part of the CONSUME domain

## CSDM Domains: Data Model Grouping

CSDM Domains: How we describe and group objects in the data model based upon function. These functions help support how our products work together.

Build -> Developmental details of Digital Products. These are not "operational"CIs.
Design -> Designing and Planning of Digital Products. These are not "operational" CIs.
Manage Technical Services -> Deployed instances of Digital Products and their related, discoverable, components. Additionally, the services that provide and support the deployed instances are documented here.
Sell/Consume -> The business that utilizes and depends on the deployed digital products.


## Build
- Has a new class called SDLC (software development life cycle) class called "SDLC Component"
  - SDLC Component - new class in CMDB
  A software part or element of a large whole for an application or technology. Related material may serve as representative of developmental details.
  Tied to Dev"Ops and CDM (Sweagle)
  Application examples:
    - Micro services
    - APIs
  Technology Examples:
    - Database Configurations
    - Security Configurations
## Design

## Manage Technical Services

## Sell/Consume

## Foundation
