# QGIS_Remote_Sensing_Workflow
A QGIS-based workflow that replaces the use of ERDAS Imagine, Arc, Google Earth and Excel sheets in the management of RS workflows. Initially designed for NSW DCEEW. Includes a multi-phase QGIS plugin toolset that includes a systematic project setup, progress indicator, rollback, image analysis, quick draw, AI-assisted raster mark up and QC reporting tools.

See this public presentation -
https://prezi.com/view/QH57ZSeyxU7RstMZTLNK/?referral_token=HUjRLNlnB3FN
or
https://docs.google.com/presentation/d/1I12qykwNXK7ENfsV2EybmJLzhrga6W5ksIR2px8yrvw/edit?usp=sharing

A video is available at https://docs.google.com/videos/d/1_9aDjb7esMjpzbvlKPKWUmKHFiLVPfVepzEakQZomPE/edit?usp=sharing

Includes
~ Project Manager: takes a xls/wiki based instruction set to a couple of click repeatable process to set up each qgis project that the Remote Sencing Scientist may then spend days working through. Ensures a standard setup that the whole team is familiar with.

~Create Grid: sets out a grid that is used to review imagery at a set scale, zoom in/out and return to last checked spot.

~Marker: Retains a record of what zones have been checked complete or need further peer review.

~Flicker: Similar to ERDAS Flicker but also allows additional layers and quick key control.

~ReCode: the core plugin that changes the raster values within an AOI. The AOI can be auto-generated and expanded or hand-drawn. Users can revert changes on the whole AOI or parts of it. Each change is logged and users can choose to add further notes. Single or multiple AOI's can be changed in one process.

All modules are customised by a settings dialog that allow changes without coding or via editing raster files. There are readme files and power point presentations for the whole workflow and for each module.


## Notes

**Author's role:**  
Created all code using AI tools and professional experience, then improved it through consultation and implementation across staging, development, test, and production environments in collaboration with senior staff and program teams (data owners) and stakeholders.

Code is maintained in an internal repository and may be accessed via official requests through **coreagc@gmail.com**, where corporate approval will be sought.

© NSW DCCEEW
