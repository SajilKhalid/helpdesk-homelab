# Ticket 001: User Cannot Log In

## Issue
User reports they are unable to log into their Windows machine.

## Environment
- OS: Windows 11 VM
- Tool: VMware Fusion

## Troubleshooting Steps
1. Verified user account exists in Windows system settings  
2. Attempted login and observed authentication failure (incorrect password)  
3. Accessed admin account and navigated to user management settings  
4. Removed and recreated affected user account to restore access  

## Root Cause
Incorrect password / user authentication failure

---

## Resolution
User account was removed and recreated successfully. Login access was restored.

---

## Outcome
User can now successfully log into the system without errors.

---

## Key Learnings
- Local user account issues can be resolved via reset or recreation  
- Admin privileges are required for user management  
- Proper documentation improves troubleshooting clarity  

---
## Screenshots
### 1. User account created
![User Created](../screenshots/Ticket-001/01%20-%20UserCreated.png)

### 2. Login failure / incorrect password
![Login Failed](../screenshots/Ticket-001/02%20-%20LoginFailed.png)

### 3. Account investigation screen
![Investigation](../screenshots/ticket-001/03%20-%20AccountInvestigation.png)

### 4. Account deletion / fix
![Resolution](../screenshots/Ticket-001/04%20-%20DeleteTestUserAccount.png)
![AccountDeleted](../screenshots/Ticket-001/05%20-%20UserAccountSuccessfullyDeleted.png)

### 5. Final verification (optional desktop/login success)
![Final State](../screenshots/Ticket-001/06%20-%20UserAccountSuccessfullyAccessed.png)
