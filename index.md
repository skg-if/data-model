---
title: Data Model
layout: default
nav_order: 3
---

# Data Model

The SKG-IF Data Model is the metadata model used for the data compliant with the [SKG-IF Interoperability Framework](/interoperability-framework/).

The SKG-IF Data Model is used to model all the SKG-IF main entities, their attributes and their relations to other entities. All these aspects are implemented using the 'language' of the Semantic Web, in particular by re-employing several existing ontological models developed to address specific modelling scenarios compatible with the aims of SKG-IF. 

The SKG-IF Data Model, summarised in convenient [Graffoo diagrams](https://essepuntato.it/graffoo), allows one to record information about the following SKG-IF entities:

* [Agent](#agent), that represents an individual (e.g., a person, an organisation, or another kind of entity being able to act) who is involved in the creation, publication, dissemination, etc. of a research product.
* [Data source](#data-source), a service or platform where a research product (its metadata and files) is stored, preserved, and made discoverable and accessible.
* [Grant](#grant), that describes funding awarded to an agent by a funding body.
* [Research product](#research-product), that may be of four types - research literature, research data, research software, or other.
* [Topic](#topic), that describes the scientific disciplines, subjects and keywords potentially relevant for a research product.
* [Venue](#venue), an entity that models a publishing “gateway” used by an agent to make their research products available to others.

The SKG-IF Data Model has been also implemented as an OWL ontology, i.e. the [SKG-IF Ontology (SKG-O)](https://w3id.org/skg-if/ontology/). It is not yet another bibliographic ontology, but rather it is just a place where existing and complementary ontological entities from several other ontologies, all employed in SKG-IF, are grouped together for the purpose of providing descriptive metadata compliant with the SKG-IF Data Model. The ontology is composed by six different ontological modules, formally imported in it, one for each type of SKG-IF entity - [SKG-O: agent](https://w3id.org/skg-if/ontology/agent/), [SKG-O: data-source](https://w3id.org/skg-if/ontology/data-source/), [SKG-O: grant](https://w3id.org/skg-if/ontology/grant/), [SKG-O: research-product](https://w3id.org/skg-if/ontology/research-product), [SKG-O: topic](https://w3id.org/skg-if/ontology/topic/), [SKG-O: venue](https://w3id.org/skg-if/ontology/venue/).

The SKG-IF data created following the [Interoperability Framework](/interoperability-framework/) are aligned with the SKG-IF Ontology via the [SKG-IF JSON-LD context](/context/). In addition, a specific [SHACL document](https://w3id.org/skg-if/validation/shacl) has been developed for semantically validating the data provided according to the data model.

## Agent

Module URL: [https://w3id.org/skg-if/ontology/agent/](https://w3id.org/skg-if/ontology/agent/)

![Agent diagram]({% link data-model/graphs/agent.png %})


## Data source

Module URL: [https://w3id.org/skg-if/ontology/data-source/](https://w3id.org/skg-if/ontology/data-source/)

![Data source diagram]({% link data-model/graphs/data-source.png %})


## Grant

Module URL: [https://w3id.org/skg-if/ontology/grant/](https://w3id.org/skg-if/ontology/grant/)

![Grant diagram]({% link data-model/graphs/grant.png %})


## Research product

Module URL: [https://w3id.org/skg-if/ontology/research-product/](https://w3id.org/skg-if/ontology/research-product/)

![Research product diagram]({% link data-model/graphs/research-product.png %})


## Topic

Module URL: [https://w3id.org/skg-if/ontology/topic/](https://w3id.org/skg-if/ontology/topic/)

![Topic diagram]({% link data-model/graphs/topic.png %})


## Venue

Module URL: [https://w3id.org/skg-if/ontology/venue/](https://w3id.org/skg-if/ontology/venue/)

![Venue diagram]({% link data-model/graphs/venue.png %})








