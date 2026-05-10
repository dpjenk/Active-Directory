# Active-Directory

Created user accounts:
<br><br>
<img width="892" height="249" alt="AD1" src="https://github.com/user-attachments/assets/98b10ed3-0682-4fe9-9a91-1c7e55d26262" />
<br><br>
Added two Workstation computers to domain:
<br><br>
<img width="885" height="245" alt="AD2" src="https://github.com/user-attachments/assets/8bad2f8c-bd45-478e-8b9c-b874d4c711b0" />
<br><br>
Created Security Groups:
<br><br>
<img width="895" height="245" alt="AD3" src="https://github.com/user-attachments/assets/4f1a3bff-de37-4682-95a4-1ba3781cb525" />
<br><br>
Reset user password:
<br><br>
<img width="1061" height="569" alt="AD4" src="https://github.com/user-attachments/assets/5c17b82e-d9c9-4b59-b8f3-9b6b4a749b4b" />
<br><br>
Unlocked user account:
<br><br>
<img width="898" height="526" alt="AD5" src="https://github.com/user-attachments/assets/ff683ff8-1c64-4b60-9bd4-289bf93e2b85" />
<br><br>
Disabled user account:
<br><br>
<img width="891" height="523" alt="AD6" src="https://github.com/user-attachments/assets/b5912b4e-f056-4549-8884-75ef199cb7e6" />
<br><br>
Enabled user account:
<br><br>
<img width="897" height="522" alt="AD7" src="https://github.com/user-attachments/assets/7528914f-30a8-4aaa-8814-8b2c69656ec3" />
<br><br>
Moved user between OUs:
<br><br>
<img width="897" height="522" alt="AD8" src="https://github.com/user-attachments/assets/5811d73e-caa1-46b7-9944-c25d6bd3f8af" />
<br><br>
Added user to Security Group:
<br><br>
<img width="895" height="524" alt="AD9" src="https://github.com/user-attachments/assets/e4c845f3-75d0-4492-bda3-47f44ce92212" />
<br>
<img width="895" height="523" alt="AD10" src="https://github.com/user-attachments/assets/478ac012-e97b-4bf5-971e-4b658b2b4069" />
<br><br>
TRUST RELATIONSHIP FAILED ISSUE EXERCISE

Error message: “Trust Relationship between this workstation and the primary domain failed”

Actions taken:

1) Logged into user’s computer using local administrator account

2) Verified network connectivity to domain

3) Located computer object in Active Directory

4) Reset computer account in Active Directory (right-clicked the computer object in the ADUCtool. This resets the machine account password and re-establishes the trust relationship with the domain.

If the above step was not successful:

5) Removed computer from domain and joined to Workgroup

6) Rebooted computer

7) Rejoined computer to domain

8) Rebooted computer

Resolved issue:

Domain trust relationship successfully restored

User now able to log in with domain credentials
