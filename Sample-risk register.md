## System Description 

**System Name:** DrPrescribe (Brightside Clinics)


DrPrescribe is a fictional cloud-based electronic prescription platform 
used by Brightside Clinics. It manages patient medication history, 
preferred pharmacy information, and real-time drug interaction checks. 
The system is used by patients, pharmacies, doctors, and healthcare 
providers to coordinate prescription workflows.

<details>
<summary>Click to expand: System Categorization</summary>

## System Categorization (FIPS 199)

| Security Objective | Impact Level | Justification |
|---------------------|--------------|----------------|
| **Confidentiality** | High | The application handles Protected Health Information (PHI), including medication history and allergy details. Exposure could cause serious patient harm and result in regulatory non-compliance with significant penalties. |
| **Integrity** | High | Inaccurate medication or drug-interaction data could seriously endanger patients and would also constitute non-compliance with legal requirements. |
| **Availability** | Medium | Short-term downtime can be mitigated through manual prescription processes until the system is restored, limiting the operational impact. |

</details>

**Overall System Categorization: High**
*(Set to the highest of the three ratings, per FIPS 199 "high water mark" methodology.)*

  
  ## Selected NIST 800-53 Controls
  
<details>
<summary>Click to expand: Access Control</summary>

| Control ID | Control Name | Implementation Description | Status |
|---------------------|--------------|----------------|----------------|
 | AC-2 | Account Management | how user accounts (doctors, pharmacies, patients) are created, reviewed, and disabled |  Implemented |
 

</details>

