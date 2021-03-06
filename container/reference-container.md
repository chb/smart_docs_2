---
layout: container
title: SMART - Reference Container for Container Developers
---

## Overview of SMART Reference Container

The SMART Reference container is a basic EMR system that fully implements the
SMART specification. It is written in Python with the Django web framework.
The patient medical data is stored in RDF graph form in a triplestore engine
(OpenRDF Sesame by default) while the user and app data is in a relational
database (Postgres or equivalent). The reference container consists of the
following modules:

* SMART Server, which implements the SMART API specification and enforces
authentication and authorization rules

* SMART UI Server, which provides a basic web UI for exploring the
patient records with SMART apps

* SMART Sample Apps Server, which hosts a collection of sample SMART medicial
apps

* SMART Sample Patient Generator, which generates a set of sample patients
to be used for demonstration purposes

Installation instructions can be found
[here](/framework/reference-implementation/architecture.html)
