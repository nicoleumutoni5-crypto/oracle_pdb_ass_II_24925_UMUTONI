# oracle_pdb_ass_II_24925_UMUTONI
Oracle PDB Assignment II
# oracle environment
oracle version: oracle database 21c
operating system: window 11
CDB name: ORCL
Tool used: oracle sql developer

## TASK 1: Create main pluggable database
### PDB Details
- *PDB Name*: um_pdb_24925
- *Admin User*: pdbadmin
- *Application User*: umutoni_plsqlauca_24925
- *status*:successfully created and opened

### Steps Performed
1. Connected to CDB as SYSDBA using SQL Developer
2. Created pluggable database with specified naming convention
3. Opened the PDB
4. Switched session to the new PDB
5. Created application user with required privileges
6. Verified user creation

### Screenshots
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/snipe2%20create%20pdb.PNG)
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/snipe%204%20%20verify%20pdb%20is%20open.PNG)
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/snipe%205%20switch%20to%20pdb.PNG)
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/SNIPE%206%20CREATE%20USER.PNG)
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/snipe%209%20%20verify%20user%20creation.PNG)
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/snipe%2010%20%20switch%20to%20cdb.PNG)
## TASK 2: Create and Delete Temporary PDB

### Temporary PDB Details
- *PDB Name*: um_to_delete_pdb_24925
- *Status*: Successfully Created and Deleted

### Steps Performed
1. Returned to CDB root container
2. Created temporary PDB
3. Opened and verified the temporary PDB
4. Closed the temporary PDB
5. Dropped the PDB including all datafiles
6. Verified complete deletion

### Screenshots
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/snipe%2011%20part%202%20create%20temp%20pdb.PNG)
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/snipe%2013%20part%202%20verify%20it%20exists.PNG)
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/SNIPE%20%2015%20part%202%20delete%20temp%20pdb.PNG)
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/snipe%2016%20part%202%20confirm%20deletion.PNG)

## TASK 3: Oracle Enterprise Manager

### OEM Access
- *URL*: https://localhost:5500/em
- *Status*: Successfully Accessed

### Steps Performed
1. Retrieved OEM HTTPS port from database
2. Accessed OEM via web browser
3. Logged in as SYSDBA
4. Navigated to Pluggable Databases section
5. Verified PDB configuration in dashboard

### Screenshots
![image alt](https://github.com/nicoleumutoni5-crypto/oracle_pdb_ass_II_24925_UMUTONI/blob/main/snipe%2017%20part%203%20%20find%20oem%20url.PNG)
![image alt](
![image alt](

## Key points covered
1. Understanding Oracle Multitenant Architecture
2. PDB lifecycle management (create, open, close, drop)
3. User management within PDBs
4. Working with Oracle Enterprise Manager
5. Importance of following naming conventions in database administration

