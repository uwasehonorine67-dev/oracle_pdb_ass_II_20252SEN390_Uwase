# Oracle PDB Assignment II

## Student Information

- Student Name: Uwase Honorine
- Student ID: 20252SEN390
- Main PDB: HO_pdb_20252SEN390
- Oracle CDB: ORCL

---

## 1. Overview of Tasks

This assignment contains four mandatory tasks:

1. Create a New Pluggable Database
2. Create and Delete a PDB
3. Configure and Access Oracle Enterprise Manager
4. Documentation and Reporting

---

## 2. Oracle Environment Used

- Oracle Database: [ACTUAL VERSION]
- CDB: ORCL
- Main PDB: HO_pdb_20252SEN390
- Operating System: Microsoft Windows
- Oracle Enterprise Manager: Database Express
- Time Zone: Africa/Kigali (UTC+02:00)

---

## 3. Task 1 — Create a New Pluggable Database

The PDB HO_pdb_20252SEN390 was created successfully.

A user named UWASE_plsqlauca_20252SEN390 was created inside the PDB.

The PDB was opened in READ WRITE mode and verified.

### Evidence

Screenshots are available in:

screenshots/pdb_creation/

---

## 4. Task 2 — Create and Delete a PDB

A temporary PDB named:

HO_to_delete_pdb_20252SEN390

was created and verified.

It was then completely deleted using:

DROP PLUGGABLE DATABASE ... INCLUDING DATAFILES;

The PDB was subsequently checked to confirm that it no longer existed.

### Evidence

Screenshots are available in:

screenshots/pdb_deletion/

---

---

## 5. Challenges Faced

One challenge I faced was ensuring that the PDB was created correctly and opened in READ WRITE mode. I had to verify the PDB status using SQL queries before continuing with the other tasks.

## 6. Integrity Statement

I confirm that the work submitted in this repository represents the work completed for this assignment and that the screenshots and documentation correspond to my Oracle environment.

---

## 8. Submission Details

Repository Link: [PASTE YOUR GITHUB REPOSITORY LINK]

PDB Name Created: HO_pdb_20252SEN390

Issues Encountered: [Yes/No]
