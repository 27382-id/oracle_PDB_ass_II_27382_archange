# oracle_pdb_ass_II_27382_archange

**Course:** Database Development with PL/SQL (INSY 8311)
**Instructor:** Eric Maniraguha
**Student Name:** Archange Muhindi
**Student ID:** 27382
**Repository Name:** oracle_pdb_ass_II_27382_archange

---

## 1. Overview

This assignment focuses on practical implementation of Oracle Multitenant Architecture using Pluggable Databases (PDBs). The tasks completed include:

* Creation of a new Pluggable Database (PDB)
* Creation of a user inside the PDB
* Creation and deletion of a temporary PDB
* Configuration and verification using Oracle Enterprise Manager (OEM)
* Professional documentation using GitHub

The objective was to demonstrate hands-on understanding of Oracle database administration concepts.

---

## 2. Oracle Environment Used

* Oracle Version: Oracle Database 21c 
* Operating System: Windows 11
* Tool Used: Oracle SQL Developer,sql plus
* Connection Type: SYSDBA for administrative tasks

---

## 3. Task 1 – Create a New Pluggable Database

### PDB Name Created:

ar_pdb_27382

### Username Created Inside the PDB:

archange_plsqlauca_27382

### Description of Steps Performed:

1. Connected to the Container Database (CDB) as SYSDBA.
2. Verified current container was CDB$ROOT.
3. Created the new PDB using the required naming convention.
4. Opened the PDB and saved its state.
5. Switched session to the created PDB.
6. Created the required user inside the PDB.
7. Granted necessary privileges to the user.
8. Verified successful creation of both the PDB and the user.

### Evidence:

Screenshots provided in the screenshots/ folder:

* PDB creation
* PDB open state
* User creation inside the PDB

---

## 4. Task 2 – Create and Delete a Temporary PDB

### Temporary PDB Name:

ar_to_delete_pdb_27382

### Description of Steps Performed:

1. Connected as SYSDBA to the CDB.
2. Created the temporary PDB using the required naming convention.
3. Verified the PDB existed.
4. Closed the temporary PDB.
5. Dropped the PDB including its datafiles.
6. Confirmed that the PDB no longer existed.

### Evidence:

Screenshots provided in the screenshots/ folder:

* Temporary PDB creation
* Temporary PDB deletion
* Verification of removal

---

## 5. Task 3 – Oracle Enterprise Manager (OEM)

Oracle Enterprise Manager was accessed through the local web interface.

### Actions Performed:

* Logged in as SYSDBA
* Navigated to the Pluggable Databases section
* Verified created PDB
* Confirmed Oracle environment status

### Evidence:

Screenshot of OEM dashboard included in screenshots/ folder.

---

## 6. Challenges Encountered

No major issues were encountered during the completion of this assignment.

---

## 7. Repository Structure

oracle_pdb_ass_II_27382_archange/
│
├── README.md
└── screenshots/
├── pdb_creation.png
├── user_creation.png
├── temp_pdb_creation.png
├── temp_pdb_deletion.png
└── oem_dashboard.png

---

## 8. Submission Information

Repository Link: (Paste your public GitHub URL here)
PDB Name Created: ar_pdb_27382
Issues Encountered: No

---

## 9. Integrity Statement

I hereby declare that this assignment was completed individually. All tasks were performed by me, and all screenshots reflect my own Oracle environment execution. I understand that academic integrity is essential in professional database practice.

---

**End of Report**
