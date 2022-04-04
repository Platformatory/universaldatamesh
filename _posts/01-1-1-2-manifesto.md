---
layout: slide
title: "The UDM Manifesto"
---

- Data services are decomposed in the same manner as application services: By DDD patterns (aggregates, bounded contexts)
  - A well defined data product value proposition, to a defined end-user audience forms a product and shall be the minimum unit of governance
- Product teams own end to end application & data service topologies, authoritative schemas
  - This includes overall stewardship, governance & intra-domain dependencies
  - Product teams manage all aspects of the product lifecycle
- Declarative data movement & processing in the mesh
  - Routing patterns to facilitate data exchange, including serialization, deserialization of data over the wire
  - Temporal, windowed queries and scalar transformation operators
- Data mesh infrastructure provides the necessary distributed data backbone for eventing, brokering & event stream processing
  - Message delivery, acknowledgements & incremental processing semantics
  - Seamless, polyglot access to publish & consume data in multiple consumption models
  - Coverage of cross cutting concerns: data observability, quality, lineage, metadata, catalog & security

