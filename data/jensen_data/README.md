# data/jensen_archived_samples

Contact: Aidan Coyle, afcoyle@uw.edu

Roberts Lab, UW-SAFS

Last edited README: 2021-12-06

## Description

This folder contains files that describe the samples sent from Pam Jensen to the Roberts Lab after her retirement.

## Manually created files:

#### jensen_archived_samples_inventory.csv

The Box ID numbers are NOT unique to that box. However, the year/survey/box ID combination is unique.

Standard 96-well plates are assumed to be full unless explicitly noted on the box, and thus the number of samples is set to 96. Boxes that aren't standard 96-well plates have the specific number of samples listed.

Boxes of mixed species/surveys will have their contents noted in another CSV - jensen_archived_mixed_boxes_inventory.csv. These are often unlabeled. The survey will be labeled as "mixed", and the Box ID will be (if none exists), mixed_box_#, with # being a sequential number for that tote

#### jensen_mixed_boxes_inventory.csv

As noted above, mixed boxes are noted in a separate CSV. In cases where multiple species were clearly labeled within a single box, each line is a different species. 

## Downloaded files

As described in scripts/1_1_downloading_jensen_data.ipynb, these are the contents of the flash drive Pam sent over upon her retirement. 

### Folders:

**Hemato_protocols:** These are a series of files labeling the protocols used throughout the course of NOAA's _Hematodinium_ monitoring project.

**Hemato_samples:** Contains several subfolders:
- BCS_Extraction_Plate_maps_2005_2013: Contains maps of the *extraction plates* made prior to PCR. Does **not** show the location on the *collection* plates. A very important distinction!!

- data_2014-2019: Contains Excel files for all systematic survey collections made after 2014

- databases_thru_2013: Contains Access database of historical sampling efforts

**NPRB_transcriptome:** Contain information on the 2017 NPRB transcriptome project. This is the one from 2017 that Grace and Pam partnered on, and the one whose data I previously analyzed. Repo from that analysis available at https://github.com/afcoyle/hemat_bairdi_transcriptome

**Special_Projects:** Contains general sampling project info, typically for NOAA surveys. Includes maps of survey stations and index sites




