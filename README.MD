## Why do we need a template

We need to minimize unnecessary local variation in file and folder management across programmes and projects in UNEP-WCMC, while still being adaptive to project circumstance, and to make it easier for sharing and transfer of GIS projects across UNEP-WCMC.
 
We are trying to improve the way we work across the Centre to improve data management and efficiency within projects and across programmes. By adopting standards our work will be better organised and more easily transferable between individuals and programmes.  
By working more consistently we will be more efficiency and improve quality:
 
- Less impact when change of technical staff during project lifecycle -  (because structure is predictable staff are brought up to speed more quickly, folders easier to navigate and data located more easily)

- Duplication of effort reduced as easier as easier to find data and analysis for projects where thematic or geographic areas are cross-cutting.

- Quality control and versioning is improved 

- Time is saved as reduced time needed for reorganising and renaming files and the history of geoprocessing is clearer if files have been named correctly on the outset and can be traced back.

- Systematic archiving at end of project ensures that information is not lost and can easily be retrieved without broken links and missing files.

- GIS users across the centre are more aware newly derived datasets and where to find them (incorporated into Centre’s geoportal (once this is functioning!)

- Restricted data stored and managed correctly to avoid future accidental wrong use or handling.

- Data that can be shared externally are added to the Centres online resources where appropriate thus improving Centre’s data profile


## Folder structure

- `docs`: Any methods documents, papers etch related to the project methods that you want to store with the project

- `mapdocs`: Any .mxds, .aprx, .qgs projects. Ensuring that naming conventions (see section below) and sub-folder names indicate latest files).  Ensure relative pathnames are always used (and no broken links to data when archiving).

- `outputs`: output maps, table, final datasets (derived data) generated for the project including full metadata

- `raw_data`: data sit in here in original format as it came in along with any metadata or links to datasets in Centre’s geoportal where possible to avoid storing duplicate copies of data

- `scratch`: an area for testing and rough workings prior to running actuals (distinct from working folder), mainly contains tests which can be deleted

- `scripts_tools`: any tools, scripts or models that have been developed to run the analysis

- `work_in_process`: A folder for any work in progress, storage of interim dataset, interim results etc. This folder should be empty once the project is finished.

- `QA_Checklist.xls`: Contain checklists associated with maps, data, tables etc for QAing any outputs. Should also suggest a second signoff- checking by someone who has not been doing the analysis as you are often blind to your own mistakes. 

- `project_inventory.xlsx`: A list of the data/files that are being used for the project (I.e. filenames and descriptions of data in the raw data folder, core datasets with relevant link and names of any derived datasets
(This will help other uses navigate your project data)

- `.gitignore`: configuration to ignore files to track

(please use the below as the `README.md` template)

---

## About

(Brief description of Project and themes covered)

## Key contacts/ project lead / GIS lead

(the people involved)

## Start date of project

(dd/MM/YYYY)

## End date of Project

(dd/MM/YYYY)

## Summary of analysis undertaken

(keep it short and simple)

## Software

(Software and what version of the software used)

## Links

(Links to any relevant docs, literature review results, if not stored in the docs folder)

## Others

(...Other important information you need someone to read before looking at the files: e.g. restrictions on reusing materials)
