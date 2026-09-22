# Oracle Pluggable Databases (PDB) Management – Individual Assignment II

| Field | Details |
|---|---|
| **Student Name** | MUGISHA Yves |
| **Student ID** | 20251SEN202 |
| **Course** | Database Development with PL/SQL (INSY 8311) |
| **Instructor** | Eric Maniraguha |
| **Teaching Assistant** | Afanyu Emmanuel |
| **Assignment Date** | September 17, 2026 |
| **Deadline** | Monday, September 22, 2026, 11:59 PM |

---

## Overview of Tasks

<!-- Write a short summary, in your own words, of the four tasks. -->

| # | Task | Object Name |
|---|---|---|
| 1 | Create a new Pluggable Database and a user inside it | PDB: `yv_pdb_20251SEN202` · User: `yves_plsqlauca_20251SEN202` |
| 2 | Create and delete a temporary PDB | `yv_to_delete_pdb_20251SEN202` |
| 3 | Oracle Enterprise Manager (OEM) dashboard | — |
| 4 | Documentation & reporting on GitHub | This repository |

---

## Oracle Environment Used

<!-- Fill in what you actually used. -->

- **Oracle Database version:**
- **Operating system / host:**
- **Client tools:** (e.g. SQL*Plus, SQL Developer)
- **Enterprise Manager:** (e.g. EM Express at https://localhost:5500/em)

---

## Task 1 – Create a New Pluggable Database

- **PDB name:** `yv_pdb_20251SEN202`
- **User created inside the PDB:** `yves_plsqlauca_20251SEN202`

<!-- Explain what you did and why, step by step. -->

### Evidence

**PDB creation command**

![PDB creation command](screenshots/pdb_creation/01_create_pdb.png)

**PDB open state**

![PDB open state](screenshots/pdb_creation/02_pdb_open_state.png)

**User created inside the PDB**

![User created inside PDB](screenshots/pdb_creation/03_user_created.png)

---

## Task 2 – Create and Delete a PDB

- **Temporary PDB name:** `yv_to_delete_pdb_20251SEN202`

<!-- Explain how you created it, verified it existed, deleted it, and confirmed it was gone. -->

### Evidence

**Temporary PDB created and verified**

![Temporary PDB created](screenshots/pdb_deletion/01_create_temp_pdb.png)

**Temporary PDB deleted and confirmed**

![Temporary PDB deleted](screenshots/pdb_deletion/02_drop_temp_pdb.png)

---

## Task 3 – Oracle Enterprise Manager (OEM)

<!-- Explain how you accessed OEM and what the dashboard shows (environment, PDBs, username). -->

### Evidence

![OEM dashboard](screenshots/oem_dashboard/01_oem_dashboard.png)

---

## Challenges Faced and Solutions

<!-- Describe any problems you hit and how you solved them, or write "No major issues encountered." -->

---

## Integrity Statement

I, MUGISHA Yves (Student ID: 20251SEN202), confirm that this assignment was completed individually.
All commands were written and executed by me, and all screenshots come from my own environment.
I did not copy from classmates or use AI tools to generate commands or solutions.

---

## Submission Details

```
Repository Link: https://github.com/Yves-Developer/oracle_pdb_ass_II_20251SEN202_yves
PDB Name Created: yv_pdb_20251SEN202
Issues Encountered: [Yes/No]
```
