---
layout: default
title: End Terminal
parent: Vehicle Restraint
grand_parent: Road Restraint
nav_order: 3
---

# End Terminal
This model was last updated on **11/01/2023**, this is version **1.0**

Experimental
{: .label .label-yellow }

## Model created
11/01/2023

## Description
Specialised treatment mounted at the beginning or end of a safety barrier, where Asset Data Management Manual Page 112 of 134 Date of Issue: October 2021 Part 4 - Asset Reference Catalogue there is no connection to aparapet/transition to another barrier. Designed to mitigate the effects of an impact from an errant vehicle. May also provide an anchorage for the barrier system.

## Asset Image

![activity](/ADMM_data_dictionary/docs/roadrestraint/diagrams/end_terminal.png)

## Asset Code
``RRET``

## UniClass
``Ss_25_16_94``

## Geometry
Linear

## Asset Rules
``RRET_2``

Ground Surface Type = Granular, unless the asset has been installed on a man made/constructed surface; in which case Ground Surface Type = Solid.

``RRET_7``

For data captured from remote survey only; End Terminal Type should default to P1, where the asset is not readily visible (i.e. e. occluded by objects/vegetation).


## Data Catalogue

For this asset there are attributes in which there can be multiple variations, such as Type.

| Asset Data Category | Attribute Name                                  | Attribute Description                                                                                                                                                            |
|---------------------|-------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Construct           | [Date of Installation](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/dateofinstallation.html)                           | The date the asset was installed on site; applicable to prefabricated items manufactured off-site. This should take the form DD-MON-YYYY.                                        |
| Construct           | [Departure - DAS ID](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/departure.html)                              | The unique identifier within the WebDAS system corresponding to an approved Departure from Standard.                                                                             |
| Construct           | Design/Drawing Number                           |                                                                                                                                                                                  |
| Construct           | [Expected Service Life](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/expectedservicelife.html)                           | The time period during which the asset is expected to remain suitable for its intended use.                                                                                      |
| Inventory           | [Additional Information](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/additonalinformation.html)                         | A text note to provide specific information about an asset, in cases where an attribute value is set to "Other".                                                                 |
| Inventory           | [CE Certificate Reference Number](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/cecertno.html)                  |                                                                                                                                                                                  |
| Inventory           | Connected Parapet                               | Indicates the presence of a connected parapet.                                                                                                                                   |
| Inventory           | [End Chainage](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/endchainage.html)                                    | The along carriageway position corresponding to the termination of a linear or polygon asset, as measured within the section.                                                    |
| Inventory           | [End Date](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/enddate.html)                                        | The date from which the asset ceases to be recognised under maintenance.  Note: a record of retirement will be populated. Should take the form DD-MON-YYYY.                      |
| Inventory           | Exit Box Class (Z)                              | The level of vehicle trajectory from the asset after impact.                                                                                                                     |
| Inventory           | Ground Surface Type                             |                                                                                                                                                                                  |
| Inventory           | [Hazard (reason for asset)](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/hazardreason.html)                       | Defines the reason for the installation of a safety barrier (i.e. e. any potential hazards to road users).                                                                       |
| Inventory           | Impact Severity Level (ISL)                     |                                                                                                                                                                                  |
| Inventory           | [Length](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/length.html)                                          |                                                                                                                                                                                  |
| Inventory           | [Location Text](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/locationtext.html)                                   | A text note to describe the local position of the asset, in generic terms.                                                                                                       |
| Inventory           | [Manufacturer](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/manufacturer.html)                                    | The manufacturer of the asset.                                                                                                                                                   |
| Inventory           | [Owner](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/owner.html)                                          |                                                                                                                                                                                  |
| Inventory           | Performance Class (P)                           |                                                                                                                                                                                  |
| Inventory           | Permanent Lateral Display Zone Character (PLDZ) | Amount of permanent lateral displacement of the asset after impact.                                                                                                              |
| Inventory           | [Product Name/ID](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/productname_id.html)                                   |                                                                                                                                                                                  |
| Inventory           | [Section](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/section.html)                                         | Section referencing is used to divide the network into sections. Further information can be found in section 4 of the Part 2 - Requirements and Additional Information document. |
| Inventory           | [Start Chainage](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/startchainage.html)                                  | The along carriageway position corresponding to the beginning of a linear or polygon asset, as measured within the section.                                                      |
| Inventory           | [Start Date](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/startdate.html)                                      | The date from which the asset is recognised in under maintenance. Should take the form DD-MON-YYYY.                                                                              |
| Inventory           | Type                                            | Defines the installed end terminal type.                                                                                                                                         |
| Inventory           | [X End (Easting)](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/xend_easting.html)                                 | OS Easting coordinate, at the end of the asset.                                                                                                                                  |
| Inventory           | [X Start (Easting)](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/xstart_easting.html)                               | OS Easting coordinate, at the beginning of the asset.                                                                                                                            |
| Inventory           | [XSP](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/xsp.html)                                             | Defines the location of the asset across the carriageway.                                                                                                                        |
| Inventory           | [Y End (Northing)](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/yend_northing.html)                                | OS Northing coordinate, at the end of the asset.                                                                                                                                 |
| Inventory           | [Y Start (Northing)](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/ystart_northing.html)                              | OS Northing coordinate, at the beginning of the asset.                                                                                                                           |
| Maintenance         | [Maintenance Contractor](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/maintenancecontractor.html)                          | Contractor responsible for maintenance of the asset. Should only be recorded if HE is responsible for the assets maintenance.                                                    |
| Maintenance         | [Maintenance Responsibility](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/maintenanceresponsibility.html)                      | The organisation responsible for the maintenance of the asset.                                                                                                                   |
| Operate             | [Area/Region](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/area_region.html)                                     |                                                                                                                                                                                  |
| Operate             | [Defect Liability Period](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/defectliabilityperiod.html)                         | The end date of the supplier assurance period. Should take the form DD-MON-YYYY.                                                                                                 |
| System              | Source ID                                       | Supplier's external reference ID (scheme, major project, survey etc.).                                                                                                           |
| System              | System ID                                       | The unique identity code for this item in its current prime system.                                                                                                              |

## Note
Notes to be inserted here, possibly with graphics and photos
