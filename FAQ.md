---
title: Data model
parent: FAQs
layout: default
nav_order: 1
---

# FAQs : Data model

## I need a new entity or relation in the Data Model and API

* Please open a ticket on https://github.com/skg-if/interoperability-framework


## How to add a simple “contributor” that is not an author ?

* See : https://github.com/skg-if/interoperability-framework/issues/11

## Is there a Project entity ?

No 

* For now you can only use the `Grant` entity. Which is ok for Grant/Project entities like EU CORDIS.
* Discussion : https://github.com/skg-if/interoperability-framework/issues/42

## Is there a Service entity ?

* Yes, see extension : https://skg-if.github.io/ext-srv/


##  The manifestation “biblio” field name does not make sense for Datasets.

* yes, technically in the JSON-LD context the bibio is a @nest and has no semantic, so OK for now, no perfect but no change is planned. Discussion here : https://github.com/skg-if/interoperability-framework/issues/22 

https://w3id.org/skg-if/context/skg-if.json 

``` json
 "biblio": "@nest",
 ```

You can still fill the fields `in` and `hosting_data_source` for the Datasets.