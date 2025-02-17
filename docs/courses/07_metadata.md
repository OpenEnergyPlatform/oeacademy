---
tags:
  - metadata
---

# 07 - Metadata

You can provide [feedback to this course](https://github.com/OpenEnergyPlatform/academy/issues/187) on GitHub

## Who is this course for and what can you learn?

:oep-icon-info: **This course is aimed at researchers, who want to**

- create fair metadata
- publish data on the OEP

:oep-icon-info: **After reading the sections of this training course you will know**

- the structure of the OEMetadata standard
- where to find the OEMetadata and how to create your own
- how to upload, download and edit OEMetadata
- how to use the different tools available for OEMetadata

## Introduction: What is Metadata?

Metadata, in simple terms, refer to data about data.
They provide valuable information regarding the characteristics, properties,
and context of a specific data item.
Metadata answer the questions of "who, what, when, where, and how" related to the data.
Metadata plays a crucial role in organizing, managing, and understanding information.

## What is the Open Energy Metadata?

- [Open Energy Metadata](https://github.com/OpenEnergyPlatform/oemetadata) (OEMetadata) is a metadata standard for energy related data
- The development of OEMetadata is a community effort and takes place on [GitHub](https://github.com/OpenEnergyPlatform/oemetadata/issues)
- There is a comprehensive [documentation for the OEMetadata Standard](https://openenergyplatform.github.io/oemetadata/latest/)
- The documentation has a detailed [Metadata Key Description](https://openenergyplatform.github.io/oemetadata/latest/oemetadata/metadata_key_description/)
- There is an introduction tutorial :oep-icon-code: [getting started with OEMetadata](../tutorials/metadata/getting_started_with_OEMetadata.ipynb)

## How can I work with OEMetadata?

- Manually create a metadata.json using the [template.json](https://github.com/OpenEnergyPlatform/oemetadata/blob/develop/oemetadata/latest/template.json) or [example.json](https://github.com/OpenEnergyPlatform/oemetadata/blob/develop/oemetadata/latest/example.json)
- Use the OEP Interface [OEMetadataBuilder](https://openenergyplatform.org/dataedit/oemetabuilder/) to create and edit metadata
- The OEMetadataBuilder is used in the tutorial :oep-icon-code: [guide on publishing data on the OEP](../tutorials/upload/OEP_Research_Data_Publishing_Guidebook.ipynb)
- Every table on the [OEP](https://openenergyplatform.org/dataedit/schemas) has a section "Meta Information" that shows the metadata
- You can download the metadata with "Download JSON"
- If you have permissions, you can click "Edit" and improve the metadata
- The "Open Peer Review" process has been implemented to review and publish data and metadata

## What other tools to work with OEMetadata are there?

- The tool for [metadata conversion and integration is `OMI`](https://github.com/OpenEnergyPlatform/omi)
- An additional helpful tool for publishing a set of data with associated metadata is `oem2orm`. It can translate table descriptions from metadata into a database structure via an object relational mapper. That way it can take a valid pair of data and metadata and upload it directly to the OEP. The structures of both need to be valid. :oep-icon-code: [A tutorial on the use of oem2orm](../tutorials/upload/OEP_Upload_Process_Data_and_Metadata_oem2orm.ipynb) explains the upload process
- The `oep client` is a tool that can create, upload, download and delete tables. It also downloads and updates metadata. It's more versatile than oem2orm but less focussed on metadata. There is a :oep-icon-code: [tutorial using oem2orm and oepclient](../tutorials/upload/OEP_Upload_Process_Data_and_Metadata_oep-client.ipynb) to upload some data and metadata

## Supplementary material and further readings

- [Poster] Open Energy Metadata (OEMetadata): Publishing Energy Data Enriched with Ontology References [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8026863.svg)](https://doi.org/10.5281/zenodo.8026863)
- [Presentation] Capacity building session - Hülk - Publication of FAIR Data and Metadata: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7835380.svg)](https://doi.org/10.5281/zenodo.7835380)
- [Tutorial] [Introduction to OEMetadata](https://openenergyplatform.github.io/academy/tutorials/99_other/getting_started_with_OEMetadata/)
- [Tutorial] :oep-icon-code: [Tutorial - Working with OEMetadata](https://openenergyplatform.github.io/academy/tutorials/99_other/oemetadata/)
- [Tutorial] :oep-icon-code: [Guidebook - How to Publish Your Data on the OEP](https://openenergyplatform.github.io/academy/tutorials/99_other/OEP_Research_Data_Publishing_Guidebook/)

---

## About this course

:oep-logo-sirop:

- Authors: christian-rli, Ludwig Hülk (@Ludee)
- Copyright: Reiner Lemoine Institut
- Contact: ludwig.huelk@rl-institut.de
- License: [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.en)
- Attribution: Open Energy Academy - Metadata Course © [Reiner Lemoine Institut](https://reiner-lemoine-institut.de/)
- You can provide [feedback to this course](https://github.com/OpenEnergyPlatform/academy/issues/187) on GitHub
