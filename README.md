# Oracle PDB Assignment II

## Overview

This repository contains my work for **Database Development with PL/SQL – Individual Assignment II**.

The assignment covers:

* Creating a Pluggable Database (PDB)
* Creating and deleting a temporary PDB
* Accessing Oracle Enterprise Manager
* Documenting the work with screenshots

## Oracle Environment

* **Oracle Database:** 21c Enterprise Edition 21.3.0.0.0
* **CDB:** ORCL
* **Created PDB:** GA_PDB_27234
* **PDB User:** GAD_PLSQLAUCA_27234
* **OEM HTTPS Port:** 5500

## Task 1: PDB Creation

Created the PDB `GA_PDB_27234` and opened it in **READ WRITE** mode.

A user named `GAD_PLSQLAUCA_27234` was also created inside the PDB.

Screenshots are available in:

`screenshots/pdb_creation/`

## Task 2: Temporary PDB

Created the temporary PDB `GA_TO_DELETE_PDB_27234`, verified that it existed, and then deleted it completely using `INCLUDING DATAFILES`.

Screenshots are available in:

`screenshots/pdb_deletion/`

## Task 3: Oracle Enterprise Manager

Oracle Enterprise Manager Database Express was configured and accessed successfully through HTTPS port **5500**.

The dashboard screenshot is available in:

`screenshots/oem_dashboard/`

## Challenges and Solutions

I initially encountered permission issues when opening the PDB using a normal user. I resolved this by connecting as **SYSDBA**.

The OEM HTTPS port was initially disabled, so I enabled it on port **5500**.

## Integrity Statement

I confirm that the work presented in this repository is my own work and that the screenshots provided are evidence of the tasks completed.

## Submission Details

**Repository Link:** [https://github.com/gadkamanzi2-coder/oracle_pdb_ass_II_27234_gad]

**PDB Name Created:** GA_PDB_27234

**Issues Encountered:** Yes
