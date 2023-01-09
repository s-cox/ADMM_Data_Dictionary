---
layout: default
title: Home
nav_order: 1
has_children: true
---
# NH Assets Introduction

This is an intial demo of how the ADMM of National Highways could be displayed using GitHub Pages with example templates showing Assets entries; including a description, their sub-class, asset and componenets (where applicable).

## Versioning

This is version 0.2, created 9 January 2023

## Structure of this site

Within the Home section there are templates that will help users add Asset Classes, Asset Subclasses, Assets and Attributes.

On the left hand side of the page following the main Home section, Asset Classes are listed and nested within them are the Asset Subclass and Asset. 

The Attribute section contains Asset Data Attributes which are populated from the ADMM Data Dictionary. Attributes may be common between numerous Assets, such as ‘Date of Construction’ or ‘CE Certificate Number’. Data Attributes may be mandatory or optional. For example if an asset has a CE Certificate Number, this attribute will be populated otherwise it will be null. 

On the Asset pages there is a Data Catalogue section with links on under the Attribute Types field to the relevant Attribue section.

## NH Data Assets 

The following is taken from the [Standards for Highways Website](https://standardsforhighways.co.uk/ha/standards/admm/index.htm)

For each asset entry there is:

- Asset Class Hierarchy – an overview of the asset class hierarchy. This takes on of the following forms:
    - Asset Class – Asset Subclass – Asset
    - Asset-Component Relationship

For each asset entry (excluding Drainage, Roadside Operational Technology and Structures asset classes):

- Description – a textual description detailing the asset, matching the description found in the Data Dictionary.

- An example image – a generic example image demonstrating the asset (this may be further highlighted to specify the asset in context).

- Asset Code – the four-digit code, referencing the asset within the Data Dictionary.

- Asset Class/Subclass –the class and subclass the asset belongs to, indicative of its relationship to a group of other assets as set out in the Data Dictionary, and the relevant procedures, rules, and personnel.

- Asset Geometry – i.e. Point, Line, or Polygon: this corresponds to the geospatial reference data for the asset and gives an idea of the space it occupies in the real world.
    - Assets that occupy a single location are considered Point (e.g. Sign Face, Reference Marker Locations, Bollards, etc.)



