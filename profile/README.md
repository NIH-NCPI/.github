<p align="center"><img src="https://github.com/NCPITest/.github/blob/main/profile/ncpi-logo-close-crop.png" width="250" alt="NCPI Logo"/></p>

<div align="center">
  <h2>
    <a> Home</a> |
    <a href="https://github.com/NIH-NCPI/About/blob/main/README.md">About</a> |
    <a href="https://github.com/NIH-NCPI/Partners/blob/main/README.md">Partners</a> |
    <a href="https://github.com/NIH-NCPI/Interoperability-Projects/blob/main/README.md" >Projects</a> |
    <a href="https://github.com/NIH-NCPI/Resources/blob/main/README.md">Resources</a> | 
    <a href="https://github.com/NIH-NCPI/Events/blob/main/README.md">Events</a>
  </h2>
</div>

# <p align="center"> NIH Cloud Platform Interoperability (NCPI) Program  </p>

The NCPI program is a partnership between multiple NIH-supported participating systems (currently AnVIL, BioData Catalyst, CRDC, dbGaP, and Kids First) developing and implementing technical standards to enable interoperability and facilitate a federated data ecosystem. 

The purpose of this page is two fold: 
  - Provide links to the technical products that underlie interoperability, These tools/resources/services are outlined in the Interoperability Resources Table.
  - Provide information regarding the NCPI program more broadly
    - The [About](https://github.com/NIH-NCPI/About/blob/main/README.md) repository provides an overview of the NCPI program and its components.
    - The [Partners](https://github.com/NIH-NCPI/Partners/blob/main/README.md) repository provides details on the NCPI partner systems.
    - The [Projects](https://github.com/NIH-NCPI/Interoperability-Projects/blob/main/README.md) repository provides an overview of ongoing and past interoperability projects.
    - The [Resources](https://github.com/NIH-NCPI/Resources/blob/main/README.md) repository provides various interoperability resources inlcuding information about key NCPI standards such as Researcher Auth Service, Data Repository Service, and FHIR.
    - The [Events](https://github.com/NIH-NCPI/Events/blob/main/README.md) repository provides details on past and future NCPI Workshops. 
  

## Interoperability Resources Table

The following table provides a quick overview of the interoperability focused tools/resources/services that underlie NCPI. 

| <p align="center">Resource</p> | <p align="center">Description</p> |
|--------|---------------|
| [NCPI Dataset Catalog](https://ncpi-data.org/platforms) | The NCPI Dataset catalog indexes aggregate data from available studies from the five NCPI Partner Systems, and allows researchers to discover studies across NIH platforms. The catalog is built on publicly available metadata and is searchable by nine facets. |
| [NCPI FHIR Implementation Guide 2](https://github.com/NIH-NCPI/ncpi-fhir-ig-2?tab=readme-ov-file) | Relaunch of the IG project with a clearer focus, an explicit style guide using the current tools including Sushi v3. NCPI FHIR IG aims to produce a shared view of research structure and semantics to accelerate the scientific process and reduce impediments needed to share knowledge among researchers.|
| [FHIR Aggregator](https://fhir-aggregator.github.io/) | An open-access tool for finding and downloading biomedical data from across the NIH developed by [Interoperability Project: Connecting FHIR, the CDA, and DRS Across NIH Cloud Resources](https://github.com/NIH-NCPI/Interoperability-Projects/blob/main/Project%20Descriptions/OHSU-FHIR.md). <br> A paper on FHIR for genomic research and the creation of the FHIR aggregator is in development, and a pre-print is available [here](https://www.biorxiv.org/content/10.64898/2025.12.22.695544v1). | 
| [Watershed](https://github.com/BennyStrobes/Watershed) and [Watershed-SV](https://github.com/jasonbhn/Watershed-SV) | The Watershed-SV model extends the existing Watershed Model to model the impact of rare structural variants (SVs) on nearby gene expressions outliers. Watershed-SV was developed by the [AnVIL-BioData Catalyst Interoperability](https://github.com/NIH-NCPI/Interoperability-Projects/blob/main/Project%20Descriptions/JHU-AnVIL-BDC.md) project team. <br> Both [Watershed](https://www.dockstore.org/workflows/github.com/schatzlab/Watershed-SNV-WDL/Watershed-SNV:main?tab=info) and [Watershed-SV](https://dockstore.org/workflows/github.com/jasonbhn/Watershed-SV/Watershed-SV:WDL?tab=info) workflows are available on Dockstore. <br> Featured workspaces demonstrating the use of [Watershed](https://anvil.terra.bio/#workspaces/nccpi-rti-P01-002-JHU-TERRA/Watershed-SNV-MAGE) and [Watershed-SV](https://anvil.terra.bio/#workspaces/nccpi-rti-P01-002-JHU-TERRA/Watershed-SV-MAGE) on 1000 Genomes and MAGE datasets are now available on Terra. <br> A demonstration on the Watershed model was given at the Fall 2025 NCPI workshop. More information can be found [here](https://github.com/NIH-NCPI/Events/blob/main/Fall-2025-Workshop-Demonstrations.md#-watershed-demonstration-).|
| [NCPI RAS Implementation Playbook](https://github.com/NIH-NCPI/Resources/blob/main/NCPI-RAS-Playbook.pdf) | Outlines how to plan and execute RAS integrations, highlighting past lessons learned, integration preparation, and providing a step-by-step playbook to reduce potential challenges in future RAS integrations. <br> More information about RAS in NCPI can be found [here](https://github.com/NIH-NCPI/Resources/blob/main/Technologies.md#-researcher-auth-service-ras-). |
| [NCPI FHIR Shiny Browser](https://github.com/NIH-NCPI/ncpi-fhir-shiny-browser) | Example R Shiny applications and supporting functions that allow browsing and parsing FHIR objects. |
| [Locutus](https://github.com/NIH-NCPI/locutus) | Backend for a web-based terminology mapping tool aimed at harmonizing dataset terms with public ontologies such as MeSH, HPO, and others. |
| [NCPI FHIR Client](https://github.com/NIH-NCPI/ncpi-fhir-client) | Basic FHIR client with built-in modular authentication. |
| [HAPI Dev](https://github.com/NIH-NCPI/HAPI-Dev) | Helper to launch a local FHIR server that persists using local storage and has some pre-defined defaults built in. |
| [NCPI Whistler](https://github.com/NIH-NCPI/ncpi-whistler) | Pipeline to transform research data tables into FHIR resources and load them into a FHIR Server using Python scripting, Whistle, and the FHIR Rest API. |
| [NCPI Whistler Tutorial](https://github.com/NIH-NCPI/NCPI-Whistler-Tutorial) | Step-by-step guide for creating a project to transform research data into FHIR resources and optionally load them into a FHIR server. |
| [Dockerized Whistle](https://github.com/NIH-NCPI/dockerized-whistle) | Docker image for a fully functional whistle application with a shell script for easy execution. |
| [map-dragon](https://github.com/NIH-NCPI/map-dragon).| This application will support several user groups in submitting and validating their data, managing and tracking data definitions, and aligning data to standardized terms.|




