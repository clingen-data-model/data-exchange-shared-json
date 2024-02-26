# ATTENTION - GENE EXPRESS JSON DATA
This repo needs to remain availbale without changes to the name (URL) to ensure the Gene Express Data is abilable.  The legacy data is available https://github.com/clingen-data-model/data-exchange-shared-json/blob/master/json-from-gene-express/ClinGen-Gene-Expess-Data-03272019.json

A new file has been added with the above data decorated with entrez_ids to facilitate genegraph 2 implementation: gci-express-with-entrez-ids.json Please update both files until Genegraph 2 rollout is complete.

# Overview
This repository has been developed to collaborate on the data schema that is share data from the interfaces to the ClinGen website based on the current display and existing database structure.  A goal is to harmonize the data structure between existing manually entered data structure with data curated in the interfaces in an effort to expedite the work.  Note, a robust Common ClinGen Data Model is planned for phase 2. 

## Phase 1 - Simplified JSON - Existing/Abridged Data
This phase will focus on;
Share only the data that is currently in use by the website at this time
Share the data from the interfaces based on a json schema in use at this time
Share the data from the interfaces to the Data Exchange

NOTE - Phase 1 will not seek the richer data from the interfaces that are available.  This will tackled in Phase 2.

### Implementation Steps 
Data Exchange Release & Documentation (Underway)
Integrate Gene Dosage Data into website based on current UI/UX (Underway)
Integrate Actionability into website based on current UI/UX
Integrate Gene Curation into website based on current UI/UX

## Phase 2 - Richer/Complete Data (Additional details will be added later)
This phase will include a series of smaller phases and this process will start during/after Phase 1 has been completed.  They will focus on;
- Planning & Discovery (Ed/Web WG)
- Plan Gene Dosage richer data utilization 
- Plan Actionability richer data utilization
- Plan Gene Curation richer data utilization
- Plan Somatic richer data utilization
- Plan CADre richer data utilization
- Plan Sequence Variant richer data utilization
- Plan Structural Variant richer data utilization

### Specifications & Development (Interface Dev Teams & Ed/Web WG) 
- Based on planning updates to the website code/structure may be required.
- Based on planning updates to the interface code/structure may be required.
- Provide richer data to the Data Exchange based on plans
- Rollout (Interface Dev Teams & Ed/Web WG) 

The release schedule will be determined during the planning and discovery steps above.
