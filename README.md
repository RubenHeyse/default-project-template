# Default Project Template

Author: Ruben Heyse \
Date: 2024-07-01

---

## Project Structure

The default project structure follows the following directory tree:

``` bash
<project name>
│── CM-Configuration Management
│── CO-Commercial
│── DD-Mechanical and Electrical
│── DE-Design - Electronic
│── DS-Design - System and Software
│── FI-Fault Investigations
│── PD-Product Development
│── PN-Production Documents
│── QA-Quality
│── RP-Reports
│── SR-System Requirements
│── TA-Testing and Analysis
│── TM-Technical Manuals
└──  ZZ-Misc
```

The contents of the above directories are specified below.

## CM-Configuration Management

Holds configuration information for product variants.

## CO-Commercial

Information relating to the commercial aspects of the project e.g. customer emails in eml file format.

## DD-Mechanical and Electrical

CAD models, technical drawings, and wiring harness schematics.

## DE-Design – Electronic

ECAD PCB schematics and layouts. Each product variant and revision MUST be in a dedicated folder.

## DS-Design - System and Software

Contains the project code. Code variants and major revisions should be in dedicated folders.

## FI-Fault Investigations

Each investigation must be in a dedicated folder.

## PD-Product Development

System design documentation e.g. calculation, mind maps, and flow charts

## PN-Production Documents

Product assembly instructions and modification guides.

## QA-Quality

Quality assurance and control documentation and certification documents and certificates

## RP-Reports

Customer evaluation reports and non-testing reports (e.g. customer visit reports).

## SR-System Requirements

Requirements established by the customer. Revisions should be put in new files.

## TA-Testing and Analysis

Internal testing results, reports, and data. Each test should ideally have a dedicated folder.

## TM-Technical Manuals

Datasheets, application notes, and whitepapers.

## ZZ-Misc

Any document that doesn’t fit the above definitions. Naming should be descriptive for searchability.
