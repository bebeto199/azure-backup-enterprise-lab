# azure-backup-enterprise-lab
This project demonstrates the implementation of Azure Backup to protect virtual machines using a Recovery Services Vault.
# Azure Backup Enterprise Lab

## Overview
This project demonstrates the implementation of Azure Backup to protect virtual machines using a Recovery Services Vault.

The lab simulates a real-world enterprise scenario including backup configuration, policy management, restore operations, and monitoring.


## Architecture
- Azure Virtual Machine (Windows Server)
- Recovery Services Vault
- Backup Policies (Daily + Retention)
- Azure Monitor (Backup Jobs)



## Key Features
- VM backup using Recovery Services Vault
- Custom backup policy configuration
- On-demand backup execution
- Full VM restore simulation
- Backup job monitoring and alerting



## Lab Scenarios

### 1. Backup Configuration
- Created Recovery Services Vault
- Enabled backup for VM

### 2. Policy Management
- Configured daily backup schedule
- Implemented retention rules

### 3. Restore Testing
- Simulated data loss
- Performed full VM restore

### 4. Monitoring
- Verified backup jobs
- Reviewed success/failure logs

---

## 📸 Screenshots
(See /screenshots folder)
<img width="864" height="914" alt="image" src="https://github.com/user-attachments/assets/9a332ae9-5d81-4667-bd60-6b7b9369ace1" />
<img width="975" height="320" alt="image" src="https://github.com/user-attachments/assets/defd2bc1-0dc5-477d-97d2-e698821dbfb8" />
<img width="975" height="322" alt="image" src="https://github.com/user-attachments/assets/11a77a7a-877c-48cf-8826-11d28ce2e661" />
<img width="831" height="788" alt="image" src="https://github.com/user-attachments/assets/fb0daaa0-f04a-43c2-8e9b-f04314d1ff74" />
<img width="878" height="851" alt="image" src="https://github.com/user-attachments/assets/6194cc27-c9b6-48ea-99cc-b4bebc6b5590" />

<img width="975" height="358" alt="image" src="https://github.com/user-attachments/assets/d08e459d-d9a0-411a-a7e2-39cd2047b1a6" />

Configure Backup for the VM

<img width="975" height="554" alt="image" src="https://github.com/user-attachments/assets/06c8fc20-fc8b-42d3-82b7-c37b3f87f4f2" />
<img width="806" height="497" alt="image" src="https://github.com/user-attachments/assets/d0520d7f-be5d-4fc7-9ad6-686ac1c87207" />

<img width="975" height="467" alt="image" src="https://github.com/user-attachments/assets/611f2605-9964-473e-a4cc-3ffe005a8f52" />

<img width="975" height="218" alt="image" src="https://github.com/user-attachments/assets/807393fc-ca23-4105-a9d8-08584d3a7a3a" />
<img width="975" height="338" alt="image" src="https://github.com/user-attachments/assets/946418d0-7be4-45b9-922c-4a2186f9dc78" />

Customize Backup Policy

<img width="975" height="539" alt="image" src="https://github.com/user-attachments/assets/19bd8ca6-4393-4925-851a-0dd9ea365c61" />
<img width="975" height="464" alt="image" src="https://github.com/user-attachments/assets/f51a6496-d872-47e3-8875-d6c5f97a1cdc" />

Run an On-Demand Backup

<img width="975" height="528" alt="image" src="https://github.com/user-attachments/assets/cad2670c-4272-4e83-8992-024eae4cad54" />

<img width="975" height="453" alt="image" src="https://github.com/user-attachments/assets/454c1e01-2a78-45aa-98f3-756bba317803" />
<img width="766" height="901" alt="image" src="https://github.com/user-attachments/assets/73998cd8-29a5-487d-93eb-e3fbcc227ee1" />


Simulate Data Loss
<img width="832" height="654" alt="image" src="https://github.com/user-attachments/assets/d4970720-b52c-4196-90c4-7f45692dcac9" />

<img width="725" height="653" alt="image" src="https://github.com/user-attachments/assets/6853019e-66a0-4cd0-8193-d302d5ad49f9" />
<img width="975" height="714" alt="image" src="https://github.com/user-attachments/assets/d1e6fbb0-b291-49d3-a5ee-8d7fba8d0439" />

<img width="975" height="543" alt="image" src="https://github.com/user-attachments/assets/ee0e4d76-35ae-4fc1-b4d8-5fd0de5abb35" />

<img width="975" height="628" alt="image" src="https://github.com/user-attachments/assets/3f7297ea-6d2d-476a-8057-ca5277b68f88" />

Restore the VM

<img width="975" height="324" alt="image" src="https://github.com/user-attachments/assets/b387f786-3f5b-445e-b7a5-d2a0a6635946" />
<img width="975" height="466" alt="image" src="https://github.com/user-attachments/assets/f085580e-06b8-43df-b05e-b78fbb5a6cc9" />


<img width="975" height="966" alt="image" src="https://github.com/user-attachments/assets/5d3afd6a-cae9-457c-bcf1-9b3d08b440ad" />


<img width="975" height="968" alt="image" src="https://github.com/user-attachments/assets/0d71ff3e-faf3-411b-9618-b82635943917" />

<img width="975" height="451" alt="image" src="https://github.com/user-attachments/assets/91a26303-9ced-4b4e-86a0-8e74682c1d17" />

<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/da9bb417-6f27-4c08-9a1f-c1bab862db93" />


---

## 💡 Lessons Learned
- Importance of testing restore, not just backup
- Retention policies must align with business requirements
- Monitoring is critical for backup reliability

---

## 🔗 Author
BEBETO Nseyani
