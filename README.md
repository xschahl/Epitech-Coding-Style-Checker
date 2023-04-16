## Scripts to generate coding style reports

### Linux

Requirement :
- [Docker](https://docs.docker.com/engine/install/) installed

Use `coding-style.sh`

### Windows

Requirements :
- [Docker](https://docs.docker.com/engine/install/) installed
- [Powershell](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows) installed

Use `coding-style.ps1`

### Report

```
-------------------------------------------------------------------------------
                          Epitech Coding Style Report

Path: /home/mr_robot/GitRepository/B-NWP-400-STG-4-1-myteams-xavier.schahl
-------------------------------------------------------------------------------
File                 Line     Error     Severity
-------------------------------------------------------------------------------
Makefile             27       C-A3      INFO
config.h             9        C-G3      MINOR
lib.h                9        C-G3      MINOR
lib.h                11       C-G3      MINOR
lib.h                13       C-G3      MINOR
lib.h                14       C-G3      MINOR
lib.h                15       C-G3      MINOR
lib.h                16       C-G3      MINOR
lib.h                17       C-G3      MINOR
lib.h                18       C-G3      MINOR
client.c             12       C-L4      MINOR
client.c             19       C-L4      MINOR
client.c             24       C-L4      MINOR
client.c             50       C-F4      MAJOR
client.c             51       C-F4      MAJOR
client.c             52       C-F4      MAJOR
Makefile             30       C-A3      INFO
Makefile             29       C-A3      INFO
lib.h                9        C-G3      MINOR
lib.h                11       C-G3      MINOR
lib.h                12       C-G3      MINOR
libmyteams.so        1        C-O1      MAJOR
logging_client.h     1        C-G1      MINOR
logging_client.h     9        C-G3      MINOR
logging_client.h     11       C-G3      MINOR
logging_client.h     130      C-F5      MAJOR
logging_client.h     205      C-F5      MAJOR
logging_client.h     384      C-F5      MAJOR
logging_client.h     430      C-F5      MAJOR
logging_server.h     1        C-G1      MINOR
logging_server.h     9        C-G3      MINOR
logging_server.h     54       C-F5      MAJOR
logging_server.h     93       C-F3      MAJOR
-------------------------------------------------------------------------------
TOTAL          MAJOR: 10       MINOR: 20      INFO: 3      NOTE: -50
-------------------------------------------------------------------------------
```